<template>
  <div>
    <h2>
      {{ doubleCounter }}
    </h2>
    <h2>
      {{ stringCounter }}
    </h2>
  </div>
</template>

<script>
import { mapGetters } from 'vuex';
export default {
  computed: {
    ...mapGetters(['doubleCounter', 'stringCounter']),
  },
};
</script>

<style scoped></style>
