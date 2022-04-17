<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 4 - Figma
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari Figma, yaitu:</p>
          <ol>
            <li>Apa itu Figma?</li>
            <li>Kelebihan dan kekurangan Figma.</li>
            <li>How to setup a Frame and a Simple Grid?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Figma?</h2>
          <p>Figma adalah sebuah aplikasi berbasis web yang berfungsi sebagai editor grafis vector dan juga alat untuk membuat prototipe dari sebuah website. Aplikasi ini digunakan oleh banyak web desainer untuk mendesain sebuah website yang enak dipandang dan juga interaktif dengan fitur prototipenya. Selain itu, Figma ini juga populer dikalangan desainer vector pada umumnya. Aplikasi ini juga dilengkapi fitur offline yang dapat dijalankan di MacOS dan Windows.</p>
          <h2 style="margin-top: 15px">Kelebihan dan kekurangan Figma.</h2>
          <p>Ada beberapa kelebihan dari Figma, yaitu:</p>
          <ol>
            <li>Gratis (untuk 2 pengguna dan 3 projek dalam satu akun)</li>
            <li>Berjalan di MacOS dan Windows PC (Sketch hanya bisa di Mac)</li>
            <li>Bisa digunakan dalam kolaborasi tim dalam waktu yang real.</li>
            <li>Bisa mengimpor file Sketch (Tapi tidak bisa mengekspor Sketch)</li>
            <li>Terintegrasi dikalangan Developers</li>
            <li>Team library yang lengkap</li>
            <li>Kualitas tinggi prototipe yang terintegrasi/high-quality prototyping</li>
          </ol>
          <p style="margin-top:15px">Sedangkan kelemahannya, yaitu:</p>
          <ol>
            <li>Harus online</li>
            <li>Agak berat di laptop yang spesifikasinya kurang</li>
          </ol>
          <h2 style="margin-top: 15px">How to setup a Frame and a Simple Grid?</h2>
          <p>Dalam membuat Frame dan Grid yang simple ada 2 tahap di dalam materi, yaitu:</p>
          <ol>
            <li>Tahap 1</li>
            <p>Membuat file baru dan pilih Frame tool (F) dari toolbar. Setelahnya lihat ke sebelah kanan sidebar dan pilih template Dekstop untuk membuat Frame baru.</p>
            <li>Tahap 2</li>
            <p>Sebelum memulai mendesain, kita set up dulu grid yang simple yang bisa memudahkan untuk meluruskan element.</p>
            <p>Kita bisa lihat ke Design panel di sebelah kanan sidebar dan klik Layout Grid section untuk menambahkan grid ke desain yang akan kita buat.</p>
            <p>Setelahnya, klik ikon biru untuk mengakses pengaturan grid. Pilih Columns dari menu drop-down dan enter yang terlihat pada pengaturan.</p>
          </ol>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/04_screenshots/figma_homepage.png" style="width: 100%" />
        <img src="screenshots/04_screenshots/figma_tentangkamipage.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/04_screenshots/figma_faqpage.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section5"> Lanjutkan Section 5 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section4Page',
}
</script>
