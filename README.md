
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Harun's Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
body {
  font-family: Arial, sans-serif;
  background: #f2f2f2;
  padding: 20px;
  margin: 0;
  text-align: center;
}
.title {
  color: #333;
  margin-bottom: 20px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}
.gallery img {
  width: 200px;
  height: auto;
  cursor: pointer;
  border: 2px solid #ccc;
  border-radius: 8px;
  transition: transform 0.3s;
}
.gallery img:hover {
  transform: scale(1.05);
}
body {
  font-family: Arial, sans-serif;
  background: #f9f9f9;
  margin: 0;
  padding: 20px;
  text-align: center;
}
.title {
  font-size: 28px;
  color: #222;
  margin-bottom: 20px;
}
.video-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
}
.video-thumb {
  width: 300px;
  height: 180px;
  object-fit: cover;
  border-radius: 8px;
  cursor: pointer;
  border: 2px solid #ccc;
  transition: transform 0.3s;
}
.video-thumb:hover {
  transform: scale(1.03);
}

/* Fullscreen Modal */
.modal {
  display: none;
  position: fixed;
  z-index: 99;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0,0,0,0.9);
  padding-top: 60px;
}
.modal-video {
  margin: auto;
  display: block;
  width: 80%;
  max-height: 80%;
}
.close {
  position: absolute;
  top: 30px;
  right: 50px;
  color: white;
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}
/* Fullscreen Modal */
.modal {
  display: none;
  position: fixed;
  z-index: 99;
  padding-top: 60px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0,0,0,0.9);
}
.modal-content {
  margin: auto;
  display: block;
  max-width: 80%;
  height: auto;
}
.close {
  position: absolute;
  top: 30px;
  right: 50px;
  color: white;
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}
    .section {
  padding: 20px;
  background-color: #f4f8fb;
  border-radius: 10px;
  max-width: 800px;
  margin: 30px auto;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

.section h2 {
  font-size: 24px;
  margin-bottom: 20px;
  color: #2c3e50;
}

.section p {
  margin: 5px 0;
  font-size: 16px;
  color: #333;
}
.social-order-section {
  text-align: center;
  padding: 20px;
}

.social-order-section h2,
.social-order-section h3 {
  color: #2c3e50;
  margin-bottom: 15px;
}

.order-buttons,
.social-buttons {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-bottom: 20px;
}

.btn {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  border-radius: 30px;
  color: #fff;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 8px;
  transition: transform 0.2s ease;
}

.btn:hover {
  transform: scale(1.05);
}

/* Individual Button Colors */
.email {
  background-color: #007BFF;
}

.whatsapp {
  background-color: #25D366;
}

.fiverr {
  background-color: #1DBF73;
}

.facebook {
  background-color: #3b5998;
}

.instagram {
  background-color: #E1306C;
}

.tiktok {
  background-color: #010101;
}

.whatsapp-alt {
  background-color: #128C7E;
}
.certificate-section,
.media-section,
.image-row,
.gallery-section {
  text-align: center;
  margin: 40px 20px;
}

.certificate-section img,
.media-section img,
.image-row img,
.gallery img {
  margin: 10px;
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.media-photo {
  width: 300px;
}

.media-video {
  width: 400px;
  margin-top: 20px;
  border-radius: 10px;
}

.image-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}

.image-row img {
  width: 150px;
  height: auto;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  padding: 10px;
}

.gallery img {
  width: 100%;
  height: auto;
  border-radius: 12px;
}
.section {
  padding: 30px;
  text-align: center;
}

.portfolio-list {
  list-style: none;
  padding: 0;
  margin-top: 15px;
}

.portfolio-list li {
  margin: 10px 0;
}

.portfolio-list a {
  text-decoration: none;
  color: #444;
  font-weight: bold;
}

.links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 30px;
}

.btn {
  padding: 10px 20px;
  color: #fff;
  font-weight: bold;
  text-decoration: none;
  border-radius: 10px;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-size: 16px;
  transition: background 0.3s;
}

.btn i {
  font-size: 18px;
}

