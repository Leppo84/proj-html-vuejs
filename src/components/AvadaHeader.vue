<template>
  <div class="hello">
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="#">Item 1</a></li>
      <li><a href="#"></a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'AvadaHeader',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
