<template>
  <div class="hello">
    <h1>De festivalzomer lacht je toe!</h1>
    <h3>Kijk ook hier:</h3>
    <ul>
      <li><a href="https://coronatest.nl/" target="_blank" rel="noopener">Coronatest.nl</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
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
