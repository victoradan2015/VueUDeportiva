<template>
  <div class="Navbar">
    <h1>{{ msg }}</h1>

    <h1 v-if="awesome">Vue is awesome!</h1>
    
    <h3>Condicionales v-if v-else, v-for</h3>

    <div v-if="Math.random() > 0.5">
      Ahora puedes verme
    </div>
    <div v-else>
      Ahora no puedes verme
    </div> 


    <h3>Installed CLI Plugins</h3>


    
  </div>
</template>

<script>
import './assets/tailwind.css';

export default {
  name: 'HolaMundo',
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
