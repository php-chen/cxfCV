<template>
  <header class="header">
    <div class="header-main">
      <div class="avatar" v-if="avatarUrl">
        <img :src="avatarUrl" alt="avatar" />
      </div>
      <div>
        <h1>陈向富</h1>
        <h2>IT部门主管（移动前端开发）</h2>
        <div class="contact">
          <span>📞 17727505463</span>
          <span>✉️ essdzihuang@163.com</span>
          <span>年龄：26</span>
        </div>
      </div>
      <img src="./1寸照.png" alt="" />
    </div>
    <div class="links">
      <a href="https://juejin.cn/user/1460615318609160" target="_blank">掘金</a>
      <a href="https://github.com/php-chen" target="_blank">GitHub</a>
      <a href="https://gitee.com/php-chen" target="_blank">Gitee</a>
    </div>
  </header>
</template>

<script setup lang="ts">
const avatarUrl = ""; // 如有头像图片可放assets并引用
</script>

<style scoped>
.header {
  border-bottom: 2px solid #eee;
  padding-bottom: 16px;
  margin-bottom: 24px;
}
.header-main {
  display: flex;
  align-items: center;
  gap: 24px;
}
.avatar img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  object-fit: cover;
  border: 2px solid #ddd;
}
h1 {
  margin: 0;
  font-size: 2.2rem;
  font-weight: bold;
}
h2 {
  margin: 4px 0 0 0;
  font-size: 1.2rem;
  color: #666;
}
.contact {
  margin-top: 8px;
  font-size: 1rem;
  color: #444;
  display: flex;
  gap: 16px;
}
.links {
  margin-top: 12px;
  display: flex;
  gap: 16px;
}
.links a {
  color: #0078e7;
  text-decoration: none;
  font-weight: 500;
}
.links a:hover {
  text-decoration: underline;
}
</style>
