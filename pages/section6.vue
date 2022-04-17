<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 6 - CSS
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin dari CSS, yaitu:</p>
          <ol>
            <li>Apa itu CSS?</li>
            <li>Ada Berapa Cara dalam Menambahkan CSS?</li>
            <li>Apa itu External, Internal, dan Inline CSS?</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu CSS?</h2>
          <p>CSS adalah singkatan dari Cascading Style Sheets yang mana CSS ini memiliki fungsi sebagai kode untuk menghias halaman web seperti mengubah (color, size, font, background, width, height, dll). CSS juga Dapat mengatur posisi pada halaman web. (float, align, display, position, dll).</p>
          <h2 style="margin-top: 15px">Ada Berapa Cara dalam Menambahkan CSS?</h2>
          <p>Ada 3 cara menambahkan file CSS ke dalam HTML, yaitu:</p>
          <ol>
            <li>External CSS</li>
            <li>Internal CSS</li>
            <li>Inline CSS</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu External, Internal, dan Inline CSS?</h2>
          <ol>
            <li>External CSS</li>
            <p>External CSS adalah penempatan baris kode CSS menggunakan file .css. Cara ini dapat digunakan untuk mendeklarasikan sebagian besar pengaturan tampilan website secara keseluruhan.</p>
            <p>Biasanya Memasukan Syntax ini di HTML nya:</p>
            <img src="css1.png" style="width: 100%" />
            <p>Syntax ini disisipkan ke dalam tag ( head ) pada HTML.</p>
            <li>Internal CSS</li>
            <p>Internal CSS yaitu tipe penulisan tanpa file CSS terpisah. Namun di dalam penggunaan CSS secara internal, baris kode HTML dituliskan di bagian atas (header) file HTML.</p>
            <p>Misalnya:</p>
            <img src="css2.png" style="width: 100%" />
            <p>Syntax ini dapat digunakan di dalam satu file HTML. Didefinisikan di dalam elemen ( style ), di dalam bagian ( head ) atau di dalam bagian ( body ). </p>
            <li>Inline CSS</li>
            <p>Inline CSS adalah penempatan CSS yang langsung dilakukan di dalam konten HTML. Penempatan CSS secara inline hanya akan mempengaruhi satu bagian baris kode.</p>
            <p>Misalnya:</p>
            <img src="css3.png" style="width: 100%" />
            <ul>
              <li>Syntax ini dapat digunakan untuk elemen tunggal pada HTML.</li>
              <li>Di prioritaskan untuk menerapkan style yang unik.</li>
            </ul>
          </ol> 
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/06_screenshots/file1.png" style="width: 100%" />
        <img src="screenshots/06_screenshots/file2.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section7"> Lanjutkan Section 7 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section6Page',
}
</script>
