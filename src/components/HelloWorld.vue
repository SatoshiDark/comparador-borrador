<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <label>Numero de Mesa</label>
    <input v-model="numero" type="text" />
    <h2>trep</h2>
    <img v-bind:src="'https://trep.oep.org.bo/resul/imgActa/' + numero + '1.jpg'" />
    <h2>computo</h2>
    <img v-bind:src="'https://computo.oep.org.bo/resul/imgActa/' + numero + '1.jpg'" />
    <p>{{ numero }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      numero: "",
      mesa: {
        numero: '',
        imagenTrep: '',
        imagenComputo: '',
      },
    }
  },
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
