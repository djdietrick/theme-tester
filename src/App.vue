<template>
  <div id="app">
    <div class="btn btn--white switch" @click="toggle">{{buttonText}}</div>
    <component :is="selectedComponent"/>
  </div>
</template>

<script>
import ThemeEditor from './components/ThemeEditor.vue'
import Overview from './components/Overview.vue'
import Demo from './components/Demo.vue'

export default {
  name: 'App',
  components: {
    demo: Demo,
    overview: Overview
  },
  data() {
    return {
      selectedComponent: "overview"
    }
  },
  methods: {
    toggle() {
      if(this.selectedComponent == "overview")
        this.selectedComponent = "demo";
      else
        this.selectedComponent = "overview";
    }
  },
  computed: {
    buttonText() {
      if(this.selectedComponent == "overview")
        return "Demo";
      else
        return "Overview";
    }
  }
}
</script>

<style lang="scss">
@import "./styles/main.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

.switch {
  position: fixed;
  top: 3rem;
  right: 10rem;
  opacity: 0.5;
  z-index: 10;
}
</style>
