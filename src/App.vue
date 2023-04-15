<template>
  <div id="app">
   <life-cycle-example></life-cycle-example>
   <script-example></script-example>
  </div>
</template>

<script>
import LifeCycleExample from '@/components/LifeCycleExample.vue'
import ScriptExample from '@/components/ScriptExample .vue';
export default {
  name: 'App',
  components: {
    LifeCycleExample,
    ScriptExample
  }
}
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
