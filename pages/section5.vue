<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 5 - HTML
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari HTML, yaitu:</p>
          <ol>
            <li>Apa itu HTML?</li>
            <li>Apa kegunaan HTML?</li>
            <li>Bagaimana struktur Halaman HTML?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu HTML?</h2>
          <p>HTML (Hypertext Markup Language) adalah sebuah standar yang digunakan secara luas untuk menampilkan halaman web. HTML biasa digunakan sebagai basis awal website untuk menampilkan tampilan ke pengguna. Bahasa Markup ini memiliki 3 penyusun utama yaitu Tag, Element, dan Attribute.</p>
          <h2 style="margin-top: 15px">Apa kegunaan HTML?</h2>
          <p>Kegunaan HTML, yaitu:</p>
          <ul>
            <li>Membuat struktur dari halaman website.</li>
            <li>Mengatur tampilan dan isi dari halaman web.</li>
            <li>Membuat tabel dengan tag HTML table.</li>
            <li>Membuat form HTML.</li>
            <li>Membuat gambar dengan canvas.</li>
            <li>Mempublikasikan halaman website secara online.</li>
          </ul>
          <h2 style="margin-top: 15px">Bagaimana struktur Halaman HTML?</h2>
          <p>Struktur HTML terdiri dari:</p>
            <img src="html.png" style="width: 100%" />  
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/05_screenshots/index.png" style="width: 100%" />
        <img src="screenshots/05_screenshots/form.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/05_screenshots/welcome.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section6"> Lanjutkan Section 6 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section5Page',
}
</script>
