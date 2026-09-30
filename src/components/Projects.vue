```vue
<template>
  <section id="projects" class="projects-section">
    <div class="projects-container">
      <h2>My Projects</h2>

      <p class="projects-intro">
        Here are some of the projects I have worked on while developing
        my skills in web development and software development.
      </p>

      <div class="projects-grid">
        <div class="project-card">
          <h3>SafeHer E-Commerce Project</h3>
          <p>
            A full-stack e-commerce platform focused on personal safety
            products and digital safety support.
          </p>

          <p class="technologies">
            Vue.js · Node.js · Express · MySQL · PayFast
          </p>
        </div>

        <div class="project-card">
          <h3>Modern Tech Solutions</h3>
          <p>
            An HR management system featuring employee management,
            attendance, payroll, and time-off functionality.
          </p>

          <p class="technologies">
            HTML · CSS · JavaScript · Node.js · Express · MySQL
          </p>
        </div>

        <div class="project-card">
          <h3>Python Mini Toolkit</h3>
          <p>
            A Python command-line toolkit containing utilities such as
            a grade calculator, even or odd checker, number guessing game,
            and study planner.
          </p>

          <p class="technologies">
            Python
          </p>
        </div>

        <div class="project-card">
          <h3>YouthConnect</h3>
          <p>
            A student opportunities and freelance marketplace designed
            to connect young people with opportunities to develop their
            skills and gain experience.
          </p>

          <p class="technologies">
            HTML · CSS · JavaScript
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.projects-section {
  padding: 100px 8%;
  background: #080808;
  color: white;
}

.projects-container {
  max-width: 1200px;
  margin: 0 auto;
  text-align: center;
}

.projects-container h2 {
  font-size: 42px;
  margin-bottom: 15px;
}

.projects-intro {
  max-width: 700px;
  margin: 0 auto 50px;
  color: #cccccc;
  line-height: 1.7;
  font-size: 17px;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 25px;
}

.project-card {
  padding: 30px;
  background: #111111;
  border: 1px solid #333333;
  border-radius: 12px;
  text-align: left;
  transition: transform 0.3s ease, border-color 0.3s ease;
}

.project-card:hover {
  transform: translateY(-6px);
  border-color: white;
}

.project-card h3 {
  font-size: 22px;
  margin-bottom: 15px;
}

.project-card p {
  color: #bbbbbb;
  line-height: 1.7;
}

.project-card .technologies {
  margin-top: 20px;
  color: white;
  font-size: 14px;
  font-weight: bold;
}

@media (max-width: 900px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 600px) {
  .projects-section {
    padding: 70px 5%;
  }

  .projects-container h2 {
    font-size: 32px;
  }
}
</style>
```
