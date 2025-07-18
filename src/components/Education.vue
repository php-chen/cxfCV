<template>
  <section class="education">
    <h3>教育经历</h3>
    <div class="edu-block">
      <span class="edu-school">北海职业学院</span>
      <span class="edu-major">计算机应用技术</span>
      <span class="edu-time">2018 - 2021</span>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>
.education {
  margin-bottom: 24px;
}
.edu-block {
  display: flex;
  gap: 24px;
  font-size: 1.1rem;
  color: #444;
  margin-top: 8px;
}
.edu-school {
  font-weight: bold;
  color: #0078e7;
}
.edu-major {
  color: #666;
}
.edu-time {
  color: #888;
}
</style> 