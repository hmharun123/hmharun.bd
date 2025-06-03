<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Md. Harun or Rosid - Personal Website</title>
  <link rel="stylesheet" href="style.css" />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
  />
  <style>
    /* Back to Top Button */
    #backToTop {
      position: fixed;
      bottom: 40px;
      right: 40px;
      background-color: #007bff;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 18px;
      display: none;
      z-index: 1000;
    }

    /* Gallery styles */
    #gallery {
      background: #f7f7f7;
      padding: 20px 15px 50px 15px;
    }
    #gallery h2 {
      text-align: center;
      margin-bottom: 25px;
    }
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      max-width: 900px;
      margin: 0 auto;
    }
    .gallery-grid img {
      width: 100%;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .gallery-grid img:hover {
      transform: scale(1.05);
    }
    #overlay {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.85);
      display: none;
      align-items: center;
      justify-content: center;
      z-index: 9999;
    }
    #overlay img {
      max-width: 90%;
      max-height: 90%;
      border-radius: 10px;
      box-shadow: 0 0 30px #000;
    }
    #closeBtn {
      position: fixed;
      top: 20px;
      right: 30px;
      font-size: 30px;
      color: white;
      cursor: pointer;
      z-index: 10000;
      font-weight: bold;
      user-select: none;
    }
  </style>
