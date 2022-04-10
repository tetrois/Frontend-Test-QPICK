<template>
  <div class="wrapper">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Main from '@/components/Main.vue';
import Footer from '@/components/Footer.vue';

export default {
  data() {
    return {
      message: 'Hello World!'
    }
  },
  components: {
    Header,
    Main,
    Footer
  }
}

</script>


<style>
  .wrapper {
    min-height: 100%;
    display: flex;
    flex-direction: column;
  } 
</style>
