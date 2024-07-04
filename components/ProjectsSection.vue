<template>
  <section class="projects"id="projects">
    <h2>My Projects</h2>
    <div class="project-list">
      <div class="project-card">
        <h3>Project One</h3>
        <p>Pengembangan Platform Pengiriman Indahcargo</p>

      </div>
      <div class="project-card">
        <h3>Project Two</h3>
        <p>Optimalisasi Pembangunan Warung Kopi melalui Media Sosial</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: #e9ecef;
  text-align: center;
}

.projects h2 {
  font-size: 2.5em;
  margin-bottom: 30px;
  color: #343a40;
}

.project-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.project-card {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  width: 300px;
  padding: 20px;
  transition: transform 0.3s;
}

.project-card:hover {
  transform: translateY(-10px);
}

.project-card h3 {
  margin-bottom: 10px;
  font-size: 1.5em;
  color: #007bff;
}

.project-card p {
  font-size: 1em;
  color: #6c757d;
  line-height: 1.6;
}


.project-link:hover {
  background: #0056b3;
}
</style>