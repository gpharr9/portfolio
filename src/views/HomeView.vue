<template>
  <section class="about">
    <div class="container">
      <h1>About Me</h1>
      <p>
        Hello! I'm Graham Pharr, a passionate Software Engineer based in
        Chicago. I specialize in Full-Stack Development, specifically with
        Vue.js and React!
      </p>
      <p>
        With two years of experience in the industry, I have honed my skills in
        Vue, React, Typescript, AWS, and Postgres. I have a high level of
        passion and energy that I would love to bring to your team!
      </p>
      <p>
        When I'm not coding, you can find me rock climbing, reading, going for a
        walk on the lakefront, or baking up a sweet treat!
      </p>
      <p>Feel free to reach out if you want to collaborate or just say hi!</p>
    </div>
  </section>
  <section class="technologies">
    <div class="container">
      <h1>Technologies I'm Proficient With!</h1>
      <ul>
        <li>Vue.js</li>
        <li>React</li>
        <li>Typescript</li>
        <li>AWS</li>
        <li>Postgres</li>
      </ul>
    </div>
  </section>

  <section class="contact">
    <div class="container">
      <h1>Contact Information</h1>
      <p>Email: <a href="mailto:gpharr@gmail.com">gpharr@gmail.com</a></p>
      <p>
        LinkedIn:
        <a href="https://www.linkedin.com/in/gpharr/" target="_blank">
          linkedin.com/in/gpharr/
        </a>
      </p>
      <p>
        GitHub:
        <a href="https://github.com/gpharr9" target="_blank">
          github.com/gpharr9
        </a>
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutPage",
};
</script>

<style scoped>
.about,
.technologies,
.contact {
  padding: 2rem;
  color: #333;
  background-color: #f9f9f9; /* Consistent background color */
}

.technologies {
  border-top: 2px solid #6a0dad; /* Distinctive top border for separation */
}

.contact {
  background-color: #eaeaea; /* Slightly different shade for differentiation */
}

.container {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
}

p {
  font-size: 1.1rem;
  line-height: 1.6;
  margin-bottom: 1rem;
}

ul {
  list-style: none;
  padding: 0;
  font-size: 1.1rem;
  line-height: 1.6;
}

li {
  margin-bottom: 0.5rem; /* Space between list items */
}

a {
  color: #6a0dad; /* Link color to match the theme */
  text-decoration: none; /* Remove underline */
}

a:hover {
  text-decoration: underline; /* Underline on hover for clarity */
}
</style>
