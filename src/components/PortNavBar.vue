<template>
  <div class="nav-bar">
    <div class="nav-bar__container">
      <router-link :to="{ name: 'home'}">
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
  left: 0px;
  top: 0px;
  position: absolute;
  width: 100%;
  z-index: 100;
  padding: 2.5rem 1.1rem 0px 0px;
  transition: transform 0.25s ease 0s, -webkit-transform 0.25s ease 0s;
}
.nav-bar__container {
  position: relative;
  width: 100%;
  padding: 0.5rem;
  display: block;
  margin-left: auto;
  text-align: right;
}
.nav-bar__left-box {
  left: 0px;
  position: absolute;
}
.nav-bar__button-top {
  padding: 0.95rem 0.8rem;
  font-size: 1.2rem;
  color: rgb(255, 255, 255);
  display: block;
  line-height: 1.6rem;
  font-family: avantgardegothicitcw01bd, sans-serif;
  font-weight: 700;
  position: relative;
  transition: color 0.25s cubic-bezier(0.625, 0.125, 0.305, 0.875) 0s,
    opacity 0.25s cubic-bezier(0.625, 0.125, 0.305, 0.875) 0s;
  outline: none !important;
}
.nav-bar__right-box {
  right: 0px;
  position: absolute;
  display: flex;
  max-width: 61.5rem;
  width: auto;
  margin: 0px;
  padding-right: 1.1rem;
  list-style: none none;
}
.nav-bar__button {
  padding: 0.95rem 0.8rem;
  color: rgb(255, 255, 255);
  display: block;
  line-height: 1.6rem;
  font-family: avantgardegothicitcw01bd, sans-serif;
  font-weight: 700;
  position: relative;
  transition: color 0.25s cubic-bezier(0.625, 0.125, 0.305, 0.875) 0s,
    opacity 0.25s cubic-bezier(0.625, 0.125, 0.305, 0.875) 0s;
  outline: none !important;
}
li:not(:first-child) {
  margin-left: 0.8rem;
}
</style>
