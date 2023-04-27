<template>
  <div id="app">
  <AppHeader />
  <div class="w-full flex">
    <DcHeros />
  </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppHeader from "./components/AppHeader";
import DcHeros from "./components/DcHeros";
export default {
  components: { AppHeader, DcHeros },
}
</script>

<style>

</style>
