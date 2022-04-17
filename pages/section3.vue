<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 3 - Introduction UI dan UX
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin, yaitu:</p>
          <ol>
            <li>Apa itu UI/UX?</li>
            <li>Mindset UX atau UX Thinking?</li>
            <li>4 Pilar dari UI</li>
          </ol>
          <h2 style="margin-top: 15px">Apa itu UI/UX?</h2>
          <p>UI/UX adalah sebuah konsep yang dapat membuat website yang kita buat menjadi lebih interaktif dan nyaman untuk digunakan. UI/UX adalah gabungan dari dua komponen yakni UI (User Interface) yang artinya Tampilan Antarmuka dan UX (User Experience) yang artinya Pengalaman Pengguna. Seperti namaya, konsep UI seniri lebih menekankan kepada estetika tampilan yang enak dipandang dan dilihat oleh orang ketika membuka website. Sebaliknya, konsep UX tidak terlalu mementingkan tampilan akan tetapi hanya berfokus kepada kenyamanan dan kemudahan pengguna dalam mengakses fitur yang ada dalam website tersebut.</p>
          <h2 style="margin-top: 15px">Mindset UX atau UX Thinking?</h2>
          <p>Ada 5 Mindset UX yang harus kita miliki ketika membuat sebuah website, yaitu:</p>
          <ol>
            <li>Emphatize</li>
            <p>Kita harus membuat sebuah website berdasarkan target user dan juga viewpoint/pandangan dari pihak user yang beragam.</p>
            <li>Define</li>
            <p>Kita harus mendefinisikan data yang sudah kita ambil dari Emphatize di fase ini supaya kita dapat mengetaui inti masalah yang bisa kita selesaikan.</p>
            <li>Ideate</li>
            <p>Di tahap ini, kita harus bisa mengimplementasikan hal-hal yang sudah di rancang di bagian define untuk dapat dilanjut ke tahap prototype.</p>
            <li>Prototype</li>
            <p>Di tahap prototype ini, kita dapat melihat wujud setengah jadi dari websiteyg akan kita buat.</p>
            <li>Validate</li>
            <p>Di tahap ini, kita memvalidasi dan mengecheck ulang apakah prototype kita berjalan sebagaimana apa yang telah direncanakan atau tidak.</p>
          </ol>
          <h2 style="margin-top: 15px">4 Pilar dari UI</h2>
          <p>4 Pilar yang fundamental bagi UI dalam website yang kita kembangkan yaitu:</p>
          <ol>
            <li>Consistency</li>
            <p>Maksud consistency di sini adalah pola desain yang konsisten dan tidak berubah-ubah dari page 1 ke page yang lain. Desain konsisten ini dapat membantu pengguna jadi lebih mudah untuk mengoperasikannya dan terlihat rapi.</p>
            <li>Keep the interface simple</li>
            <p>Menjaga agar tampilan tetap simple juga adalah bagian dari UI yang simple dan enak dipandang.</p>
            <li>Good Typhography</li>
            <p>Penggunaan Font dan huruf yang enak dipandang dan juga simple sangat mempengaruhi penampilan website.</p>
            <li>Offer Informative Feedback</li>
            <p>Website harus menampilkan feedback yang informatif dan menarik agar user tidak bosan ketika menggunakan website tersebut.</p>
          </ol>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/03_screenshots/homepage.png" style="width: 100%" />
        <img src="screenshots/03_screenshots/tentangkamipage.png" style="width: 100%; margin-top:15px" />
        <img src="screenshots/03_screenshots/faqpage.png" style="width: 100%; margin-top:15px" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section4"> Lanjutkan Section 4 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section3Page',
}
</script>
