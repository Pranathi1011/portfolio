# portfolio
   @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Ubuntu:wght@400;500;700&display=swap');
   *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  scroll-behavior: smooth;
}

/* Custom Scroll Bar CSS */
::-webkit-scrollbar {
    width: 10px;
}
::-webkit-scrollbar-track {
    background: #f1f1f1;
}
::-webkit-scrollbar-thumb {
    background: #6e93f7;
    border-radius: 12px;
    transition: all 0.3s ease;
}

::-webkit-scrollbar-thumb:hover {
    background: #4070f4;
}
/* navbar styling */
nav{
  position: fixed;
  width: 100%;
  padding: 20px 0;
  z-index: 998;
  transition: all 0.3s ease;
  font-family: 'Ubuntu', sans-serif;
}
nav.sticky{
  background: #4070f4;
  padding: 13px 0;
}
nav .navbar{
  width: 90%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: auto;
}
nav .navbar .logo a{
  font-weight: 500;
  font-size: 35px;
  color: #4070f4;
}
nav.sticky .navbar .logo a{
  color: #fff;
}
nav .navbar .menu{
  display: flex;
  position: relative;
}
nav .navbar .menu li{
  list-style: none;
  margin: 0 8px;
}
.navbar .menu a{
  font-size: 18px;
  font-weight: 500;
  color: #0E2431;
  padding: 6px 0;
  transition: all 0.4s ease;
}
.navbar .menu a:hover{
  color: #4070f4;
}
nav.sticky .menu a{
  color: #FFF;
}
nav.sticky .menu a:hover{
  color: #0E2431;
}
.navbar .media-icons a{
  color: #4070f4;
  font-size: 18px;
  margin: 0 6px;
}
nav.sticky .media-icons a{
  color: #FFF;
}

/* Side Navigation Menu Button CSS */
nav .menu-btn,
.navbar .menu .cancel-btn{
  position: absolute;
  color: #fff;
  right: 30px;
  top: 20px;
  font-size: 20px;
  cursor: pointer;
  transition: all 0.3s ease;
  display: none;
}
nav .menu-btn{
  color: #4070f4;
}
nav.sticky .menu-btn{
  color: #FFF;
}
.navbar .menu .menu-btn{
  color: #fff;
}

