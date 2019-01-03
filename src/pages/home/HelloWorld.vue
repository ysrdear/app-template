<template>
  <div class="hello">
    <van-nav-bar
      title="标题"
      left-text="返回"
      right-text="按钮"
      left-arrow
    />
    <h1>{{ msg }}</h1>

  </div>
</template>

<script>
  import { NavBar } from 'vant';

  export default {
    name: 'HelloWorld',
    components: {
      [NavBar.name]: NavBar
    },
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
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
