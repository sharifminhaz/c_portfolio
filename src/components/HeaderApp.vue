<template>
  <v-app-bar app color="white" light elevation="6" elevate-on-scroll style="padding: 0px 90px;">
    <v-toolbar-title>DevGhor</v-toolbar-title>
    <v-spacer />
    <v-list link v-for="(menu, index) in menus" :key="index" :to="menu.route">
      <v-list-item>{{menu.title}}</v-list-item>
    </v-list>
    <v-btn text class="pt-2">
      <v-text-field
          label="Search"
          required
      ></v-text-field>
      <v-icon>mdi-magnify</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: 'HeaderApp',

  data(){
    return{
      menus:[
        {title:'Home', route:'home'},
        {title:'About', route:'about'},
        {title:'Services', route:'services'},
        {title:'Portfolio', route:'portfolio'},
        {title:'Team', route:'team'},
        {title:'Contact', route:'contact'},
      ]
    }
  }

}
</script>
<style>
  .v-toolbar__title{
    font-size: 32px !important;
    color: indigo;
    font-weight: bold;
}
</style>