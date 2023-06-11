<script setup lang="ts">
// import { RouterLink, RouterView } from 'vue-router'
import {ref} from 'vue';
import $ from "jquery";
import AOS from 'aos';
import 'aos/dist/aos.css';
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap";


const scrolltop = (caseName)=>{
  $('html, body').animate({
      // scrollTop: $(".connection-wrap").offset().top
      scrollTop: $(caseName).offset().top
  }, 300);
}
// function scrollTop(casename){
//   $('html, body').animate({
//       // scrollTop: $(".connection-wrap").offset().top
//       scrollTop: $(casename).offset().top
//   }, 300);
// }


AOS.init();
</script>
<template>
<div class="wrap">
  <nav aria-label="breadcrumb" class="breadcrumbNav lead">
  <ol class="breadcrumb text-center justify-content-center ">
    <li class="breadcrumb-item"><a href="#" @click="scrolltop('.header')" class="text-decoration-none">Home</a></li>
    <li class="breadcrumb-item"><a href="#" @click="scrolltop('.exp')" class="text-decoration-none">Experience</a></li>
    <li class="breadcrumb-item"><a href="#" @click="scrolltop('.skill')" class="text-decoration-none">Skill</a></li>
    <li class="breadcrumb-item"><a href="#" @click="scrolltop('.edu-content')" class="text-decoration-none">Education</a></li>
    <li class="breadcrumb-item"><a href="#" @click="scrolltop('.connection-wrap')" class="text-decoration-none">Contact</a></li>
  </ol>
