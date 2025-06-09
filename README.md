<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Muditha Bathiya</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      .fade-in-up {
        opacity: 0;
        transform: translateY(20px);
        animation: fadeInUp 1s ease-out forwards;
      }

      @keyframes fadeInUp {
        to {
          opacity: 1;
          transform: translateY(0);
        }
      }

      .glow-text {
        text-shadow: 0 0 5px #00f0ff, 0 0 10px #00f0ff;
      }
    </style>
  </head>
  <body class="bg-gradient-to-br from-[#0f172a] to-[#1e293b] text-white font-sans">

    <section class="text-center py-10 fade-in-up">
      <h1 class="text-4xl font-bold glow-text">👋 Hi, I'm Muditha Bathiya</h1>
      <p class="text-xl mt-3 text-cyan-300">Creative Web Developer & Designer</p>
    </section>

    <section class="text-center px-5 max-w-3xl mx-auto fade-in-up">
      <p class="text-gray-300 text-lg mb-6">
        I’m a passionate web developer with a keen eye for design and a love for
        building immersive, user-friendly websites. I bring together clean code and beautiful visuals to create
        amazing digital experiences.
      </p>
    </section>

    <section class="fade-in-up px-5 py-10">
      <h2 class="text-2xl text-cyan-400 font-semibold mb-4 text-center">🚀 Skills</h2>
      <ul class="flex flex-wrap justify-center gap-4 text-white text-base">
        <li class="bg-cyan-700 px-4 py-2 rounded-lg shadow hover:bg-cyan-600 transition">Web Development</li>
        <li class="bg-pink-600 px-4 py-2 rounded-lg shadow hover:bg-pink-500 transition">Graphic Design</li>
        <li class="bg-indigo-600 px-4 py-2 rounded-lg shadow hover:bg-indigo-500 transition">E-Commerce</li>
      </ul>
    </section>

    <section class="fade-in-up px-5 py-10">
      <h2 class="text-2xl text-cyan-400 font-semibold mb-4 text-center">🎨 Tools I Use</h2>
      <div class="flex flex-wrap justify-center gap-6">
        <img src="https://skillicons.dev/icons?i=photoshop,illustrator,canva&theme=dark" />
      </div>
    </section>

    <section class="fade-in-up px-5 py-10">
      <h2 class="text-2xl text-cyan-400 font-semibold mb-4 text-center">💻 Languages & Tools</h2>
      <div class="flex flex-wrap justify-center gap-6">
        <img src="https://skillicons.dev/icons?i=html,css,js,java,git,mysql,csharp,php,python,wordpress&theme=dark" />
      </div>
    </section>

    <section class="fade-in-up px-5 py-10">
      <h2 class="text-2xl text-cyan-400 font-semibold mb-4 text-center">📬 Contact</h2>
      <ul class="text-center text-white space-y-2">
        <li>📧 <a href="mailto:metablendorg.info@gmail.com" class="text-cyan-300 hover:underline">metablendorg.info@gmail.com</a></li>
        <li>🔗 <a href="https://www.linkedin.com/in/muditha-bathiya-liyanage" target="_blank" class="text-cyan-300 hover:underline">LinkedIn</a></li>
        <li>📸 <a href="https://www.instagram.com/iambathiya/" target="_blank" class="text-cyan-300 hover:underline">Instagram</a></li>
      </ul>
    </section>

    <footer class="text-center text-sm text-gray-400 py-5">
      🚀 Let’s connect and build something amazing together!
    </footer>
  </body>
</html>
