<template>
  <div id="main-form">
    <form>
      <label>Numero de Mesa</label>
      <input type="text" :v-model="mesa"/>
      <button>Buscar</button>
    </form>
  </div>
</template>

<script>
  export default {
    name: 'main-form',
    props: {
      employees: Array,
    },
    data() {
      return {
        mesa: {
          numero: '',
          imagenTrep: '',
          imagenComputo: '',
        },
      }
    },
  }
</script>

<style>
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>
