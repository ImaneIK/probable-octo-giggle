<template>
  <advertisement></advertisement>
</template>

<script>
import advertisement from '../components/adv.vue'


export default {
 // eslint-disable-next-line vue/multi-word-component-names
 name: 'advertisement',
  props: {
    msg: String
  },

    components: {
    advertisement,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}


.about{
  width: 800px;
  height: 500px;
  margin: 100px;
  display: flex;
  left: 16%;
  top: 5%;
  background: url("../assets/section.jpg")no-repeat center;
  background-size: cover; 
  border-radius: 32px;
  align-items: center;
  justify-content: center;
  margin: 6rem auto;
}




</style>

