<template>
  <div>
      <h1>hello world</h1>
      <input type="text" v-model="message">
      <div style="margin-top: 20px;">
        {{ message }}
      </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: 'Adamlovecode'
    }
  },
  created() {
    console.log("hello thiss");
  },
  mounted() {
    console.log("good job 12321321");
  }
}
</script>
<style lang="">
  
</style>