<template>
  <v-container class="mt-10">

    <v-row>
      <v-col lg="6" class="text-center">
        <img src="./../assets/image/about_01.jpg" width="90%">
      </v-col>
      <v-col lg="6">
        <v-subheader class="text--h3 section_title mb-6">
          About Us
        </v-subheader>
        <v-subheader class="f-24 text--h2 font-weight-bold pb-2">
          Welcome to DevGhor for Amazing Websites, Web Apps and Templates
        </v-subheader>
        <p></p>
        <v-list>
          <v-list-item>
            <v-icon color="success" class="mx-3">mdi-check-all</v-icon>
            <v-list-item-subtitle>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</v-list-item-subtitle>
          </v-list-item>
          <v-list-item>
            <v-icon color="success" class="mx-3">mdi-check-all</v-icon>
            <v-list-item-subtitle>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</v-list-item-subtitle>
          </v-list-item>
          <v-list-item>
            <v-icon color="success" class="mx-3">mdi-check-all</v-icon>
            <v-list-item-subtitle>Lorem Ipsum is simply dummy text of typesetting industry.</v-list-item-subtitle>
          </v-list-item>
          <v-list-item>
            <v-icon color="success" class="mx-3">mdi-check-all</v-icon>
            <v-list-item-subtitle>Lorem Ipsum is simply dummy text of the printing industry.</v-list-item-subtitle>
          </v-list-item>
        </v-list>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
  export default {
    name:'AboutUs',
  }
</script>