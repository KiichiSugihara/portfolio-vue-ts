<template>
  <PortPage>
    <PortNavBar>hoge-</PortNavBar>
  </PortPage>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import PortButton from "@/components/PortButton.vue";
import PortPage from "@/components/PortPage.vue";
import PortNavBar from "@/components/PortNavBar.vue";

@Component({
  components: {
    PortButton,
    PortPage,
    PortNavBar
  }
})
export default class Home extends Vue {}
</script>

<style scoped>
</style>
