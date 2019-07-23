<template>
  <div class="nav-bar">hoge</div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class PortNavBar extends Vue {}
</script>

<style scoped>
.nav-bar {
  width: 100vw;
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
