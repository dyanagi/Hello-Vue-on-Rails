<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  props: ["message"],

  // data: function () {
  //   return {
  //     message: "Hello Vue!"
  //   }
  // }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
