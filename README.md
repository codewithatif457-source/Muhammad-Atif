<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muhammad Atif - Portfolio</title>
  <!-- Fonts and icons -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <!-- Styles -->
  <style>
    body { margin:0; font-family: 'Roboto', sans-serif; background:#0d1117; color:white; }
    a { color:#58a6ff; text-decoration:none; }
    section { padding:60px 20px; max-width:1000px; margin:auto; }
    .hero { text-align:center; padding:100px 20px; background:#161b22; }
    .hero h1 { font-size:3rem; margin-bottom:20px; }
    .hero h2 { font-size:2rem; color:#58a6ff; }
    .section-title { font-size:2rem; margin-bottom:20px; border-bottom:2px solid #58a6ff; display:inline-block; padding-bottom:5px; }
    .tech-stack img { margin:5px; height:50px; }
    .projects table { width:100%; border-collapse: collapse; margin-top:20px; }
    .projects th, .projects td { border:1px solid #333; padding:10px; text-align:left; }
    .socials a { margin:0 10px; font-size:1.5rem; }
  </style>
</head>
<body>

  <!-- ===== Hero Section ===== -->
  <section class="hero">
    <h1>Hi, I'm Muhammad Atif</h1>
    <h2><span id="element"></span></h2>
  </section>

  <!-- ===== About Me ===== -->
  <section>
    <h2 class="section-title">About Me</h2>
    <p>
      I’m a passionate <strong>Frontend & Full Stack Developer</strong> specializing in React.js, Node.js, and modern web technologies. 
      I enjoy creating responsive, user-friendly web applications. I have experience working with multiple companies and continuously growing my skills in full stack development and AI integration.
    </p>
  </section>

  <!-- ===== Tech Stack ===== -->
  <section>
    <h2 class="section-title">Tech Stack</h2>
    <div class="tech-stack">
      <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
      <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
      <img src="https://img.shields.io/badge/node.js-%23339933.svg?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
      <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
      <img src="https://img.shields.io/badge/mongodb-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
      <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
      <img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" alt="Django">
      <img src="https://img.shields.io/badge/aws-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
      <img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" alt=".NET">
      <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
      <img src="https://img.shields.io/badge/canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white" alt="Canva">
    </div>
  </section>

  <!-- ===== Projects ===== -->
  <section class="projects">
    <h2 class="section-title">Projects</h2>
    <table>
      <tr>
        <th>Project</th>
        <th>Description</th>
        <th>Tech Stack</th>
        <th>Link</th>
      </tr>
      <tr>
        <td>Portfolio Website</td>
        <td>My personal portfolio to showcase my work</td>
        <td>React, CSS, Figma</td>
        <td><a href="https://yourportfolio.com" target="_blank">View</a></td>
      </tr>
      <tr>
        <td>E-Commerce App</td>
        <td>Full-featured shopping platform</td>
        <td>React, Node.js, MongoDB</td>
        <td><a href="https://github.com/MuhammadAtif/ecommerce" target="_blank">View</a></td>
      </tr>
      <tr>
        <td>AI Chat App</td>
        <td>Chatbot using OpenAI API</td>
        <td>React, Node.js</td>
        <td><a href="https://github.com/MuhammadAtif/AI-ChatApp" target="_blank">View</a></td>
      </tr>
    </table>
  </section>

  <!-- ===== GitHub Stats ===== -->
  <section>
    <h2 class="section-title">GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=MuhammadAtif&theme=dark&show_icons=true&count_private=true" alt="GitHub Stats" style="width:100%; max-width:800px;">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MuhammadAtif&theme=dark&layout=compact" alt="Top Languages" style="width:100%; max-width:500px; margin-top:10px;">
  </section>

  <!-- ===== GitHub Trophies ===== -->
  <section>
    <h2 class="section-title">GitHub Trophies</h2>
    <img src="https://github-profile-trophy.vercel.app/?username=MuhammadAtif&theme=radical&no-bg=true&margin-w=10" alt="GitHub Trophies">
  </section>

  <!-- ===== Contact / Socials ===== -->
  <section>
    <h2 class="section-title">Connect with Me</h2>
    <div class="socials">
      <a href="https://instagram.com/atiiliciouss" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://linkedin.com/in/muhammad-atif-444534386/" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:codewithatif457@gmail.com"><i class="fas fa-envelope"></i></a>
    </div>
  </section>

  <!-- ===== Typed.js ===== -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed('#element', {
      strings: [
        'Frontend Developer.',
        'Full Stack Developer.',
        'AI Enthusiast.',
        'React & Node.js Specialist.'
      ],
      typeSpeed: 50,
      backSpeed: 25,
      backDelay: 1500,
      loop: true,
      smartBackspace: true
    });
  </script>

</body>
</html>
