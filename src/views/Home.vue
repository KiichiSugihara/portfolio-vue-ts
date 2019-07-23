<template>
  <PortPage>
    <!-- <PortButton></PortButton> -->
  </PortPage>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import PortButton from "@/components/PortButton.vue";
import PortPage from "@/components/PortPage.vue";

@Component({
  components: {
    PortButton,
    PortPage
  }
})
export default class Home extends Vue {}
</script>

<style scoped>
</style>
