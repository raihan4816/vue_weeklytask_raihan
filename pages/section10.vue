<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 10 - Frontend Fundamental
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari Frontend Fundamental, yaitu:</p>
          <ol>
            <li>Apa yang dipelajari di Frontend Fundamental?</li>
            <li>Apa itu Media Queries?</li>
            <li>Apa itu NPM dan Bagaimana cara kerja dan struktur proyek NPM?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa yang dipelajari di Frontend Fundamental?</h2>
          <p>Yang dipelajari dari materi Frontend Fundamental adalah:</p>
          <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Node.js</li>
            <li>NPM</li>
            <li>Git</li>
          </ul>
          <h2 style="margin-top: 15px">Apa itu Media Queries?</h2>
          <p>Media Queries/Media Query adalah sebuah modul CSS yang mana memungkinkan kita untuk membuat layout atau tampilan yang dibuat menjad lebih responsive dengan menyesuaikan tampilan berdasarkan ukuran layar perangkat/devices kita. Media query ini biasanya disetting dengan patokan width pixel sesuai kemampuan device.</p>
          <h2 style="margin-top: 15px">Apa itu NPM dan Bagaimana cara kerja dan struktur proyek NPM?</h2>
          <h2 style="margin-top: 15px">Apa itu NPM</h2>
          <p>NPM atau Node Package Manager adalah sebuah tool atau alat berupa command line yang berfungsi untuk menginstall dan meng-uninstall package, mengelola versi, dan dependensi yang diperlukan untuk menjalankan proyek.</p>
          <h2 style="margin-top: 15px">Cara Kerja NPM</h2>
          <p>NPM bekerja untuk mengatur package pada proyek yang berjalan dengan node.js. Package pada nodejs memuat semua file yang dibutuhkan seagai module. Module adalah library Javascript yang dapat kita masukkan ke dalam proyek.</p>
          <h2 style="margin-top: 15px">Struktur Proyek NPM</h2>
          <p>Untuk membuat proyek aplikasi, jalankan perintah "$npm init" kemudian tekan enter untuk semua pertanyaan di bawahnya. Lalu, sebuah file berama package.json akkan muncul pada direktori proyek.</p>
          <p>Key yang penting untuk diingat:</p>
          <ul>
            <li><i>name</i> adalah nama proyek</li>
            <li><i>scripts</i> adalah daftar perintah yang bisa kita jalankan di dalam proyek, contoh: <i>npm run tes</i></li>
            <li><i>dependencies</i> adalah daftar library yang dipakai di proyek ketika production.</li>
            <li><i>devDependencies</i> adalah daftar library yang dipakai di proyek ketika tahap pengembangan.</li>
          </ul>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/10_screenshots/latihan_0-600px.png" style="width: 100%" />
        <img src="screenshots/10_screenshots/latihan_600-960px.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/10_screenshots/latihan_960-1366px.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section11"> Lanjutkan Section 11 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section10Page',
}
</script>
