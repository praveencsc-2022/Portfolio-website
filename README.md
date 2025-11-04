# Portfolio-website
portfolio/
│
├── index.html
[Uploading <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Praveen Cris | Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Hero Section -->
  <header class="hero">
    <div class="container">
      <h1>Hi, I’m Praveen Cris</h1>
      <p>I build <strong>Websites</strong> & run <strong>Meta & Google Ads</strong> to help brands grow.</p>
      <a href="#contact" class="btn">Get in Touch</a>
    </div>
  </header>

  <!-- Services Section -->
  <section id="services">
    <div class="container">
      <h2>Services</h2>
      <div class="service-cards">
        <div class="card">
          <h3>Website Development</h3>
          <p>Custom websites, landing pages, and e-commerce solutions that convert.</p>
        </div>
        <div class="card">
          <h3>Meta Ads</h3>
          <p>Scroll-stopping ad designs with data-driven strategies for better ROI.</p>
        </div>
        <div class="card">
          <h3>Google Ads</h3>
          <p>Targeted campaigns to attract leads and boost sales for your business.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="project-grid">
        <div class="project-card">
          <img src="images/project1.jpg" alt="Project 1">
          <h4>Website for Clothing Brand</h4>
        </div>
        <div class="project-card">
          <img src="images/project2.jpg" alt="Project 2">
          <h4>Lead Gen Funnel for Fitness Coach</h4>
        </div>
        <div class="project-card">
          <img src="images/project3.jpg" alt="Project 3">
          <h4>Landing Page for Photographer</h4>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/praveencris" target="_blank">Praveen Cris</a></p>
      <p>Email: <a href="mailto:yourmail@example.com">yourmail@example.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/your-number">Chat Now</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Praveen Cris | Website Development & Digital Marketing</p>
  </footer>

</body>
</html>
index.html…]()

├── style.css[Uploading index.html…]()
[style.css](https://github.com/user-attachments/files/23323108/style.css)
/* Reset & Fonts */
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: 'Montserrat', sans-serif; line-height: 1.6; color: #333; }

/* Buttons */
.btn { display: inline-block; padding: 10px 20px; background: #0077b6; color: #fff; text-decoration: none; border-radius: 5px; }

/* Container */
.container { max-width: 1000px; margin: auto; padding: 40px 20px; }

/* Hero Section */
.hero { background: #023e8a; color: #fff; text-align: center; padding: 100px 20px; }
.hero h1 { font-size: 48px; margin-bottom: 20px; }
.hero p { font-size: 20px; margin-bottom: 30px; }

/* Services */
#services { background: #f1f1f1; padding: 60px 0; }
#services h2 { text-align: center; margin-bottom: 40px; font-size: 36px; }
.service-cards { display: flex; justify-content: space-around; flex-wrap: wrap; gap: 20px; }
.card { background: #fff; padding: 20px; border-radius: 10px; width: 300px; text-align: center; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
.card h3 { margin-bottom: 10px; color: #0077b6; }

/* Projects */
#projects { padding: 60px 0; }
#projects h2 { text-align: center; margin-bottom: 40px; font-size: 36px; }
.project-grid { display: flex; justify-content: space-around; flex-wrap: wrap; gap: 20px; }
.project-card { width: 300px; }
.project-card img { width: 100%; border-radius: 10px; }
.project-card h4 { text-align: center; margin-top: 10px; }

/* Contact */
#contact { background: #f1f1f1; text-align: center; padding: 60px 20px; }
#contact h2 { margin-bottom: 20px; font-size: 36px; }
#contact a { color: #0077b6; text-decoration: none; }

/* Footer */
footer { text-align: center; padding: 20px; background: #023e8a; color: #fff; }


└── images/
      ├── project1.jpg
      ├── project2.jpg
      └── project3.jpg
