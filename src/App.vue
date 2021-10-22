<template>
  <h1 class="text-primary" @click="helloWorld()">Hello World</h1>
</template>

<script>


export default {
  name: "App",
  components: {},
  setup() {
    const helloWorld = () => {
      alert("Hallo Guys");
    };

    return {
      helloWorld,
    };
  }
};
</script>

<style>
  body {
    padding: 0;
    margin: 0;
  }
</style>