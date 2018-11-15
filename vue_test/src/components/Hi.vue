<template>
  <div class="hello">
    {{msg}}
  </div>
</template>
<script>
  export default{
    name: 'hi',
    data(){
      return {
        msg: 'hi chg.jin'
      }
    }
  }
</script>
<style scoped>
  .hello{
    font-size: 18px;
    text-align: center;
  }
</style>
