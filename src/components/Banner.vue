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
    background-image: url("https://www.guaruja.sp.gov.br/wp-content/uploads/2023/08/53077417851_cdba364fed_k-1024x683.jpg");
    background-position: 0 -250px;
    background-size: cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
  }
</style>