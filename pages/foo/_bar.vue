<template>
  <div>
    <nuxt-link :to="{params: {bar: 1}}">Bar 1</nuxt-link>
    <nuxt-link :to="{params: {bar: 2}}">Bar 2</nuxt-link>
  </div>
</template>

<script>
export default {
  created() {
    console.log("created");
  }
};
</script>

<style>
</style>
