#
 
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hassan Saeed | Model Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', sans-serif;
      background: #0f0f0f;
      color: #ffffff;
      line-height: 1.6;
    }
    header {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,.55), rgba(0,0,0,.55)), url('1000020307.jpg') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 4px;
      font-weight: 700;
    }
    header p {
      margin-top: 10px;
      font-size: 1.1rem;
      opacity: .85;
    }
    section {
      max-width: 1100px;
      margin: auto;
      padding: 80px 20px;
    }
    h2 {
      font-size: 1.8rem;
      margin-bottom: 20px;
      font-weight: 600;
      letter-spacing: 2px;
    }
    .about p {
      max-width: 700px;
      opacity: .9;
    }
    .stats {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: #181818;
      padding: 25px;
      border-radius: 12px;
      text-align: center;
    }
    .card h3 {
      font-size: 1.2rem;
      margin-bottom: 8px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 25%;
      border-radius: 10px;
      object-fit: cover;
    }
    footer {
      background: #080808;
      padding: 40px 20px;
      text-align: center;
    }
    footer p {
      opacity: .8;
    }
    a { color: #ffffff; text-decoration: none; }
  
    /* Animations */
    html { scroll-behavior: smooth; }

    .fade-up {
      opacity: 0;
      transform: translateY(40px);
      animation: fadeUp 1s ease forwards;
    }

    header .fade-up { animation-delay: .3s; }
    section.fade-up { animation-delay: .4s; }

    @keyframes fadeUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Hover effects */
    .card {
      transition: transform .4s ease, box-shadow .4s ease;
    }

    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 15px 40px rgba(0,0,0,.4);
    }

    .gallery img {
      transition: transform .5s ease, filter .5s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
      filter: brightness(1.1);
    }
  </style>
</head>
<body>

<header class="fade-up">
  <div>
    <h1>HASSAN SAEED</h1>
    <p>MODEL · EDITORIAL · LIFESTYLE</p>
  </div>
</header>

<section class="about fade-up">
  <h2>ABOUT</h2>
  <p>
    I am a confident and versatile model based in Kuala Lumpur, showing discipline,
    professionalism, and strong visual presence in every shoot.
  </p>

  <div class="stats">
    <div class="card"><h3>Age</h3><p>21</p></div>
    <div class="card"><h3>Location</h3><p>Kuala Lumpur</p></div>
    <div class="card"><h3>Languages</h3><p>English · Arabic · Multilingual</p></div>
    <div class="card"><h3>Availability</h3><p>Fashion · Editorial · Commercial</p></div>
  </div>
</section>

<section class="fade-up">
  <h2>PORTFOLIO</h2>
  <div class="gallery">
    <img src="SHL04166.JPG" alt="Hassan Saeed Model" />
  </div>
</section>

<section class="fade-up">
  <h2>EXPERIENCE</h2>
  <p>
    Background in hospitality and volunteering shaped my confidence, communication skills,
    and professionalism on set.
  </p>
</section>

<footer class="fade-up">
  <h2>CONTACT</h2>
  <p>📞 +60 18-3960 824</p>
  <p>📧 hassanbusiness.one@gmail.com</p>
  <p>📍 Kuala Lumpur, Malaysia</p>
  <p><a href="https://wa.me/60183960824" target="_blank">💬 WhatsApp</a></p>
  <p><a href="https://instagram.com/7sn_04" target="_blank">📸 Instagram @7sn_04</a></p>
</footer>

</body>
</html>
