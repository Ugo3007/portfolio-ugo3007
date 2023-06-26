<script setup lang="ts">

</script>

<template>
  <header>
    <section>Logo</section>
    <section>
      <ul>
        <li>Home</li>
        <li>À propos</li>
        <li>Projets</li>
        <li>CV</li>
      </ul>
    </section>
  </header>
</template>

<style scoped>
  header {
    max-width: 1440px;
    width: 100%;
    height: 64px;
    display: flex;
    justify-content: space-between;
    background-color: #FFEFDF;
  }

  section {
    display: flex;
    align-items: center;
    margin: 0 10px;
    font-size: 20px;
    font-family: Inter, sans-serif;
    font-weight: 700;
  }

  ul {
    display: flex;
    list-style: none;
  }

  li {
    margin: 0 10px;
  }

</style>