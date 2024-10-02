<template>
  <section class="hero">
    <h1>Mendukung Hewan Tunawisma</h1>
    <p>Bergabunglah dalam upaya kami memberikan perawatan untuk hewan yang membutuhkan</p>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
};
</script>

<style scoped>
.hero {
  height: 100vh;
  background: url('/path-to-background.jpg') center/cover no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}
</style>
