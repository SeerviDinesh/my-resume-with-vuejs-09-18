<template>
<div class="first">
  <div class="hello">
    <div class="row">
      <div class="col-sm-8 text-left">
        <h1> {{restitle}} </h1>
        <h3> {{web}} </h3>
      </div>
      <div class="col-sm-4 text-left hello1">
          <div class="fa fa-phone icon1"> &nbsp;&nbsp;
            {{phone}}
          </div><br>
          <div class="fa fa-map-marker"> &nbsp;&nbsp;
            {{address}}
          </div><br>
          <div  class="fa fa-envelope">&nbsp;&nbsp;
            {{email}}
          </div>
      </div>
    </div>
  </div>
  <hr>
  <div class="bc1">
    <div class="text-left text3">
      <h2> {{text1}} </h2>
    </div>
    <p class="abouttext text-left">
      {{text2}}
    </p>
  </div>
  <div class="row">
  <div class="text-left text4 col-sm-8 text-left">
    <h2> {{text4}} </h2>
    <p class="abouttext">
      <b>January 2017 - August 2018 | Senior Web Developer
        <br>
        Aaimaa web Solutions Jodhpur
      </b><br>
      Senior Web Developer, Project Manager at Aaimaa Web Solutions and Chief Operations Officer at ToletForStudents. Responsible for helping a company seek out, develop and apply effective solutions to improve the company’s growth.
    </p><br>
    <h2>Education</h2>
    <p class="abouttext">
      <b>Bachelor of Technology | 2013 - 2017</b><br>
      Bachelor of Technology in Electronics and Communication from Jodhpur Institute of Engineering and Technology, Jodhpur (Raj.) with 60.50%.<br><br>
      <b>Training and Seminar -</b><br><br>
      <ol>
        <li>Completed 45 days Industrial Training from “State Remote Sensing and Application Centre Jodhpur” and undertaken “Density Based Traffic Control System” project during 25 May 2016 to 23 July 2016.
</li>
<li>Won 2nd prize in Open House 2015 - “Programming with LED”.</li>
<li> Project on “Programming with LCD” (Open House 2016).</li>
<li> Presented seminar on “Magnetoresistive Random Access Memory”.</li>
      </ol><br>
      <b>Senior Secondary Education | 2013</b><br>
      RBSE - Shri Aai Jee School Bilara, Jodhpur with 66.67%. <br><br>
      <b>Secondary Education | 2011</b><br>
      RBSE - R.D.S.S. School Bilara, jodhpur with 72.67%. <br>
    </p>
  </div>
  <div class="col-sm-4">
    <div class="text5 text-left">
    <p class="tec">Technology</p>
    <p class="text-left"><b>Javascript / Vue Js</b></p>
    </div>
    <div class="progress prog1">
  <div class="progress-bar bg-info" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
</div><br>
<p class="text-left"><b>PHP / React Native</b></p>
    <div class="progress prog1">
  <div class="progress-bar bg-info" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
</div><br>
<p class="text-left"><b>HTML5 / CSS3 / Bootstrap / UIKIT
</b></p>
    <div class="progress prog1">
  <div class="progress-bar bg-info" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
</div><br>
<p class="text-left"><b>Photoshop / Illustrator</b></p>
    <div class="progress prog1">
  <div class="progress-bar bg-info" role="progressbar" style="width: 60%" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100"></div>
</div><br>
<p class="text-left"><b>Decision-making / Teamwork</b></p>
    <div class="progress prog1">
  <div class="progress-bar bg-info" role="progressbar" style="width: 70%" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100"></div>
</div><br>
<p class="text-left"><b>Time Management / Responsibility</b></p>
    <div class="progress prog1">
  <div class="progress-bar bg-info" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
</div>
<div class="text5 text-left">
    <p class="tec">Proficiency</p>
    <div>
    <img src="../assets/win.png">
      <div class="float-right">
       <div class="progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
    </div><br>
    <div>
    <img src="../assets/osx.png">
      <div class="float-right">
       <div class="progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
      <div class="float-right">
     <div class="progress-bar progress prog2 vertical"></div>
    </div>
    </div><br><br>
</div>
    <router-view/>
  </div>
</div>
<div class="bc2 row">
  <div class="col-6">
    <div class="text-left text3 abouttext tec1">
      <p><b> {{text5}}</b> </p>
    </div>
    <p class="abouttext text-left">
      <b class="fa fa-certificate">&nbsp;&nbsp;&nbsp;&nbsp; Best Project Open House 2015</b>
    </p>
  </div>
  <div class="col-6">
    <div class="text-left text3 abouttext tec1">
      <p><b>Hobbies</b> </p>
    </div>
    <p class="abouttext text-left">
      <i class="fa fa-futbol-o"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <i class="fa fa-bicycle"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <i class="fa fa-book"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <i class="fa fa-camera"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <i class="fa fa-cutlery"></i>
    </p><br>
  </div>
</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      restitle: 'DINESH SEERVI',
      phone: '+91-7877613144',
      web: 'Web Developer',
      address: 'Bilara, Jodhpur (Raj.)',
      email: 'crvidinesh@gmail.com',
      text1: 'About Me',
      text2: 'Team player software engineer with a can-do attitude, phenomenal time management skills, and a strong user focused approach. I intend to establish myself as Software Engineer, contributing to the company growth and in turn ensuring personal growth with in the organization. I believe that my technical, functional and communication skills will enable me in facing the challenging career ahead.',
      text4: 'Work Experience',
      text5: 'Awards'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: bold;
  color: steelblue;
  font-size: 60px;
}
.bc1 {
  background-color: #c7e2e8;
  height: 100%;
  margin-top: -16px;
}
.bc2 {
  background-color: rgb(221, 221, 221);
  height: 100%;
  margin-left: 0;
  margin-right: 0;
}
.abouttext {
  padding-left: 50px;
}
.text3 {
  padding-top: 20px;
}
.text4 {
  padding-top: 30px;
}
.text5 {
  padding-top: 20px;
}
.tec {
  color: steelblue;
  font-size: 30px;
  font-family: inherit;
    font-weight: 500;
}
.tec1 {
  color: rgb(99, 93, 93);
  font-size: 30px;
  font-family: inherit;
  font-weight: 500;
}
.prog1 {
  margin-right: 30px;
  height: 7px;
}
.prog2 {
  margin-top: 25px;
  margin-right: 10px;
}
.vertical {
  height: 7px;
  width: 50px;
  -webkit-transform: rotate(-90deg); /* Chrome, Safari, Opera */
  transform: rotate(-90deg);
}
h3 {
  color:grey;
}
h2 {
  color: steelblue;
  padding-left: 50px;
}
hr {
    margin-left: auto;
    margin-right: auto;
    border-width: 3px;
    border-color: steelblue
}
.hello {
  padding-left: 50px;
  padding-right: 50px;
  margin-top: 50px;
}
.hello1 {
  padding-top: 25px;
  padding-bottom: 20px;
  padding-left: 20px;
}
.first {
  margin: 20px 20px 20px 20px;
  border: 1px solid gray;
  box-shadow: 1px;
}
img {
  height: 60px;
  width: 17%;
}
</style>
