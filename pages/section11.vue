<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 11 - Vue Fundamental
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari Vue Fundamental, yaitu:</p>
          <ol>
            <li>Apa itu Vue Fundamental?</li>
            <li>Kenapa Vue?</li>
            <li>Bagaimana cara kerja Vue?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Vue Fundamental?</h2>
          <p>Vue adalah framework dari Javascript untuk mengembangkan tampilan website yang lebih interaktif, dinamis, dan menyenangkan. Framework Vue mirip seperti React, Angular, dan lainnya karena berbasis Javascript.</p>
          <h2 style="margin-top: 15px">Kenapa Vue?</h2>
          <ul>
            <li>Mudah membuat aplikasi frontend dan website.</li>
            <li>Mudah dipelajari dan menyenangkan.</li>
            <li>Dokumentasi yang lengkap dan rapi.</li>
            <li>Ramping dan cepat</li>
          </ul>
          <h2 style="margin-top: 15px">Bagaimana cara kerja Vue?</h2>
          <p>Cara kerja vue itu ada dua, yakni:</p>
          <ol>
            <li>Vue CDN</li>
            <li>Vue CLI</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Vue CDN?</h2>
          <p>Vue dapat digunakan langsung di file HTML dengan menambahkan.</p>
          <h2 style="margin-top: 15px">Apa itu Vue CLI?</h2>
          <p>Menggunakan perkakas standar dari ekosistem Vue untuk memudahkan setup/pembuatan aplikasi Vue.</p>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/11_screenshots/latihan_1.png" style="width: 100%" />
        <img src="screenshots/11_screenshots/latihan_2.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/11_screenshots/latihan_3.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/"> Kembali ke Homepage </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section11Page',
}
</script>
