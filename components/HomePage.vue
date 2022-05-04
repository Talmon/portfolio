<template>
<div>
  <el-header class="mt-2 mb-2 header-text">RESUME - TALMON MWAKESI MWAZO</el-header>
  <el-tabs :tab-position="tabPosition" style="height: 80%;" class="demo-tabs">
    <el-tab-pane class="tab-pane" label="Profile">
      <Profile />
    </el-tab-pane>
    <el-tab-pane label="Work Experience"> <WorkExperience /></el-tab-pane>
    <el-tab-pane label="Education"> <Education /> </el-tab-pane>
    <!-- <el-tab-pane label="Skills"> <Skills /> </el-tab-pane> -->
    <el-tab-pane label="Hobbies"> <Hobbies /> </el-tab-pane>
    <el-tab-pane label="References"> <References /> </el-tab-pane>
  </el-tabs>
  </div>
</template>
<script lang="ts" setup>
import { ref } from '@vue/composition-api'
const tabPosition = ref('left')
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@300&display=swap');


.demo-tabs > .el-tabs__content {
  padding: 32px;
  color: #6b778c;
  font-size: 29px;
  font-weight: 400;
  font-family: 'Raleway', sans-serif;
}

.tab-pane{
    font-size: 40px;
}

.el-tabs--right .el-tabs__content,
.el-tabs--left .el-tabs__content {
  height: 100%;
}
.header-text {
    /* margin-top: 10px; */
    font-size: 50px;
    text-align: center;
    background-color: rgb(150, 104, 194);
    color: #fff;
    margin-bottom: 30px;
    font-family: 'Raleway', sans-serif;
    height: 500px;
}
</style>
