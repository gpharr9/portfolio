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
    <h1>Technologies I'm Proficient With!</h1>
  <v-row>
    <v-col>
      <div class="techcontainer">
      <h3>Front End Technologies</h3>
      <spacer />
      <ul>
        <li>Vue.js</li>
        <li>React</li>
        <li>Typescript</li>
        <li>Flask</li>
      </ul>
    </div>
    </v-col>
    <v-col>
      <div class="techcontainer">
      <h3>Back End Technologies</h3>
      <spacer />
      <ul>
        <li>AWS</li>
        <li>Postgres</li>
        <li>Python</li>
        <li>DynamoDB</li>
        <li>SQL</li>
      </ul>
    </div>
    </v-col>
  </v-row>  
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

.techcontainer {
  margin: 0 auto;
  text-align: center;
  width: 50%;
  background-color: #f9f9f9;
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
