<template>
<div>
  <h1 class="mt-2 mb-5">My Resume - Talmon Mwakesi Mwazo</h1>
  <el-tabs :tab-position="tabPosition" style="height: 1000px" class="demo-tabs">
    <el-tab-pane label="User">Profile</el-tab-pane>
    <el-tab-pane label="Config">Work Experience</el-tab-pane>
    <el-tab-pane label="Role">Education</el-tab-pane>
    <el-tab-pane label="Skills">Skills</el-tab-pane>
    <el-tab-pane label="Hobbies">Hobbies</el-tab-pane>
    <el-tab-pane label="References">References</el-tab-pane>
  </el-tabs>
  </div>
</template>
<script lang="ts" setup>
import { ref } from '@vue/composition-api'
const tabPosition = ref('left')
</script>
<style>
.demo-tabs > .el-tabs__content {
  padding: 32px;
  color: #6b778c;
  font-size: 40px;
  font-weight: 600;
}
.el-tabs--right .el-tabs__content,
.el-tabs--left .el-tabs__content {
  height: 100%;
}
</style>
