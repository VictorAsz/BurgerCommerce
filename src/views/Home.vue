<script>

import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';
export default{
  name: "Home",
  components: {
    Banner,
    BurgerForm
  }


}
</script>


<template>
  <div class="main-container">
    <Banner/>
    
    <BurgerForm/>
  </div>
</template>

<style scoped>


</style>

