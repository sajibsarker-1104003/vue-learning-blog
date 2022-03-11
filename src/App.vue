<template>
<div id="app">
<Header/>
<Latest/>
<Posts/>
</div>
</template>

<script>
import Header from './components/Header';
import Latest from './components/Latest.vue';
import Posts from './components/Posts.vue';

export default {
  name: 'App',
  components: {
    Header,
    Latest,
    Posts,
  
  }
}
</script>

<style lang="scss" scoped>
body{
  background-color:#F3F3F3;
  font-family:"Rockwell" serif;

  h3{
    color:#171717;
    font-size:28px;
    font-weight:700;
  }
}
</style>
