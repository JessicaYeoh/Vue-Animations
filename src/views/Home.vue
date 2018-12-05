<template>
<transition name="router-anim" enter-active-class="animated fadeInRight" leave-active-class="animated fadeOutLeft">
  <div class="home page">
  
    <HelloWorld msg="This is the home page"/>

    <input type="text" placeholder="Not Specified">

    <router-link to="/about">Continue</router-link>
  </div>
  </transition>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
