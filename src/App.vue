<template>
  <img alt="Vue logo" src="./assets/laravel.png">
  <!-- <HelloWorld msg="This is new Project"/> -->
  <ChildComponent message ="I love your combodai"/>
  <!-- <ChildComponent message ="Hello Komphong speu"/> -->
  <!-- <ChildComponent :message ="msg" type = "ok"/> -->
</template>

<script>
import ChildComponent from './components/ChildComponent.vue'

export default {
  name: 'App',
  components: {
    ChildComponent
  },
  // data(){
  //   return{
  //     msg:'Good Morning',
  //   }
  // }

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
