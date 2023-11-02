<template>
  <v-app>
    <menu-vertical-vue/>
    <header-vue/>
    <main-vue/>
   <footer-vue/>
  </v-app>
</template>

<script>
  import FooterVue from './components/Footer.vue'
  import HeaderVue from './components/Header.vue'
  import MainVue from './components/Main.vue'
  import MenuVerticalVue from './components/MenuVertical.vue'
export default {
  name: 'Body',
  components: {
    MenuVerticalVue,
    HeaderVue,
    FooterVue,
    MainVue
  }
}
</script>
