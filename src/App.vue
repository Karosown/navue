<template>
  <div id="app">
    <!--    <img alt="Vue logo" src="./assets/logo.png">-->
    <content-page></content-page>
  </div>
</template>

<script>
import ContentPage from "@/view/learn/contentPage";

export default {
  name: 'App',
  components: {
    ContentPage
  },
  mounted(){
    alert(123);
  }
}
</script>

<style>
#app {
  margin:0px;
  padding: 0px;
}
</style>
