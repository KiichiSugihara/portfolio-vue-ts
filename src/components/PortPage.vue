<template>
  <div class="page">
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class PortPage extends Vue {}
</script>

<style scoped>
.page {
  width: 100vw;
  min-height: 100vh;
  top: 0px;
  left: 0;
  position: absolute;
  background: #ee5050;
  color: #ffffff;
  font-family: Josefin Sans, sans-serif;
  font-size: inherit;
  word-wrap: break-word;
}
</style>
