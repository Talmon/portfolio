<template>
<div>
  <el-header class="mt-2 mb-2  header-text">RESUME - TALMON MWAKESI MWAZO</el-header>
  <el-tabs :tab-position="tabPosition" style="height: 80%;" class="resume-tabs">
    <el-tab-pane class="tab-pane" >
      <template #label>
        <h1 class="h1-text">Profile</h1>  
      </template>  
      <Profile />
    </el-tab-pane>
    <el-tab-pane label="Work Experience"> 
      <template #label>
        <h1 class="h1-text">Work Experience</h1>  
      </template>  
      <WorkExperience />
    </el-tab-pane>
    <el-tab-pane label="Education">
      <template #label>
        <h1 class="h1-text">Education</h1>  
      </template>  
      <Education /> 
    </el-tab-pane>
    <el-tab-pane label="Hobbies">
      <template #label>
        <h1 class="h1-text">Hobbies</h1>  
      </template>  
      <Hobbies />
    </el-tab-pane>
    <el-tab-pane label="References"> 
      <template #label>
        <h1 class="h1-text">References</h1>  
      </template>  
        <References />
    </el-tab-pane>
  </el-tabs>
  </div>
</template>
<script lang="ts" setup>
import { ref } from '@vue/composition-api'
const tabPosition = ref('left')
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@300&display=swap');


.resume-tabs > .el-tabs__content {
  padding: 32px;
  color: #6b778c;
  font-size: 29px;
  font-weight: 400;
  font-family: 'Raleway', sans-serif;
}

.h1-text {
    font-size: 15px;
    font-family: 'Raleway', sans-serif;
}

.el-tabs--right .el-tabs__content,
.el-tabs--left .el-tabs__content {
  height: 100%;
}
.header-text {
    /* margin-top: 10px; */
    display: none;
    font-size: 50px;
    text-align: center;
    background-color: rgb(150, 104, 194);
    color: #fff;
    margin-bottom: 30px;
    font-family: 'Raleway', sans-serif;
    height: 500px;
}

/* //Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { 
    .avatar {
        margin-top: 30px;
        margin-left: 5%;
        height: 300px;
        width: 300px;
   }



}

/* // Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { 
  .header-text {
    display: block;
  } 

  .h1-text {
    font-size: 25px;
    font-family: 'Raleway', sans-serif;
  }
    
}

/* // Large devices (desktops, 992px and up) */
@media (min-width: 992px) { 
    .header-text {
    display: block;
  } 

  .h1-text {
    font-size: 30px;
    font-family: 'Raleway', sans-serif;
  }
}

/* // X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { 
    .header-text {
        display: block;
    } 

    .h1-text {
        font-size: 35px;
        font-family: 'Raleway', sans-serif;
    }
}

/* // XX-Large devices (larger desktops, 1400px and up) */
@media (min-width: 1400px) { 
    .header-text {
        display: block;
    }
    
    .h1-text {
        font-size: 40px;
        font-family: 'Raleway', sans-serif;
    }
}

</style>
