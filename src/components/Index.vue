<template>
  <div class="body">
    <link rel='stylesheet' href='https://cdn-uicons.flaticon.com/uicons-regular-rounded/css/uicons-regular-rounded.css'>

    <nav class="nav-bar">

      <!-- <img :src="require('@/images/setup.svg')" alt="setup"> -->
     <img src="../images/setup.svg" width="300" height="100">

     <div class="mobile-nav">
       <span></span>
       <span></span>
     </div>

     <div class="mobile-nav-content">
       <ul>
          <li>Home</li>
          <li>Intrest</li>
          <li>Portfolio</li>
          <li>Contact Me</li>
        </ul>
     </div>


     <div class="desktop-nav">
       <ul>
          <li>Home</li>
          <li>Intrest</li>
          <li>Portfolio</li>
          <li>Contact Me</li>
        </ul>
     </div>
    </nav>

     
   

   <div class="intro">
     <picture>
       <img src="../images/profile-pic.jpg" alt="profile-pic" class="profile-pic">
     </picture>

     <h1>Hi!</h1>
     <h2>My name is <strong>KOLAWOLE HENRY OLUWATOBI.</strong></h2>
   </div>

   <div class="intrest-container">
     <h2>MY INTREST</h2>
     <div class="basket-ball">
       <img src="../images/ball-and-ring.jpg" alt="ball-and-ring">
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

     <div class="music-container">
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
       <img src="../images/black-headphone.jpg" alt="headphone">
     </div>

     <div class="books-container">
       <img src="../images/book.jpg" alt="headphone">
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

    <div class="projects">
      <h2>PROJECTS</h2>

      <div>
        <a href="http://www.Haullersonline.com">
          <img src="../images/red-truck.jpg" alt = "red-truck">
        </a>
        <p>Haullersonline is an online haulage platform that provides haulage services to businesses and individuals.</p>
      </div>

      <div>
        <a href="http://www.Alonacanada.com">
          <img src="../images/spices.jpg" alt="spices">
        </a>
        <p>Alonacanada makes from roots of the ginseg plant to maintain good health in the most natural way.</p>
      </div>

      <div>
        <a href="http://www.Diamondbeautyng.com">
          <img src="../images/beauty.jpg">
        </a>
        <p>Diamondbeautyng is your one stop shop for your beuty needs.</p>
      </div>
    
    </div>

    <div class="contact footer">
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
  /* box-sizing: border-box; */
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

a {
  color: #42b983;
}

</style>
