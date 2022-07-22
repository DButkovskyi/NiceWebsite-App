<template>
  <div class="blog">
    <SocialList class="social"/>
  </div>
</template>

<script>
// @ is an alias to /src
import SocialList from "/src/components/SocialList.vue"
export default {
  name: 'BlogView',
  components: {
    SocialList
  }
}
</script>

<style>
  
</style>