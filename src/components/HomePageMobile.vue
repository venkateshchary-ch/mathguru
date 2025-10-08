<template>
  <div class="homePageMobile">
       <div style="background-color: rgb(29, 82, 102);height: 75px;width: 218.6;"><img alt="Institute Header" src="/images/InstHeadName.JPG" class="logo" style="width: unset;
     height: 76px;"/></div>
       <div style="background-color:#f1bf1ff2;height: 50px;" data-v-fab63700=""><img src="/images/InstHeadName3.JPG" alt="Logo" class="logo" style="width:375px;height: 50px;" data-v-fab63700=""><div style="background-color:#f2f2f2;padding-top:20px;" data-v-fab63700=""><nav data-v-fab63700=""><a href="#about" data-v-fab63700="">About</a><a href="#courses" data-v-fab63700="">Courses</a><a href="#contact" data-v-fab63700="">Contact</a></nav></div></div>
      <section id="about" style="
    width: 275px; padding-top: 20px;

">
    <h2 style="width: 250px;">About Us</h2>

    <div class="text-video-row">
      <p class="left-text" style="max-width: 100%;">
        We provide specialized tuition for Mathematics (IIT-JEE Level) for Intermediate 11th & 12th students.  
        Our goal is to guide students towards securing admissions in prestigious institutes like IITs and NITs.  
        Classes are held at our tuition centre (not virtual).  
        Demo lectures are available before enrollment.  
        Fee details can be discussed via contact.      </p>
    
   <div class="video-circle">
        <video autoplay muted loop playsinline>
          <source src="videos/MGInstitute.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
      </div>
    </div>

  </section>

  <section id="courses" style="width: 275px; padding-top: 40px;">
    <h2>Courses Offered</h2>
    <p style="text-align:center;">
      📘 JEE MAINS & ADVANCED<br>
        📗 INTERMEDIATE<br>
      📘CBSE/State IPE / ICSE<br>
        📗 EAPCET / NEET <br>
      <span  style="color:rgb(248, 12, 12);padding-right: 80px;padding-left: 0px;">6,7,8,9 &10 IIT Foundation</span>
            
         📘 MATHS<br>
        📗 PHYSICS<br>
       📘CHEMISTRY<br>
    </p>
  </section>

  <section id="contact" style="width: 275px; padding-top: 40px;">
    <h2>Contact Us</h2>
    <div class="contact-info">
      <address>
       <strong>MATH GURU COACHING CENTER</strong>
       3rd Floor,Plot No:58 MP,Above Medplus Medical Hall,<br>
         Santhoshi Matha Temple Line,Hasthinapuram North,<br>
    Karmanghat,HYD-70.<br>
      <p>📧 Email: <a href="mailto:mathguru.solutions@gmail.com" style="color:#ffdd57;">mathguru.solutions@gmail.com</a></p>
      <p>📞 : <button onclick="window.location.href='tel:+919440586101'"> 9440586101 </button>
        <button onclick="window.location.href='tel:+919032642682'"> 9032642682</button>

      </p>
      </address>
      <!-- <p>📷 Instagram: <a href="https://instagram.com/yourprofile" target="_blank" style="color:#ffdd57;">@yourprofile</a></p>
      <p>💼 LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank" style="color:#ffdd57;">linkedin.com/in/yourprofile</a></p> -->
    </div>
  </section>

    <!-- WhatsApp Support Button -->
  <a href="https://wa.me/9440586101" class="whatsapp-button" target="_blank">💬 Chat on WhatsApp</a>

    <!-- <h1>{{ msg }}</h1> -->
  </div>
</template>

<script>
export default {
  name: 'HomePageMobile',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
 nav {
      margin-top: -22px;
      margin-bottom: 2px;
    }

 
 nav a {
  color: #ff6d57;
  margin-left: 35px;  /* spacing between links */
  text-decoration: none;
  font-weight: bold;
}
    .video-circle video {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.text-video-row {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
  margin: 2rem auto;
  padding: 1rem;
  max-width: 1000px;
  flex-wrap: wrap;
}
  .section {
      padding: 50px 20px;
      background: rgba(0,0,0,0.6);
      margin: 20px;
      border-radius: 10px;
    }

    .section h2 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 20px;
      color: #ffdd57;
    }
      .contact-info {
      text-align: center;
    }

    .contact-info p {
      margin: 10px 0;
      font-size: 1.1rem;
    }
.left-text {
  flex: 1;
  font-size: 1.2rem;
  line-height: 1.6;
  color: #333;
  text-align: left;
  max-width: 60%;
}
 footer {
      background: rgba(0,0,0,0.8);
      text-align: center;
      padding: 15px;
      font-size: 0.9rem;
      margin-top: 20px;
    }

    footer a {
      color: #ffdd57;
      margin: 0 10px;
      text-decoration: none;
    }
    .whatsapp-button {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25d366;
    color: white;
    padding: 15px 20px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
}

</style>
