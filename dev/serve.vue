<script>
import Vue from 'vue';
import { TailwueSample } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    TailwueSample,
  }
});
</script>

<template>
  <div id="app">
    <tailwue-sample />
  </div>
</template>
