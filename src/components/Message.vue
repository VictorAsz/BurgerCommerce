<script>
    export default {
        name: "Message",
        props: {
            msg: String
        }
    }
</script>

<template>
    <div class="message-container">
        <p>{{ msg }}</p>
    </div>
</template>

<style scoped>
 .message-container {
    color: #004085;
    background-color: #cce5ff;
    text-align: center;
    padding: 15px 0px 5px 0px;
    max-width: 100%;
    
    
  }
</style>