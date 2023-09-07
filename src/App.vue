<template>
  <SideBar />
  <MyHome />
</template>

<script>
import MyHome from "./components/MyHome.vue";
import SideBar from "./components/SideBar.vue";

export default {
  name: "App",
  components: {
    MyHome,
    SideBar,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
