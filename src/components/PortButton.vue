<template>
  <button>
    <slot>MyButtons</slot>
  </button>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class PortButton extends Vue {}
</script>

<style scoped>
</style>
