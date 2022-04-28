<template>
  <MyProjects/>
  <MyContainers/>
  <MyDatas/>
</template>

<script>
import MyProjects from './components/MyProject'
import MyContainers from './components/MyContainer'
import MyDatas from './components/MyData'

export default {
  name: 'App',
  components: {
    MyProjects,
    MyContainers,
    MyDatas,
  },
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
