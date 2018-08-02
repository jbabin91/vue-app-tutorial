<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <Navbar/>
  </div>
</template>

<script>
import Navbar from './Navbar';
export default {
  name: 'app',
  components: {
    Navbar,
  },
  data() {
    return {
      title: 'My first Vue app',
    };
  },
};
</script>

<style>
h1 {
  color: #444;
  font-weight: 400;
  text-align: center;
}
</style>
