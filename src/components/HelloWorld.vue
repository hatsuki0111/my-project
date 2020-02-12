<template>
  <div class="hello">
   <div class="twitter"><a href="https://twitter.com/hisaku0111"target="_blank" title="twitter"><font-awesome-icon :icon="['fab', 'twitter']" size="5x" style="color:#FFFFFF"/></a></div>
   <div class="github"><a href="https://github.com/hatsuki0111" target="_blank" title="github"><font-awesome-icon :icon="['fab', 'github']"　size="5x" style="color:#FFFFFF"/></a></div>
   <div class="blogger"><a href="https://hisaku.hatenablog.com/archive" target="_blank" title="blogger"><font-awesome-icon :icon="['fab', 'blogger']" size="5x" style="color:#FFFFFF"/></a></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
.twitter{
  margin: 10px;
}
.github{
  margin: 10px;
}
.blogger{
  margin: 10px;
}
</style>
