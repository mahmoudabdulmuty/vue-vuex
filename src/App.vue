<template>
  <div id="app">
    <another-result />
    <counter />
    <result />
  </div>
</template>

<script>
import AnotherResult from './components/AnotherResult.vue';
import Counter from './components/Counter.vue';
import Result from './components/Result.vue';
export default {
  components: {
    Counter,
    Result,
    AnotherResult,
  },
};
</script>
