<template>
  <div class="hello">
    <h1>First time hosting with Heroku!</h1>
    <input type="text" placeholder="Type your message!" v-model="message"/>
    <h3>{{ message }}</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: ""
    }
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
