<script setup>
import { ref } from 'vue'

const listaCidades = [
  'São Paulo',
  'Rio de Janeiro',
  'Belo Horizonte',
  'Salvador',
  'Fortaleza',
  'Curitiba',
  'Manaus',
  'Recife',
  'Porto Alegre',
  'Brasília',
];

</script>
<template>
  <ul>
    <li v-for="(value, key) in listaCidades.sort()" :key="key">{{ key }}: {{ value }}</li>
  </ul>
</template>
<style>
ul {
  font-size: 35px;

}
</style>