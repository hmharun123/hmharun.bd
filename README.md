<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Md. Harun Or Rashid</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
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
  </style>
</head>
<body>

  <header>
    Md. Harun Or Rashid
    <button class="menu-button" onclick="toggleMenu()">&#8942;</button>
  </header>

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

  <div id="profile" class="section">
    <h2>Profile</h2>
    <p>I am Md. Harun Or Rashid, a skilled and dedicated professional specializing in data entry, web research, and PDF to Excel conversions. I also create Payoneer account tutorials and provide project-based services through platforms like Fiverr.</p>
  </div>

  <div id="privacy" class="section">
    <h2>Privacy Policy</h2>
    <p>All information collected through this site is used solely to improve user experience and will not be shared with third parties. You may contact me for any concerns about your data privacy.</p>
  </div>

  <div id="contact" class="section">
    <h2>Contact</h2>
    <p>
      Email: hmharun796@gmail.com<br />
      Phone: +880 1648-131500<br />
      Facebook: <a href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit My Facebook</a><br />
      WhatsApp: <a href="https://wa.me/8801648131500" target="_blank">Chat on WhatsApp</a>
    </p>
  </div>

  <div id="about" class="section">
    <h2>About</h2>
    <p>I'm passionate about providing efficient data entry and digital solutions. My goal is to ensure client satisfaction through quality work and timely delivery. I also manage a YouTube channel for educational content.</p>
  </div>

  <div id="settings" class="section">
    <h2>Settings</h2>
    <p>
      Website Theme: Default<br />
      Language: English<br />
      Notifications: Enabled<br />
      <em>(Settings options can be expanded based on development needs)</em>
    </p>
  </div>

  <div id="certificate" class="section">
    <h2>Certificates</h2>
    <ul>
      <li><img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate 1" width="200" /></li>
      <li><img src="312.jpg" alt="Certificate 2" width="200" /></li>
      <li><img src="076ac6.jpg" alt="Certificate 3" width="200" /></li>
    </ul>
  </div>

  <div id="media" class="section">
    <h2>Tutorial</h2>
    <p>Watch my video tutorials on YouTube:</p>
    <video controls width="320">
      <source src="video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <p><a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube Channel</a></p>
  </div>

  <div class="container">
    <!-- Search Bar -->
    <h2>Search My Website</h2>
    <div class="gcse-search"></div>
  </div>

  <header>
    <div id="profile" class="section active">
      <h2>My Profile</h2>
      <img src="harun.jpg" alt="Harun's Photo" class="profile" />
      <p><strong>Name:</strong> Md. Harun Or Rashid</p>
      <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
      <p><strong>Email:</strong> hmharun796@gmail.com</p>
      <p><strong>Education:</strong> SSC, Lemubari Binoda Sundori High School</p>
      <p><strong>Profession:</strong> Freelancer</p>
      <p><strong>Skills:</strong> Data Entry, E-commEntry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>
    </div>
  </header>

  <div id="contact" class="section">
    <h2>Contact</h2>
    <p><strong>Phone:</strong> +8801648131500</p>
    <p><strong>Phone:</strong> +8801316888404</p>
    <p><strong>Email:</strong> hmharun796@gmail.com</p>
    <a href="mailto:hmharun123@gmail.com?subject=Hiring%20Request&body=Hello,%20I%20would%20like%20to%20hire%20you%20for%20a%20project." target="_blank">
      <button class="button">Order Now</button>
    </a>
    <a href="https://wa.me/8801795815184?text=Hi%20Harun,%20I%20am%20interested%20in%20your%20services." target="_blank">
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

  <div id="about" class="section">
    <h2>About</h2>
    <p>I am a freelancer specialized in data entry and online tasks.</p>
  </div>

  <div id="settings" class="section">
    <h2>Settings</h2>
    <p>Settings coming soon.</p>
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

  <!-- YouTube -->
  <section class="section">
    <h2>My YouTube Channel</h2>
    <p>Subscribe to my channel for tutorials, tips, and more!</p>
    <a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube</a>

    <!-- Portfolio -->
    <section class="section portfolio-section">
      <h2>My Portfolio</h2>
      <ul>
        <li><a href="https://docs.google.com/spreadsheets/d/1FSV3CzDlRSDJHaumYrCcvKFcBKGedUhFU9qPDY6viW4/edit?usp=drivesdk" target="_blank">Sample Data Entry Work</a></li>
        <li><a href="https://drive.google.com/file/d/1xA2EXAMPLE123/view" target="_blank">Product Listing (Excel)</a></li>
        <li><a href="https://drive.google.com/file/d/1yB3EXAMPLE456/view" target="_blank">Web Research Sample</a></li>
        <li><a href="https://drive.google.com/file/d/1zC4EXAMPLE789/view" target="_blank">PDF to Excel Conversion</a></li>
      </ul>
    </section>
  </section>

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

  <section class="section">
    <h2>Testimonials</h2>
    <blockquote>"Harun is very talented and delivers high quality work!" - Client A</blockquote>
    <blockquote>"A great developer to work with.

   <script>
  function toggleMenu() {
    var menu = document.getElementById("menu");
    menu.style.display = (menu.style.display === "block") ? "none" : "block";
  }

  function showSection(id) {
    var sections = document.querySelectorAll(".section");
    sections.forEach(function (section) {
      section.style.display = "none";
    });

    var selectedSection = document.getElementById(id);
    if (selectedSection) {
      selectedSection.style.display = "block";
    }

    // Hide menu after selecting
    document.getElementById("menu").style.display = "none";
  }

  // Optional: Hide menu when clicking outside
  window.addEventListener("click", function (e) {
    if (!e.target.matches('.menu-button')) {
      document.getElementById("menu").style.display = "none";
    }
  });
</script>
