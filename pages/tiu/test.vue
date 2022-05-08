<template>
  <section class="section">
    <div class>
      <div class="row">
        <div class="col-12">
          <div class="card">
            <div class="card-header">
              <h4>Perception And Preference Inventory</h4>
            </div>
            <div class="card-body">
              <form
                @submit="store"
                method="POST"
                action="#"
                class="needs-validation"
                novalidate=""
              >
                <div class="form-group">
                  "<label>1.</label>
                  <img src="~/assets/img/tiu1.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb1" value="1" /> 1
                      <input type="radio" v-model="jwb1" value="2" /> 2
                      <input type="radio" v-model="jwb1" value="3" /> 3
                      <input type="radio" v-model="jwb1" value="4" /> 4
                      <input type="radio" v-model="jwb1" value="5" /> 5
                    </li>
                  </ul>
                  <label>2.</label>
                  <img src="~/assets/img/tiu2.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb2" value="1" /> 1
                      <input type="radio" v-model="jwb2" value="2" /> 2
                      <input type="radio" v-model="jwb2" value="3" /> 3
                      <input type="radio" v-model="jwb2" value="4" /> 4
                      <input type="radio" v-model="jwb2" value="5" /> 5
                    </li>
                  </ul>
                  <label>3.</label>
                  <img src="~/assets/img/tiu3.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb3" value="1" /> 1
                      <input type="radio" v-model="jwb3" value="2" /> 2
                      <input type="radio" v-model="jwb3" value="3" /> 3
                      <input type="radio" v-model="jwb3" value="4" /> 4
                      <input type="radio" v-model="jwb3" value="5" /> 5
                    </li>
                  </ul>
                  <label>4.</label>
                  <img src="~/assets/img/tiu4.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb4" value="1" /> 1
                      <input type="radio" v-model="jwb4" value="2" /> 2
                      <input type="radio" v-model="jwb4" value="3" /> 3
                      <input type="radio" v-model="jwb4" value="4" /> 4
                      <input type="radio" v-model="jwb4" value="5" /> 5
                    </li>
                  </ul>
                  <label>5.</label>
                  <img src="~/assets/img/tiu5.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb5" value="1" /> 1
                      <input type="radio" v-model="jwb5" value="2" /> 2
                      <input type="radio" v-model="jwb5" value="3" /> 3
                      <input type="radio" v-model="jwb5" value="4" /> 4
                      <input type="radio" v-model="jwb5" value="5" /> 5
                    </li>
                  </ul>
                  <label>6.</label>
                  <img src="~/assets/img/tiu6.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb6" value="1" /> 1
                      <input type="radio" v-model="jwb6" value="2" /> 2
                      <input type="radio" v-model="jwb6" value="3" /> 3
                      <input type="radio" v-model="jwb6" value="4" /> 4
                      <input type="radio" v-model="jwb6" value="5" /> 5
                    </li>
                  </ul>
                  <label>7.</label>
                  <img src="~/assets/img/tiu7.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb7" value="1" /> 1
                      <input type="radio" v-model="jwb7" value="2" /> 2
                      <input type="radio" v-model="jwb7" value="3" /> 3
                      <input type="radio" v-model="jwb7" value="4" /> 4
                      <input type="radio" v-model="jwb7" value="5" /> 5
                    </li>
                  </ul>
                  <label>8.</label>
                  <img src="~/assets/img/tiu8.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb8" value="1" /> 1
                      <input type="radio" v-model="jwb8" value="2" /> 2
                      <input type="radio" v-model="jwb8" value="3" /> 3
                      <input type="radio" v-model="jwb8" value="4" /> 4
                      <input type="radio" v-model="jwb8" value="5" /> 5
                    </li>
                  </ul>
                  <label>9.</label>
                  <img src="~/assets/img/tiu9.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb9" value="1" /> 1
                      <input type="radio" v-model="jwb9" value="2" /> 2
                      <input type="radio" v-model="jwb9" value="3" /> 3
                      <input type="radio" v-model="jwb9" value="4" /> 4
                      <input type="radio" v-model="jwb9" value="5" /> 5
                    </li>
                  </ul>
                  <label>10.</label>
                  <img src="~/assets/img/tiu10.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb10" value="1" /> 1
                      <input type="radio" v-model="jwb10" value="2" /> 2
                      <input type="radio" v-model="jwb10" value="3" /> 3
                      <input type="radio" v-model="jwb10" value="4" /> 4
                      <input type="radio" v-model="jwb10" value="5" /> 5
                    </li>
                  </ul>
                  <label>11.</label>
                  <img src="~/assets/img/tiu11.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb11" value="1" /> 1
                      <input type="radio" v-model="jwb11" value="2" /> 2
                      <input type="radio" v-model="jwb11" value="3" /> 3
                      <input type="radio" v-model="jwb11" value="4" /> 4
                      <input type="radio" v-model="jwb11" value="5" /> 5
                    </li>
                  </ul>
                  <label>12.</label>
                  <img src="~/assets/img/tiu12.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb12" value="1" /> 1
                      <input type="radio" v-model="jwb12" value="2" /> 2
                      <input type="radio" v-model="jwb12" value="3" /> 3
                      <input type="radio" v-model="jwb12" value="4" /> 4
                      <input type="radio" v-model="jwb12" value="5" /> 5
                    </li>
                  </ul>
                  <label>13.</label>
                  <img src="~/assets/img/tiu13.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb13" value="1" /> 1
                      <input type="radio" v-model="jwb13" value="2" /> 2
                      <input type="radio" v-model="jwb13" value="3" /> 3
                      <input type="radio" v-model="jwb13" value="4" /> 4
                      <input type="radio" v-model="jwb13" value="5" /> 5
                    </li>
                  </ul>
                  <label>14.</label>
                  <img src="~/assets/img/tiu14.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb14" value="1" /> 1
                      <input type="radio" v-model="jwb14" value="2" /> 2
                      <input type="radio" v-model="jwb14" value="3" /> 3
                      <input type="radio" v-model="jwb14" value="4" /> 4
                      <input type="radio" v-model="jwb14" value="5" /> 5
                    </li>
                  </ul>
                  <label>15.</label>
                  <img src="~/assets/img/tiu15.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb15" value="1" /> 1
                      <input type="radio" v-model="jwb15" value="2" /> 2
                      <input type="radio" v-model="jwb15" value="3" /> 3
                      <input type="radio" v-model="jwb15" value="4" /> 4
                      <input type="radio" v-model="jwb15" value="5" /> 5
                    </li>
                  </ul>
                  <label>16.</label>
                  <img src="~/assets/img/tiu16.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb16" value="1" /> 1
                      <input type="radio" v-model="jwb16" value="2" /> 2
                      <input type="radio" v-model="jwb16" value="3" /> 3
                      <input type="radio" v-model="jwb16" value="4" /> 4
                      <input type="radio" v-model="jwb16" value="5" /> 5
                    </li>
                  </ul>
                  <label>17.</label>
                  <img src="~/assets/img/tiu17.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb17" value="1" /> 1
                      <input type="radio" v-model="jwb17" value="2" /> 2
                      <input type="radio" v-model="jwb17" value="3" /> 3
                      <input type="radio" v-model="jwb17" value="4" /> 4
                      <input type="radio" v-model="jwb17" value="5" /> 5
                    </li>
                  </ul>
                  <label>18.</label>
                  <img src="~/assets/img/tiu18.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb18" value="1" /> 1
                      <input type="radio" v-model="jwb18" value="2" /> 2
                      <input type="radio" v-model="jwb18" value="3" /> 3
                      <input type="radio" v-model="jwb18" value="4" /> 4
                      <input type="radio" v-model="jwb18" value="5" /> 5
                    </li>
                  </ul>
                  <label>19.</label>
                  <img src="~/assets/img/tiu19.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb19" value="1" /> 1
                      <input type="radio" v-model="jwb19" value="2" /> 2
                      <input type="radio" v-model="jwb19" value="3" /> 3
                      <input type="radio" v-model="jwb19" value="4" /> 4
                      <input type="radio" v-model="jwb19" value="5" /> 5
                    </li>
                  </ul>
                  <label>20.</label>
                  <img src="~/assets/img/tiu20.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb20" value="1" /> 1
                      <input type="radio" v-model="jwb20" value="2" /> 2
                      <input type="radio" v-model="jwb20" value="3" /> 3
                      <input type="radio" v-model="jwb20" value="4" /> 4
                      <input type="radio" v-model="jwb20" value="5" /> 5
                    </li>
                  </ul>
                  <label>21.</label>
                  <img src="~/assets/img/tiu21.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb21" value="1" /> 1
                      <input type="radio" v-model="jwb21" value="2" /> 2
                      <input type="radio" v-model="jwb21" value="3" /> 3
                      <input type="radio" v-model="jwb21" value="4" /> 4
                      <input type="radio" v-model="jwb21" value="5" /> 5
                    </li>
                  </ul>
                  <label>22.</label>
                  <img src="~/assets/img/tiu22.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb22" value="1" /> 1
                      <input type="radio" v-model="jwb22" value="2" /> 2
                      <input type="radio" v-model="jwb22" value="3" /> 3
                      <input type="radio" v-model="jwb22" value="4" /> 4
                      <input type="radio" v-model="jwb22" value="5" /> 5
                    </li>
                  </ul>
                  <label>23.</label>
                  <img src="~/assets/img/tiu23.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb23" value="1" /> 1
                      <input type="radio" v-model="jwb23" value="2" /> 2
                      <input type="radio" v-model="jwb23" value="3" /> 3
                      <input type="radio" v-model="jwb23" value="4" /> 4
                      <input type="radio" v-model="jwb23" value="5" /> 5
                    </li>
                  </ul>
                  <label>24.</label>
                  <img src="~/assets/img/tiu24.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb24" value="1" /> 1
                      <input type="radio" v-model="jwb24" value="2" /> 2
                      <input type="radio" v-model="jwb24" value="3" /> 3
                      <input type="radio" v-model="jwb24" value="4" /> 4
                      <input type="radio" v-model="jwb24" value="5" /> 5
                    </li>
                  </ul>
                  <label>25.</label>
                  <img src="~/assets/img/tiu25.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb25" value="1" /> 1
                      <input type="radio" v-model="jwb25" value="2" /> 2
                      <input type="radio" v-model="jwb25" value="3" /> 3
                      <input type="radio" v-model="jwb25" value="4" /> 4
                      <input type="radio" v-model="jwb25" value="5" /> 5
                    </li>
                  </ul>
                  <label>26.</label>
                  <img src="~/assets/img/tiu26.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb26" value="1" /> 1
                      <input type="radio" v-model="jwb26" value="2" /> 2
                      <input type="radio" v-model="jwb26" value="3" /> 3
                      <input type="radio" v-model="jwb26" value="4" /> 4
                      <input type="radio" v-model="jwb26" value="5" /> 5
                    </li>
                  </ul>
                  <label>27.</label>
                  <img src="~/assets/img/tiu27.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb27" value="1" /> 1
                      <input type="radio" v-model="jwb27" value="2" /> 2
                      <input type="radio" v-model="jwb27" value="3" /> 3
                      <input type="radio" v-model="jwb27" value="4" /> 4
                      <input type="radio" v-model="jwb27" value="5" /> 5
                    </li>
                  </ul>
                  <label>28.</label>
                  <img src="~/assets/img/tiu28.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb28" value="1" /> 1
                      <input type="radio" v-model="jwb28" value="2" /> 2
                      <input type="radio" v-model="jwb28" value="3" /> 3
                      <input type="radio" v-model="jwb28" value="4" /> 4
                      <input type="radio" v-model="jwb28" value="5" /> 5
                    </li>
                  </ul>
                  <label>29.</label>
                  <img src="~/assets/img/tiu29.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb29" value="1" /> 1
                      <input type="radio" v-model="jwb29" value="2" /> 2
                      <input type="radio" v-model="jwb29" value="3" /> 3
                      <input type="radio" v-model="jwb29" value="4" /> 4
                      <input type="radio" v-model="jwb29" value="5" /> 5
                    </li>
                  </ul>
                  <label>30.</label>
                  <img src="~/assets/img/tiu30.png" />
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb30" value="1" /> 1
                      <input type="radio" v-model="jwb30" value="2" /> 2
                      <input type="radio" v-model="jwb30" value="3" /> 3
                      <input type="radio" v-model="jwb30" value="4" /> 4
                      <input type="radio" v-model="jwb30" value="5" /> 5
                    </li>
                  </ul>
                  
                </div>

                <div class="form-group">
                  <label
                    class="
                      col-form-label
                      text-md-right
                      col-12 col-md-3 col-lg-3
                    "
                  ></label>
                  <div class="col-sm-12 col-md-7">
                    <button type="submit" class="btn btn-primary">
                      Simpan
                    </button>
                  </div>
                </div>
              </form>
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
      //state post
      jwb1: "",
      jwb2: "",
      jwb3: "",
      jwb4: "",
      jwb5: "",
      jwb6: "",
      jwb7: "",
      jwb8: "",
      jwb9: "",
      jwb10: "",
      jwb11: "",
      jwb12: "",
      jwb13: "",
      jwb14: "",
      jwb15: "",
      jwb16: "",
      jwb17: "",
      jwb18: "",
      jwb19: "",
      jwb20: "",
      jwb21: "",
      jwb22: "",
      jwb23: "",
      jwb24: "",
      jwb25: "",
      jwb26: "",
      jwb27: "",
      jwb28: "",
      jwb29: "",
      jwb30: "",
      no_pendaftaran: "",
      rest:[
        2,5,4,4,5,4,5,1,5,3,
        5,4,5,3,2,3,2,3,4,4,
        3,3,4,4,5,1,2,5,3,5
      ],
      jbnr:"",
      ss:"",
      cls:"",

      provinsi: {
        provinsi: "",
      },
      //state validation
      validation: [],
    };
  },

    mounted() {
    this.no_pendaftaran = localStorage.no_pendaftaran
    console.log("run on tiu test");
    // let endPoint = `/api/papiuserresult/no_pendaftaran=${this.no_pendaftaran}`;
    // this.$axios
    //   .$get(endPoint)
    //   .then((response) => {
    //     if (res.data.status == "ok") {
    //       this.status = "disable";
    //     }
    //     else{
    //       this.status = "enable"
    //     }
    //   })
    //   .catch((error) => {
    //     console.log(error.response.data);
    //   });
  },

 methods: {
    async store(e) {
      e.preventDefault();
      var obj = {
        no_pendaftaran: [],
      };
      obj.no_pendaftaran.push("456789123");
      let datax = {
        data: [
          {
            no_pendaftaran: this.no_pendaftaran,
            jwb1: this.jwb1,
            jwb2: this.jwb2,
            jwb3: this.jwb3,
            jwb4: this.jwb4,
            jwb5: this.jwb5,
            jwb6: this.jwb6,
            jwb7: this.jwb7,
            jwb8: this.jwb8,
            jwb9: this.jwb9,
            jwb10: this.jwb10,
            jwb11: this.jwb11,
            jwb12: this.jwb12,
            jwb13: this.jwb13,
            jwb14: this.jwb14,
            jwb15: this.jwb15,
            jwb16: this.jwb16,
            jwb17: this.jwb17,
            jwb18: this.jwb18,
            jwb19: this.jwb19,
            jwb20: this.jwb20,
            jwb21: this.jwb21,
            jwb22: this.jwb22,
            jwb23: this.jwb23,
            jwb24: this.jwb24,
            jwb25: this.jwb25,
            jwb26: this.jwb26,
            jwb27: this.jwb27,
            jwb28: this.jwb28,
            jwb29: this.jwb29,
            jwb30: this.jwb30
          },
        ],
      };

      await this.$axios({
        method: "post",
        headers: { "content-type": "application/json" },
        url: "/api/tiu",
        data: datax,
      })
        .then(() => {
          this.$router.push({
            name: "tiu",
          });
        })
        .catch((error) => {
          this.validation = error.response.data;
        });
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
