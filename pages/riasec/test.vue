<template>
  <section class="section">
    <div class>
      <div class="row">
        <div class="col-12">
          <div class="card">
            <div class="card-header">
              <h4>RIASEC</h4>
                            <h4>Bacalah setiap pernyataan yang ada di bawah ini. jika Anda setuju dengan pernyaataan tersebut maka berikan tanda silang pada kotak yang telah disediakan,
jika tidak setuju dengan pernyataan tersebut, maka anda tidak perlu memberikan tanda apapun pada kolom yang ada.</h4>

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

 

                  <table class="table table-striped table-dark" border="1">
                    <tr>
                      <th>No</th>
                      <th>Pernyataan</th>
                      <th>R</th>
                      <th>I</th>
                      <th>A</th>
                      <th>S</th>
                      <th>E</th>
                      <th>C</th>
                    </tr>
                    <tr>
                      <td>1</td>
                      <td>
                        Saya Menyukai Hal Hal Yang Berkaitan Dengan Otomotif
                      </td>
                      <td><input type="text" id="riasec1" name="riasec1" v-model="jawab1" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>2</td>
                      <td>Saya menyukai teka - teki</td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec2" name="riasec2" v-model="jawab2" class="form-control"></td>
                        <td></td>
                     
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>3</td>
                      <td>Saya bisa bekerja secara mandiri</td>
                      <td></td>
                      <td></td>
                      <td><input type="text" id="riasec3" name="riasec3" v-model="jawab3" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>4</td>
                      <td>Saya suka bekerja dalam tim</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td><input type="text" id="riasec4" name="riasec4" v-model="jawab4" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>5</td>
                      <td>
                        Saya orang yang ambisius. Saya menetapkan tujuan untuk
                        diri saya sendiri
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td><input type="text" id="riasec5" name="riasec5" v-model="jawab5" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>6</td>
                      <td>
                        Saya suka mengatur tugas-tugas saya (seperti mengefile,
                        mengatur meja dan kantor)
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td><input type="text" id="riasec6" name="riasec6" v-model="jawab6" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>7</td>
                      <td>Saya suka merancang sesuatu</td>
                      <td><input type="text" id="riasec7" name="riasec7" v-model="jawab7" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>8</td>
                      <td>
                        Saya suka membaca hal-hal yang berkaitan dengan seni dan
                        musik
                      </td>
                      <td></td>
                      <td></td>
                      <td><input type="text" id="riasec8" name="riasec8" v-model="jawab8" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>9</td>
                      <td>Saya suka mengikuti instruksi yang jelas</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td><input type="text" id="riasec9" name="riasec9" v-model="jawab9" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>10</td>
                      <td>Saya suka membujuk atau mempengaruhi orang lain</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec10" name="riasec10" v-model="jawab10" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>11</td>
                      <td>Saya suka melakukan eksperimen</td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec11" name="riasec11" v-model="jawab11" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>12</td>
                      <td>
                        Saya suka mengajar atau memberikan training kepada orang
                        lain
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec12" name="riasec12" v-model="jawab12" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>13</td>
                      <td>
                        Saya suka membantu orang lain untuk memecahkan masalah
                        mereka
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec13" name="riasec13" v-model="jawab13" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>14</td>
                      <td>Saya suka merawat binatang</td>
                      <td>
                        <input type="text" id="riasec14" name="riasec14" v-model="jawab14" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>15</td>
                      <td>
                        Saya tidak keberatan untuk bekerja selama 8 jam setiap
                        hari dikantor
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec15" name="riasec15" v-model="jawab15" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>16</td>
                      <td>Saya suka menjual barang</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec16" name="riasec16" v-model="jawab16" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>17</td>
                      <td>Saya suka menulis kreatif</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec17" name="riasec17" v-model="jawab17" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>18</td>
                      <td>
                        Saya menyukai hal-hal yang berhubungan dengan ilmu
                        pengetahuan
                      </td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec18" name="riasec18" v-model="jawab18" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>19</td>
                      <td>Saya cepat dalam mengambil tanggung jawab baru</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec19" name="riasec19" v-model="jawab19" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>20</td>
                      <td>
                        Saya menyukai hal-hal yang berkaitan dengan penyembuhan
                        orang
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec20" name="riasec20" v-model="jawab20" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>21</td>
                      <td>
                        Saya tertarik untuk mencari tahu bagaimana cara kerja
                        sesuatu
                      </td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec21" name="riasec21" v-model="jawab21" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>22</td>
                      <td>Saya suka merakit dan merangkai sesuatu</td>
                      <td>
                        <input type="text" id="riasec22" name="riasec22" v-model="jawab22" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>23</td>
                      <td>Saya orang yang kreatif</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec23" name="riasec23" v-model="jawab23" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>24</td>
                      <td>Saya suka memperhatikan hal-hal detail</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec24" name="riasec24" v-model="jawab24" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>25</td>
                      <td>
                        Saya suka melakukan mengefile dokumen atau mengetik
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec25" name="riasec25" v-model="jawab25" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>26</td>
                      <td>
                        Saya suka menganalisis sesuatu (masalah / situasi)
                      </td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec26" name="riasec26" v-model="jawab26" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>27</td>
                      <td>Saya suka memainkan alat musik atau bernyanyi</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec27" name="riasec27" v-model="jawab27" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>28</td>
                      <td>Saya suka mempelajari budaya lain</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec28" name="riasec28" v-model="jawab28" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>29</td>
                      <td>Saya ingin memulai bisnis (membuka usaha sendiri)</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec29" name="riasec29" v-model="jawab29" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>30</td>
                      <td>Saya suka memasak</td>
                      <td>
                        <input type="text" id="riasec30" name="riasec30" v-model="jawab30" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>31</td>
                      <td>Saya suka bermain akting dalam suatu drama</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec31" name="riasec31" v-model="jawab31" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>32</td>
                      <td>Saya orang yang praktis</td>
                      <td>
                        <input type="text" id="riasec32" name="riasec32" v-model="jawab32" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>33</td>
                      <td>Saya suka bekerja dengan angka atau grafik</td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec33" name="riasec33" v-model="jawab33" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>34</td>
                      <td>Saya suka mendiskusikan isu-isu</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec34" name="riasec34" v-model="jawab34" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>35</td>
                      <td>
                        Saya pandai menyimpan catatan yang berhubungan dengan
                        pekerjaan saya
                      </td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec35" name="riasec35" v-model="jawab35" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>36</td>
                      <td>Saya suka memimpin</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec36" name="riasec36" v-model="jawab36" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>37</td>
                      <td>Saya suka bekerja di luar ruangan</td>
                      <td>
                        <input type="text" id="riasec37" name="riasec37" v-model="jawab37" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>38</td>
                      <td>Saya suka bekerja di dalam ruangan</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec38" name="riasec38" v-model="jawab38" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>39</td>
                      <td>Saya pandai matematika</td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec39" name="riasec39" v-model="jawab39" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>40</td>
                      <td>Saya suka menolong orang</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec40" name="riasec40" v-model="jawab40" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>41</td>
                      <td>Saya suka menggambar</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec41" name="riasec41" v-model="jawab41" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>42</td>
                      <td>Saya suka berpidato</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec42" name="riasec42" v-model="jawab42" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td colspan="2">SKOR TOTAL</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td colspan="2"></td>
                      <td>R</td>
                      <td>I</td>
                      <td>A</td>
                      <td>S</td>
                      <td>E</td>
                      <td>C</td>
                    </tr>
                  </table>
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
      jawab1: "",
      jawab2: "",
      jawab3: "",
      jawab4: "",
      jawab5: "",
      jawab6: "",
      jawab7: "",
      jawab8: "",
      jawab9: "",
      jawab10: "",
      jawab11: "",
      jawab12: "",
      jawab13: "",
      jawab14: "",
      jawab15: "",
      jawab16: "",
      jawab17: "",
      jawab18: "",
      jawab19: "",
      jawab20: "",
      jawab21: "",
      jawab22: "",
      jawab23: "",
      jawab24: "",
      jawab25: "",
      jawab26: "",
      jawab27: "",
      jawab28: "",
      jawab29: "",
      jawab30: "",
      jawab31: "",
      jawab32: "",
      jawab33: "",
      jawab34: "",
      jawab35: "",
      jawab36: "",
      jawab37: "",
      jawab38: "",
      jawab39: "",
      jawab40: "",
      jawab41: "",
      jawab42: "",
      no_pendaftaran: "",

     
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
            jawab1: this.jawab1,
            jawab2: this.jawab2,
            jawab3: this.jawab3,
            jawab4: this.jawab4,
            jawab5: this.jawab5,
            jawab6: this.jawab6,
            jawab7: this.jawab7,
            jawab8: this.jawab8,
            jawab9: this.jawab9,
            jawab10: this.jawab10,
            jawab11: this.jawab11,
            jawab12: this.jawab12,
            jawab13: this.jawab13,
            jawab14: this.jawab14,
            jawab15: this.jawab15,
            jawab16: this.jawab16,
            jawab17: this.jawab17,
            jawab18: this.jawab18,
            jawab19: this.jawab19,
            jawab20: this.jawab20,
            jawab21: this.jawab21,
            jawab22: this.jawab22,
            jawab23: this.jawab23,
            jawab24: this.jawab24,
            jawab25: this.jawab25,
            jawab26: this.jawab26,
            jawab27: this.jawab27,
            jawab28: this.jawab28,
            jawab29: this.jawab29,
            jawab30: this.jawab30,
            jawab31: this.jawab31,
            jawab32: this.jawab32,
            jawab33: this.jawab33,
            jawab34: this.jawab34,
            jawab35: this.jawab35,
            jawab36: this.jawab36,
            jawab37: this.jawab37,
            jawab38: this.jawab38,
            jawab39: this.jawab39,
            jawab40: this.jawab40,            
            jawab41: this.jawab41,            
            jawab42: this.jawab42
          },
        ],
      };

      await this.$axios({
        method: "post",
        headers: { "content-type": "application/json" },
        url: "/api/riasec",
        data: datax,
      })
        .then(() => {
          this.$router.push({
            name: "riasec",
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
