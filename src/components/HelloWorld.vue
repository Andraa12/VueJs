<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
      <b-container>    
         <b-col cols="4-5" class="card mt-5"><h1></h1></b-col>
         <b-col cols="4-5" class="card mt-5"></b-col>
         <b-col cols="4-5" class="card mt-5"></b-col>
      </b-container>
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
.card{
  height: 300px;
  background-color: gray;
}
</style>
