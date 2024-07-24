<template>
  <!-- <link rel="stylesheet" href="SnowWorld.css"> -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
  <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'> 
  <div>
  <p class="attention">Free Courses <i class="bi bi-brightness-high-fill"></i> Sale Ends Soon,Get it Now  <i class="bi bi-arrow-right-short"></i></p>
  </div>
  <nav class="nav-bar">
    <div class="container-1">
      <div class="sub-container-1">
       <img src="../assets/images/Logologo.png" alt="" >
       <ul>
        <li>Home</li>
        <li>Courses</li>
        <li>About Us</li>
        <li>Pricing</li>
        <li>Contact</li>
       </ul>
      </div>
       <div class="sub-container-2">
        <button class=" button btn__white">Sign Up</button>
        <button class="button btn__primary">Login</button>
      </div>
    </div>
    <!-- <div class="container-2" id="container-2">
      <div>
        <img src="../assets/images/Logologo.png" alt="">
      </div>
      <div>
        <button class=" button btn__white">Sign Up</button>
        <button class="button btn__primary">Login</button>
      </div>
      <div>
        <button id="button" onclick="toggleButton()"><i class='bx bx-menu-alt-right'></i></button>
        <ul id="list">
          <li>Home</li>
          <li>Courses</li>
          <li>About us</li>
          <li>Pricing</li>
          <li>Contact</li>
        </ul>
      </div>
     
      
    </div> -->
  </nav>
  <!-- ================BODY STARTS================= -->
   <div class="bod">
    <button>
      <div>
        <img src="../assets/images/Icon Containerflash - Copy.png" alt="">
      </div>
      <div>
        <h1><span>Unlock</span> Your Creative Potential</h1>
      </div>
    </button>
   </div>
   <div class="container-3">
    <h2><b>with Online Design and Development Courses.</b> </h2>
    <p>learn from Industry Experts and Enhance Your Skills.</p>
    <div class="subcontainer-3">
      <button class=" button btn__primary"><b>Explore Courses</b></button>
      <button class="button btn__white"><b>View Pricing</b></button>
    </div>
   </div>
   <div class="container-4">
    <div>
      <img src="../assets/images/Logozapier.png" alt="" class="ima">
    </div>
    <div>
      <img src="../assets/images/Logospotify.png" alt="" class="imag">
    </div>
    <div>
      <img src="../assets/images/Logozoom.png" alt="" class="imag">
    </div>
    <div>
      <img src="../assets/images/Logoamazon.png" alt="" class="imag">
    </div>
    <div>
      <img src="../assets/images/Adobe.png" alt="" class="imag">
    </div>
    <div>
      <img src="../assets/images/Logonotion.png" alt="" class="imag">
    </div>
    <div>
      <img src="../assets/images/Cardnetflix - Copy.png" alt="" class="netflix">
    </div>
   </div>
   <div class="container-5">
    <div>
      <img src="../assets/images/ContainerheroImg - Copy.png" alt="image" class="background-image">
   </div>
   </div>
   <div class="container-6">
    <div>
      <h1>
        Benefits
      </h1>
    </div>
    <div class="mother">
      <div>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eos ipsum, necessitatibus distinctio ipsa placeat totam nisi aliquam neque quam doloremque, amet velit <br> repudiandae ut itaque recusandae tempore iusto at ad!</p>
      </div>
      <div>
        <button>View All</button>
      </div>
    </div>
   </div>
   <!-- <div class="container-7">
    <div>
      <div>
         <h1>01</h1>
         <div>
          <h3>Flexible Learning Schedule</h3>
         <p>Fit your coursework around your existing <br>commitments and obligations.</p>
         
         </div>
      </div>
      <div>
        <h1>04</h1>
         <div>
          <h3>Updated Curriculum</h3>
         <p>Access courses with up-to-date content<br>reflecting the latest trends and industry <br>practices.</p>
         <i class="bi bi-arrow-up-right-square"></i>
         </div>
      </div>
    </div>
    <div>
      <div>
         <h1>02</h1>
         <div>
          <h3>Flexible Learning Schedule</h3>
         <p>Fit your coursework around your existing <br>commitments and obligations.</p>
         <i class="bi bi-arrow-up-right-square"></i>
         </div>
      </div>
      <div>
        <h1>01</h1>
         <div>
          <h3>Flexible Learning Schedule</h3>
         <p>Fit your coursework around your existing <br>commitments and obligations.</p>
         <i class="bi bi-arrow-up-right-square"></i>
         </div>
      </div>
    </div>
    <div>
      <div>
         <h1>01</h1>
         <div>
          <h3>Flexible Learning Schedule</h3>
         <p>Fit your coursework around your existing <br>commitments and obligations.</p>
         <i class="bi bi-arrow-up-right-square"></i>
         </div>
      </div>
      <div>
        <h1>01</h1>
         <div>
          <h3>Flexible Learning Schedule</h3>
         <p>Fit your coursework around your existing <br>commitments and obligations.</p>
         <i class="bi bi-arrow-up-right-square"></i>
         </div>
      </div>
    </div>
   </div> -->

   <div class="container-7">
    <!-- <div>
      <div>
        <h1></h1>
        <div>
          <b></b>
          <p></p>
          <i class="bi bi-arrow-up-right-square"></i>
        </div>
      </div>
      <div>
        <div>
        <h1></h1>
        <div>
          <b></b>
          <p></p>
          <i class="bi bi-arrow-up-right-square"></i>
        </div>
      </div> -->
      <div>
       <div>
        <h1></h1>
        <div class="flex">
          <div v-for="tutor in tutors" :key="tutor.id" class="snow">
             <h1>{{  tutor.tag }}</h1>
             <b>{{ tutor.bold }}</b>
             <p>{{ tutor.para }}</p>
             <i class="bi bi-arrow-up-right icon"></i>
             <div>
              
               
             </div>
          </div>
        </div>
      </div>
    </div>
   </div>
   <!-- </div>
   </div>y65   -->
   <div class="container-8">
     <div>
      <h1>Our Courses</h1>
      <div class="c8-subcontainer-1">
        <div>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium ipsa, esse non quis dignissimos nihil odio, rem perferendis commodi eaque obcaecati nemo <br> iste maxime dolores. Nulla odit voluptatibus officiis minima.</p>
        </div>
        <div>
          <button>View All</button>
        </div>
      </div>
     </div>
     <div  v-for="course in courses" :key="course.id">
      <img :src="course.img" alt="">
       <!-- <p>{{ course.img }}</p> -->
     </div>
   </div>
   <!-- =================BODY STOPS================/ -->
