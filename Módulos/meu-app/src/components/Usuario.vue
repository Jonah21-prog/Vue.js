<template>
  <div id="usuario">
    <h2>Olá: {{nome}} </h2>
  </div>
</template>

<script>
export default {
  name: "usuario",
  props: ['nome']
};
</script>

<style>
</style>
