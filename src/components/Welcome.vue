<template>
  <div class="hello">
    <h1>Join our Community!</h1>
    <h2><a href="http://wpdfw.org">wpdfw.org</a></h2>
    <p>Join our <a href="https://wpdfw.org/">Slack group</a> for help from friendly community members here in DFW.</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
