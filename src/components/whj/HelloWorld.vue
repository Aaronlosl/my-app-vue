<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <br>Please enter your username at the box below<br>
      <input class="form__input" type="text" placeholder="Username"><br>
      <input class="form__input" type="text" placeholder="Password">
    </p>
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
