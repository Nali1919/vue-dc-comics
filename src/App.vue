<template>
  <div id="app">
    <HeaderComponent />
    <SectionMainComponent />
    <SecondSectionComponent />
   
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import SectionMainComponent from './components/SectionMainComponent.vue';
import SecondSectionComponent from './components/SecondSectionComponent.vue';



export default {
  name: 'App',
  components: {
    HeaderComponent,
    SectionMainComponent,
    SecondSectionComponent,
  
}
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
} 

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
