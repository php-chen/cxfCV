<script setup lang="ts">
// 组件导入
import Header from "./components/Header.vue";
import About from "./components/About.vue";
import Skills from "./components/Skills.vue";
import Experience from "./components/Experience.vue";
import Projects from "./components/Projects.vue";
import Education from "./components/Education.vue";
import Links from "./components/Links.vue";
</script>

<template>
  <div class="resume-container">
    <Header />
    <About />
    <Skills />
    <Experience />
    <Projects />
    <Education />
    <Links />
  </div>
</template>

<style scoped>
.resume-container {
  max-width: 900px;
  margin: 0 auto;
  padding: 24px 12px;
  font-family: "Segoe UI", "PingFang SC", "Microsoft YaHei", Arial, sans-serif;
  background: #fff;
  color: #222;
}
</style>
