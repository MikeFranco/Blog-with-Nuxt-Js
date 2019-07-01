<template>
  <v-layout
    column
    justify-center
    align-center
  >
  <Header/>
  <nuxt-link to="/users" > Users </nuxt-link>
  <button @click="goToProducts" >Products Page</button>
  </v-layout>
</template>

<script>
import Header from '~/components/Header.vue';
import VuetifyLogo from '~/components/VuetifyLogo.vue';

export default {
  components: {
    Header,
    VuetifyLogo
  },
  methods:{
    goToProducts(){
      this.$router.push('/products')
    }
  }
}
</script>
