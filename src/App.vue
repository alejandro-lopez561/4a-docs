<template>
  <div id="app">
    <Header />
    <Content />
    <div>
      <Main />
    </div>
  </div>
</template>

<script>

import Header from './components/Header.vue';
import Content from './components/Content.vue';
import Main from './components/Main.vue';

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Main
  }
}
</script>

<style>
body {
  font-family: 'Lato', sans-serif;
  
}

.container {
    width: 1200px;
    margin: 0 auto;
    
}

a{
  text-decoration: none;
  
}

ul{
  list-style: none;
}
</style>
