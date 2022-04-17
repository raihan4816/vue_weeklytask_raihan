<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 8 - JavaScript Refreshment
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari Javascript Refreshment, yaitu:</p>
          <ol>
            <li>Apa itu Javascript?</li>
            <li>Apa itu Declaration?</li>
            <li>Apa itu Destructuring?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Javascript?</h2>
          <p>JavaScript adalah Bahasa Pemrograman yang High-Level, Scripting, Untyped, dan Interpreted. Bahasa JavaScript biasanya digunakan dalam bidang Front-End atau pembuatan web. JavaScript digunakan untuk membuat website menjadi lebih fluid dan interaktif sehingga pengguna dapat meggunakannya dengan nyaman.</p>
          <h2 style="margin-top: 15px">Apa itu Declaration?</h2>
          <p>Declaration adalah proses pembuatan variabel untuk menyimpan data. Dalam declaration, ada yang bernama variabel yang terdiri dari Var, Let, dan Const.</p>
          <ol>
            <li>Var</li>
            <p>Var adalah sebuah declaration berupa variabel yang dapat digunakan untuk menyimpan data. Var adalah versi pertama dari let dan var sekarang ini sudah jarang digunakan.</p>
            <li>Let</li>
            <p>Let sama seperti Var adalah sebuah declaration berupa variabel yang dapat digunakan untuk menyimpan data. Let dianjurkan digunakan karena diperbarui di tahun 2015 yang namanya ECMAScript 2015.</p>
            <li>Const</li>
            <p>Const adalah sebuah declaration berupa variabel yang dapat digunakan untuk menyimpan data. Akan tetapi, Const tidak reassignable/tidak bisa di replace datanya. Const ini biasanya digunakan ketika menuliskan data yang fixed dan tidak akan diubah.</p>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Destructuring?</h2>
          <p>Destructuring adalah ekspresi dari JavaScript yang memungkinkan untuk menyalin nilai dari array, atau properti dari objek, ke dalam variabel yang berbeda. Di dalam Destructuring kita bisa membongkar isi array dan objek untuk disimpan pada beberapa variabel dan akhirnya kita dapat menghemat kode secara signifikan.</p>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/08_screenshots/javascript.png" style="width: 100%" />
        <img src="screenshots/08_screenshots/javascriptno3.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/08_screenshots/javascriptno4.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/08_screenshots/javascriptno5.png" style="width: 100%" />
        <img src="screenshots/08_screenshots/javascriptno6.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section9"> Lanjutkan Section 9 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section8Page',
}
</script>
