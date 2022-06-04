<template>
  <div>
    {{ counter }}
  </div>
</template>

<script>
export default {
  computed: {
    counter() {
      return this.$store.getters.double;
    },
  },
};
</script>

<style scoped></style>
