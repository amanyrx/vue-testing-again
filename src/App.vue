<template>
  <HelloWorld msg="Welcome to Web Techniques"/>
  <DemoComponent msg="I did it!"/>
  <main>
    <p>My name is Amany K00331923</p>
  </main>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import DemoComponent from "@/components/DemoComponent.vue";

export default {
  name: 'App',
  components: {
    DemoComponent,
    HelloWorld
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
