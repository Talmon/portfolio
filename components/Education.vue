<template>
    <div>
         <h1>Education</h1> 
         <el-card >
        <div class="education" style="padding: 5px">
           <p> <strong> August 2007 - December 2011 </strong> </p>
           <p> <strong> Bachelor's Degree in Computer Science </strong> </p>
           <p> <strong> Kenyatta University ▪ Mombasa ▪ Kenya</strong> </p>
           <p>Got a Degree in Bachelor of Science,Computer Science. </p>
           
        </div>
        <hr>
        <div class="education" style="padding: 5px">
           <p> <strong> February 2003 - December 2006 </strong> </p>
           <p> <strong> Secondary School </strong> </p>
           <p> <strong>Kiambu High School ▪ Kiambu ▪ Kenya</strong> </p>
           <p> Scored a B minus in my K.C.S.E </p>    
        </div>
        <hr>
        <div class="education" style="padding: 5px">
           <p> <strong> January 2000 - December 2002 </strong> </p>
           <p> <strong> Primary School </strong> </p>
           <p> <strong> Mary Immaculate Primary School ▪ Kiambu ▪ Kenya </strong> </p>
           <p>Scored 402 marks in my K.C.P.E </p>
        </div>
        <hr>
        <div class="education" style="padding: 5px">
           <p> <strong> January 1995 - December 1999 </strong> </p>
           <p> <strong> Primary School </strong> </p>
           <p> <strong> Marion Preparatory School ▪ Kiambu ▪ Kenya </strong> </p>
           <p>Studied class 1 to 5 here. </p>
        </div>
      </el-card>
    </div>
</template>

<style>
.education {
    font-size: 25px;
}

ul li {
    list-style: none;
}



/* The other queries are for xs */

/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { 
    .education {
        overflow: auto;
    }
}

/*  Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { 
  .education {
        overflow: auto;
    }
    
}

/*  Large devices (desktops, 992px and up) */
@media (min-width: 992px) { 
    .education {
        overflow: auto;
    }

}

/*  X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) { 
    .education {
        overflow: auto;
    }
}

/*  XX-Large devices (larger desktops, 1400px and up) */
@media (min-width: 1400px) { 
   .education {
        overflow: auto;
    }
}


</style>