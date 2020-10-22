<template>
  <div class="main">
    <h1>{{ title }}</h1>
    <iframe src="https://coda.io/embed/TIpvNYN4lb/_suqgf?viewMode=embedplay&hideSections=true" width=100% height=3700 style="max-width: 100%;" allow="fullscreen"></iframe>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    title: String
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
