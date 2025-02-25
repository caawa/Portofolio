<script>
// Add this JavaScript to your existing script or create a new script file
document.addEventListener('DOMContentLoaded', function() {
  const menuToggle = document.getElementById('menu-toggle');
  const menuIcon = document.getElementById('menu-icon');
  const navbar = document.querySelector('.navbar');
  const navLinks = document.querySelectorAll('.navbar a');
  
  // Toggle menu when icon is clicked
  menuIcon.addEventListener('click', function() {
    menuToggle.checked = !menuToggle.checked;
  });
  
  // Close menu when a nav link is clicked
  navLinks.forEach(link => {
    link.addEventListener('click', function() {
      menuToggle.checked = false;
    });
  });
  
  // Close menu when clicking outside
  document.addEventListener('click', function(event) {
    const isClickInsideNavbar = navbar.contains(event.target);
    const isClickOnMenuIcon = menuIcon.contains(event.target);
    
    if (!isClickInsideNavbar && !isClickOnMenuIcon && menuToggle.checked) {
      menuToggle.checked = false;
    }
  });
});
</script>
<template>
  <header class="header">
    <a href="#home" class="logo">Caw <span>Wa!</span></a>
    <input type="checkbox" id="menu-toggle" />
    <label for="menu-toggle" id="menu-icon">
      <i class="bx bx-menu" id="open-icon"></i>
    </label>

    <nav class="navbar">
      <i class="bx bx-x" id="close-icon"></i>
      <a href="#home" class="active">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#project">Project</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="home">
    <div class="home-content">
      <h1>Hi, Saya <span>Salwa</span></h1>
      <h3 class="text-animation">Saya <span> </span></h3>
      
      <div class="social-icons">
        <a href="https://linkedin.com/in/salwanas" target="_blank" rel="noopener noreferrer"><i class="bx bxl-linkedin"></i></a>
        <a href="https://github.com/caawa" target="_blank" rel="noopener noreferrer"><i class="bx bxl-github"></i></a>
        <a href="https://instagram.com/salwanrar" target="_blank" rel="noopener noreferrer"><i class="bx bxl-instagram-alt"></i></a>
        <a target="_blank" rel="noopener noreferrer"><i class="bx bxl-twitter"></i></a>
      </div>

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
      <h2>Tentang <span>Saya</span></h2>
      <p>
        Halo semuanya, saya Salwa Nur Amelia Suhendar. Frontend Developer dengan pengalaman dalam pengembangan aplikasi berbasis React dan Vue.js. Berpengalaman dalam menangani proyek manajemen tugas, integrasi API, dan pengujian kualitas. Terbiasa bekerja dalam tim dan menerapkan kontrol versi menggunakan GitHub.
      </p>
      <a href="../../public/CV_Salwa.pdf" download="../../public/CV Salwa.pdf" class="btn">Download CV</a>
    </div>
  </section>

  <section class="experience" id="experience">
  <h2 class="heading">Pengalaman <span>Saya</span></h2>
  
  <div class="experience-container">
    <div class="experience-box">
      <div class="experience-info">
        <h3>Frontend Developer</h3>
        <h4>PT CURAWEDA PALAGAN INNOTECH</h4>
        <span class="experience-date">Juli 2024 - Oktober 2024</span>
        <p>Mengembangkan aplikasi web yang responsif dan ramah pengguna menggunakan React, TypeScript, dan Tailwind CSS. Menerapkan framework UI modern untuk menciptakan pengalaman pengguna yang interaktif. Bekerja sama dengan tim desain dan backend untuk menghadirkan produk berkualitas tinggi.</p>
      </div>
    </div>
  </div>
</section>

  <section class="service" id="skills">
    <h2 class="heading">Skills</h2>

    <div class="services-container">

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-html5'></i>
          <h4>HTML</h4>
        </div>
        <div class="service-text">
          <p>Mahir - Menguasai strukturisasi halaman web dengan elemen semantik untuk memastikan aksesibilitas dan performa yang optimal.</p>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-css3' ></i>
          <h4>CSS</h4>
        </div>
        <div class="service-text">
          <p>Mahir - Terampil dalam styling responsif, animasi, dan desain modern dengan pendekatan yang efisien.</p>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-javascript' ></i>
          <h4>JAVASCRIPT</h4>
        </div>
        <div class="service-text">
          <p>Menengah - Memahami dasar-dasar Vue.js, state management, serta integrasi dengan API untuk membangun aplikasi web interaktif.</p>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-vuejs' ></i>
          <h4>VUE JS</h4>
        </div>
        <div class="service-text">
          <p>Menengah - Memahami dasar-dasar Vue.js, state management, serta integrasi dengan API untuk membangun aplikasi web interaktif.</p>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-react'></i>
          <h4>REACT</h4>
        </div>
        <div class="service-text">
          <p>Menengah - Berpengalaman dalam membangun antarmuka pengguna dinamis menggunakan React, hooks, dan state management.</p>
        </div>
      </div>

      <div class="services-box">
        <div class="service-info">
          <i class='bx bxl-tailwind-css'></i>

          <h4>TAILWIND CSS</h4>
        </div>
        <div class="service-text">
          <p>Menengah - Mahir dalam styling berbasis utility-first untuk menghasilkan desain yang konsisten dan cepat.</p>
        </div>
      </div>


      <div class="services-box">
        <div class="service-info">
          <i class="bx bxl-figma"></i>
          <h4>FIGMA</h4>
        </div>
        <div class="service-text">
          <p>Menengah - Memahami desain UI/UX, wireframing, dan prototyping untuk pengembangan aplikasi yang user-friendly.</p>
        </div>
      </div>

      
      <div class="services-box">
        <div class="service-info">
          <i class="bx bxl-github"></i>
          <h4>GITHUB</h4>
        </div>
        <div class="service-text">
          <p>Menengah - Berpengalaman dalam version control, kolaborasi tim, serta manajemen repository dengan Git dan GitHub.</p>
        </div>
      </div>

    </div>
  </section>

  <section class="project" id="project">
    <h2 class="heading">Pengalaman Project</h2>

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

          <h3>TaskFlow</h3>
          <p>Frontend Developer</p>

          </div>
      </a>

      <a target="_blank" href="https://www.figma.com/design/j7Nmwu4o6mVDHYHawtgGMF/Portofolio-UI?node-id=0-1&t=YVoeHkKtBO6LLkLS-1">
        <div class="project-card">

          <img src="../../public/images/uiDesign.png" alt="" />

          <h3>Learn4Ward</h3>
          <p>Frontend Developer</p>

          </div>
      </a>

    </div>
  </section>

  <footer class="footer">
    <div class="social-icons">
        <a href="https://linkedin.com/in/salwanas" target="_blank" rel="noopener noreferrer"><i class="bx bxl-linkedin"></i></a>
        <a href="https://github.com/caawa" target="_blank" rel="noopener noreferrer"><i class="bx bxl-github"></i></a>
        <a href="https://instagram.com/salwanrar" target="_blank" rel="noopener noreferrer"><i class="bx bxl-instagram-alt"></i></a>
        <a href="https://linkedin.com/in/salwanas" target="_blank" rel="noopener noreferrer"><i class="bx bxl-twitter"></i></a>
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