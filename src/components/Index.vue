<template>
  <div class="body">
    <link rel='stylesheet' href='https://cdn-uicons.flaticon.com/uicons-regular-rounded/css/uicons-regular-rounded.css'>

    <nav class="nav-bar">

      <!-- <img :src="require('@/images/setup.svg')" alt="setup"> -->
      <img src="../images/setup.svg" width="150" height="100">
     

     <div class="mobile-nav">
       <span></span>
       <span></span>
     </div>

     <div class="mobile-nav-content">
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
     <picture>
       <img src="../images/profile-pic.jpg" alt="profile-pic" class="profile-pic">
     </picture>

     <div>
       <h1>Hi!</h1>
       <h2>My name is <strong>KOLAWOLE HENRY OLUWATOBI.</strong></h2>
     </div>
   </div>



     
  

   <h2 id="Intrest" class="section-header">MY INTREST</h2>

   <div class="intrest-container">
     
     <div class="basket-ball">
       <img src="../images/ball-and-ring.jpg" alt="ball-and-ring">
     </div>

     <div class="basketball-content">
       <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
         Incidunt quas suscipit deleniti error ea magni ducimus accusamus quo sint odit nisi placeat quidem dolores blanditiis rem, 
         quisquam distinctio cum illum.
       </p>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
           quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
       </p>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
           quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
       </p>
       <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
           quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
       </p>
     </div>

     <div class="music-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
        Incidunt quas suscipit deleniti error ea magni ducimus accusamus quo sint odit nisi placeat quidem dolores blanditiis rem, 
        quisquam distinctio cum illum.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>
      </div>

      <div>
        <img src="../images/black-headphone.jpg" alt=" Black headphone on cheese barrel ">
      </div>

    
     <div>
        <img src="../images/book.jpg" alt="book-library" class="book-img">
      </div>

       
      <div class="book-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
        Incidunt quas suscipit deleniti error ea magni ducimus accusamus quo sint odit nisi placeat quidem dolores blanditiis rem, 
        quisquam distinctio cum illum.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>

        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Dignissimos, iusto maiores dolorem adipisci ipsam quasi alias doloribus,
        quos sed neque consequuntur, nihil magnam? Sed saepe incidunt ipsa illum optio asperiores.
        </p>
      </div>
      
    
    </div>

     <h2 class="section-header" id="Projects">PROJECTS</h2>

    <div class="projects-container">
     
      <div class="projects">
        <a href="http://www.Haullersonline.com">
          <img src="../images/red-truck.jpg" alt = "red-truck" class="project-img">
        </a>
        <p>Haullersonline is an online haulage platform that provides <br>haulage services to businesses and individuals.</p>
      </div>

      <div class="projects">
        <a href="http://www.Alonacanada.com">
          <img src="../images/spices.jpg" alt="spices" class="project-img">
        </a>
        <p>Alonacanada makes from roots of the ginseg plant to maintain <br> good health in the most natural way.</p>
      </div>

      <div class="projects">
        <a href="http://www.Diamondbeautyng.com">
          <img src="../images/beauty.jpg" alt ="beauty" class="project-img">
        </a>
        <p>Diamondbeautyng is your one stop shop for your beuty needs.</p>
      </div>
    
    </div>

    <div class="contact footer" id="Contact-Me">
      <div class="email">
        <h3>henrykay53@gmail.com</h3>
        <a href="mailto:henrykay53@gmail.com"><button class="email-btn">Email Henry</button></a>
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



.nav-bar {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}

.desktop-links{
  text-decoration: none;
  font-size: 1.5rem;
  color: grey;
  /* margin-left: 20px; */
  padding-left: 50px;
}

.desktop-links::before {
  content: "";
  position: absolute;
  height: 5px;
  width: 5%;
  top: 70px;
  background: blue;
  transition: 400ms ease-in-out;
  opacity: 0;
}

.desktop-links:hover::before {
  opacity: 1;
}



.intro {
  display: grid;
  grid-template-columns: auto auto;
}

.profile-pic {
  border: 4px solid blue;
  border-radius: 10px;
  padding: 4px 4px;
}

:hover.profile-pic {
  border: 4px solid yellow;

}

.mobile-nav-content {
  display: none;
}

/* intrest gird-display */
.intrest-container {
  display: inline-grid;
  grid-template-columns: auto auto;
}

.section-header{
  text-align: center;
}

.projects-container {
  display: flex;
  justify-content: space-between;
  margin: 90px 40px;
}

.project-img {
  border: 4px solid white;
  border-radius: 6px;
}
:hover.project-img {
  border: 4px solid #008ccf;
}

.footer {
  height: 10vh;
  background-color: #008ccf;
  padding-top: 20px;
}
.email {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
h1 {
  margin: 40px 0 0;
  font-size: var(--fs-small);
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}



</style>
