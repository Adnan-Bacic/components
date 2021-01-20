<template>
  <div><!--Root tag-->
  <Navbar/>
    <h1>{{ title }}</h1>
    <h2>{{ subtitle }}</h2>
  <Content/>
  <Footer/>
  </div>
</template>

<script>
import Navbar from './Navbar.vue'
import Content from './Content.vue'
import Footer from './Footer.vue'

export default {
  name: 'app',

  components:{
    Navbar: Navbar,
    Content: Content,
    Footer: Footer
  },
  
  data () {
    return {
      title: 'VueJS',
      subtitle: 'Webapp'
    }
  }
}
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
  font-family: 'Helvetica';
  text-align: center;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
