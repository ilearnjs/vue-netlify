<template>
  <div id="app">
    <div>{{ meesage }}</div>
    <div>New commit master</div>
  </div>
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
