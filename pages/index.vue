<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <img src="VB-01.jpeg" class="gambar" />
      </v-card>
      <v-card>
        <v-card-title class="headline">
          Weekly Task 2 Vue JS - 10 Summaries of Learning with Alterra Academy
        </v-card-title>
        <v-card-text>
          <p>Name: Raihan Hafizh</p>
          <p>Class: Vue JS - Kelas A</p>
          <p>
            Ini adalah 10 rangkuman materi yang saya pelajari selama belajar dengan Alterra Academy.
          </p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="primary" nuxt to="/section2"> Lanjutkan Section 2 </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style scoped>
.gambar {
  width: 35%;
}
</style>