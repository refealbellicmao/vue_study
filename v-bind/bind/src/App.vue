<template>
  <div id="app">
    <h2>{{message}}}</h2>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
const app = new Vue({
  el:'#app',
  data:{
    message:'hello'
  }
})
</script>

<style>

</style>
