<template>
  <section class="experience">
    <h3>工作经历</h3>
    <div class="job">
      <div class="job-header">
        <span class="job-title">IT部门主管（移动前端开发）</span>
        <span class="job-company">广森数码印刷股份有限公司</span>
        <span class="job-time">2022.06 - 2025.08</span>
      </div>
      <ul>
        <li>系公司IT部门主管，参与公司决策及各类型会议，带领IT部门完成各项需求</li>
        <li>制定IT部门绩效考核制度与年度开发任务与规划，制定次年部门预算</li>
        <li>协助同事开发，解决同事工作中的各类问题，分析公司内部系统功能及开发方向</li>
        <li>收集同事各项需求，汇报给直属领导，提高部门开发效率</li>
        <li>带领IT部门完成各项工作</li>
      </ul>
    </div>
    <div class="job">
      <div class="job-header">
        <span class="job-title">移动前端开发</span>
        <span class="job-company">广州云润大数据</span>
        <span class="job-time">2021.09 - 2022.06</span>
      </div>
      <ul>
        <li>负责移动端H5页面与小程序的研发工作，主要对数据进行可视化渲染</li>
        <li>对组件可拓展性进行优化，完善复杂业务模块的前端开发</li>
        <li>对已有的功能进行日常维护，项目问题处理，具备独立承担前端开发能力</li>
      </ul>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
.experience {
  margin-bottom: 24px;
}
.job {
  margin-bottom: 18px;
}
.job-header {
  font-weight: bold;
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  margin-bottom: 6px;
}
.job-title {
  color: #0078e7;
}
.job-company {
  color: #444;
}
.job-time {
  color: #888;
}
ul {
  margin: 0 0 0 18px;
  padding: 0;
}
li {
  margin-bottom: 4px;
}
</style>