</head>
<body>
  <!-- Search and 3-dot menu -->
  <div class="top-bar">
    <div class="search-box">
      <input type="text" id="searchInput" placeholder="Search..." />
      <button onclick="searchFunction()"><i class="fas fa-search"></i></button>
    </div>
    <div class="menu-button" onclick="toggleMenu()">
      <i class="fas fa-ellipsis-v"></i>
    </div>
  </div>

  <!-- Address and Profile -->
  <section id="home" class="section active">
    <h2>Welcome to My Profile</h2>
    <div class="address">
      <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
    </div>
    <div style="text-align: center; margin: 20px 0;">
      <img
        src="harun.jpg"
        alt="Md. Harun or Rosid"
        style="width: 180px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"
      />
    </div>
  </section>

  <!-- Navigation Buttons -->
  <nav class="button-nav">
    <button onclick="showSection('home')">Profile</button>
    <button onclick="showSection('privacy')">Privacy Policy</button>
    <button onclick="showSection('contact')">Contact</button>
    <button onclick="showSection('gallery')">Gallery</button>
    <button onclick="showSection('project')">Project</button>
    <button onclick="showSection('settings')">Settings</button>
    <button onclick="showSection('about')">About</button>
    <button onclick="showSection('sendMessage')">Send Message</button>
  </nav>

  <!-- About Section -->
  <section id="about" class="section" style="display:none;">
    <h2>About Me</h2>
    <p><strong>Name:</strong> Md. Harun or Rosid</p>
    <p><strong>Profession:</strong> Freelancer</p>
    <p>
      <strong>Title:</strong> Data Entry, Web Research, Copy-Paste, Data Scraping,
      Web Scraping
    </p>
    <p><strong>Phone:</strong> 01648131500, 01316888404</p>
    <p><strong>Email:</strong> harunrm900@gmail.com</p>
    <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
    <p><strong>Education:</strong> SSC, Lemu Bari Binoda Sundari High School</p>
    <p><strong>Skills:</strong> Data Entry, Web Scraping, Copy Paste, Research</p>
    <p><strong>Languages:</strong> Bengali, English, Hindi</p>
    <a href="your-cv-file.pdf" download class="cv-button">Download My CV</a>

    <h3>Short Introduction</h3>
    <p>
      I am Md. Harun or Rosid, a dedicated and skilled freelancer with expertise
      in data entry, web research, and related fields. I have successfully
      completed a professional data entry course and have practical experience
      working on Fiverr and other platforms. My aim is to provide accurate and
      timely services to clients worldwide.
    </p>

    <h3>My Certificate</h3>
    <img
      src="file-Y6wKbf9DgL1qnw3VQN2rwa"
      alt="Certificate"
      style="max-width: 100%; height: auto; border: 2px solid #ddd; padding: 5px; border-radius: 10px;"
    />

    <h3>My Design Sample</h3>
    <img
      src="file-FXHorjMhUvr7PhcKJmH4dU"
      alt="Poster Design"
      style="max-width: 100%; height: auto; border: 2px solid #ddd; padding: 5px; border-radius: 10px; margin-bottom: 10px;"
    />

    <h3>Social Media Profiles</h3>
    <div class="buttons">
      <a
        class="button fiverr"
        href="https://www.fiverr.com/s/dDlW3G3"
        target="_blank"
        style="background: #1dbf73"
        >Visit My Fiverr</a
      >
      <a
        class="button"
        href="https://www.facebook.com/share/r/1BcEg68nzy/"
        target="_blank"
        style="background: #3b5998"
        >Facebook</a
      >
      <a
        class="button"
        href="https://www.instagram.com/p/DIeAfFXT_oO/"
        target="_blank"
        style="background: #e1306c"
        >Instagram</a
      >
      <a
        class="button"
        href="https://www.tiktok.com/@user6071584366187"
        target="_blank"
        style="background: #000"
        >TikTok</a
      >
      <a
        class="button"
        href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you"
        target="_blank"
        style="background: #25d366"
        >WhatsApp</a
      >
    </div>

    <h3>Order Now</h3>
    <div class="buttons">
      <a
        class="button"
        href="https://www.fiverr.com/s/dDlW3G3"
        target="_blank"
        style="background: #ff5a5f"
        ><i class="fas fa-shopping-cart"></i> Order on Fiverr</a
      >
      <a
        class="button"
        href="mailto:harunrm900@gmail.com"
        target="_blank"
        style="background: #007bff"
        ><i class="fas fa-envelope"></i> Email Order</a
      >
      <a
        class="button"
        href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20order%20a%20service"
        target="_blank"
        style="background: #25d366"
        ><i class="fab fa-whatsapp"></i> WhatsApp Order</a
      >
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="section" style="display:none;">
    <h2>Md. Harun's Gallery</h2>
    <div class="gallery-grid">
      <img src="gallery/image1.jpg" alt="Gallery Image 1" loading="lazy" />
      <img src="gallery/image2.jpg" alt="Gallery Image 2" loading="lazy" />
      <img src="gallery/image3.jpg" alt="Gallery Image 3" loading="lazy" />
      <img src="gallery/image4.jpg" alt="Gallery Image 4" loading="lazy" />
      <img src="gallery/image5.jpg" alt="Gallery Image 5" loading="lazy" />
      <img src="gallery/image6.jpg" alt="Gallery Image 6" loading="lazy" />
    </div>

    <!-- Fullscreen Image Overlay -->
    <div id="overlay">
      <span id="closeBtn" onclick="closeOverlay()">×</span>
      <img id="fullImage" src="" alt="Full Size Image" />
    </div>
  </section>

  <!-- Back to Top Button -->
  <button onclick="topFunction()" id="backToTop" title="Go to top">
    <i class="fas fa-arrow-up"></i>
  </button>

  <script>
    // Show Back to Top button on scroll
    window.onscroll = function () {
      const btn = document.getElementById('backToTop');
      if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        btn.style.display = 'block';
      } else {
        btn.style.display = 'none';
      }
    };

    function topFunction() {
      document.body.scrollTop = 0;
      document.documentElement.scrollTop = 0;
    }

    // Section show/hide function
    function showSection(id) {
      const sections = document.querySelectorAll('.section');
      sections.forEach((sec) => {
        sec.style.display = 'none';
      });
      const activeSection = document.getElementById(id);
      if (activeSection) {
        activeSection.style.display = 'block';
        window.scrollTo(0, 0);
      }
    }

    // Search function
    function searchFunction() {
      let input = document.getElementById('searchInput').value;
      alert('You searched for: ' + input);
    }

    // Gallery overlay functionality
    const overlay = document.getElementById('overlay');
    const fullImage = document.getElementById('fullImage');

    document.querySelectorAll('.gallery-grid img').forEach((img) => {
      img.addEventListener('click', () => {
        fullImage.src = img.src;
        overlay.style.display = 'flex';
      });
    });

    function closeOverlay() {
      overlay.style.display = 'none';
      fullImage.src = '';
    }

    overlay.addEventListener('click', (e) => {
      if (e.target === overlay) {
        closeOverlay();
      }
    });

    // Dummy toggleMenu function (you can customize)
    function toggleMenu() {
      alert('Menu toggled!');
    }
  </script>
</body>
</html>
