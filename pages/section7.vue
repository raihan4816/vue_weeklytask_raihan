<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 7 - Bootstrap
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari Bootstrap, yaitu:</p>
          <ol>
            <li>Apa itu Bootstrap?</li>
            <li>Kenapa Bootstrap?</li>
            <li>Bagaimana cara memulai Bootstrap dan mengenal fitur class Bootstrap?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Bootstrap?</h2>
          <p>Bootstrap adalah sebuah framework front-end berbasis HTML & CSS yang memiliki aturan kode yang memudahkan programmer dalam membuat tampilan website.</p>
          <h2 style="margin-top: 15px">Kenapa Bootstrap?</h2>
          <p>Alasan kenpa kita memakai framework Bootstrap dalam membuat tampilan website adalah:</p>
          <ol>
            <li>Gratis</li>
            <li>Mudah Dipelajari</li>
            <li>Cepat</li>
            <li>Mendukung Responsif</li>
          </ol>
          <h2 style="margin-top: 15px">Bagaimana cara memulai Bootstrap dan mengenal fitur class Bootstrap?</h2>
          <p>Memulai Bootstrap langkahnya adalah:</p>
          <ol>
            <li>Untuk dapat menggunakan bootstrap, dapat langsung menuju website bootstrap dan unduh secara langsung di https://getbootstrap.com/docs/5.1/getting-started/download/</li>
            <li>Setelah mengunduh bootstrap, langkah selanjutnya adalah bisa dengan cara mempelajari example, ataupun mempelajari komponen-komponen yang ada pada bootstrap di https://getbootstrap.com/docs/5.1/layout/containers/</li>
          </ol>
          <p style="margin-top: 15px">Untuk fitur class pada Bootstrap terdapat:</p> 
          <ol>
            <li>Container: container, container-fluid.</li>
            <li>Row: row</li>
            <li>Column: col-md-12, col-lg-12, col-sm-6, dll.</li>
            <li>Button: btn-primary, btn-success, btn-danger, dll.</li>
          </ol>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/07_screenshots/bootstrap-1.png" style="width: 100%" />
        <img src="screenshots/07_screenshots/bootstrap-2.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/07_screenshots/bootstrap-3.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section8"> Lanjutkan Section 8 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section7Page',
}
</script>
