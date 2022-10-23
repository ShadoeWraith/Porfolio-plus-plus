<template>
  <div>
    <Navbar />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  name: 'app',
  components: {
    Navbar,
  },
};
</script>

<style>
@import url('./style.css');

body {
  background-color: #333;
}
</style>
