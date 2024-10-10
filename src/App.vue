<template>
  <CardBlue run="11.222.222-2" apellidos="Daria Manx" nombres="Lorena Urtado" nacionalidad="Chilena" sexo="F" fechaNacimiento="19-09-2000" fechaDocumento="20-09-2000" numeroDocumento="21.222.42" fechaEmision="24-09-2020" fechaVencimiento="24-09-2027" />
  <CardBlue run="22.222.222-2" apellidos="Mario X" nombres="German Verde" nacionalidad="Argentina" sexo="M" fechaNacimiento="19-09-2000" fechaDocumento="20-09-2000" numeroDocumento="24.222.42" fechaEmision="24-09-2020" fechaVencimiento="24-09-2027" />
</template>

<script>
import CardBlue from './components/CardBlue.vue'

export default {
  name: 'App',
  components: {
    CardBlue
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
