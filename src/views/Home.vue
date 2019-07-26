<template>
  <PortPage>
    <PortNavBar>hoge-</PortNavBar>
    <div class="app-content">
      <h1 class="app-content__top--title">We don’t even like the internet.</h1>
    </div>
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
.app-content {
  padding-top: 5rem;
  max-width: 61.5rem;
  width: calc(100% - 3rem);
}
.app-content__top--title {
  margin-bottom: 0;
  font-size: 2.25rem;
  max-width: 9em;
  margin: 5rem auto;
  text-align: center;
  font-feature-settings: "liga" 1, "kern" 1;
  display: block;
  font-family: avantgardegothicitcw01bd, sans-serif;
  font-weight: 600;
  letter-spacing: -0.05em;
  line-height: 1.2;
}
</style>
