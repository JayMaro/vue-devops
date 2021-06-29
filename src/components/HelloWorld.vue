<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>My name is Kim</h1>
    <h2> <a href="https://github.com/JayMaro">My github</a> </h2>
    <h2> <a href="https://github.com/JayMaro/Project">Projects</a> </h2>
    
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
