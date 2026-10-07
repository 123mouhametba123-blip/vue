<script setup>
const Message ="breukh";
</script>

<template>
  <section class="card">
    <h2>01 hello world</h2>
    <p>Premier composant Vue (SFC)</p>
    <div class="box"> 
      <strong>Message:</strong>{{Message.toUpperCase()}}
    </div>
  </section>
</template>



<style scoped>
.card{
 padding : 16px;
 border: 1px solid #eee;
 border-radius: 12px;
}
.box{
  margin-top: 10px;
  padding: 12px;
  border: 1px dashed #ccc;
  border-radius: 12px;
}
</style>