/* home section styling */
.home{
  height: 100vh;
  width: 100%;
  background: url("images/background.png") no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  font-family: 'Ubuntu', sans-serif;
}
.home .home-content{
  width: 90%;
  height: 100%;
  margin: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.home .text-one{
  font-size: 25px;
  color: #0E2431;
}
.home .text-two{
  color: #0E2431;
  font-size: 75px;
  font-weight: 600;
  margin-left: -3px;
}
.home .text-three{
  font-size: 40px;
  margin: 5px 0;
  color: #4070f4;
}
.home .text-four{
  font-size: 23px;
  margin: 5px 0;
  color: #0E2431;
}
.home .button{
  margin: 14px 0;
}
.home .button button{
  outline: none;
  padding: 8px 16px;
  border-radius: 6px;
  font-size: 25px;
  font-weight: 400;
  background: #4070f4;
  color: #fff;
  cursor: pointer;
  border: 2px solid transparent;
  transition: all 0.4s ease;
}
.home .button button:hover{
  border-color: #4070f4;
  background-color: #fff;
  color: #4070f4;
}

section {
    padding-top: 30px;
    margin-top: 0; /* changed from 10px to 0 */
  }
  
  section .content {
    width: 90%;
    margin: 20px auto;
    font-family: 'Poppins', sans-serif;
    padding-top: 0; /* added this line */
  }
  
  .about .about-details {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  section .title {
    display: flex;
    justify-content: center;
    margin-top: 20px; /* changed from 50px to 20px */
    padding-bottom: 10px; /* added this line */
  }
  
  section .title span {
    color: #0E2431;
    font-size: 30px;
    font-weight: 600;
    position: relative;
    padding-bottom: 6px;
  }
  
  section .title span::before,
  section .title span::after {
    content: '';
    position: absolute;
    height: 3px;
    width: 100%;
    background: #4070f4;
    left: 0;
    bottom: 0;
  }
  
  section .title span::after {
    bottom: -7px;
    width: 70%;
    left: 50%;
    transform: translateX(-50%);
  }
  
  .about .about-details .left {
    width: 45%;
  }
  
  .about .left img {
    height: 400px;
    width: 300px;
    object-fit: cover;
    border-radius: 12px;
  }
  
  .about-details .right {
    width: 55%; /* changed from 75% to 55% */
  }
  
  section .topic {
    color: #0E2431;
    font-size: 25px;
    font-weight: 700;
    margin-bottom: 10px;
  }
  
  .about-details .right p {
    text-align: justify;
    color: #0E2431;
  }
  
  section .button {
    margin: 16px 0;
  }
  
  section .button button {
    outline: none;
    padding: 8px 16px;
    border-radius: 4px;
    font-size: 25px;
    font-weight: 400;
    background: #4070f4;
    color: #fff;
    border: 2px solid transparent;
    cursor: pointer;
    transition: all 0.4s ease;
  }
  
  section .button button:hover {
    border-color: #4070f4;
    background-color: #fff;
    color: #4070f4;
  }
  
  

 /* My Skills CSS */
 .skills{
   background: #F0F8FF;
 }
 .skills .content{
   padding: 20px 30px;
 }
 .skills .skills-details{
   display:flex;
   justify-content: space-round;
   align-items: left;
 }
 .skills-details .text{
   width: 90%;
 }
 .skills-details p{
   color: #0E2431;
   text-align: justify;
 }
.skills .skills-details .experience{
  display: flex;
  align-items:center;
  margin: 0 30px;
}
.skills-details .experience .num{
  color: #0E2431;
  font-size: 80px;
}
.skills-details .experience .exp{
  color: #0E2431;
  margin-left: 20px;
  font-size: 18px;
  font-weight: 500;
  margin: 0 6px;
}
.skills-details .boxes{
  width: 35%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.skills-details .box{
  width: calc(100% / 2 - 10px);
  margin: 20px 0;
}
.skills-details .boxes .topic{
  font-size: 20px;
  color: #4070f4;
}
.skills-details .boxes .per{
  font-size: 60px;
  color: #4070f4;
}

/* My Services CSS */
.services .boxes{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.services .boxes .box{
  margin: 20px 0;
  width: calc(100% / 3 - 20px);
  text-align: center;
  border-radius: 12px;
  padding: 20px 10px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.12);
  cursor: default;
  transition: all 0.4s ease;
}
.services .boxes .box:hover{
  background: #4070f4;
  color: #fff;
}
.services .boxes .box .icon{
  height: 50px;
  width: 50px;
  background: #4070f4;
  border-radius: 50%;
  text-align: center;
  line-height: 50px;
  font-size: 18px;
  color: #fff;
  margin: 0 auto 10px auto;
  transition: all 0.4s ease;
}
.boxes .box:hover .icon{
  background-color: #fff;
  color: #4070f4;
}
.services .boxes .box:hover .topic,
.services .boxes .box:hover p{
  color: #0E2431;
  transition: all 0.4s ease;
}
.services .boxes .box:hover .topic,
.services .boxes .box:hover p{
  color: #fff;
}
/* Contact Me CSS */
.contact{
  background: #F0F8FF;
}
.contact .content{
  margin: 0 auto;
  padding: 30px 0;
}
.contact .text{
  width: 80%;
  text-align: center;
  margin: auto;
}

/* Footer CSS */
footer{
  background: #4070f4;
  padding: 15px 0;
  text-align: center;
  font-family: 'Poppins', sans-serif;
}
footer .text span{
  font-size: 17px;
  font-weight: 400;
  color: #fff;
}
footer .text span a{
  font-weight: 500;
  color: #FFF;
}
footer .text span a:hover{
  text-decoration: underline;
}
/* Scroll TO Top Button CSS */
.scroll-button a{
  position: fixed;
  bottom: 20px;
  right: 20px;
  color: #fff;
  background: #4070f4;
  padding: 7px 12px;;
  font-size: 18px;
  border-radius: 6px;
  box-shadow: rgba(0, 0, 0, 0.15);
  display: none;
}

/* Responsive Media Query */
@media (max-width: 1190px) {
  section .content{
    width: 85%;
  }
}
@media (max-width: 1000px) {
  .about .about-details{
    justify-content: center;
    flex-direction: column;
  }
  .about .about-details .left{
    display: flex;
    justify-content: center;
    width: 100%;
  }
  .about-details .right{
    width: 90%;
    margin: 40px 0;
  }
  .services .boxes .box{
    margin: 20px 0;
    width: calc(100% / 2 - 20px);
  }
}
@media (max-width: 900px) {
  .about .left img{
    height: 350px;
    width: 350px;
  }
}

@media (max-width: 750px) {
  nav .navbar{
    width: 90%;
  }
  nav .navbar .menu{
    position: fixed;
    left: -100%;
    top: 0;
    background: #0E2431;
    height: 100vh;
    max-width: 400px;
    width: 100%;
    padding-top: 60px;
    flex-direction: column;
    align-items: center;
    transition: all 0.5s ease;
  }
  .navbar.active .menu{
    left: 0;
  }
  nav .navbar .menu a{
    font-size: 23px;
    display: block;
    color: #fff;
    margin: 10px 0;
  }
  nav.sticky .menu a:hover{
    color: #4070f4;
  }
  nav .navbar .media-icons{
    display: none;
  }
  nav .menu-btn,
  .navbar .menu .cancel-btn{
    display: block;
  }
  .home .text-two{
    font-size: 65px;
  }
  .home .text-three{
    font-size: 35px;
  }
  .skills .skills-details{
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .skills-details .text{
    width: 100%;
    margin-bottom: 50px;
  }
  .skills-details .boxes{
    justify-content: center;
    align-items: center;
    width: 100%;
  }
  .services .boxes .box{
    margin: 20px 0;
    width: 100%;
  }
  .contact .text{
    width: 100%;
}
}

@media (max-width: 500px){
  .home .text-two{
    font-size: 55px;
  }
  .home .text-three{
    font-size: 33px;
  }
  .skills-details .boxes .per{
    font-size: 50px;
    color: #4070f4;
  }
}
<!DOCTYPE html>
<!-- Website - www.codingnepalweb.com -->
<html lang="en" dir="ltr">
  <head>
    <meta charset="UTF-8" />
    <title>portfolio</title>
    <link rel="stylesheet" href="portfolio/folio.css" />
    <!-- Fontawesome CDN Link -->
    <link rel="stylesheet" href="portfolio/folio.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
    <!-- Move to up button -->
    <div class="scroll-button">
      <a href="#home"><i class="fas fa-arrow-up"></i></a>
    </div>
    <!-- navgaition menu -->
    <nav>
      <div class="navbar">
        <div class="logo"><a href="#">Portfolio.</a></div>
        <ul class="menu">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#my skills">Services</a></li>
          <li><a href="#contact">Contact</a></li>
          <div class="cancel-btn">
            <i class="fas fa-times"></i>
          </div>
        </ul>
      </div>
      <div class="menu-btn">
        <i class="fas fa-bars"></i>
      </div>
    </nav>

    <!-- Home Section Start -->
    
<section class="home" id="home">
      <div class="home-content">
        <div class="text">
          <div class="text-one">Hello,</div>
          <div class="text-two">I'm y.pranathi sai</div>
          <div class="text-four">B.Tech Computer Science Student</div>
        </div>
        <div class="button"></div>
      </div>
    </section>

    <!-- About Section Start -->
   <section class="about" id="about">
      <div class="content">
        <div class="title"><span>About Me</span></div>
        <div class="about-details">
          <div class="left">
            <img src="prana.jpg" alt="my image " />
          </div>
          <div class="right">
            
   <p>
              I am a btech computer science student who is Aspiring Software Engineer with a strong background in Computer Science and Engineering, specializing in Artificial
              Intelligence and Machine Learning. with good coding skills in multiple programming languages. Passionate to build innovative
              projects in a collaborative environment.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- My Skill Section Start -->
    <!-- Section Tag and Other Div will same where we need to put same CSS -->
<section class="skills" id="skills">
       <div class="content">
        <div class="title"><span>My Skills</span></div>
        <div class="skills-details">
          <div class="text">
            <div class="topic">Skills Reflects Our Knowledge</div>
            <p>Working as a virtual barath intern 
              I had a great time being a member of the team barath internship. 
              It was a fantastic experience, and I was able to improve 
              my skills while learning a few new ones. Thanks for giving 
              me an opportunity to work as a role of "web Developer.
              . I have gained new experiences working with them.</p>
            
   <div class="boxes">
            <div class="box">
              <div class="topic">HTML</div>
             
   </div>
            <div class="box">
              <div class="topic">CSS</div>
              
  </div>
            <div class="box">
              <div class="topic">JavScript</div>
             
  </div>
            <div class="box">
              <div class="topic">python</div>
             
   </div>
          </div>
        </div>
      </div>
    </section>

   <!-- My Services Section Start -->
<section class="services" id="services">
    <div class="content">
      <div class="title"><span>My Skills</span></div>
      <div class="boxes">
        <div class="box">
          <div class="icon">
            <i class="fas fa-desktop"></i>
          </div>
          <div class="topic">Web Development</div>
          <p>I am good at making front-end projects.</p>
        </div>
        <div class="box">
          <div class="icon">
            <i class="fas fa-paint-brush"></i>
          </div>
          <div class="topic">Python</div>
          <p>I have a vast knowledge of Python.</p>
        </div>
        <div class="box">
          <div class="icon">
            <i class="fas fa-chart-line"></i>
          </div>
          <div class="topic">Data Structure</div>
          <p>I also have a good knowledge of data structures and algorithms.</p>
        </div>
        <div class="box">
          <div class="icon">
            <i class="fas fa-camera-retro"></i>
          </div>
          <div class="topic">Machine Learning</div>
          <p>I have a great knowledge of machine learning.</p>
        </div>
        <div class="box">
          <div class="icon">
            <i class="fas fa-tablet-alt"></i>
          </div>
          <div class="topic">DBMS</div>
          <p>I have knowledge of SQL, MongoDB as databases.</p>
        </div>
      </div>
    </div>
  </section>
  
  
  <!-- Contact Me section Start -->
  <section class="contact" id="contact">
      <div class="content">
        <div class="title"><span>Contact Me</span></div>
        <div class="text">
          <div class="topic">Email - </div>
          <p>pranathisaiyadav@gmail.com</p>
          <br>
        </div>
      </div>
    </section>

    <!-- Footer Section Start -->
   <footer>
      <div class="text">
        <span>Created By pranathisai; 2024 All Rights Reserved</span>
      </div>
    </footer>

   <script src="script.js"></script>
  </body>
</html>
