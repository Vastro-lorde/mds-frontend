<template>
  <!-- <HelloWorld /> -->
  <img id="logo" alt="Mater Dei logo" src="../assets/logo.png">
        <HelloWorld msg="Mater Dei College"/>
  <loginForm />
</template>

<script>

import loginForm from '../components/Form.vue'
import HelloWorld from '../components/HelloWorld.vue'

// let call = "If you are not registered, please sign-up first";

export default {
  name: 'Login',
  components: {
    loginForm,
    HelloWorld
  },
  props: {
    msg: String
  }
}

// let count = HelloWorldVue.count
// let counting = setInterval(()=>{count++}, 100)

</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#logo {
  width: 30%;
}
</style>
