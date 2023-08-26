<script setup>
const msg = 'teste';

const pessoa = ["André Rafael", 29];
const pessoa2 = {
  data: {
    nome: "André Rafael",
    idade: 29,
  },

}
pessoa2.data.idade = 30;
</script>

<template>
  <p>{{ msg }}</p>
  <div>
    {{ pessoa[0] }}
  </div>
  <div>
    {{ pessoa2.data.idade }}
  </div>
</template>

<style scoped></style>
