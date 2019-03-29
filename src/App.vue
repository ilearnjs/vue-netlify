<template>
  <div id="app">{{ meesage }}</div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      meesage: process.env.VUE_APP_MESSAGE
    };
  }
};
</script>