</nav>
  <div class="header">
      <h1>Kelvin Leung</h1>
      <hr>
      <img src="./assets/name.svg" class="rounded-circle" alt="cotact me">
      <hr>
  </div>
  <div class="exp">
    <h2 class="text-danger mt-3 text-center" >Experience</h2>
  </div>
    <div class="container py-5">
    <div class="main-exp-content text-white">
      <div class="exp-content left-side" data-aos="fade-up-right" data-aos-duration="2000" data-aos-anchor-placement="bottom-bottom">
        <div class="card gradient-custom">
          <div class="card-body p-4" >
            <div class="col-12 d-flex">
              <div class="col-3"><h5 class="text-start text-white">Date:</h5></div>
              <div class="col-6 text-wrap"><h5 class="text-end text-white">August 2022 to February 2023</h5></div>
            </div>
            <div class="col-12 d-flex">
              <div class="col-3">
                <h5>Company:</h5>
              </div>
              <div class="col-6">
                <h5 class="text-center text-wrap">Epro Telecome Services Limited</h5>
              </div>
            </div>
            <div class="col-12 d-flex">
              <div class="col-3">
                <h5>Position:</h5>
              </div>
              <div class="col-6">
                <h5 class="text-center">Senior Web Developer</h5>
              </div>
            </div>
            <p>   
              <ul>
                <li >Worked as part of a team to develop web applications using ASP.NET</li>
                <li>Developed a CMS system for government projects</li>
                <li>Contributed to development and maintenance web applications</li>
              </ul> 
            </p>
          </div>
        </div>
      </div>
      <div class="exp-content right-side" data-aos="fade-up-left" data-aos-duration="2000" data-aos-anchor-placement="bottom-bottom">
        <div class="card gradient-custom-4">
          <div class="card-body p-4">
            <div class="col-12 d-flex">
              <div class="col-3"><h5 class="text-start text-white">Date:</h5></div>
              <div class="col-6 text-wrap"><h5 class="text-end text-white" >October 2021 to December 2021</h5></div>
            </div>
            <div class="col-12 d-flex">
              <div class="col-3">
                <h5>Company:</h5>
              </div>
              <div class="col-6">
                <h5 class="text-center text-wrap">Alliance Computer Systems Ltd</h5>
              </div>
            </div>
            <div class="col-12 d-flex">
              <div class="col-3">
                <h5>Position:</h5>
              </div>
              <div class="col-6">
                <h5 class="text-center">Analyst Programmer</h5>
              </div>
            </div>
            <p>            
              <ul>
                <li>Collaborated with a team to develop a booking and ticketing web application using Golang</li>
                <li>Worked on the backend development of the application</li>
                <li>Company closed in December 2021</li>
              </ul> 
            </p>
          </div>
        </div>
      </div>
      <div class="exp-content left-side" data-aos="fade-up-right" data-aos-duration="2000">
        <div class="card gradient-custom">
          <div class="card-body p-4">
            <div class="col-12 d-flex">
              <div class="col-3"><h5 class="text-start text-white">Date:</h5></div>
              <div class="col-6 text-wrap"><h5 class="text-end text-white">July 2018 to October 2021</h5></div>
            </div>
            <div class="col-12 d-flex">
              <div class="col-3">
                <h5>Company:</h5>
              </div>
              <div class="col-6">
                <h5 class="text-center text-wrap">Novation Solutions Limited</h5>
              </div>
            </div>
            <div class="col-12 d-flex">
              <div class="col-3">
                <h5>Position:</h5>
              </div>
              <div class="col-6">
                <h5 class="text-center">Programmer</h5>
              </div>
            </div>
            <p>
              <ul>
                <li>Developed, maintained, and supported application programs using .NET</li>
                <li>Developed a document and image processing system</li>
                <li>Built Windows-based applications and automation tools</li>
                <li>Worked on a variety of financial applications for the company's customers</li>
              </ul> 
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>  

  <div class="skill mt-5 mb-5" >
          <div class="skill-back w-100 mt-5"  data-aos="fade-down-left" data-aos-duration="2000" data-aos-easing="ease-out-cubic">
            <div class="skill-content">
            <div class="row">
              <div class="col-12">
                <h1 class="text-center">Skill</h1>
                  <hr>
              </div>
            <div class="col-6 col-lg">
                <div class="pb-10">
                  <div class="skill-item">
                  <h4 class="text-primary">
                    Program Skill
                  </h4>
                  <ul class="skill-ul">
                    <li>ASP.NET</li>
                    <li>C#</li>
                    <li>Golang</li>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>MSSQL</li>
                    <li>MY SQL</li>
                  </ul>
                </div>
                </div>
            </div>
            <div class="col-6 col-lg">
                <div class="pb-10">
                  <div class="skill-item">
                  <h4 class="text-primary">Language Skill</h4>
                  <ul class="skill-ul">
                    <li>Cantonese</li>
                    <li>English</li>
                    <li>mandarin</li>
                  </ul>
                </div>
                </div>
            </div>
          </div>
          </div>
     </div>
     </div>



  <div class="edu-container my-5 mt-5" data-aos="fade-up" data-aos-duration="3000">
  <div class="row">
    <div class="col-md-6 offset-md-3">
      <h2 class="text-danger text-center">Education</h2>
      <ul class="edu-content">
        <li>
          <a href="#!">BACHELOR OF COMPUTING</a>
          <a href="#!" class="float-end">2018~2021</a>
          <p class="mt-2">The Open University of Hong Kong(HKMU)</p>
        </li>
        <li>
          <a href="#!">Higher Diploma in Software Engineering</a>
          <a href="#!" class="float-end">2016~2018</a>
          <p class="mt-2">Hong Kong Institute of Vocation Education</p>
        </li>
      </ul>
    </div>
  </div>
</div>


<div class="connection-wrap text-center mb-2 py-3">
    <div class="container">
      <div class="title-bottom-line">
        <h2>Contact ME</h2>
        <span>CONTACT METHOD</span>
        <hr>
      </div>
​
      <div class="connection">
        <div>Name:Leung Ka Man</div>
        <div>Mail：leungkaman335@gmail.com</div>
        <div>Phone：65070576</div>
      </div>
    </div>
  </div>

</div>


</template>

