<template>
  <div class="body">
    <link rel='stylesheet' href='https://cdn-uicons.flaticon.com/uicons-regular-rounded/css/uicons-regular-rounded.css'>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500&family=Open+Sans:wght@300&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Laila:wght@300;400&display=swap" rel="stylesheet">

    <nav class="nav-bar">

      <!-- <img :src="require('@/images/setup.svg')" alt="setup"> -->
      <img src="../images/setup.svg" width="150" height="100">
     

     <div class="hamburger-menu">
       <span></span>
       <span></span>
     </div>

     <div class="hamburger-content">
       <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Intrest</a></li>
          <li><a href="#">Portfolio</a></li>
          <li><a href="#">Contact Me</a>Contact Me</li>
        </ul>
     </div>


     <div class="desktop-nav">
       <ul>
          <li><a href="#" class="desktop-links">Home</a></li>
          <li><a href="#Intrest" class="desktop-links">Intrest</a></li>
          <li><a href="#Projects" class="desktop-links">Projects</a></li>
          <li><a href="#Contact-Me" class="desktop-links">Contact Me</a></li>
        </ul>
     </div>
    </nav>


   <div class="intro">
    
     <div>
       <h1 class="greeter">Hi!</h1> <h2>I KOLAWOLE HENRY OLUWATOBI.</h2>
       <p>I am passionate about expressing my thoughts and ideas,<br>
       and I have found a way of doing so through design and codes.</p>
       <p> I create functional but asethetic websites that not only satisfy<br>
       your needs, but also appeals to the soul.</p>
       <p>Stick with me as I take you through my intrest and completed projects.</p>
     </div>

     <picture>
       <img src="../images/profile-pic.jpg" alt="profile-pic" class="profile-pic">
     </picture>

   </div>



     
  

   <h2 id="Intrest" class="section-header">MY INTREST</h2>

   <div class="intrest-container">
     <div class="basketball">
       <img src="../images/ball-and-ring.jpg" alt="ball-and-ring" class="intrest-img">
     </div>

     <div class="basketball-content">
       <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
         Incidunt quas suscipit deleniti error ea magni ducimus<br> accusamus quo sint odit nisi placeat quidem dolores blanditiis rem, 
         quisquam distinctio cum illum.
       </p>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Dignissimos, iusto maiores dolorem adipisci <br>ipsam quasi alias doloribus,
           quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
       </p>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Dignissimos, iusto maiores dolorem adipisci <br>ipsam quasi alias doloribus,
           quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
       </p>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Dignissimos, iusto maiores dolorem adipisci <br>ipsam quasi alias doloribus,
           quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
       </p>
     </div>

     <div class="music-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
        Incidunt quas suscipit deleniti error ea magni ducimus<br> 
        accusamus quo sint odit nisi placeat quidem dolores blanditiis rem, 
        quisquam distinctio cum illum.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci <br>ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci <br><br>ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>
      </div>

      <div>
        <img src="../images/black-headphone.jpg" alt=" Black headphone on cheese barrel" class="intrest-img">
      </div>

    
     <div>
        <img src="../images/book.jpg" alt="book-library" class="intrest-img">
      </div>

       
      <div class="book-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
        Incidunt quas suscipit deleniti error ea magni ducimus <br>
        accusamus quo sint odit nisi placeat quidem dolores blanditiis rem, 
        quisquam distinctio cum illum.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci <br>ipsam quasi alias doloribus,
        quos sed neque consequuntur, <br>nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci <br>
        ipsam quasi alias doloribus,
        quos sed neque consequuntur, <br>nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam <br>
        quasi alias doloribus,
        quos sed neque consequuntur,<br> nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>
      </div>
      
    
    </div>

    <h2 class="section-header" id="Projects">PROJECTS</h2>

    <div class="projects-container">
     
      <div class="projects">
        <a href="http://www.Haullersonline.com">
          <img src="../images/red-truck.jpg" alt = "red-truck" class="project-img">
        </a>
        <p>Haullersonline is an online haulage platform that <br> provides haulage services to businesses and individuals.</p>
      </div>

      <div class="projects">
        <a href="http://www.Alonacanada.com">
          <img src="../images/spices.jpg" alt="spices" class="project-img">
        </a>
        <p>Alonacanada makes from roots of the ginseg plant to <br> maintain good health in the most natural way.</p>
      </div>

      <div class="projects">
        <a href="http://www.Diamondbeautyng.com">
          <img src="../images/beauty.jpg" alt ="beauty" class="project-img">
        </a>
        <p>Diamondbeautyng is your one stop shop for your beuty <br> needs.</p>
      </div>
    
    </div>

    <h2 class="section-header" id="Contact-Me">CONTACT ME</h2>
    <div class="contact footer">
      <div class="email">
        <h3>henrykay53@gmail.com</h3>
        <a href="mailto:henrykay53@gmail.com"><div class="email-btn">Email Henry</div></a>
      </div>
    </div>

  </div>
  
