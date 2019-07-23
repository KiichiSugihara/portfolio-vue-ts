<template>
  <div class="page"></div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class PortPage extends Vue {}
</script>

<style scoped>
.page {
  width: 100vw;
  height: 100vw;
  top: 0px;
  left: 0;
  position: absolute;
  background: #ee5050;
  color: #333;
  font-family: Josefin Sans, sans-serif;
  font-size: inherit;
  word-wrap: break-word;
}
</style>
