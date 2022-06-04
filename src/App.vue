<template>
  <div id="app">
    <result />
    <counter />
  </div>
</template>

<script>
import Counter from './components/Counter.vue';
import Result from './components/Result.vue';
export default {
  components: {
    Counter,
    Result,
  },
};
</script>
