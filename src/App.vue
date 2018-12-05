<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->

    <router-view/>

  </div>
</template>


<style lang="scss">
@import url('https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css');

html, body {
  height: calc(100% - 50px);
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  width: 50%;
  background: rgb(179, 233, 236);
  margin: 0 auto;
  height: 100%;
  padding: 30px;
}

.page {
  position: fixed;
  width: inherit;
  text-align: center;
}

.fadeInRight {
    -webkit-animation-name: fadeInRight;
    animation-name: fadeInRight;
    -webkit-animation-duration: 0.5s;
    animation-duration: 0.5s;
}

.fadeOutLeft {
    -webkit-animation-name: fadeOutLeft;
    animation-name: fadeOutLeft;
    -webkit-animation-duration: 0.5s;
    animation-duration: 0.5s;
}
</style>
