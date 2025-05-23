 <!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Md. Harun Or Rashid</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css">
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .navbar {
      position: sticky;
      top: 0;
      background: #fff;
      padding: 10px 20px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      z-index: 999;
    }
    .navbar h1 {
      margin: 0;
    }
    .container {
      padding: 20px;
    }
    .profile {
      width: 200px;
      border-radius: 15px;
    }
    .buttons a {
      display: inline-block;
      margin: 5px;
      padding: 10px 20px;
      background: #007BFF;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .certificate-section img,
    .image-row img,
    .media-section img,
    .gallery img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin: 10px 0;
    }
    #preloader {
      background: white;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 10000;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .loader {
      width: 40px;
      height: 40px;
      border: 5px solid #007BFF;
      border-top-color: transparent;
      border-radius: 50%;
      animation: spin 1s linear infinite;
    }
    @keyframes spin {
      to { transform: rotate(360deg); }
    }
    #backToTop {
      position: fixed;
      bottom: 30px;
      right: 30px;
      padding: 10px;
      font-size: 18px;
      display: none;
      border: none;
      background: #007BFF;
      color: white;
      border-radius: 5px;
      cursor: pointer;
      z-index: 9999;
    }
    .typing {
      border-right: 2px solid #000;
      white-space: nowrap;
      overflow: hidden;
      display: inline-block;
    }
  </style>
</head>
<body>
  <div id="preloader">
    <div class="loader"></div>
  </div>  <div class="navbar">
    <h1>Md. Harun Or Rashid</h1>
  </div>  <div class="container">
    <img src="harun.jpg" alt="Harun's Photo" class="profile" data-aos="fade-up">
    <h2>I am a <span class="typing"></span></h2>
    <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
    <p><strong>Email:</strong> hmharun796@gmail.com</p>
    <p><strong>Phone:</strong> +880 1648 131 500</p><div class="buttons">
  <a href="https://www.fiverr.com/s/dDlW3G3" target="_blank"><i class="fab fa-fiverr"></i> Fiverr</a>
  <a href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank"><i class="fab fa-facebook"></i> Facebook</a>
  <a href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
  <a href="https://www.tiktok.com/@user6071584366187" target="_blank"><i class="fab fa-tiktok"></i> TikTok</a>
  <a href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
  <a href="https://youtube.com/@mdharun-n6j" target="_blank"><i class="fab fa-youtube"></i> YouTube</a>
</div>

<div class="certificate-section" data-aos="fade-up">
  <h2>Certificate of Completion</h2>
  <img src="certificate.jpg" alt="Certificate">
</div>

<div class="media-section" data-aos="fade-up">
  <h2>My Photo & Video</h2>
  <img src="media/myphoto.jpg" alt="My Photo">
  <video controls width="400">
    <source src="media/myvideo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div class="gallery-section" data-aos="fade-up">
  <h2>My Gallery</h2>
  <div class="gallery">
    <img src="media/photo1.jpg" alt="Photo 1">
    <img src="media/photo2.jpg" alt="Photo 2">
    <img src="media/photo3.jpg" alt="Photo 3">
    <img src="media/photo4.jpg" alt="Photo 4">
  </div>
</div>

<div class="contact-section" data-aos="fade-up">
  <h2>Contact Me</h2>
  <form action="https://formspree.io/f/mjvnavrw" method="POST">
    <input type="text" name="name" placeholder="Your Name" required><br><br>
    <input type="email" name="email" placeholder="Your Email" required><br><br>
    <textarea name="message" rows="5" placeholder="Your Message" required></textarea><br><br>
    <button type="submit">Send Message</button>
  </form>
</div>

  </div><button id="backToTop">↑</button>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>  <script>
    AOS.init();
  </script>  <script>
    window.addEventListener('load', () => {
      document.getElementById('preloader').style.display = 'none';
    });
  </script>  <script>
    const btn = document.getElementById('backToTop');
    window.onscroll = () => {
      if (window.scrollY > 300) {
        btn.style.display = 'block';
      } else {
        btn.style.display = 'none';
      }
    };
    btn.onclick = () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    };
  </script>  <script>
    const words = ["Freelancer", "Data Entry Expert", "Web Researcher"];
    let i = 0, j = 0, currentWord = "", isDeleting = false;
    function type() {
      currentWord = words[i];
      let display = isDeleting ? currentWord.slice(0, j--) : currentWord.slice(0, j++);
      document.querySelector(".typing").textContent = display;
      if (!isDeleting && j === currentWord.length) {
        isDeleting = true;
        setTimeout(type, 1000);
      } else if (isDeleting && j === 0) {
        isDeleting = false;
        i = (i + 1) % words.length;
        setTimeout(type, 300);
      } else {
        setTimeout(type, isDeleting ? 60 : 100);
      }
    }
    type();
  </script></body>
</html>
