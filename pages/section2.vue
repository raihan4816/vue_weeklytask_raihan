<template>
<v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card>
        <v-card-title class="headline">
          Section 2 - Version Control and Branch Management (Git)
        </v-card-title>
        <v-card-text>
          <h2>Resume</h2>
          <p>Dalam materi ini, saya mempelajari 3 poin, yaitu:</p>
          <ol>
            <li>Proses Instalasi Github</li>
            <li>Proses Setting Up Github</li>
            <li>Proses Commit dan Branch di Github</li>
          </ol>
          <h2 style="margin-top: 15px">Proses Instalasi Github</h2>
          <p>Proses Instalasi Github merupakan proses yang harus dilakukan semua programmer yang ingin menginstall Github Bash dan GUI di devicenya. Untuk Windows OS, proses penginstallan Github dilakukan dengan cara mendownload Git for Windows Installernya di situs Githubnya dan lakukan penginstallan deperti aplikasi biasa. Untuk pengguna MacOS pun mirip tinggal download Git for Mac Installernya dan tinggal diikuti langkahnya. Untk pengguna linux, cara menginstallnya dengan cara mengetikan <i>"sudo apt-get install git"</i> di command prompt nya.</p>
          <h2 style="margin-top: 15px">Proses Setting Up Github</h2>
          <p>Proses ini adalah proses lanjutan dari sudah berhaslnya Github terpasang di komputer kita. Proses pengaturan awal ini dimulai dengan git config. Caranya dengan mengetikan command ini di git bash:</p>
          <p><i>"git config --global user.name"</i>
            misal <i>git config --global raihan4816"</i>"
            dan <i>"git config --global user.email"</i>
            misal <i>"git config --global raihan4816@gmail.com"</i>
            setelahnya kita buat repository di guthub dan kita clone ke computer kita dengan cara mengetikan command ini di git bash:</p>  
            <p><i>"git clone remote repo ssh"</i>
            <i>"git clone git@github.com:raihan4816/vue_raihan-hafizh.git"</i></p>
          <h2 style="margin-top: 15px">Proses Commit, Push, Branch, dan Checkout di Github</h2>
          <p>Proses Commit, Push, dan Branch di Github ini sangat penting dan sering digunakan dalam memasukan atau merevisi file dalam local ke repository yang ada di github. Yang kita lakukan untuk melakukan penyimpanan pada perubahan yaitu dengan mengetikan:
            <p><i>"git add ."</i> untuk memindahkan file yang baru disimpan di working directory ke staging area <i>"git commit -m (pesan perubahan yang ingin disampaikan)"</i> untuk memindahkan dari staging area ke repository dan <i>"git push origin master"</i> untuk benar-benar mempublish file yang kita tambahkan/revisi.</p>
          <p></p>
        </v-card-text>
      </v-card>
      <v-card class="logo py-4 justify-center">
        <v-card-text>
          <h2>Di bawah ini hasil screenshots dari tugasnya</h2>
        </v-card-text>
        <img src="screenshots/02_screenshots/insight-network.png" style="width: 100%" />
      </v-card>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section3"> Lanjutkan Section 3 </v-btn>
        </v-card-actions>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Section2Page',
}
</script>
