# Personal-Portfolio-



<!DOCTYPE html>
<html>
  <head>
  <title> Personal Portfolio </title>
  <style>
    body {
      background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS3hUuxWzv8NKM7pd1Y3Ao-4_qpWEIzpW__NZF3weM_CPi4Pb95&usqp=CAU);
  background-size: cover;
     
      background-repeat: no-repeat;
      background-position: center;
    }
    #welcome-section {
     text-align: center; 
      height: 100vh;
     line-height: 1.5;
      position: relative;
     top: 80px;
      font-size: 3em;
      color: red;
    }
    #projects {
      
    }
    #projects a {
      text-decoration: none;
      color: red;
      line-height: 1.5;
      font-size: 2em;
    }
    .project-tile, h2 {
      font-size: 2.5em;
      color: white;
    }
    #navbar {
    position: fixed;
      top: 0;
      width: 100%;
      background: black;
      overflow: hidden;
      padding: 10px;
    }
    #navbar a{
      float: right;
      display: block;
      text-decoration: none;
      text-align: center;
      color: red;
    }
    #navbar ul {
      list-style: none;
      display: inline;
      text-align: right;
    }
    #navbar li {
      display: inline;
      list-style: none;
    }
    #navbar li a {
      height: 50px;
      width: 6em;
      text-decoration: none;
      font-size: 2em;
      text-align: center;
    }
    #profile-link {
      text-decoration: none;
      color: red;
      font-size: 2em;
    }
    @media only screen and (max-width: 600px) {
      body {
        background-color: lightblue;
      }
    }
    img {
      border-radius: 100%;
      position: relative;
      top: 70px;
      border: solid;
      border-color: white;
    }
    </style>
  </head>
  <body>
    <div>
      <nav id="navbar">
        <ul>
          <li>  <a href="#welcome-section"> About </a> </li>
      <li>    <a href="#profile-link"> Contact </a> </li>
     <li>   <a href="#projects"> Projects </a> </li>
        </ul>
      </nav>
    </div>
    <section id="welcome-section">
      <div>
        <img src="https://media-exp1.licdn.com/dms/image/C5603AQFmzMPjQBKRTw/profile-displayphoto-shrink_200_200/0?e=1594252800&v=beta&t=t7R6agXkiTtfDj_T4t5hhsEN6xIcLMadrqgfj7te9e8" alt="my  photo">
      <h1> I AM <br>
        VICTOR DENISE IDONGESIT <p> Web Developer </p> </h1>
      </div>
    </section>
    
    <section id="projects">
      <h2 class="project-tile"> Projects:  </h2>
  <ul> 
    <li>      <a href="https://codepen.io/pen?template=NWGJYQQ"> A Tribute Page  </a> </li>
    <li> <a href="https://codepen.io/Thegirlnextdoordee/pen/ZEbZxdG"> A Survey Form </a> </li>
    <li> <a href="https://codepen.io/Thegirlnextdoordee/pen/VwvJJMY"> A Product Landing Page </a> </li>
    <li> <a href="https://codepen.io/Thegirlnextdoordee/pen/WNreWRM"> A Technical Documentation Page </a> </li>
      </ul>
    </section>
    
      <div>
        <h2> A  link to my work portfolio </h2>
        <a id="profile-link" href="https://www.freecodecamp.org/fcc8db51f70-80e3-404e-8ce8-b76717439291" target="_blank"> Freecodecamp </a>
    </div>
  
    
    
    
    
    
    
    
    
    
    
    
    
    
  </body>
  <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"> </script>
</html>
 
