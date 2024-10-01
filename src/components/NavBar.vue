<template>
  <nav class="nav">
    <div class="container">
      <router-link class="link" to="/">Home</router-link>
      <router-link class="link" to="/about">Projects</router-link>
    </div>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "NavBar",
});
</script>

<style scoped>
.nav {
  background-color: #6a0dad; /* Vibrant purple */
  height: 60px; /* Height for navbar */
  display: flex;
  align-items: center; /* Center links vertically */
  position: sticky;
  top: 0; /* Stick to the top */
  background-color: #6a0dad; /* Background color */
  z-index: 1000; /* Ensure it’s above other elements */
  padding: 1rem 0; /* Padding for visual spacing */
}

.container {
  display: flex; /* Flexbox for horizontal layout */
  gap: 1rem; /* Space between links */
}

.link {
  color: white; /* Link color */
  text-decoration: none; /* Remove underline */
  font-size: 1.2rem; /* Font size */
  padding: 0.5rem 1rem; /* Padding for better click area */
  transition: background-color 0.3s, color 0.3s; /* Smooth transitions */
}

.link:hover {
  background-color: rgba(255, 255, 255, 0.2); /* Hover effect */
  color: #ffeb3b; /* Hover color */
}
</style>
