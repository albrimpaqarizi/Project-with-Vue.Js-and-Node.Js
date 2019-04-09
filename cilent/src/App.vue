<template>
  <div id="app">
    <Header />
    <router-view class="container"></router-view>
    <Footer />
  </div>
</template>

<script>

import Header from '@/components/TheHeader';
import Footer from '@/components/TheFooter';

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
#app {
  color: #2c3e50;
}
</style>
