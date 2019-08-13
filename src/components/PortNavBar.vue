<template>
  <div class="nav-bar">
    <b class="nav-bar__block"></b>
    <div class="nav-bar__container">
      <router-link style="text-decoration:none;" :to="{ name: 'home'}">
        <div class="nav-bar__left-box">
          <p class="nav-bar__button-top">KIICHI SUGIHARA</p>
        </div>
      </router-link>
      <ul class="nav-bar__right-box">
        <li class="nav-bar__button">Project</li>
        <li class="nav-bar__button">Career</li>
        <li class="nav-bar__button">Link</li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
import "@/styles.css";

@Component
export default class PortNavBar extends Vue {}
</script>

<style scoped>
.nav-bar {
  left: 0;
  top: 0;
  position: fixed;
  width: 100%;
  z-index: 100;
  background: #ee5050;
}

.nav-bar__block {
  height: 52px;
  left: 0;
  position: absolute;
  top: 0;
  width: 100%;
  background: #ee5050;
}

.nav-bar__container {
  position: relative;
  display: flex;
  justify-content: space-between;
  padding: 0 16px 0 12px;
  margin-top: 20px;
  text-decoration: none;
}

.nav-bar__button-top {
  color: rgb(255, 255, 255);
  display: block;
  font-family: avantgardegothicitcw01bd, sans-serif;
  font-weight: 700;
  position: relative;
  outline: none !important;
  border-style: none;
}
.nav-bar__right-box {
  right: 0px;
  display: flex;
  list-style: none none;
}
.nav-bar__button {
  color: rgb(255, 255, 255);
  padding: 16px 12px;
  font-family: avantgardegothicitcw01bd, sans-serif;
  font-weight: 700;
  outline: none !important;
}
</style>
