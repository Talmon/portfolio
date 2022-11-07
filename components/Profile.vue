<template>
    <div>
         <h1>Profile</h1> 
         <el-card >
        <img
          src="../static/official_pic.jpeg"
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
    overflow: auto;
    font-size: 25px;
}

.profile span p{
    font-weight: 600px;
}

.avatar {
    height: 100px;
    width: 100px;
}

.profile ul li {
    list-style: square;
}


/* The other queries are for xs */

/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { 
    .avatar {
        height: 150px;
        width: 150px;
   }
}

/*  Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { 
  .header-text {
    display: block;
  } 

  .avatar {
    height: 300px;
    width: 300px;
  }
    
}

/*  Large devices (desktops, 992px and up) */
@media (min-width: 992px) { 
    .header-text {
    display: block;
  } 

  .avatar { 
    height: 300px;
    width: 300px;
  }

}

/*  X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { 
    .header-text {
        display: block;
  } 

  .avatar {
    height: 300px;
    width: 300px;
  }
}

/*  XX-Large devices (larger desktops, 1400px and up) */
@media (min-width: 1400px) { 
    .header-text {
        display: block;
    } 

   .avatar {
        height: 300px;
        width: 300px;
   }
}

</style>