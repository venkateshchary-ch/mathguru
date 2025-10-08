<template>
  <div class="home">
       <div style="background-color: #1d5266;padding: -8px;"><img alt="Institute Header" src="/images/InstHeadName.JPG" class="logo" style="width: unset;
     height: 75px;"></div>
       <div style="background-color:#f1bf1ff2;height:32px;"><img src="/images/InstHeadName3.JPG" alt="Logo" class="logo" style="
    width: unset;
    height: 32px;
    ">
     <nav>
        <a href="#about">About</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
    <section id="about" style="margin-top: 40px;">
    <h2>About Us</h2>

    <div class="text-video-row">
      <p class="left-text">
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

  <section id="courses">
    <h2>Courses Offered</h2>
    <p style="text-align:center;">
      📘 JEE MAINS & ADVANCED<br>
      📗 INTERMEDIATE<br>
     📘CBSE/State IPE / ICSE<br>
       📗 EAPCET / NEET <br>
      <strong  style="color: rgb(248, 12, 12); font-size: 20px;">6,7,8,9 &10 IIT Foundation</strong>
       📘 MATHS<br>
      📗 PHYSICS<br>
     📘CHEMISTRY</p>
  </section>

  <section id="contact">
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

  <footer>
    <p>&copy; Math Guru. All Rights Reserved.</p>
  </footer>

    <!-- <h1>{{ msg }}</h1> -->
  </div>
</template>

<script>
export default {
  name: 'HomePage',
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
      margin-top: 10px;
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