/* Color Variants */
.blue { background-color: #1877F2; }
.red { background-color: #FF0000; }
.darkgreen { background-color: #25D366; }
.purple { background-color: #C13584; }
.pink { background-color: #FF69B4; }
.green { background-color: #1DBF73; }

.btn:hover {
  opacity: 0.9;
}

.icon {
  width: 20px;
  height: auto;
}
.portfolio-buttons {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 20px;
}

.btn {
  padding: 10px 20px;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 8px;
  font-size: 16px;
  transition: 0.3s ease;
}

/* Button Colors */
.orange { background-color: #f57c00; }
.teal { background-color: #009688; }
.purple { background-color: #9c27b0; }
.darkblue { background-color: #1a237e; }

.btn:hover {
  opacity: 0.85;
}
/* Back to Top Button Style */
#backToTopBtn {
  display: none;
  position: fixed;
  bottom: 30px;
  right: 30px;
  z-index: 99;
  font-size: 20px;
  border: none;
  outline: none;
  background-color: #ff4081; /* গোলাপি */
  color: white;
  cursor: pointer;
  padding: 12px 16px;
  border-radius: 50%;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
  transition: background-color 0.3s, transform 0.3s;
}

#backToTopBtn:hover {
  background-color: #e91e63; /* গা dark গোলাপি */
  transform: scale(1.1);
}
/* Contact Section Styles */
.contact-section {
  background-color: #f9f9f9;
  padding: 40px 20px;
  text-align: center;
}

.contact-section h2 {
  margin-bottom: 20px;
  color: #333;
}

.contact-form {
  max-width: 500px;
  margin: 0 auto;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 12px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 16px;
}

.contact-form textarea {
  height: 150px;
  resize: vertical;
}

.contact-form button {
  background-color: #4CAF50;
  color: white;
  border: none;
  padding: 12px 25px;
  font-size: 16px;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact-form button:hover {
  background-color: #45a049;
}
.gallery-button {
  display: inline-block;
  padding: 12px 24px;
  background-color: #28a745; 
  color: #fff;
  font-size: 16px;
  font-weight: bold;
  text-decoration: none;
  border-radius: 8px;
  transition: background-color 0.3s ease, transform 0.2s ease;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
}

.gallery-button:hover {
  background-color: #218838; 
  transform: scale(1.05);
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Harun's Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Three dot menu */
    .menu-toggle {
      position: absolute;
      top: 20px;
      right: 20px;
      cursor: pointer;
      font-size: 24px;
      padding: 10px;
    }

    .menu-content {
      display: none;
      position: absolute;
      top: 60px;
      right: 20px;
      background-color: #f9f9f9;
      border: 1px solid #ccc;
      border-radius: 5px;
      z-index: 1000;
      min-width: 180px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .menu-content a {
      display: block;
      padding: 10px;
      color: #333;
      text-decoration: none;
    }

    .menu-content a:hover {
      background-color: #eee;
    }

    .section {
      padding: 20px;
    }

    /* Google search bar style */
    .gcse-search {
      margin: 20px auto;
      max-width: 600px;
    }
  </style>
  <!-- Google CSE Script -->
  <script async src="https://cse.google.com/cse.js?cx=d3251f7aa5ee247d5"></script>
</head>
<body>

  <!-- Three dot button -->
  <div class="menu-toggle" onclick="toggleMenu()">☰</div>

  <!-- Menu content -->
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

  <!-- Google Search Bar always visible on homepage -->
  <div class="gcse-search"></div>

  <!-- Sections -->
  <div id="profile" class="section">
    <h2>Profile</h2>
    <p>I am Md. Harun Or Rashid, a skilled and dedicated professional specializing in data entry, web research, and PDF to Excel conversions...</p>
  </div>

  <div id="privacy" class="section" style="display:none">
    <h2>Privacy Policy</h2>
    <p>All information collected through this site is used solely to improve user experience...</p>
  </div>

  <div id="contact" class="section" style="display:none">
    <h2>Contact</h2>
    <p>Email: hmharun796@gmail.com<br>Phone: +880 1648-131500<br>
    Facebook: <a href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit</a><br>
    WhatsApp: <a href="https://wa.me/8801648131500" target="_blank">Chat</a></p>
  </div>

  <div id="about" class="section" style="display:none">
    <h2>About</h2>
    <p>I'm passionate about providing efficient data entry and digital solutions...</p>
  </div>

  <div id="settings" class="section" style="display:none">
    <h2>Settings</h2>
    <p>Website Theme: Default<br>Language: English<br>Notifications: Enabled</p>
  </div>

  <div id="certificate" class="section" style="display:none">
    <h2>Certificates</h2>
    <ul>
      <li><img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate 1" width="200" /></li>
      <li><img src="312.jpg" alt="Certificate 2" width="200" /></li>
      <li><img src="076ac6.jpg" alt="Certificate 3" width="200" /></li>
    </ul>
  </div>

  <div id="media" class="section" style="display:none">
    <h2>Tutorial</h2>
    <video controls width="320">
      <source src="video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <p><a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube Channel</a></p>
  </div>

  <script>
    function toggleMenu() {
      var menu = document.getElementById("menu");
      menu.style.display = (menu.style.display === "block") ? "none" : "block";
    }

    function showSection(id) {
      var sections = document.getElementsByClassName("section");
      for (var i = 0; i < sections.length; i++) {
        sections[i].style.display = "none";
      }
      document.getElementById(id).style.display = "block";
    }
  </script>
  
   <div>
      <p><strong>Name:</strong> Md. Harun Or Rashid</p>
      <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
      <p><strong>Email:</strong> <a href="mailto:hmharun796@gmail.com">hmharun796@gmail.com</a></p>
      <p><strong>Education:</strong> SSC, Lemubari Binoda Sundori High School</p>
      <p><strong>Profession:</strong> Freelancer</p>
      <p><strong>Skills:</strong> Data Entry, E-commEntry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>
      <p><strong>Phone 1:</strong> <a href="tel:+8801648131500">+8801648131500</a></p>
      <p><strong>Phone 2:</strong> <a href="tel:+8801316888404">+8801316888404</a></p>
    </div>
  <div class="social-order-section">

  <h2>Hire Me or Connect with Me</h2>

  <div class="order-buttons">
    <a href="mailto:harunrm900@gmail.com?subject=Hiring%20Request&body=Hello,%20I%20would%20like%20to%20hire%20you%20for%20a%20project." target="_blank" class="btn email">
      <i class="fas fa-envelope"></i> Order Now (Email)
    </a>
    <a href="https://wa.me/8801648131500?text=Hi%20Harun,%20I%20am%20interested%20in%20your%20services." target="_blank" class="btn whatsapp">
      <i class="fab fa-whatsapp"></i> Order on WhatsApp
    </a>
  </div>

  <h3>Connect on Social Media</h3>

  <div class="social-buttons">
    <a class="btn fiverr" href="https://www.fiverr.com/s/dDlW3G3" target="_blank"><i class="fas fa-briefcase"></i> Fiverr</a>
    <a class="btn facebook" href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank"><i class="fab fa-facebook-f"></i> Facebook</a>
    <a class="btn instagram" href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
    <a class="btn tiktok" href="https://www.tiktok.com/@user6071584366187" target="_blank"><i class="fab fa-tiktok"></i> TikTok</a>
    <a class="btn whatsapp-alt" href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
  </div>
<!-- Certificate Section -->
<div class="certificate-section">
  <h2>Certificate of Completion</h2>
  <img src="certificate.jpg" alt="Certificate" />
  <img src="file_00000000758861f884606a82c460dc7a (1).png " alt="Certificate" />
</div>

<!-- Homepage section -->
<section id="gallery-link">
  <h2>My Gallery</h2>
  <a href="gallery.html" class="gallery-button">View Gallery</a>
</section>

<!-- YouTube Section -->
<section class="section">
  <h2>My YouTube Channel</h2>
  <p>Subscribe to my channel for tutorials, tips, and more!</p>
  <a class="btn red" href="https://youtube.com/@mdharun-n6j" target="_blank">
    <i class="fa-brands fa-youtube"></i> Visit My YouTube
  </a>
</section>

<video controls width="400">
  <source src="media/Ami_Soia_Geleo_Soibena_Bidhata.mp4" type="video/mp4" />
</video>

<!-- Portfolio Section -->
<section class="section portfolio-section">
  <h2>My Portfolio</h2>
  <div class="portfolio-buttons">
    <a href="https://docs.google.com/spreadsheets/d/1FSV3CzDlRSDJHaumYrCcvKFcBKGedUhFU9qPDY6viW4/edit?usp=drivesdk" target="_blank" class="btn orange">
      Sample Data Entry Work
    </a>
    <a href="https://drive.google.com/file/d/1xA2EXAMPLE123/view" target="_blank" class="btn teal">
      Product Listing (Excel)
    </a>
    <a href="https://drive.google.com/file/d/1yB3EXAMPLE456/view" target="_blank" class="btn purple">
      Web Research Sample
    </a>
    <a href="https://drive.google.com/file/d/1zC4EXAMPLE789/view" target="_blank" class="btn darkblue">
      PDF to Excel Conversion
    </a>
  </div>
</section>

<!-- Social Media Links -->
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
  
<!-- Back to Top Button -->
<button onclick="scrollToTop()" id="backToTopBtn" title="Go to top">↑</button>
</section>
<script>
// Show/hide the button on scroll
window.onscroll = function() {
  const btn = document.getElementById("backToTopBtn");
  btn.style.display = (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) ? "block" : "none";
};
  
// Scroll to top smoothly
function scrollToTop() {
  window.scrollTo({ top: 0, behavior: 'smooth' });
}
</script>  

<!-- Contact Form Start -->
<section class="contact-section">
  <h2>Contact Me</h2>
  <form action="https://formsubmit.co/harunrm900@email.com" method="POST" class="contact-form">
    <input type="hidden" name="_captcha" value="false">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>
<!-- Contact Form End -->

</body>
</html>

<a href="assets/Md_Harun_CV_New.pdf" download>Download CV</a>
