<script>

import Banner from '@/components/Banner.vue';
import BurguerForm from '@/components/BurguerForm.vue';
export default{
  name: "Home",
  components: {
    Banner,
    BurguerForm
  }


}
</script>


<template>
  <p>banner</p>
  <div class="main-container">
    <Banner/>
     <h1>Monte o seu burger</h1>
     <BurguerForm/>
  </div>
</template>

