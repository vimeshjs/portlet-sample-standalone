<template>
  <p>{{ greeting }} <span class="text-xl text-red-600"> World!</span></p>
</template>

<script>
module.exports = {
  data: function () {
    return {
      greeting: "Hello",
    };
  },
};
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>