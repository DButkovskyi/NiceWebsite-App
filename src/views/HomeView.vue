<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
      <SocialList/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "/src/components/HelloWorld.vue"
import SocialList from "/src/components/SocialList.vue"
export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    SocialList
  }
}
</script>
