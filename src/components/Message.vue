<template>
  <div>
    <div class="message-container">
      {{ msg }}
    </div>
  </div>
</template>

<script>
export default {
  name:'Message',
  props: ['msg']
}
</script>
<style scoped>
  .message-container{
    color: #004085;
    background-color: #cce5ff;
    border: 2px solid #B8DAFF;
    border-radius: 5px;
    padding: 10px;
    max-width: 400px;
    margin: 30px auto;
  }
</style>