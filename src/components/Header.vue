<template>
  <header>
    <nav>
      <ul>
        <li><a href="#about">Tentang Kami</a></li>
        <li><a href="#projects">Proyek</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header'
};
</script>

<style scoped>
nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}
</style>
