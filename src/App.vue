<template>
  <div id="app"> 
    <FirstPage></FirstPage>
    <SecondPage></SecondPage>
    <ThirdPage></ThirdPage>
  </div>
</template>

<script>
import FirstPage from './components/FirstPage'
import SecondPage from './components/SecondPage'
import ThirdPage from './components/ThirdPage'

export default {
  name: 'app',
  components: {
    FirstPage,
    SecondPage,
    ThirdPage
  }
}
</script>

<style>
#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
  font-family: 'Source Sans Pro', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  width: 100vw;
  overflow: hidden;
}

body { 
  background-image: url("./assets/blackground.jpg");
  background-color: antiquewhite;
}
</style>
