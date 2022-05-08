<template>
  <section class="section">
    <div class>
      <div class="row">
        <div class="col-12">
          <div class="card">
            <div class="card-header">
              <h4>
                RIASEC
              </h4>
            </div>
            <div class="card-body">
              <div class="form-group">
                <label>Masukkan Kode Test</label>
                <input type="text" v-model="password" class="form-control" />
              </div>

              <div class="form-group">
                <!-- <label>Provinsi</label> -->
                <!-- <div class="col-sm-12 col-md-7"> -->
                <!-- <input type="text" v-model="password" class="form-control" /> -->
                <!-- <button type="submit" class="btn btn-primary">
                      Next
                    </button> -->
                 <div v-if="this.status === 'enable'">
                  <button @click="goToTest()" class="btn btn-primary">
                    Next
                  </button>
                </div>
                <div v-else>
                  {{ this.status }}
                  anda sudah mengerjakan test ini
                </div>
                <!-- </div> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: "stisla/default",
  components: {},
  data() {
    return {
      password: "",
    };
  },
  computed: {
    check: function () {
      console.log(this.password);
    },
  },

  mounted() {
    this.no_pendaftaran = localStorage.no_pendaftaran;
    console.log("coba");
    let endPoint = `/api/riasecuserresult/?no_pendaftaran=${this.no_pendaftaran}`;
    this.$axios
      .$get(endPoint)
      .then((res) => {
        if (res.data.status == "ok") {
          console.log("tombol disable");
          this.status = "disable";
        } else {
          console.log("tombol enable");
          this.status = "enable";
        }
      })
      .catch((error) => {
        console.log("tombol gj");
        this.status = "enable";
        console.log(error.response.data);
      });
  },
  methods: {
    goToTest() {
      if (this.password === "next") {
        this.$router.push("/riasec/test");
      } else {
        console.log("invalid password");
      }
      //    this.$router.push('/home');
    },
  },
};
</script>


<style scoped>
.main-wrapper-1 .section .section-header {
  margin-left: -30px;
  margin-right: -30px;
  margin-top: -10px;
  border-radius: 0;
  border-top: 1px solid #f9f9f9;
  padding-left: 35px;
  padding-right: 35px;
}
</style>
