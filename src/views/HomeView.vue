import { useCounterStore } from '../stores/counter';
<template>
  <h1>Home View: {{counterStore.counter}}</h1>

  <h3>Number of changes: {{counterStore.numberOfChanges}}</h3>
</template>

<script lang="ts" setup>
  import {useCounterStore} from '../stores/counter';
  const counterStore = useCounterStore();
</script>