<template>
  <h1 class="text-danger">Hello World</h1>
  <Header />
</template>

<script>
import Header from "./components/Header";

export default {
  name: "App",
  components: {
    Header,
  }
};
</script>

<style>
  .text-danger {
    color: red;
  }
</style>