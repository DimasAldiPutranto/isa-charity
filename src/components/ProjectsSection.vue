<template>
  <section id="projects" class="projects-section">
    <h2>Proyek Kami</h2>
    <div class="projects">
      <div class="project-card" v-for="project in projects" :key="project.id">
        <img :src="project.image" :alt="project.name" />
        <h3>{{ project.name }}</h3>
        <p>{{ project.description }}</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection',
  data() {
    return {
      projects: [
        { id: 1, name: 'Proyek 1', description: 'Membantu penampungan 1', image: '/path-to-image1.jpg' },
        { id: 2, name: 'Proyek 2', description: 'Membantu penampungan 2', image: '/path-to-image2.jpg' }
      ]
    };
  }
};
</script>

<style scoped>
.projects-section {
  padding: 50px;
  background-color: #fff;
  text-align: center;
}
.project-card {
  display: inline-block;
  width: 300px;
  margin: 20px;
}
</style>
