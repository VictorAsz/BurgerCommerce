<template>
 
    <Navbar :logo="logo_src" :alt="app_name"/>
    <router-view/>
    <Footer />

</template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.min.js';

export default{
  components: {
    Navbar,
    Footer
  },
  data() {
    return{
      logo_src: "/img/logo.png",
      app_name: "Make Your Burguer"
    }
  }
}
</script>

<style >
* {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

 
  .main-container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }


</style>
