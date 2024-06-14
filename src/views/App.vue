<template>
  <header class="header">
    <a href="#home" class="logo">Caw <span>Wa!</span></a>
    <input type="checkbox" id="menu-toggle" />
    <label for="menu-toggle" id="menu-icon"> <i class="bx bx-menu"></i></label>

    <nav class="navbar">
      <a href="#home" class="active">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#project">Project</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="home">
    <div class="home-content">
      <h1>Hi, I'm <span>Salwa</span></h1>
      <h3 class="text-animation">I'm a <span> </span></h3>
      <p>
        I am a student who is interested in web development and design. Able to create attractive UI/UX designs and have the ability as a frontend developer. Enthusiastic to keep learning and growing, in web development and design.
      </p>
      <!--<div class="social-icons">
        <a href=""><i class="bx bxl-linkedin"></i></a>
        <a><i class="bx bxl-github"></i></a>
        <a><i class="bx bxl-instagram-alt"></i></a>
        <a><i class="bx bxl-twitter"></i></a>
      </div>-->

      <div class="btn-group">
        <a href="#" class="btn">Hire</a>
        <a href="#contact" class="btn">Contact</a>
      </div>
    </div>
    <div class="home-img">
      <img src="../../public/images/salwa.jpg" alt="" />
    </div>
  </section>

  <section class="about" id="about">
    <div class="about-img">
      <img src="../../public/images/salwa.jpg" alt="" />
    </div>

    <div class="about-content">
      <h2>About <span>Me</span></h2>
      <p>
        Hello everyone, I am Salwa Nur Amelia Suhendar. I am a student at SMKN 4 Bandung, majoring in Software Engineering. I am always enthusiastic to learn new things, especially those related to design. In web development, I can be a frontend developer and UI/UX designer.
      </p>
      <a href="#" class="btn">Read more</a>
    </div>
  </section>

  <section class="service" id="skills">
    <h2 class="heading">Skills</h2>

    <div class="services-container">
      <div class="services-box">
        <div class="service-info">
          <i class="bx bxl-figma"></i>
          <h4>Figma</h4>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-html5'></i>
          <h4>HTML</h4>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-css3' ></i>
          <h4>CSS</h4>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-vuejs' ></i>
          <h4>VUE JS</h4>
        </div>
      </div>
    </div>
  </section>

  <section class="project" id="project">
    <h2 class="heading">Project</h2>

    <div class="projects-box">
      
      <a>
        <div class="project-card">
        <img src="../../public/images/projectAbsensi.png" alt="" />

        <h3>Absensi SMKN 4 Bandung</h3>
        <p>Frontend Developer</p>
      </div>
      </a>

      

      <a>
        <div class="project-card">

          <img src="../../public/images/uiDesign.png" alt="" />

          <h3>MyLoon</h3>
          <p>UI / Design</p>

          </div>
      </a>

      <a target="_blank" href="https://www.figma.com/design/j7Nmwu4o6mVDHYHawtgGMF/Portofolio-UI?node-id=0-1&t=YVoeHkKtBO6LLkLS-1">
        <div class="project-card">

          <img src="../../public/images/uiDesign.png" alt="" />

          <h3>MyLoon</h3>
          <p>UI / Design</p>

          </div>
      </a>

    </div>
  </section>

  <footer class="footer">
    <div class="social-icons">
        <a href=""><i class="bx bxl-linkedin"></i></a>
        <a><i class="bx bxl-github"></i></a>
        <a><i class="bx bxl-instagram-alt"></i></a>
        <a><i class="bx bxl-twitter"></i></a>
      </div>

      <ul class="list">
        <li>
          <a href="#">FAQ</a>
        </li>

        <li>
          <a href="#Services">Services</a>
        </li>

        <li>
          <a href="#about">About</a>
        </li>

        <li>
          <a href="#project">Projects</a>
        </li>
      </ul>

      <p class="copyright">
        Cawwa! | All Rights Reserved
      </p>

  </footer>

</template>

<style scoped>
@import "../../public/style/style.css";
</style>
