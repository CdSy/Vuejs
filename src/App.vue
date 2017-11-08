<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style lang="less">
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px; 

    .button {
      width: 200px;
      margin: 0 auto;
      padding: 15px 0;
      background-color: rgba(255, 10, 10, 0.4);
      border-radius: 3px;
      text-align: center;
      color: #fff;
      cursor: pointer;

      &:hover {
        background-color: rgba(255, 10, 10, 0.7);
      }
    }
  }
</style>
