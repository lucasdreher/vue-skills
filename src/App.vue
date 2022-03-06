<template>
  <div id="app">
    <SkillsAll />
  </div>
</template>

<script>
import SkillsAll from "./components/SkillsAll.vue";

export default {
  name: "App",
  components: {
    SkillsAll,
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
  margin-top: 60px;
}
</style>
