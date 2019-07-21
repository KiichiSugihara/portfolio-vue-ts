<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/> -->
    <PortButton></PortButton>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import PortButton from "@/components/PortButton.vue";

@Component({
  components: {
    HelloWorld,
    PortButton
  }
})
export default class Home extends Vue {}
</script>
