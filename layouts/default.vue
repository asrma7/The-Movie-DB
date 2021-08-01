<template>
<div class="container">
  <AppHeader />
  <Nuxt />
</div>
</template>

<script>
import AppHeader from "../components/AppHeader.vue";
export default {
  components: {
    AppHeader
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  background-color: #f4f4f4;
  font-size: 1rem;
  line-height: 1.6;
  font-family: Arial, Helvetica, sans-serif;
}

ul {
  list-style: none;
}

a {
  color: #333;
  text-decoration: none;
}

.container {
  max-width: 1000px;
  background-color: #fff;
  margin: 2rem auto;
  padding: 1rem 2rem;
}
</style>