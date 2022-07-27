<template>
  <div class="home">
    <HelloWorld msg="Hi I'm Dan"/>
    <SocialList class="social"/>
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
    SocialList,
  },
}
</script>

<style>
  
</style>
