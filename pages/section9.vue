<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 9 - Clean Code
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari Clean Code, yaitu:</p>
          <ol>
            <li>Apa itu Clean Code?</li>
            <li>Apa karakterstik Clean Code?</li>
            <li>Apa itu KISS, DRY, dan Refactoring?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu Clean Code?</h2>
          <p>Clean Code adalah istilah untuk kode yang mudah dibaca, difahami, dan diubah oleh programmer. Clean Code ini fungsinya agar semua programmer bisa membaca kode dengan mudah yang mana akan berdampak pada cepatnya pengembangan kode jika ingin dikembangkan.</p>
          <h2 style="margin-top: 15px">Apa karakterstik Clean Code?</h2>
          <p>Karakteristik Clean Code, yaitu:</p>
          <ol>
            <li>Mudah difahami</li>
            <li>Mudah dieja dan dicari</li>
            <li>Singkat namun mendeskripsikan konteks</li>
            <li>Konsisten</li>
            <li>Hindari penmbahan konteks yang tidak perlu</li>
            <li>Komentar</li>
            <li>Good function</li>
            <li>Gunakan konvensi</li>
            <li>Formatting</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu KISS, DRY, dan Refactoring?</h2>
          <h2 style="margin-top: 15px">KISS</h2>
          <p>KISS adalah singkatan dari Keep It So Simple yang maknanya adalah hindari membuat fungsi yang dibuat untuk melakukan A, sekaligus memodifikasi B, mengecek fungsi C, dst.</p>
          <p>Tips untuk selalu KISS, yaitu:</p>
          <ul>
            <li>Fungs atau class harus kecil</li>
            <li>Fungsi dibuat untuk melakukan satu tugas saja.</li>
            <li>Jangan gunakan terlalu banyak argumen pada fungsi</li>
            <li>Harus diperhatikan untuk mencapai kondisi yang seimbang, kecil, dan jumlahnya minimal.</li>
          </ul>
          <h2 style="margin-top: 15px">DRY</h2>
          <p>DRY adalah singkatan dari Don't Repeat Yourself yang artinya jangan melakukan duplikasi kode yang digunakan secara berulang.</p>
          <h2 style="margin-top: 15px">Refactoring</h2>
          <p>Refactoring adalah proses restrukturisasi kode yang dibuat, dengan cara mengubah struktur internal tanpa mengubah perilaku eksternal. Prinsip KISS dan DRY bisa dicapai dengan cara refactor.</p>
          <p>Teknik Refactoring, yaitu:</p>
          <ul>
            <li>Membuat sebuah abstraksi.</li>
            <li>Memecah kode dengan fungsi/class.</li>
            <li>Perbaiki penamaan dan lokasi kode</li>
            <li>Deteksi kode yang memiliki duplikasi.</li>
          </ul>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/09_screenshots/cleancode.png" style="width: 100%" />
        <img src="screenshots/09_screenshots/cleancode2.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section10"> Lanjutkan Section 10 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section9Page',
}
</script>
