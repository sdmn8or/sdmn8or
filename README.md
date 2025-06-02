<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>sdmn8or | Digital Dev</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/devicon/devicon.min.css" rel="stylesheet">
    <style>
      body {
        background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
        font-family: 'Courier New', Courier, monospace;
      }
      .glow {
        text-shadow: 0 0 5px #0ff, 0 0 10px #0ff, 0 0 15px #0ff;
      }
      .glass {
        background: rgba(255, 255, 255, 0.05);
        backdrop-filter: blur(10px);
        border: 1px solid rgba(255, 255, 255, 0.1);
      }
      .icon:hover {
        transform: scale(1.15);
        transition: transform 0.3s ease;
      }
    </style>
  </head>
  <body class="text-white">
    <!-- Hero -->
    <section class="min-h-screen flex flex-col justify-center items-center text-center px-4">
      <h1 class="text-5xl md:text-7xl font-bold glow mb-4">sdmn8or</h1>
      <p class="text-xl md:text-2xl text-purple-400">Full-stack Web Developer & Digital Architect</p>
      <p class="text-sm mt-2">Mission: Build digital worlds, entertain minds, and conquer the grid.</p>
    </section>

    <!-- Skills -->
    <section class="py-12 px-6 bg-black/20 glass">
      <h2 class="text-3xl font-bold mb-6 text-center glow">🚀 Tech Arsenal</h2>
      <div class="grid grid-cols-4 md:grid-cols-8 gap-6 justify-items-center">
        <i class="devicon-html5-plain colored text-5xl icon"></i>
        <i class="devicon-css3-plain colored text-5xl icon"></i>
        <i class="devicon-javascript-plain colored text-5xl icon"></i>
        <i class="devicon-tailwindcss-plain colored text-5xl icon"></i>
        <i class="devicon-bootstrap-plain colored text-5xl icon"></i>
        <i class="devicon-react-original colored text-5xl icon"></i>
        <i class="devicon-nodejs-plain colored text-5xl icon"></i>
        <i class="devicon-git-plain colored text-5xl icon"></i>
      </div>
    </section>

    <!-- About -->
    <section class="py-12 px-6">
      <div class="max-w-3xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4 glow">⚡ Who Am I?</h2>
        <div class="text-left bg-black/20 p-6 rounded-xl glass">
          <p><span class="text-green-400">Name:</span> Sadmaan Al Saad</p>
          <p><span class="text-green-400">Alias:</span> sdmn8or</p>
          <p><span class="text-green-400">Role:</span> Full-stack Web Developer</p>
          <p><span class="text-green-400">Location:</span> Earth 2.0 (Bangladesh)</p>
          <p><span class="text-green-400">Mission:</span> Build digital worlds, entertain minds, & conquer the grid.</p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="text-center py-6 text-sm text-gray-500">
      Built by <span class="text-purple-300">sdmn8or</span> — Glitched in the Grid 💻
    </footer>

    <script>
      gsap.from(".icon", {
        opacity: 0,
        y: 30,
        duration: 0.6,
        stagger: 0.1,
        ease: "power2.out"
      });
    </script>
  </body>
</html>
