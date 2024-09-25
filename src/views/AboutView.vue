<template>
  <div class="about">
    <h1>Hi! My name is Graham Pharr</h1>
    <h2>
      I am a full-stack software engineer with over a year of experience, I
      graduated with a bachelors degree from ISU in 2023, and have been working
      ever since at GROWMARK in order to help feed and fuel the world
    </h2>
  </div>
  <v-card class="card">
    <v-card-title>Technologies</v-card-title>
    <v-card-text>Vue (kinda)</v-card-text>
  </v-card>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "about-page",
});
</script>

<style scoped>
.about {
  background-color: aquamarine;
  border-radius: 2vh;
}
.card {
  width: 50%;
}
</style>