<style scoped>
    /* .wrap{
      margin: auto;
    } */
    .breadcrumbNav{
      background:linear-gradient(60deg,#B1A7A6,#D3D3D3);
    }

    hr{
      width: 80%;
      margin: 10px 10% 0 10%;
      background-color:#000;
      height: 2px;
    }

    .header{
      text-align: center;
    }
    .header h1{
      padding-bottom: .3em;
      margin-bottom: .3em;
    }
    .header img{
      margin-top: 20px;
      border: 1px solid #888;
      width: 300px;
      height: 300px;
    }

    .exp{
      margin-left: 10%;
      margin-right: 10%;
    }



    /* The actual timeline (the vertical ruler) */
.main-exp-content {
  position: relative;
}

/* The actual timeline (the vertical ruler) */
.main-exp-content::after {
  content: "";
  position: absolute;
  width: 3px;
  background-color: #bbb;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.exp-content {
  position: relative;
  background-color: inherit;
  width: 50%;
  transition: .5s;
}

.exp-content .card{
  transition: .8s;
}

.exp-content .card:hover{
  scale: 1.1;

}

/* The circles on the timeline */
.exp-content::after {
  content: "";
  position: absolute;
  width: 25px;
  height: 25px;
  right: -11px;
  background-color: #bbb;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left-side {
  padding: 0px 40px 20px 0px;
  left: 0;
}

/* Place the container to the right */
.right-side {
  padding: 0px 0px 20px 40px;
  left: 50%;
}

/* Add arrows to the left container (pointing right) */
.left-side::before {
  content: " ";
  position: absolute;
  top: 18px;
  z-index: 1;
  right: 30px;
  border: medium solid  #BDE0FE;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent #BDE0FE;
}

/* Add arrows to the right container (pointing left) */
.right-side::before {
  content: " ";
  position: absolute;
  top: 18px;
  z-index: 1;
  left: 30px;
  border: medium solid #FFC8DD;
  border-width: 10px 10px 10px 0;
  border-color: transparent #FFC8DD transparent transparent;
}

/* Fix the circle for containers on the right side */
.right-side::after {
  left: -14px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .main-exp-content::after {
    left: 31px;
  }

  .exp-content {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

  .exp-content::before {
    left: 60px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
    white-space: wrap;
    overflow-wrap: break-word;

  }

  .left-side::after,
  .right-side::after {
    left: 18px;
  }

  .left-side::before {
    right: auto;
  }
  .right-side {
    left: 0%;
  }
}

.gradient-custom {
  background: #6a11cb;

  background: -webkit-linear-gradient(
    to right,
    #BDE0FE,#A2D2FF
  );

  background: linear-gradient(
    to right,
    #BDE0FE,#A2D2FF
  );
}

.gradient-custom-4 {
  background: #f093fb;

  background: -webkit-linear-gradient(
    to left,
    #FFC8DD,#FFAFCC
  );

  background: linear-gradient(
    to left,
    #FFC8DD,#FFAFCC
  );
}

.skill{
  height: 300px;
  background-color: #6096BA;
  transition: 1s;
}

.skill-back{
  position:absolute;
  display: flex;
  justify-content: center;
  margin-bottom: 80px;
}

.skill-content{
background-color: #A3CEF1;
width: 60%;
height: 400px;
position: relative;
margin: -100px;
display: flex;
justify-content: center;
}

.skill-content .skill-text{
  font-size: 20px;
}

.skill:hover{
  color: #fff;
  font-size: 18px;
}
.skill-content ul{
  display: flex;
  flex-direction: column;
  padding: 0;
  margin: 0;
}

.skill-content .skill-ul li{
  list-style-type: none;
  line-height: 1.8em;
}


.edu-container{
  padding-top: 50px;
}
ul.edu-content {
  list-style-type: none;
  position: relative;
}
ul.edu-content:before {
  content: " ";
  background: #d4d9df;
  display: inline-block;
  position: absolute;
  left: 29px;
  width: 2px;
  height: 100%;
  z-index: 400;
}
ul.edu-content > li {
  margin: 20px 0;
  padding-left: 20px;
}
ul.edu-content > li:before {
  content: " ";
  background: white;
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 3px solid #22c0e8;
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 400;
}
.edu-content a{
  text-decoration: none;
}

.connection-wrap{
  background-color: #A3CEF1;
}
.connection-wrap .connection{
  font-size: 18px;
}

</style>
