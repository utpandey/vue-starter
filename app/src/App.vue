<template>

<div id="app">
  {{ message }} Nice to meet Vue.
</div>
</template>

<script>


const App = {
  data() {
    return {
      message: 'This is a good place to type things.'  
    }
  }
}

export default {
  App
  // components: {
  //   HelloWorld
  // }
}
</script>

<style>
#app {
  margin-top: 60px;
}
</style>

