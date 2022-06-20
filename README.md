# nramirezcv
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Nancy Ramirez</title>
    <link rel="stylesheet" href="CSS/styles.css">
    <link rel="icon" href="favicon.ico">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Merriweather&family=Montserrat&family=Sacramento&display=swap" rel="stylesheet">
  </head>
  <body>
    <div class="top-container">
      <img class="top-cloud"src="images/cloud.png" alt="cloud-img">
      <h1>Im Nancy.</h1>
      <h2>a <span class="pro">pro</span>grammer.</h2>
      <img class="buttom-cloud"src="images/cloud.png" alt="cloud-img">
      <img src="images/mountain.png" alt="mountain-img">

    </div>
    <div class="middle-container">
  <div class="profile">
    <img src="images/circle-me.png" alt="circle-me" width="200" height="200">

    <h2>Hello.</h2>
    <p class="intro">I am a Computer Systems Engineering student. I like to constantly learn new things,
 currently I am very passionate about learning new languages.</p>
  </div>
  <hr>
  <div class="skills">
    <h2>My Skills.</h2>
    <div class="skill-row">
      <img class="code-image-circle" src="images/code-image-circle.png" alt="code-image-circle" width="200"height="200">
      <h3>Development</h3>
      <p>I started learning HTML, CSS, JAVA SCRIPT and I will continue learning full stack web developer. I also have knowledge in Bootstrap, GitHub, C #, SQL and JAVA.</p>
    </div>
    <div class="skill-row">
      <img class="programadora-img" src="images/programadora.png" width="200" height="200" alt="programadora-img">
      <h3>My Goal</h3>
      <p>I am very excited to work in a very important company, and use my knowledge and be able to continue learning more</p>
    </div>
  </div>
  <hr>
  <div class="contact-me">
    <h2>Get In Touch</h2>
    <h3>If you want to hire someone with a great desire to learn and grow like me.</h3>
    <p class="contact-message">Thanks for looking at my CV.</p>
    <a class="btn" href="mailto:nan.onlyme@gmail.com">CONTACT ME</a>
  </div>
</div>


<div class="bottom-container">
  <a class="footer-link" href="https://www.linkedin.com/in/nancy-ram%C3%ADrez-067900218">LinkedIn</a>
  <a class="footer-link" href="https://twitter.com/">Twitter</a>
  <a class="footer-link" href="">Website</a>
  <p class="copyright">©2022 Nancy Ramirez.</p>
</div>





  </body>
</html>
body {
  color: #40514E;
  margin: 0;
  text-align: center;
  font-family: 'Merriweather', serif;
}

h1 {
  font-size: 5.635rem;
  margin-top: 50px auto 0 auto;
  font-family: 'Sacramento', cursive;
  color: #66BFBF;
  line-height: 2;
}

h2 {
  font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  font-weight: normal;
  color: #66BFBF;
  padding-bottom: 10px;
}

h3 {
  font-family: 'Montserrat', sans-serif;
  color: #11999E;
  margin: 100px;
}

p {
  margin-top: 50px auto 0 auto;
  line-height: 2;
  margin-bottom: 60px;
}

hr {
  border: dotted #EAF6F6 6px;
  border-bottom: none;
  width: 4%;
  margin: 100px auto;
}
a{
color:  #11999E;
font-family: 'Montserrat', sans-serif;
margin: 10px 20px;
text-decoration: none;
}
a:hover{
  color: #EAF6F6;
}

.top-container {
  background-color: #EAF6F6;
  position: relative;
  padding-top: 100px;
}

.middle-container {
  margin: 100px 0;
}

.bottom-container {
  background-color: #66BFBF;
  padding: 50px 0 20px;
}

.skills {
  margin: 100px auto;
}

.skill-row {
  width: 50%;
  margin:100px auto;
  text-align: left;
}

.pro {
  text-decoration: underline;
}

.intro {
  width: 30%;
  margin: auto;
}
.contact-message{
  width: 40%;
  margin: 40px auto 60px;
}

.contact-me {
  width: 40%;
  margin: 40px auto 60px;
}
.copyright{

  color: #EAF6F6;
  font-size:0.75rem;
  padding: 20px 0px;
}

.top-cloud {
  position: absolute;
  right: 300px;
  top: 40px;
}

.buttom-cloud {
  position: absolute;
  left: 250px;
  bottom: 300px;
}

.code-image-circle {
  width: 25%;
  float: left;
  margin-right: 30px;
}

.programadora-img {
  width: 25%;
  float: right;
  margin-left: 30px;
}
.btn {
  background: #11CDD4;
  background-image: -webkit-linear-gradient(top, #11CDD4, #11999e);
  background-image: -moz-linear-gradient(top, #11CDD4, #11999e);
  background-image: -ms-linear-gradient(top, #11CDD4, #11999e);
  background-image: -o-linear-gradient(top, #11CDD4, #11999e);
  background-image: linear-gradient(to bottom, #11CDD4, #11999e);
  -webkit-border-radius: 8;
  -moz-border-radius: 8;
  border-radius: 8px;
  font-family: 'Montserrat', sans-serif;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}

.btn:hover {
  background: #30e3cb;
  background-image: -webkit-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -moz-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -ms-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -o-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: linear-gradient(to bottom, #30e3cb, #2bc4ad);
  text-decoration: none;
}
