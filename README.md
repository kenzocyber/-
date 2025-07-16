# tws
<!DOCTYPE html><html lang="en" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kenzo | Black Hat Hacker</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <script>
    if (window.matchMedia('(prefers-color-scheme: light)').matches) {
      document.documentElement.classList.remove('dark');
    } else {
      document.documentElement.classList.add('dark');
    }
  </script>
  <style>
    body {
      background-color: #0c0c1d;
      color: #00fff7;
      font-family: 'Courier New', monospace;
    }
    h2, h3 {
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .card {
      border: 1px solid #00fff7;
      border-radius: 0.5rem;
      padding: 1.25rem;
      background-color: #111122;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #00fff7;
    }
  </style>
</head>
<body>
  <!-- Hero -->
  <section class="text-center p-6 max-w-md mx-auto" data-aos="fade-down">
    <h1 class="text-2xl font-bold mb-2">Kenzo | Black Hat Hacker</h1>
    <p class="text-cyan-300">Ethical Hacker & Cybersecurity Enthusiast</p>
  </section>  <!-- About Me -->  <section class="px-4 py-6 max-w-md mx-auto" data-aos="fade-up">
    <h2 class="text-lg mb-4 text-cyan-300">About Me</h2>
    <p class="text-base leading-relaxed">
      Saya Kenzo, fokus dalam keamanan siber dan etikal hacking. Tujuan saya adalah mengamankan sistem dan berbagi pengetahuan dengan komunitas.
    </p>
  </section>  <!-- Skills -->  <section class="px-4 py-6 bg-zinc-900 max-w-md mx-auto" data-aos="zoom-in">
    <h2 class="text-lg mb-4 text-cyan-300">Skills</h2>
    <div class="grid gap-4">
      <div class="card">
        <h3 class="mb-1 text-cyan-200">Programming ⭐⭐⭐⭐☆</h3>
        <p>Python, JavaScript, Bash</p>
      </div>
      <div class="card">
        <h3 class="mb-1 text-cyan-200">Security ⭐⭐⭐⭐⭐</h3>
        <p>Penetration Testing, Network Security</p>
      </div>
      <div class="card">
        <h3 class="mb-1 text-cyan-200">Tools ⭐⭐⭐⭐☆</h3>
        <p>Kali Linux, Metasploit, Wireshark</p>
      </div>
    </div>
  </section>  <!-- Projects -->  <section class="px-4 py-6 max-w-md mx-auto" data-aos="fade-up">
    <h2 class="text-lg mb-4 text-cyan-300">Projects</h2>
    <div class="grid gap-4">
      <div class="card">
        <h3 class="mb-1 text-cyan-200">nethunter-termux ⭐⭐⭐⭐☆</h3>
        <p class="mb-1">Hacking via smartphone.</p>
        <a href="#" class="underline text-cyan-400">View Repo</a>
      </div>
      <div class="card">
        <h3 class="mb-1 text-cyan-200">XSS Detector ⭐⭐⭐⭐⭐</h3>
        <p class="mb-1">Deteksi XSS otomatis.</p>
        <a href="#" class="underline text-cyan-400">View Repo</a>
      </div>
      <div class="card">
        <h3 class="mb-1 text-cyan-200">AutoRecon ⭐⭐⭐⭐☆</h3>
        <p class="mb-1">Tool recon untuk bug bounty.</p>
        <a href="#" class="underline text-cyan-400">View Repo</a>
      </div>
    </div>
  </section>  <!-- Blog -->  <section class="px-4 py-6 bg-zinc-900 text-center max-w-md mx-auto" data-aos="zoom-in">
    <h2 class="text-lg mb-2 text-cyan-300">Blog</h2>
    <p class="mb-2">Berisi tips, writeup, dan cerita hacking.</p>
    <a href="#" class="underline text-cyan-400">Visit My Blog</a>
  </section>  <!-- Tools -->  <section class="px-4 py-6 text-center max-w-md mx-auto" data-aos="fade">
    <h2 class="text-lg mb-2 text-cyan-300">Tools</h2>
    <p class="mb-2">Kumpulan tools pribadi saya.</p>
    <a href="#" class="underline text-cyan-400">Explore Tools</a>
  </section>  <!-- Contact -->  <section class="px-4 py-6 bg-zinc-900 max-w-md mx-auto" data-aos="fade-up">
    <h2 class="text-lg mb-4 text-cyan-300">Contact</h2>
    <form action="mailto:pykcyber@gmail.com" method="POST" enctype="text/plain" class="grid gap-3">
      <input type="text" name="name" value="Kenzo" class="p-2 rounded bg-black text-white border border-cyan-400" readonly />
      <input type="email" name="email" value="pykcyber@gmail.com" class="p-2 rounded bg-black text-white border border-cyan-400" readonly />
      <textarea name="message" rows="4" placeholder="Message" class="p-2 rounded bg-black text-white border border-cyan-400" required></textarea>
      <button type="submit" class="bg-cyan-500 hover:bg-cyan-400 text-black font-bold py-2 rounded">Send Message</button>
    </form>
  </section>  <!-- Footer -->  <footer class="text-center text-xs py-6 border-t border-cyan-400 max-w-md mx-auto">
    &copy; 2025 Kenzo — Designed with ⚡ cyber spirit
  </footer>  <script>AOS.init();</script></body>
</html>
