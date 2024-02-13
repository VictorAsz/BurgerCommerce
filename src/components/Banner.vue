<script>
export default {
   name: "Banner"

}
</script>

<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<style scoped>
 #main-banner {
    background-image: url("https://tacomfome.com.br/home/assets/img/bg-2.jpg") ;
    background-position: 0 -450px;
    background-size: none;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    background-repeat: no-repeat;
    
    
  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
  }
</style>