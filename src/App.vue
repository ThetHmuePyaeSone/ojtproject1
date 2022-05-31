<template>
    <div id="app">
      <Header />
      <FirstContent />
      <Footer />
    </div> <!--end of app div -->
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import FirstContent from './components/FirstOjtContent.vue';

export default {
  components:{
    Header,
    Footer,
    FirstContent,
    }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
    margin: 0;
    padding: 0;
} 
</style>
