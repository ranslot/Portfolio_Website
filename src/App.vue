<script></script>

<template>
  <header class="top-0">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/skills">Skill</router-link>
      <router-link to="/projects">Projects</router-link>
      <router-link to="/contact">Contact</router-link>
    </nav>
  </header>
  <main>
    <router-view />
  </main>
</template>

<style scoped></style>
