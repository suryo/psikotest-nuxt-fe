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
                  <label>1.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb1" value="0" /> Saya
                      seorang pekerja keras
                    </li>
                    <li>
                      <input type="radio" v-model="jwb1" value="1" /> saya bukan
                      seorang pemurung
                    </li>
                  </ul>

                  <label>2.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb2" value="0" /> Saya suka
                      bekerja lebih baik dari yang lain
                    </li>
                    <li>
                      <input type="radio" v-model="jwb2" value="1" /> Saya suka
                      menekuni pekerjaan yang saya lakukan sampai selesai
                    </li>
                  </ul>

                  <label>3.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb3" value="0" /> saya suka
                      memberi petunjuk kepada orang bagaimana melakukan sesuatu
                    </li>
                    <li>
                      <input type="radio" v-model="jwb3" value="1" /> Saya ingin
                      berbuat semaksimal mungkin
                    </li>
                  </ul>

                  <label>4.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb4" value="0" /> saya suka
                      melakukan hal-hal yang lucu
                    </li>
                    <li>
                      <input type="radio" v-model="jwb4" value="1" /> Saya suka
                      memberitahukan orang apa yang harus dikerjakan
                    </li>
                  </ul>

                  <label>5.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb5" value="0" /> Saya suka
                      bergabung dalam kelompok
                    </li>
                    <li>
                      <input type="radio" v-model="jwb5" value="1" /> saya suka
                      Jika diperhatikan oleh kelompok
                    </li>
                  </ul>

                  <label>6.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb6" value="0" /> saya suka
                      membuat teman pribadi yang dekat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb6" value="1" /> saya suka
                      Jika diperhatikan oleh kelompok
                    </li>
                  </ul>

                  <label>7.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb7" value="0" /> saya cepat
                      berubah jika saya diperlukan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb7" value="1" /> Saya
                      berusaha membuat teman-teman pribadi yang dekat
                    </li>
                  </ul>

                  <label>8.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb8" value="0" /> saya suka
                      membalas jika saya disakiti
                    </li>
                    <li>
                      <input type="radio" v-model="jwb8" value="1" /> Saya suka
                      melakukan hal-hal yang baru dan berbeda
                    </li>
                  </ul>

                  <label>9.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb9" value="0" /> Saya ingin
                      agar atasan menyukai saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb9" value="1" /> saya suka
                      memberitahu orang jika mereka salah
                    </li>
                  </ul>

                  <label>10.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb10" value="0" /> Saya suka
                      mengikuti petunjuk-petunjuk yang diberikan kepada saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb10" value="1" /> Saya suka
                      mendukung pendapat atasan saya
                    </li>
                  </ul>

                  <label>11.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb11" value="0" /> Saya
                      berusaha sangat keras
                    </li>
                    <li>
                      <input type="radio" v-model="jwb11" value="1" /> Saya
                      seorang yang teratur titik Saya menaruh semua barang pada
                      tempatnya
                    </li>
                  </ul>

                  <label>12.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb12" value="0" /> saya
                      dapat membuat orang melakukan apa yang saya inginkan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb12" value="1" /> saya
                      tidak mudah marah
                    </li>
                  </ul>

                  <label>13.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb13" value="0" /> Saya suka
                      memberitahukan kepada kelompok apa yang harus mereka
                      kerjakan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb13" value="1" /> saya
                      selalu menekuni suatu pekerjaan sampai selesai
                    </li>
                  </ul>

                  <label>14.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb14" value="0" /> saya
                      ingin tampil menarik dan mendebarkan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb14" value="1" /> saya
                      ingin menjadi orang yang sangat berhasil
                    </li>
                  </ul>

                  <label>15.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb15" value="0" /> Saya
                      ingin sesuai dan diterima dalam kelompok
                    </li>
                    <li>
                      <input type="radio" v-model="jwb15" value="1" /> Saya suka
                      membantu orang dalam mengambil keputusan
                    </li>
                  </ul>

                  <label>16.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb16" value="0" /> saya
                      cemas bila seseorang tidak menyukai saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb16" value="1" /> Saya suka
                      orang memperhatikan saya
                    </li>
                  </ul>

                  <label>17.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb17" value="0" /> Saya suka
                      mencoba hal-hal baru
                    </li>
                    <li>
                      <input type="radio" v-model="jwb17" value="1" /> saya
                      lebih suka bekerja bersama orang lain daripada sendirian
                    </li>
                  </ul>

                  <label>18.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb18" value="0" /> saya
                      kadang-kadang menyalahkan orang lain jika terjadi
                      kesalahan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb18" value="1" /> saya
                      merasa terganggu Jika ada yang tidak menyukai saya
                    </li>
                  </ul>

                  <label>19.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb19" value="0" /> Saya suka
                      mendukung pendapat atasan saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb19" value="1" /> saya Suka
                      mencoba pekerjaan-pekerjaan yang baru dan berbeda
                    </li>
                  </ul>

                  <label>20.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb20" value="0" /> Saya
                      menyukai petunjuk-petunjuk terperinci dalam menyelesaikan
                      pekerjaan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb20" value="1" /> bila saya
                      terganggu oleh siapapun, saya akan memberitahukannya
                    </li>
                  </ul>

                  <label>21.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb21" value="0" /> Saya suka
                      melaksanakan tugas setiap langkah dengan hati-hati
                    </li>
                    <li>
                      <input type="radio" v-model="jwb21" value="1" /> saya
                      selalu berusaha keras
                    </li>
                  </ul>

                  <label>22.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb22" value="0" /> saya
                      benar-benar pemimpin yang baik
                    </li>
                    <li>
                      <input type="radio" v-model="jwb22" value="1" /> saya
                      dapat mengorganisir suatu pekerjaan dengan baik
                    </li>
                  </ul>

                  <label>23.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb23" value="0" /> saya
                      mudah tersinggung
                    </li>
                    <li>
                      <input type="radio" v-model="jwb23" value="1" /> saya
                      lamban mengambil keputusan
                    </li>
                  </ul>

                  <label>24.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb24" value="0" /> bila saya
                      berada dalam satu kelompok saya suka berdiam diri
                    </li>
                    <li>
                      <input type="radio" v-model="jwb24" value="1" /> saya suka
                      mengerjakan beberapa pekerjaan sekaligus
                    </li>
                  </ul>

                  <label>25.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb25" value="0" /> Saya
                      sangat suka bila saya diundang
                    </li>
                    <li>
                      <input type="radio" v-model="jwb25" value="1" /> Saya
                      ingin lebih baik dari yang lain dalam mengerjakan sesuatu
                    </li>
                  </ul>

                  <label>26.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb26" value="0" /> Saya suka
                      membuat teman-teman pribadi yang dekat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb26" value="1" /> saya
                      suka  menasehati orang lain
                    </li>
                  </ul>

                  <label>27.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb27" value="0" /> Saya suka
                      melakukan hal-hal baru dan berbeda
                    </li>
                    <li>
                      <input type="radio" v-model="jwb27" value="1" /> Saya suka
                      menceritakan bagaimana saya berhasil dalam melakukan
                      sesuatu
                    </li>
                  </ul>

                  <label>28.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb28" value="0" /> bila saya
                      betul, saya suka mempertahankannya.
                    </li>
                    <li>
                      <input type="radio" v-model="jwb28" value="1" /> saya suka
                      ingin diterima dan diakui dalam suatu kelompok
                    </li>
                  </ul>

                  <label>29.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb29" value="0" /> saya
                      menghindar menjadi orang yang berbeda
                    </li>
                    <li>
                      <input type="radio" v-model="jwb29" value="1" /> Saya
                      berusaha menjadi sangat dekat dengan orang
                    </li>
                  </ul>

                  <label>30.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb30" value="0" /> Saya
                      senang memberitahukan bagaimana melakukan sesuatu
                      pekerjaan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb30" value="1" /> saya
                      mudah bosan
                    </li>
                  </ul>

                  <label>31.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb31" value="0" /> Saya
                      bekerja keras
                    </li>
                    <li>
                      <input type="radio" v-model="jwb31" value="1" /> saya
                      banyak berpikir dan merencana 
                    </li>
                  </ul>

                  <label>32.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb32" value="0" /> Saya
                      memimpin kelompok
                    </li>
                    <li>
                      <input type="radio" v-model="jwb32" value="1" /> detail
                      (hal-hal kecil) menarik bagi saya
                    </li>
                  </ul>

                  <label>33.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb33" value="0" /> saya
                      dapat mengambil keputusan secara mudah dan tepat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb33" value="1" /> saya
                      menyimpan barang-barang saya secara rapi dan teratur
                    </li>
                  </ul>

                  <label>34.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb34" value="0" /> saya
                      cepat dalam melaksanakan suatu pekerjaan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb34" value="1" /> saya
                      tidak sering marah atau sedih
                    </li>
                  </ul>

                  <label>35.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb35" value="0" /> Saya
                      ingin menjadi bagian dari kelompok
                    </li>
                    <li>
                      <input type="radio" v-model="jwb35" value="1" /> saya
                      hanya ingin melakukan satu pekerjaan pada satu saat
                    </li>
                  </ul>

                  <label>36.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb36" value="0" /> Saya
                      berusaha membuat teman dekat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb36" value="1" /> Saya
                      berusaha keras menjadi yang terbaik
                    </li>
                  </ul>

                  <label>37.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb37" value="0" /> Saya suka
                      mode terbaru untuk pakaian atau mobil
                    </li>
                    <li>
                      <input type="radio" v-model="jwb37" value="1" /> saya suka
                      bertanggung jawab untuk kepentingan orang lain
                    </li>
                  </ul>

                  <label>38.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb38" value="0" /> Saya 
                      menyukai perdebatan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb38" value="1" /> Saya suka
                      mendapatkan perhatian
                    </li>
                  </ul>

                  <label>39.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb39" value="0" /> Saya suka
                      mendukung orang-orang yang menjadi atasan saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb39" value="1" /> Saya
                      tertarik menjadi bagian dari kelompok
                    </li>
                  </ul>

                  <label>40.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb40" value="0" /> saya suka
                      mengikuti peraturan dengan hati-hati
                    </li>
                    <li>
                      <input type="radio" v-model="jwb40" value="1" /> saya suka
                      orang mengenal saya dengan baik
                    </li>
                  </ul>

                  <label>41.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb41" value="0" /> Saya
                      benar-benar bekerja keras
                    </li>
                    <li>
                      <input type="radio" v-model="jwb41" value="1" /> Saya
                      mempunyai sifat bersahabat
                    </li>
                  </ul>

                  <label>42.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb42" value="0" /> orang
                      berpendapat bahwa saya benar-benar seorang pemimpin yang
                      baik
                    </li>
                    <li>
                      <input type="radio" v-model="jwb42" value="1" /> saya
                      berpikir panjang dan berhati-hati
                    </li>
                  </ul>

                  <label>43.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb43" value="0" /> saya
                      sering mengambil kesempatan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb43" value="1" /> saya
                      senang mengurus hal-hal kecil
                    </li>
                  </ul>

                  <label>44.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb44" value="0" /> orang
                      berpendapat bahwa saya bekerja cepat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb44" value="1" /> orang
                      berpendapat bahwa saya rapi dan teratur
                    </li>
                  </ul>

                  <label>45.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb45" value="0" /> Saya
                      senang berolahraga
                    </li>
                    <li>
                      <input type="radio" v-model="jwb45" value="1" /> Saya
                      mempunyai pribadi yang menyenangkan
                    </li>
                  </ul>

                  <label>46.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb46" value="0" /> Saya
                      senang jika orang dekat dan bersahabat dengan saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb46" value="1" /> Saya
                      selalu berusaha untuk menyelesaikan sesuatu yang telah
                      saya mulai
                    </li>
                  </ul>

                  <label>47.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb47" value="0" /> saya
                      senang bereksperimen dan mencoba hal-hal baru
                    </li>
                    <li>
                      <input type="radio" v-model="jwb47" value="1" /> saya suka
                      melaksanakan suatu pekerjaan sulit dengan baik
                    </li>
                  </ul>

                  <label>48.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb48" value="0" /> saya suka
                      diperlakukan secara adil
                    </li>
                    <li>
                      <input type="radio" v-model="jwb48" value="1" /> Saya suka
                      memberitahu orang lain bagaimana melaksanakan sesuatu
                    </li>
                  </ul>

                  <label>49.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb49" value="0" /> Saya suka
                      melakukan apa yang diharapkan dari saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb49" value="1" /> saya suka
                      memperoleh perhatian
                    </li>
                  </ul>

                  <label>50.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb50" value="0" /> Saya suka
                      petunjuk-petunjuk terperinci dalam melaksanakan suatu
                      pekerjaan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb50" value="1" /> saya suka
                      berada diantara orang-orang banyak
                    </li>
                  </ul>

                  <label>51.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb51" value="0" /> saya
                      selalu Berusaha menyelesaikan pekerjaan secara sempurna
                    </li>
                    <li>
                      <input type="radio" v-model="jwb51" value="1" /> orang
                      Mengatakan bahwa saya tidak mengenal lelah
                    </li>
                  </ul>

                  <label>52.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb52" value="0" /> Saya tipe
                      pemimpin
                    </li>
                    <li>
                      <input type="radio" v-model="jwb52" value="1" /> saya
                      mudah berteman
                    </li>
                  </ul>

                  <label>53.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb53" value="0" /> saya
                      selalu berspekulasi
                    </li>
                    <li>
                      <input type="radio" v-model="jwb53" value="1" /> saya
                      banyak sekali berpikir
                    </li>
                  </ul>

                  <label>54.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb54" value="0" /> Saya
                      bekerja dengan kecepatan yang teratur
                    </li>
                    <li>
                      <input type="radio" v-model="jwb54" value="1" /> Saya
                      senang bekerja dengan hal-hal kecil atau terperinci
                    </li>
                  </ul>

                  <label>55.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb55" value="0" /> Saya
                      mempunyai banyak tenaga untuk berolahraga
                    </li>
                    <li>
                      <input type="radio" v-model="jwb55" value="1" /> saya
                      menyimpan barang-barang saya secara rapi dan teratur
                    </li>
                  </ul>

                  <label>56.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb56" value="0" /> saya
                      dapat bergaul dengan baik terhadap semua orang
                    </li>
                    <li>
                      <input type="radio" v-model="jwb56" value="1" /> saya
                      seorang yang mempunyai pembawaan yang tenang (even
                      tempered)
                    </li>
                  </ul>

                  <label>57.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb57" value="0" />Saya ingin
                      bertemu dengan orang-orang baru dan melakukan hal yang
                      baru
                    </li>
                    <li>
                      <input type="radio" v-model="jwb57" value="1" /> saya
                      selalu ingin menyelesaikan pekerjaan yang telah saya mulai
                    </li>
                  </ul>

                  <label>58.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb58" value="0" /> Saya
                      biasanya mempertahankan pendapat yang saya yakini
                    </li>
                    <li>
                      <input type="radio" v-model="jwb58" value="1" /> Saya
                      biasanya suka bekerja keras
                    </li>
                  </ul>

                  <label>59.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb59" value="0" /> Saya suka
                      saran-saran dari orang-orang yang saya kagumi
                    </li>
                    <li>
                      <input type="radio" v-model="jwb59" value="1" /> Saya suka
                      melayani orang-orang yang berwenang terhadap saya
                    </li>
                  </ul>

                  <label>60.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb60" value="0" /> saya
                      biarkan diri saya banyak dipengaruhi oleh orang lain
                    </li>
                    <li>
                      <input type="radio" v-model="jwb60" value="1" /> Saya suka
                      jika mendapat banyak perhatian
                    </li>
                  </ul>

                  <label>61.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb61" value="0" /> Saya
                      berusaha bekerja keras
                    </li>
                    <li>
                      <input type="radio" v-model="jwb61" value="1" /> Saya
                      mengerjakan sesuatu dengan cepat
                    </li>
                  </ul>

                  <label>62.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb62" value="0" /> apabila
                      saya bicara, kelompok mendengarkan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb62" value="1" /> saya
                      terampil dengan perkakas (alat-alat)
                    </li>
                  </ul>

                  <label>63.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb63" value="0" /> saya
                      lambat dalam mendapatkan teman
                    </li>
                    <li>
                      <input type="radio" v-model="jwb63" value="1" /> saya
                      lambat dalam mengambil keputusan
                    </li>
                  </ul>

                  <label>64.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb64" value="0" /> Saya
                      biasanya makan secara cepat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb64" value="1" /> Saya suka
                      membaca
                    </li>
                  </ul>

                  <label>65.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb65" value="0" /> Saya suka
                      pekerjaan dimana saya banyak bergerak
                    </li>
                    <li>
                      <input type="radio" v-model="jwb65" value="1" /> Saya suka
                      pekerjaan yang harus dilaksanakan secara hati-hati
                    </li>
                  </ul>

                  <label>66.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb66" value="0" /> saya
                      membuat sebanyak mungkin teman
                    </li>
                    <li>
                      <input type="radio" v-model="jwb66" value="1" /> apa yang
                      telah saya simpan, akan mudah saya temukan kembali
                    </li>
                  </ul>

                  <label>67.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb67" value="0" /> saya
                      merencanakan jauh-jauh sebelumnya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb67" value="1" /> saya
                      selalu menyenangkan
                    </li>
                  </ul>

                  <label>68.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb68" value="0" /> saya
                      mempertahan Dengan bangga nama baik saya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb68" value="1" /> saya
                      terus menekuni suatu masalah sampai selesai
                    </li>
                  </ul>

                  <label>69.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb69" value="0" /> saya suka
                      mendukung orang-orang yang saya kagumi
                    </li>
                    <li>
                      <input type="radio" v-model="jwb69" value="1" /> Saya
                      ingin sukses
                    </li>
                  </ul>

                  <label>70.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb70" value="0" /> Saya suka
                      orang lain yang membuat keputusan-keputusan untuk kelompok
                    </li>
                    <li>
                      <input type="radio" v-model="jwb70" value="1" /> saya suka
                      membuat keputusan-keputusan untuk kelompok
                    </li>
                  </ul>

                  <label>71.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb71" value="0" /> saya
                      selaku berusaha bekerja keras
                    </li>
                    <li>
                      <input type="radio" v-model="jwb71" value="1" /> saya
                      mengambil keputusan secara cepat dan mudah
                    </li>
                  </ul>

                  <label>72.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb72" value="0" /> kelompok
                      biasanya melakukan apa yang saya inginkan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb72" value="1" /> saya
                      biasanya terburu-buru
                    </li>
                  </ul>

                  <label>73.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb73" value="0" /> saya
                      sering merasa lelah
                    </li>
                    <li>
                      <input type="radio" v-model="jwb73" value="1" /> Saya
                      lambat menentukan sikap
                    </li>
                  </ul>

                  <label>74.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb74" value="0" /> saya
                      bekerja cepat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb74" value="1" /> saya
                      mudah berteman
                    </li>
                  </ul>

                  <label>75.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb75" value="0" /> Saya
                      biasanya mempunyai Gairah dan tenaga
                    </li>
                    <li>
                      <input type="radio" v-model="jwb75" value="1" /> saya
                      banyak menghabiskan waktu dengan berpikir
                    </li>
                  </ul>

                  <label>76.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb76" value="0" /> saya
                      sangat ramah terhadap orang
                    </li>
                    <li>
                      <input type="radio" v-model="jwb76" value="1" /> Saya suka
                      dengan pekerjaan yang memerlukan ketelitian
                    </li>
                  </ul>

                  <label>77.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb77" value="0" /> saya
                      banyak berpikir dan merencana
                    </li>
                    <li>
                      <input type="radio" v-model="jwb77" value="1" /> saya
                      menyimpan segala sesuatu pada tempatnya
                    </li>
                  </ul>

                  <label>78.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb78" value="0" /> Saya suka
                      pekerjaan yang menuntut hal-hal terperinci
                    </li>
                    <li>
                      <input type="radio" v-model="jwb78" value="1" /> Saya
                      tidak mudah marah
                    </li>
                  </ul>

                  <label>79.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb79" value="0" /> Saya suka
                      mengikuti orang yang saya kagumi
                    </li>
                    <li>
                      <input type="radio" v-model="jwb79" value="1" /> saya
                      selalu menyelesaikan pekerjaan yang telah saya mulai
                    </li>
                  </ul>

                  <label>80.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb80" value="0" /> Saya suka
                      petunjuk yang jelas
                    </li>
                    <li>
                      <input type="radio" v-model="jwb80" value="1" /> Saya suka
                      bekerja keras
                    </li>
                  </ul>

                  <label>81.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb81" value="0" /> saya
                      mengejar apa yang saya inginkan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb81" value="1" /> saya
                      seorang pemimpin yang baik
                    </li>
                  </ul>

                  <label>82.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb82" value="0" /> saya
                      dapat membuat orang lain bekerja sesuai dengan yang saya
                      inginkan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb82" value="1" /> saya
                      seorang yang bertipe santai tapi beruntung
                    </li>
                  </ul>

                  <label>83.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb83" value="0" /> saya
                      mengambil keputusan secara tepat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb83" value="1" /> Saya
                      ingin berbuat semaksimal mungkin
                    </li>
                  </ul>

                  <label>84.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb84" value="0" /> saya
                      biasanya bekerja cepat
                    </li>
                    <li>
                      <input type="radio" v-model="jwb84" value="1" /> Saya suka
                      berolahraga secara teratur
                    </li>
                  </ul>

                  <label>85.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb85" value="0" /> Saya
                      tidak suka bertemu orang
                    </li>
                    <li>
                      <input type="radio" v-model="jwb85" value="1" /> saya
                      cepat merasa lelah
                    </li>
                  </ul>

                  <label>86.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb86" value="0" /> Saya
                      membuat banyak sekali teman
                    </li>
                    <li>
                      <input type="radio" v-model="jwb86" value="1" /> saya
                      banyak menghabiskan waktu dengan berpikir
                    </li>
                  </ul>

                  <label>87.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb87" value="0" /> Saya suka
                      bekerja dengan teori
                    </li>
                    <li>
                      <input type="radio" v-model="jwb87" value="1" /> Saya suka
                      bekerja dengan hal-hal terperinci
                    </li>
                  </ul>

                  <label>88.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb88" value="0" /> saya
                      dapat menikmati hal-hal atau pekerjaan yang terperinci
                    </li>
                    <li>
                      <input type="radio" v-model="jwb88" value="1" /> Saya suka
                      mengorganisir pekerjaan saya
                    </li>
                  </ul>

                  <label>89.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb89" value="0" /> Saya
                      menaruh barang pada tempatnya
                    </li>
                    <li>
                      <input type="radio" v-model="jwb89" value="1" /> Saya
                      selalu menyenangkan
                    </li>
                  </ul>

                  <label>90.</label>
                  <ul>
                    <li>
                      <input type="radio" v-model="jwb90" value="0" /> Saya suka
                      diberitahu tentang apa yang saya perlu lakukan
                    </li>
                    <li>
                      <input type="radio" v-model="jwb90" value="1" /> saya
                      harus menyelesaikan apa yang saya mulai 
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
