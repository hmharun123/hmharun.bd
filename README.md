<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Md. Harun Or Rashid</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
 font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
  color: #333;
}
h2 {
  color: #222;
}
a {
  text-decoration: none;
  color: inherit;
}
.section {
  padding: 20px;
  display: none;
  background-color: white;
  margin: 10px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
}
.section.active {
  display: block;
  }
header {
  background-color: #0077cc;
  color: white;
  padding: 15px;
  text-align: center;
  font-size: 22px;
  position: sticky;
  top: 0;
  z-index: 1000;
}
.menu-button {
  float: right;
  font-size: 24px;
  background: none;
  border: none;
  color: white;
  cursor: pointer;
}
.menu-content {
  display: none;
  background-color: #333;
  padding: 10px;
}
.menu-content a {
  display: block;
  color: white;
  padding: 10px;
  margin: 5px 0;
  background-color: #444;
  border-radius: 5px;
}
.menu-content a:hover {
  background-color: #555;
}
.button {
  display: inline-block;
  padding: 10px 20px;
  margin: 6px 5px;
  font-size: 16px;
  font-weight: bold;
  text-decoration: none;
  border: none;
  border-radius: 8px;
  color: #fff;
  cursor: pointer;
  transition: background 0.3s ease;
}
.button.youtube {
  background-color: #ff0000;
}
.button.youtube:hover {
  background-color: #cc0000;
}
.button.portfolio {
  background-color: #007bff;
}
.button.portfolio:hover {
  background-color: #0056b3;
}
.button.web-research {
  background-color: #20c997;
}
.button.web-research:hover {
  background-color: #169c77;
}
.button.data-entry {
  background-color: #fd7e14;
}
.button.data-entry:hover {
  background-color: #e8590c;
}
.button, .btn {
  display: inline-block;
  padding: 10px 15px;
  margin: 5px 5px 10px 0;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
.button:hover, .btn:hover {
  opacity: 0.9;
}
.btn.blue { background-color: #3b5998; }
.btn.red { background-color: #ff0000; }
.btn.darkgreen { background-color: #25D366; }
.btn.purple { background-color: #833AB4; }
.btn.pink { background-color: #E1306C; }
.btn.green { background-color: #1dbf73; }
.button.fiverr {
  background-color: #1dbf73;
}
.button.facebook {
  background-color: #1877f2;
}
.button.instagram {
  background-color: #e1306c;
}
.button.tiktok {
  background-color: #000000;
}
.button.whatsapp {
  background-color: #25D366;
}
form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}
form button {
  background-color: #0077cc;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 5px;
  cursor: pointer;
}
form button:hover {
  background-color: #005fa3;
}
img {
  max-width: 100%;
  height: auto;
  border-radius: 5px;
}
.image-row, .gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}
.gallery img {
  width: 150px;
  height: auto;
}
#backToTop {
  position: fixed;
  bottom: 20px;
  right: 20px;
  padding: 10px 15px;
  font-size: 20px;
  border: none;
  background-color: #333;
  color: white;
  border-radius: 5px;
  cursor: pointer;
  display: none;
  z-index: 1000;
}
#backToTop.show {
  display: block;
}
.footer {
  background-color: #222;
  color: #ddd;
  text-align: center;
  padding: 15px;
  font-size: 14px;
}
.footer a {
  color: #ccc;
  margin: 0 5px;
}
.footer a:hover {
  text-decoration: underline;
}
    .menu-button {
      font-size: 24px;
      background: none;
      border: none;
      cursor: pointer;
      padding: 10px;
    }
    .menu-content {
      display: none;
      position: absolute;
      right: 10px;
      background-color: #f1f1f1;
      min-width: 200px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1000;
    }
 .menu-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
    }
  .menu-content a:hover {
      background-color: #ddd;
    }
    .section {
      display: none;
      padding: 20px;
      border: 1px solid #ccc;
      margin-top: 10px;
    }
.section.active {
      display: block;
    }
  </style>
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <body>
    <header>
  Md. Harun Or Rashid
  <button class="menu-button" onclick="toggleMenu()">&#8942;</button>
  <div class="menu-content" id="menu">
    <a href="#" onclick="showSection('profile')">Profile</a>
    <a href="#" onclick="showSection('privacy')">Privacy Policy</a>
    <a href="#" onclick="showSection('contact')">Contact</a>
    <a href="#" onclick="showSection('about')">About</a>
    <a href="#" onclick="showSection('settings')">Settings</a>
    <a href="#" onclick="showSection('certificate')">Certificates</a>
    <a href="#" onclick="showSection('media')">Tutorial</a>
    <a href="assets/Harun_CV.pdf" download>Download CV</a>
    <a href="mailto:hmharun796@gmail.com?subject=Hello&body=I want to connect with you.">Send Email</a>
  </div>
      
 <div id="profile" class="section active">
    <h2>Profile</h2>
   <img src="harun.jpg" alt="Harun's Photo" class="profile" />
    <p>I am Md. Harun Or Rashid, a skilled and dedicated professional...</p>
  </div>

  <div id="privacy" class="section">
    <h2>Privacy Policy</h2>
    <p>All information collected through this site is used solely...</p>
  </div>

  <div id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: hmharun796@gmail.com<br>Phone: +880 1648-131500</p>
  </div>

  <div id="about" class="section">
    <h2>About</h2>
    <p>I'm passionate about providing efficient data entry and digital solutions...</p>
  </div>

  <div id="settings" class="section">
    <h2>Settings</h2>
    <p>Website Theme: Default<br>Language: English</p>
  </div>

  <div id="certificate" class="section">
    <h2>Certificates</h2>
    <ul>
      <li><img src="file_00000000875861f990b4e5fffbcbb32e.png" width="200" /></li>
      <li><img src="312.jpg" width="200" /></li>
      <li><img src="076ac6.jpg" width="200" /></li>
    </ul>
  </div>

  <div id="media" class="section">
    <h2>Tutorial</h2>
    <video controls width="320">
      <source src="video.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p><a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube Channel</a></p>
  </div>
<script>
    function toggleMenu() {
      const menu = document.getElementById('menu');
      menu.style.display = (menu.style.display === 'block') ? 'none' : 'block';
    }
    function showSection(id) {
      document.getElementById('menu').style.display = 'none';

      const sections = document.querySelectorAll('.section');
      sections.forEach(section => section.classList.remove('active'));

      const target = document.getElementById(id);
      if (target) {
        target.classList.add('active');
      }
    window.addEventListener('click', function(e) {
      if (!e.target.matches('.menu-button')) {
        document.getElementById('menu').style.display = 'none';
      }
    });
  </script>

<div class="container">
    <!-- Search Bar -->
    <h2>Search My Website</h2>
    <div class="gcse-search"></div>
  </div>

  <div class="profile" class="section active">
      <h2>My Profile</h2>
      <img src="harun.jpg" alt="Harun's Photo" class="profile" />
      <p><strong>Name:</strong> Md. Harun Or Rashid</p>
      <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
      <p><strong>Email:</strong> hmharun796@gmail.com</p>
      <p><strong>Education:</strong> SSC, Lemubari Binoda Sundori High School</p>
      <p><strong>Profession:</strong> Freelancer</p>
      <p><strong>Skills:</strong> Data Entry, E-commEntry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>
    </div>
   
<div class="contact" class="section">
    <h2>Contact</h2>
    <p><strong>Phone:</strong> +8801648131500</p>
    <p><strong>Phone:</strong> +8801316888404</p>
    <p><strong>Email:</strong> hmharun796@gmail.com</p>
    <a href="mailto:hmharun123@gmail.com?subject=Hiring%20Request&body=Hello,%20I%20would%20like%20to%20hire%20you%20for%20a%20project." target="_blank">
      <button class="button">Order Now</button>
    </a>
    <a href="https://wa.me/8801648131500?text=Hi%20Harun,%20I%20am%20interested%20in%20your%20services." target="_blank">
      <button class="button" style="background-color: #25D366;">Order on WhatsApp</button>
    </a>
    <div class="buttons">
      <a class="button fiverr" href="https://www.fiverr.com/s/dDlW3G3" target="_blank">Visit My Fiverr Profile</a>
      <a class="button" href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit My Facebook</a>
      <a class="button" href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank">View My Instagram</a>
      <a class="button" href="https://www.tiktok.com/@user6071584366187" target="_blank">TikTok</a>
      <a class="button" href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank">WhatsApp</a>
    </div>
  </div>
 
<div class="certificate-section">
    <h2>Certificate of Completion</h2>
    <img src="certificate.jpg" alt="Certificate" />
    <img src="file_000000004bd461f89c7906893d08c772.png" alt="Certificate" />
  </div>

  <!-- Photo & Video Section -->
  <div class="media-section">
    <h2>My Photo & Video</h2>
    <img src="media/myphoto.jpg" alt="My Photo" style="width: 300px;" />
    <video controls width="400">
      <source src="media/Ami_Soia_Geleo_Soibena_Bidhata.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </div>

  <!-- Image Row -->
  <div class="image-row">
    <img src="data-antry.png" alt="Data Entry" />
    <img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate" />
    <img src="312.jpg" alt="Certificate" />
    <img src="076ac6.jpg" alt="076ac6" />
    <img src="SAMPLE.jpeg" alt="Sample" />
    <img src="data.jpg" alt="Data" />
  </div>

<section class="media" class="section">
  <h2>My YouTube Channel</h2>
  <p>Subscribe to my channel for tutorials, tips, and more!</p>
  <a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube</a>
</div>
</section>

<section class="portfolio" class="section">
  <h2>My Portfolio</h2>
  <ul>
    <li><a href="https://docs.google.com/spreadsheets/d/1FSV3CzDlRSDJHaumYrCcvKFcBKGedUhFU9qPDY6viW4/edit?usp=drivesdk" target="_blank">Sample Data Entry Work</a></li>
    <li><a href="https://drive.google.com/file/d/1xA2EXAMPLE123/view" target="_blank">Product Listing (Excel)</a></li>
    <li><a href="https://drive.google.com/file/d/1yB3EXAMPLE456/view" target="_blank">Web Research Sample</a></li>
    <li><a href="https://drive.google.com/file/d/1zC4EXAMPLE789/view" target="_blank">PDF to Excel Conversion</a></li>
  </ul>
</div>
  </section>
  
  <!-- Gallery Section -->
  <div class="gallery-section">
    <h2>My Gallery</h2>
    <div class="gallery">
      <img src="076ac6.jpg" alt="Photo 1" />
      <img src="media/photo2.jpg" alt="Photo 2" />
      <img src="media/photo3.jpg" alt="Photo 3" />
      <img src="media/photo4.jpg" alt="Photo 4" />
    </div>
  </div>

 <section class="links">
    <a href="https://www.facebook.com/share/r/1BcEg68nzy/" class="btn blue" target="_blank">
      <i class="fa-brands fa-facebook-f"></i> Facebook
    </a>
    <a href="https://youtube.com/@mdharun-n6j" class="btn red" target="_blank">
      <i class="fa-brands fa-youtube"></i> YouTube
    </a>
    <a href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" class="btn darkgreen" target="_blank">
      <i class="fa-brands fa-whatsapp"></i> WhatsApp
    </a>
    <a href="https://www.instagram.com/p/DIeAfFXT_oO/" class="btn purple" target="_blank">
      <i class="fa-brands fa-instagram"></i> Instagram
    </a>
    <a href="https://www.tiktok.com/@user6071584366187" class="btn pink" target="_blank">
      <i class="fa-brands fa-tiktok"></i> TikTok
    </a>
    <a href="https://www.fiverr.com/s/dDlW3G3" class="btn green" target="_blank">
      <img src="fiverr-logo.png" alt="Fiverr" class="icon" /> Fiverr
    </a>
  </section>

<!-- Contact Section -->
<section class="contact" class="section">
  <h2>Contact Me</h2>
 </section>
  <form>
    <input type="text" placeholder="Your Name" required><br>
    <input type="email" placeholder="Your Email" required><br>
    <textarea placeholder="Your Message" required></textarea><br>
    <button type="submit">Send Message</button>
  </form>
</section>
<body>
 <!-- Back to Top Button --><button id="backToTop" onclick="scrollToTop()">↑</button>

<!-- Footer --><footer class="footer">
  <p>© 2025 HM Harun. All rights reserved.</p>
  <p>
    <a href="#">Facebook</a> |
    <a href="#">LinkedIn</a> |
    <a href="#">GitHub</a>
  </p>
  <a href="#top">&uarr;</a>
</footer>

<script>
 // Optional: Track YouTube link click
document.addEventListener("DOMContentLoaded", function () {
  const ytLink = document.querySelector('a[href*="youtube.com/@"]');
  if (ytLink) {
    ytLink.addEventListener("click", function () {
      console.log("User clicked on YouTube channel link.");
    });
   // Optional: Portfolio link click effect
document.addEventListener("DOMContentLoaded", function () {
  const portfolioLinks = document.querySelectorAll(".portfolio-section a");

  portfolioLinks.forEach(link => {
    link.addEventListener("click", function () {
      console.log("Portfolio link clicked:", this.href);
    });
  });
});
  }
});
  const backToTopButton = document.getElementById("backToTop");

  window.addEventListener("scroll", () => {
    if (window.scrollY > 200) {
      backToTopButton.classList.add("show");
    } else {
      backToTopButton.classList.remove("show");
    }
  });

  function scrollToTop() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
  <script>
    function toggleMenu() {
      const menu = document.getElementById('menu');
      menu.style.display = (menu.style.display === 'block') ? 'none' : 'block';
    }
    function showSection(id) {
      document.getElementById('menu').style.display = 'none';

      const sections = document.querySelectorAll('.section');
      sections.forEach(section => section.classList.remove('active'));

      const target = document.getElementById(id);
      if (target) {
        target.classList.add('active');
      }
    window.addEventListener('click', function(e) {
      if (!e.target.matches('.menu-button')) {
        document.getElementById('menu').style.display = 'none';
      }
    });
    
</script>

</body>
</html>




  

