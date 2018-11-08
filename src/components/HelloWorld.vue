<template>
  <div class="hello">
    <rightside />
    <leftside />
  </div>
</template>

<script>
import Rightside from '@/components/Rightside'
import Leftside from '@/components/Leftside'

export default {
  name: 'HelloWorld',
  components: {
    Rightside,
    Leftside
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
h1,
h2 {
  font-weight: normal;
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