</template>

<script>
export default {
     name:'SnowWorld',
     data(){
      return{
        tutors : [
            { name: 'Tutors Name',tag:"01",bold:"Flexible Learning schedule",para:"Fit your course work around your existing commitments and obligations."},
            { name: 'Tutors Name',tag:"02",bold:"Expert Instruction",para:"Learn from industry experts who have hands on experience in design and development."},
            { name: 'Tutors Name',tag:"03",bold:"Diverse Course Offerings",para:"Explore a wide range of design and development courses covering various topics."},
            { name: 'Tutors Name',tag:"04",bold:"Updated Curriculum",para:"Access courses with up-to-date content reflecting the latest trends and industry practices."},
             { name: 'Tutors Name',tag:"05",bold:"Practical Projects and Assignments",para:"Develop a portfolio showcasing your skills and abilities to potential employers."},
            { name: 'Tutors Name',tag:"06",bold:"Interactive Learning Environment",para:"Collaborate with fellow learners,exchanging ideas and feedback to enhance your understanding."}
      ],
      courses:[
      { img:"/src/assets/images/Imagecourse1 - Copy.png",},
      {},
      {},
      {},
      {},
      {}
      ]
      }
     }
}

// function toggleButton() {
//         var list = document.getElementById("list");

//         if (list.style.display === "none") {
//             list.style.display = "block";
//         } else {
//            list.style.display = "none";
//         }
//       }    

</script>

<style>

</style>
<nav>

</nav>