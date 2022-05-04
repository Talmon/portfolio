<template>
    <div>
         <h1>Profile</h1> 
         <el-card >
        <img
          src="https://media-exp1.licdn.com/dms/image/C5103AQFo-DjHQKc_dg/profile-displayphoto-shrink_800_800/0/1516443673669?e=1657152000&v=beta&t=dfsfdoWotGVfVSdpBjwW-OOZBEPOJrDE8k_9w18emxU"
          class="image avatar"
        />
        <div class="profile" style="padding: 14px">
          <span> <p>  Name: Talmon Mwakesi Mwazo </p> </span>
          <span><p> Mobile No: +254 727 136 485 </p>  </span>
          <span> <p>  Email: talimwakesi@gmail.com </p> </span>
          <span> <p> Github profile:  <a href="https://github.com/Talmon" target="_"> Click here  </a> </p>    </span>
           <p class="lead">I am a born again believer of Jesus Christ,I dedicated my whole life to him. </p>
           <p>I am also a full stack developer with over 4 years experience in development with <strong> PHP </strong>,<strong>Javascript </strong> and <strong>Python </strong>.I've mainly used <strong> MySQL </strong>,<strong> PostgreSQL </strong> and <strong> Firebase </strong> for databases.I'm proficient with <strong> GCP </strong>  for DevOps.My main frameworks are: </p>
               <ul>
                   <li>Laravel</li>
                   <li>VueJS</li>
                   <li>ReactJS</li>
                   <li>FASTapi</li>
                   <li>ElementUI</li>
                   <li>Vuetify</li>
                   <li>AdonisJS</li>
                   <!-- <li></li> -->
               </ul>
        </div>
      </el-card>
    </div>
</template>


<style>
.profile {
    font-size: 25px;
}

.profile span p{
    font-weight: 600px;
}

.avatar {
    margin-top: 30px;
    margin-left: 45%;
    height: 300px;
    width: 300px;
}

.profile ul li {
    list-style: square;
}

</style>