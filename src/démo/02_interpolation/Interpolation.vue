<template>
  <ul class="bb">
    <li>Nom: {{ person.fullName.toUpperCase() }}</li>
    <li>Role:{{ person.role.toUpperCase()}}</li>
    <li>Montant: {{ montant }}</li>
    <li>Anne:{{ annee }}</li>
    <li>salaireNet:{{ salaireNet }}</li>
  </ul>
</template>

<script setup>
const montant = 10000000;
const annee = new Date().getFullYear();
const prime = 0.5;
const salaireNet = prime *montant;
const person = {
    fullName:"mouhamed",
    role : "0stacks",
};
</script>

<style>
.bb{
    background-color: red;
}
</style>