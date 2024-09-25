<!-- eslint-disable prettier/prettier -->
<template>
    <div class="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "nav-bar",
});
</script>

<style scoped>
.nav {
  background-color: red;
  height: 3vh;
}
</style>
