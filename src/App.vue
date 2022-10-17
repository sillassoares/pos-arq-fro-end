<script setup>
import Bio from './components/Bio.vue'
import Blog from './components/Blog.vue'
</script>

<template>
  <header>
      <a href="#">Blog</a>
      <a href="#">Sobre</a>
      <a href="#">Descrição</a>
  </header>

  <main>
    <Bio />
    <Blog />
  </main>
</template>

<style scoped>
header {
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    display: flex;
    flex: 1;
    align-items: center;
    justify-content: center;
    background-color: #2F568D;
    height: 70px;
    margin-bottom: 70px;
}

a {
    text-decoration: none;
    color: #fff;
    padding: 10px;
}

main {
    width: 100%;
    padding-top: 70px;
}
</style>
