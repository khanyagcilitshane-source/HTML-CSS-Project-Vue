<template>
  <section id="skills" class="skills-section">
    <div class="skills-container">
      <h2>My Skills</h2>

      <p class="skills-intro">
        Here are some of the technologies and tools I have been learning
        and using while building my projects.
      </p>

      <div class="skills-grid">
        <div class="skill-card">
          <h3>HTML</h3>
          <p>Building structured and accessible web pages.</p>
        </div>

        <div class="skill-card">
          <h3>CSS</h3>
          <p>Creating responsive layouts and styling modern websites.</p>
        </div>

        <div class="skill-card">
          <h3>JavaScript</h3>
          <p>Adding functionality and interactive features to websites.</p>
        </div>

        <div class="skill-card">
          <h3>Vue.js</h3>
          <p>Building reusable components and interactive interfaces.</p>
        </div>

        <div class="skill-card">
          <h3>Node.js</h3>
          <p>Developing server-side applications and backend services.</p>
        </div>

        <div class="skill-card">
          <h3>Express.js</h3>
          <p>Creating backend routes and REST APIs.</p>
        </div>

        <div class="skill-card">
          <h3>MySQL</h3>
          <p>Working with databases, queries, tables, and relationships.</p>
        </div>

        <div class="skill-card">
          <h3>Git & GitHub</h3>
          <p>Managing code, branches, commits, and collaborative projects.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.skills-section {
  padding: 100px 8%;
  background: #050505;
  color: white;
}

.skills-container {
  max-width: 1200px;
  margin: 0 auto;
  text-align: center;
}

.skills-container h2 {
  font-size: 42px;
  margin-bottom: 15px;
}

.skills-intro {
  max-width: 700px;
  margin: 0 auto 50px;
  color: #cccccc;
  line-height: 1.7;
  font-size: 17px;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

.skill-card {
  padding: 30px 20px;
  border: 1px solid #333;
  border-radius: 12px;
  background: #0d0d0d;
  transition: transform 0.3s ease, border-color 0.3s ease;
}

.skill-card:hover {
  transform: translateY(-6px);
  border-color: white;
}

.skill-card h3 {
  margin-bottom: 12px;
  font-size: 21px;
}

.skill-card p {
  color: #bbbbbb;
  line-height: 1.6;
  font-size: 14px;
}

@media (max-width: 900px) {
  .skills-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .skills-section {
    padding: 70px 5%;
  }

  .skills-container h2 {
    font-size: 32px;
  }

  .skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>