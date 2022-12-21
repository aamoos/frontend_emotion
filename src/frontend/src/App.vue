<template>
  <div>
    <Header></Header>
    <router-view></router-view>
    <Footer></Footer>
  </div>
</template>

<script>

import Header from '@/layout/HeaderView';
import Footer from '@/layout/FooterView';

export default {
  name: 'App',
  components: {
    Header,
    Footer,
  }
}
</script>