</template>

<script>
export default {
  name: 'Index'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

/* All media queries */
@media(max-width: 786px) {
  .desktop-nav {
    display: none !important;
  }
}

@media(max-width: 786px) {
  .hamburger-menu {
    margin-left: 250px;
  }
}
@media(min-width: 787px) {
  .hamburger-menu {
    display: none;
  }
}

@media(max-width: 787px) {
  .intro {
    display: block !important;
    padding: 30px 30px;
  }


}


@media(max-width: 600px) {
  .intrest-container {
    display: block !important;
  }
}

@media(max-width: 600px) {
  .basketball-content, .book-content, .music-content {
    background-color: gold;
    display: block;
  }
}

@media(max-width: 800px) {
  .projects-container {
    display: block !important;
  }
}



.nav-bar {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  /* background-color: #008ccf; */
  width: 100%;
}

.nav-bar {
  position: fixed;
  top: 0;
  left: 0;
  height: 9vh;
  margin-top: 50px;
}

/* Hamburger menu */
span {
  display: block;
  width: 30px;
  height: 2px;
  background-color: black;
 
}

/* Give a margin of 4px to the element that is not last */
span:not(:last-child) {
  margin-bottom: 4px;
}

span:first-child {
  transform: rotate(45deg);
  /* Align the first child along it's Y and X axis */
  /* 8px for upward and downward movement 4px for left and right movement */
  transform-origin: 8px 4px;
}

span:last-child {
  /* When an element is rotated at a negative(-) degree
  it is inclined to the left and vice versa */
  transform: rotate(-45deg);
}


.desktop-links{
  text-decoration: none;
  font-size: 1.3rem;
  color: black;
  padding-left: 50px;
}

/* Simple animation style for when nav links are hovered */
.desktop-links::before {
  content: "";
  position: absolute;
  height: 5px;
  width: 5%;
  top: 65px;
  background: rgb(9, 9, 175);
  transition: 400ms ease-in-out;
  opacity: 0;
}

/* Opacity makes the animatiion visible when the links are hovered on */
.desktop-links:hover::before {
  opacity: 1;
}

/* Hero image and text */
.intro {
  display: flex;
  /* flex-direction: row-reverse; */
  justify-content: space-evenly;
}

.intro {
  margin: 150px 0;
}

.greeter::first-letter {
  font-size: 60px;
}

.profile-pic {
  width: 100%;
  height: 100%;
  margin-right: -20px;
  border: 4px solid blue;
  border-radius: 10px;
  padding: 4px 4px;
}

:hover.profile-pic {
  border: 4px solid yellow;

}

.hamburger-content {
  display: none;
}


.intrest-container {
  display: grid;
  grid-template-columns: auto auto;
  grid-row-gap: 90px;
  grid-column-gap: 120px;
}

.intrest-container {
  margin: 0 115px;
}

.intrest-img {
  width: 100%;
  box-shadow: 8px 0px 8px rgb(166, 166, 166);
}


/* All h2 element have their text centered */
.section-header{
  text-align: center;
}

/* Project section  */
.projects-container {
  display: flex;
  justify-content: space-evenly;
  margin: 90px 40px;
}

.project-img {
  width: 100%;
  border: 4px solid white;
  border-radius: 6px;
  /* box-shadow: 2px 2px 2px rgba(124, 154, 112); */
}

:hover.project-img {
  border: 4px solid #008ccf;
}

.footer {
  height: 10vh;
  /* background-color: #008ccf; */
  padding-top: 20px;
}

.email {
  display: flex;
  align-items: center;
  justify-content: center;
  color: rgb(77, 77, 77);
  font-size: 1.2rem;
}

.email-btn {
  border-radius: 8px;
  padding: 10px 10px;
  background-color: #008ccf;
  color: black;
  margin-left: 40px;
}

a {
  text-decoration: none;
}

p {
  color: rgb(77, 77, 77);
  font-size: 1.2rem;
  line-height: 2;
}

/* Testing multiple font families */
p {
  /* font-family: 'Dancing Script', cursive; */
  /* font-family: 'Open Sans', sans-serif; */
  font-family: 'Laila', sans-serif;
}


li {
  display: inline-block;
  margin: 0 10px;
}



</style>
