<template>
  <ul>
    <the-header title="Rememeber Me"></the-header>
    <the-resource></the-resource>
  </ul>
</template>
<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResource from './components/learning-resources/TheResource.vue';
export default {
  components: {
    TheHeader,
    TheResource,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>
