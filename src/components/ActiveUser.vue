<template>
  <section>
    <h2>Name of User</h2>
    <h3>37 years</h3>
  </section>
</template>
<script>
export default {
  props: {
    name: {
      type: String,
      required: true,
    },
    age: {
      type: Number,
      required: true,
    },
  },
};
</script>
<style>
section {
  margin: 2rem auto;
  max-width: 40rem;
  border-radius: 12px;
  border: 1px solid #ccc;
}
</style>
