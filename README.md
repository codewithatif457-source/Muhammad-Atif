<!-- ===== Hero Section with Typed.js ===== -->
<section class="hero" style="text-align:center; padding:50px; background:#0d1117; color:white;">
  <h1>Hi, I'm Muhammad Atif</h1>
  <h2>
    <span id="element"></span>
  </h2>
</section>

<!-- Load Typed.js library from CDN -->
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
