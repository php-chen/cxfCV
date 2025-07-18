<template>
  <section class="links-section">
    <h3>个人链接</h3>
    <div class="links-list">
      <a href="https://juejin.cn/user/1460615318609160" target="_blank">掘金</a>
      <a href="https://github.com/php-chen" target="_blank">GitHub</a>
      <a href="https://gitee.com/php-chen" target="_blank">Gitee</a>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
.links-section {
  margin-bottom: 24px;
}
.links-list {
  display: flex;
  gap: 18px;
  margin-top: 8px;
}
.links-list a {
  color: #0078e7;
  text-decoration: none;
  font-weight: 500;
}
.links-list a:hover {
  text-decoration: underline;
}
</style>
