<template>
  <frame></frame>
</template>

<script>
import Frame from "@/components/Frame.vue";
export default {
  name: "App",
  components: { Frame },
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

html {
  -webkit-app-region: drag;
}

html,
body,
#app {
  width: 100%;
  height: 100%;
  margin: 0;
  box-sizing: border-box;
  background: rgba(0, 0, 0, 0);
}
</style>
