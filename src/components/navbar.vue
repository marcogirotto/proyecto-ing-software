<template>
  <nav class="navbar">
    <div class="navbar-brand">
      <a class="encabezadoItem" href="#">
        <img src="https://vuejs.org/images/logo.png" alt="Vue logo" />
      </a>
    </div>

    <div class="encabezadoMenu">
      <div class="encabezadoInicio">
        <a class="encabezadoItem" href="/">Incio</a>
        <a class="encabezadoItem" href="/about">Top juegos</a>
        <a class="encabezadoItem" href="/contact">Review</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'navbar',
};
</script>

<style scoped>
.navbar {
  background-color: #42b983;
  padding: 1rem;
}

.encabezadoItem {
  color: white;
  text-decoration: none;
  padding: 0.5rem 1rem;
}

.encabezadoItem:hover {
  background-color: #35495e;
}
</style>
