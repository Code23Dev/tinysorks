<template>
  <div>
  <Header/>
  <Footer/>
  </div>
</template>

<script>
import Footer from '../components/Footer'
import Header from '../components/Header'

export default {
  components: {
    Footer,
    Header
  },
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
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
