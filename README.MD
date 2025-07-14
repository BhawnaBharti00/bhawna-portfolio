<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Edit by Bhawan</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0b0b0b;
      color: #f1f1f1;
      scroll-behavior: smooth;
      overflow-x: hidden;
    }

    /* Animations */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 0.8s forwards;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Landing */
    #landing {
      height: 100vh;
      background: url("momo-face.gif") center center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      backdrop-filter: brightness(0.4);
      padding: 40px 20px;
    }

    #landing h1 {
      font-size: 3rem;
      color: #ffcc70;
      text-shadow: 0 2px 10px #000;
    }

    #landing p {
      margin-top: 10px;
      font-size: 1.2rem;
      color: #ccc;
    }

    .portal-buttons {
      margin-top: 30px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .portal-buttons a {
      text-decoration: none;
      background: #ffcc70;
      color: #0f0f0f;
      padding: 14px 28px;
      border-radius: 50px;
      font-weight: bold;
      box-shadow: 0 0 12px #ffcc70;
      transition: all 0.3s ease;
    }

    .portal-buttons a:hover {
      background: #ffc643;
      transform: scale(1.05);
    }

    header {
      text-align: center;
      padding: 60px 20px 40px;
    }

    header img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      box-shadow: 0 0 20px #ffcc70;
      margin-bottom: 20px;
    }

    header h1 {
      color: #ffcc70;
      font-size: 2rem;
    }

    header p {
      color: #aaa;
    }

    section {
      max-width: 1100px;
      margin: auto;
      padding: 60px 20px;
    }

    section h2 {
      color: #ffcc70;
      font-size: 1.8rem;
      margin-bottom: 30px;
      text-align: center;
      border-bottom: 1px solid #333;
      padding-bottom: 10px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .projects img,
    .projects video {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 0 10px #222;
      transition: transform 0.3s ease, box-shadow 0.3s;
    }

    .projects img:hover,
    .projects video:hover {
      transform: scale(1.03);
      box-shadow: 0 0 20px #ffcc70;
    }

    ul.tools {
      list-style: none;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    ul.tools li {
      background: #1a1a1a;
      padding: 16px;
      border-radius: 10px;
      text-align: center;
      color: #ccc;
      box-shadow: 0 0 10px #000 inset;
    }

    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 24px;
      background-color: #25D366;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 10px #25D366;
    }

    .button:hover {
      background-color: #1fa855;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 30px 10px;
      color: #777;
      font-size: 14px;
    }

    footer a {
      color: #57b3ff;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <!-- Landing -->
  <section id="landing">
    <h1 class="fade-in">Welcome to Edit by Bhawan</h1>
    <p class="fade-in" style="animation-delay: 0.3s;">Animation • Storytelling • Illustration</p>
    <div class="portal-buttons fade-in" style="animation-delay: 0.5s;">
      <a href="#animation">🎞 Animation</a>
      <a href="#illustrations">🖌 Illustration</a>
      <a href="#testshots">🎭 Tests</a>
      <a href="#tools">🧰 Tools</a>
      <a href="#booking">💬 Book Me</a>
    </div>
  </section>

  <!-- Profile -->
  <header>
    <img src="momo-face.gif" alt="Profile Image" />
    <h1>Bhawan Bharti</h1>
    <p>Creative Animator & Visual Storyteller</p>
  </header>

  <!-- Sections -->
  <section id="animation">
    <h2>🎞 Animation Project</h2>
    <div class="projects">
      <video controls>
        <source src="rigged cloths_3.mp4" type="video/mp4" />
        Your browser does not support video.
      </video>
    </div>
  </section>

  <section id="illustrations">
    <h2>🖌 Illustrations</h2>
    <div class="projects">
      <img src="elements-2.gif" alt="Illustration 1" />
      <img src="pot.gif" alt="Illustration 2" />
    </div>
  </section>

  <section id="testshots">
    <h2>🎭 Emotional Test Shots</h2>
    <div class="projects">
      <img src="momo-face.gif" alt="Test 1" />
      <img src="pot.gif" alt="Test 2" />
    </div>
  </section>

  <section id="tools">
    <h2>🧰 Tools I Use</h2>
    <ul class="tools">
      <li>Adobe Animate</li>
      <li>Adobe Illustrator</li>
      <li>After Effects</li>
      <li>Figma</li>
    </ul>
  </section>

  <section id="booking" style="text-align: center;">
    <h2>💬 Book an Edit</h2>
    <a href="https://wa.me/919263300290" target="_blank" class="button">Message on WhatsApp</a>
  </section>

  <footer>
    <p>📧 Email: bhartibhawna4488@example.com</p>
    <p>🔗 <a href="https://www.behance.net/bhawnabharti48" target="_blank">Visit My Behance</a></p>
    <p>&copy; 2025 Edit by Bhawan</p>
  </footer>

</body>
</html>
