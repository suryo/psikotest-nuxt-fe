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
                      <td><input type="text" id="riasec1" name="riasec1" class="form-control"></td>
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
                        <input type="text" id="riasec2" name="riasec2" class="form-control"></td>
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
                      <td><input type="text" id="riasec3" name="riasec3" class="form-control"></td>
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
                      <td><input type="text" id="riasec4" name="riasec4" class="form-control"></td>
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
                      <td><input type="text" id="riasec5" name="riasec5" class="form-control"></td>
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
                      <td><input type="text" id="riasec6" name="riasec6" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>7</td>
                      <td>Saya suka merancang sesuatu</td>
                      <td><input type="text" id="riasec7" name="riasec7" class="form-control"></td>
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
                      <td><input type="text" id="riasec8" name="riasec8" class="form-control"></td>
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
                      <td><input type="text" id="riasec9" name="riasec9" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>10</td>
                      <td>Saya suka membujuk atau mempengaruhi orang lain</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec10" name="riasec10" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>11</td>
                      <td>Saya suka melakukan eksperimen</td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec11" name="riasec11" class="form-control"></td>
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
                        <input type="text" id="riasec12" name="riasec12" class="form-control"></td>
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
                        <input type="text" id="riasec13" name="riasec13" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>14</td>
                      <td>Saya suka merawat binatang</td>
                      <td>
                        <input type="text" id="riasec14" name="riasec14" class="form-control"></td>
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
                        <input type="text" id="riasec15" name="riasec15" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>16</td>
                      <td>Saya suka menjual barang</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec16" name="riasec16" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>17</td>
                      <td>Saya suka menulis kreatif</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec17" name="riasec17" class="form-control"></td>
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
                        <input type="text" id="riasec18" name="riasec18" class="form-control"></td>
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
                        <input type="text" id="riasec19" name="riasec19" class="form-control"></td>
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
                        <input type="text" id="riasec20" name="riasec20" class="form-control"></td>
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
                        <input type="text" id="riasec21" name="riasec21" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>22</td>
                      <td>Saya suka merakit dan merangkai sesuatu</td>
                      <td>
                        <input type="text" id="riasec22" name="riasec22" class="form-control"></td>
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
                        <input type="text" id="riasec23" name="riasec23" class="form-control"></td>
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
                        <input type="text" id="riasec24" name="riasec24" class="form-control"></td>
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
                        <input type="text" id="riasec25" name="riasec25" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>26</td>
                      <td>
                        Saya suka menganalisis sesuatu (masalah / situasi)
                      </td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec26" name="riasec26" class="form-control"></td>
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
                        <input type="text" id="riasec27" name="riasec27" class="form-control"></td>
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
                        <input type="text" id="riasec28" name="riasec28" class="form-control"></td>
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
                        <input type="text" id="riasec29" name="riasec29" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>30</td>
                      <td>Saya suka memasak</td>
                      <td>
                        <input type="text" id="riasec30" name="riasec30" class="form-control"></td>
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
                        <input type="text" id="riasec31" name="riasec31" class="form-control"></td>
                      <td></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>32</td>
                      <td>Saya orang yang praktis</td>
                      <td>
                        <input type="text" id="riasec32" name="riasec32" class="form-control"></td>
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
                        <input type="text" id="riasec33" name="riasec33" class="form-control"></td>
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
                        <input type="text" id="riasec34" name="riasec34" class="form-control"></td>
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
                        <input type="text" id="riasec35" name="riasec35" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>36</td>
                      <td>Saya suka memimpin</td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec36" name="riasec36" class="form-control"></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>37</td>
                      <td>Saya suka bekerja di luar ruangan</td>
                      <td>
                        <input type="text" id="riasec37" name="riasec37" class="form-control"></td>
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
                        <input type="text" id="riasec38" name="riasec38" class="form-control"></td>
                    </tr>
                    <tr>
                      <td>39</td>
                      <td>Saya pandai matematika</td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec39" name="riasec39" class="form-control"></td>
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
                        <input type="text" id="riasec40" name="riasec40" class="form-control"></td>
                      <td></td>
                      <td></td>
                    </tr>
                    <tr>
                      <td>41</td>
                      <td>Saya suka menggambar</td>
                      <td></td>
                      <td></td>
                      <td>
                        <input type="text" id="riasec41" name="riasec41" class="form-control"></td>
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
                        <input type="text" id="riasec42" name="riasec42" class="form-control"></td>
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
      jwb31: "",
      jwb32: "",
      jwb33: "",
      jwb34: "",
      jwb35: "",
      jwb36: "",
      jwb37: "",
      jwb38: "",
      jwb39: "",
      jwb40: "",
      jwb41: "",
      jwb42: "",
      jwb43: "",
      jwb44: "",
      jwb45: "",
      jwb46: "",
      jwb47: "",
      jwb48: "",
      jwb49: "",
      jwb50: "",
      jwb51: "",
      jwb52: "",
      jwb53: "",
      jwb54: "",
      jwb55: "",
      jwb56: "",
      jwb57: "",
      jwb58: "",
      jwb59: "",
      jwb60: "",
      jwb61: "",
      jwb62: "",
      jwb63: "",
      jwb64: "",
      jwb65: "",
      jwb66: "",
      jwb67: "",
      jwb68: "",
      jwb69: "",
      jwb70: "",
      jwb71: "",
      jwb72: "",
      jwb73: "",
      jwb74: "",
      jwb75: "",
      jwb76: "",
      jwb77: "",
      jwb78: "",
      jwb79: "",
      jwb80: "",
      jwb81: "",
      jwb82: "",
      jwb83: "",
      jwb84: "",
      jwb85: "",
      jwb86: "",
      jwb87: "",
      jwb88: "",
      jwb89: "",
      jwb90: "",

      provinsi: {
        provinsi: "",
      },
      //state validation
      validation: [],
    };
  },

  methods: {
    //method "store"
    async store(e) {
      e.preventDefault();

      //send data ke Rest API
      await this.$axios
        .post("/api/provinsi", {
          //data yang dikirim ke server
          provinsi: this.provinsi.provinsi,
        })
        .then(() => {
          //redirect ke route "post"
          this.$router.push({
            name: "provinsi",
          });
        })
        .catch((error) => {
          //assign validation
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
