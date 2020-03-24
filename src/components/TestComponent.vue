<template>
  <div>
    <h1>{{text}}</h1>
    <a :href="url">Click here !</a>
    <p>{{boolean}}</p>
  </div>
</template>

<script>
export default {
  name: "TestComponent",
  props: {
    url: String,
    text: String,
    boolean: Boolean
  }
};
</script>

<style scoped></style>