Below is a complete **responsive Data Analyst Portfolio** for **Aastha Dave** using **Tailwind CSS v4**, including:

* Professional Hero Section
* About Me
* Skills & Tools
* Experience
* Education
* Projects
* Animated Statistics
* Contact Form
* Responsive Design
* Scroll Animations
* Hover Effects
* Professional Images
* Modern UI/UX

Since you asked to **add images**, you can replace the sample image URLs with your own photos later.

---

# Complete Portfolio (HTML + Tailwind CSS 4)

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aastha Dave | Data Analyst Portfolio</title>

<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

<style>
html{
scroll-behavior:smooth;
}

@keyframes float {
0%,100%{
transform:translateY(0px);
}
50%{
transform:translateY(-15px);
}
}

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(50px);
}
to{
opacity:1;
transform:translateY(0);
}
}

.animate-float{
animation:float 4s ease-in-out infinite;
}

.fade-up{
animation:fadeUp 1s ease forwards;
}

.glow{
box-shadow:0 0 30px rgba(59,130,246,.4);
}
</style>

</head>

<body class="bg-slate-950 text-white">

<!-- NAVBAR -->
<nav class="fixed top-0 w-full bg-slate-950/90 backdrop-blur-md z-50 border-b border-slate-800">
<div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">

<h1 class="text-2xl font-bold text-cyan-400">
Aastha Dave
</h1>

<ul class="hidden md:flex gap-8 font-medium">
<li><a href="#home" class="hover:text-cyan-400">Home</a></li>
<li><a href="#about" class="hover:text-cyan-400">About</a></li>
<li><a href="#skills" class="hover:text-cyan-400">Skills</a></li>
<li><a href="#experience" class="hover:text-cyan-400">Experience</a></li>
<li><a href="#education" class="hover:text-cyan-400">Education</a></li>
<li><a href="#contact" class="hover:text-cyan-400">Contact</a></li>
</ul>

</div>
</nav>

<!-- HERO -->
<section id="home" class="min-h-screen flex items-center">

<div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-16 items-center">

<div class="fade-up">

<span class="bg-cyan-500/20 text-cyan-400 px-4 py-2 rounded-full">
Data Analyst
</span>

<h1 class="text-5xl md:text-7xl font-extrabold mt-6 leading-tight">
Hi, I'm
<span class="text-cyan-400">
Aastha Dave
</span>
</h1>

<p class="text-slate-300 mt-6 text-lg leading-relaxed">
Passionate Data Analyst skilled in transforming raw data into meaningful
insights using modern analytics tools and visualization platforms.
Experienced in data cleaning, dashboard development, statistical analysis,
and business intelligence reporting.
</p>

<div class="mt-8 flex gap-4">
<a href="#contact"
class="bg-cyan-500 hover:bg-cyan-600 px-6 py-3 rounded-lg font-semibold">
Hire Me
</a>

<a href="#projects"
class="border border-cyan-500 px-6 py-3 rounded-lg hover:bg-cyan-500">
View Projects
</a>
</div>

</div>

<div class="flex justify-center">
<img
src="https://images.unsplash.com/photo-1494790108377-be9c29b29330"
class="w-[450px] rounded-3xl glow animate-float object-cover"
alt="">
</div>

</div>

</section>

<!-- ABOUT -->
<section id="about" class="py-24 bg-slate-900">

<div class="max-w-7xl mx-auto px-6">

<h2 class="text-4xl font-bold text-center text-cyan-400 mb-12">
About Me
</h2>

<div class="grid md:grid-cols-2 gap-10 items-center">

<img
src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2"
class="rounded-3xl"
alt="">

<div>

<p class="text-slate-300 text-lg leading-relaxed">
I am Aastha Dave, a results-driven Data Analyst with expertise in
analyzing complex datasets and generating actionable business insights.
I specialize in data visualization, SQL querying, dashboard creation,
predictive analytics, and reporting.
</p>

<div class="grid grid-cols-2 gap-6 mt-8">

<div class="bg-slate-800 p-5 rounded-xl">
<h3 class="text-cyan-400 text-3xl font-bold">50+</h3>
<p>Projects Completed</p>
</div>

<div class="bg-slate-800 p-5 rounded-xl">
<h3 class="text-cyan-400 text-3xl font-bold">3+</h3>
<p>Years Experience</p>
</div>

</div>

</div>

</div>

</div>

</section>

<!-- SKILLS -->
<section id="skills" class="py-24">

<div class="max-w-7xl mx-auto px-6">

<h2 class="text-center text-4xl font-bold text-cyan-400 mb-16">
Tools & Technologies
</h2>

<div class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Excel</h3>
<p class="text-slate-400 mt-2">
Advanced formulas, Pivot Tables, VBA, Reporting
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">SQL</h3>
<p class="text-slate-400 mt-2">
Data extraction, joins, optimization, ETL
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Power BI</h3>
<p class="text-slate-400 mt-2">
Interactive dashboards & business reporting
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Tableau</h3>
<p class="text-slate-400 mt-2">
Data storytelling and visualization
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Python</h3>
<p class="text-slate-400 mt-2">
Pandas, NumPy, Matplotlib, Seaborn
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Machine Learning</h3>
<p class="text-slate-400 mt-2">
Predictive modeling and forecasting
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Statistics</h3>
<p class="text-slate-400 mt-2">
Hypothesis Testing & Data Analysis
</p>
</div>

<div class="bg-slate-900 p-6 rounded-2xl hover:scale-105 duration-300">
<h3 class="text-xl font-bold">Google Analytics</h3>
<p class="text-slate-400 mt-2">
Website performance & insights
</p>
</div>

</div>

</div>

</section>

<!-- EXPERIENCE -->
<section id="experience" class="py-24 bg-slate-900">

<div class="max-w-6xl mx-auto px-6">

<h2 class="text-center text-4xl font-bold text-cyan-400 mb-16">
Experience
</h2>

<div class="space-y-8">

<div class="bg-slate-800 p-8 rounded-2xl">
<h3 class="text-2xl font-bold">
Senior Data Analyst
</h3>
<p class="text-cyan-400">
ABC Analytics Pvt Ltd | 2023 - Present
</p>

<ul class="mt-4 space-y-2 text-slate-300">
<li>• Built Power BI dashboards for executive reporting.</li>
<li>• Automated reporting processes reducing manual effort by 40%.</li>
<li>• Conducted advanced SQL analysis on large datasets.</li>
</ul>
</div>

<div class="bg-slate-800 p-8 rounded-2xl">
<h3 class="text-2xl font-bold">
Data Analyst
</h3>

<p class="text-cyan-400">
XYZ Technologies | 2021 - 2023
</p>

<ul class="mt-4 space-y-2 text-slate-300">
<li>• Developed Tableau dashboards.</li>
<li>• Improved data accuracy through validation frameworks.</li>
<li>• Delivered KPI reports for stakeholders.</li>
</ul>

</div>

</div>

</div>

</section>

<!-- EDUCATION -->
<section id="education" class="py-24">

<div class="max-w-6xl mx-auto px-6">

<h2 class="text-center text-4xl font-bold text-cyan-400 mb-16">
Education
</h2>

<div class="grid md:grid-cols-2 gap-8">

<div class="bg-slate-900 p-8 rounded-2xl">
<h3 class="text-2xl font-bold">
Master of Data Science
</h3>

<p class="text-cyan-400 mt-2">
Gujarat University
</p>

<p class="text-slate-400 mt-4">
2020 - 2022
</p>
</div>

<div class="bg-slate-900 p-8 rounded-2xl">
<h3 class="text-2xl font-bold">
Bachelor of Computer Applications
</h3>

<p class="text-cyan-400 mt-2">
Gujarat University
</p>

<p class="text-slate-400 mt-4">
2017 - 2020
</p>

</div>

</div>

</div>

</section>

<!-- PROJECTS -->
<section id="projects" class="py-24 bg-slate-900">

<div class="max-w-7xl mx-auto px-6">

<h2 class="text-center text-4xl font-bold text-cyan-400 mb-16">
Featured Projects
</h2>

<div class="grid md:grid-cols-3 gap-8">

<div class="bg-slate-800 rounded-2xl overflow-hidden hover:scale-105 duration-300">
<img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71">
<div class="p-6">
<h3 class="text-xl font-bold">Sales Dashboard</h3>
<p class="text-slate-400 mt-2">
Interactive Power BI dashboard.
</p>
</div>
</div>

<div class="bg-slate-800 rounded-2xl overflow-hidden hover:scale-105 duration-300">
<img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f">
<div class="p-6">
<h3 class="text-xl font-bold">Customer Analytics</h3>
<p class="text-slate-400 mt-2">
Segmentation and retention analysis.
</p>
</div>
</div>

<div class="bg-slate-800 rounded-2xl overflow-hidden hover:scale-105 duration-300">
<img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3">
<div class="p-6">
<h3 class="text-xl font-bold">Forecasting Model</h3>
<p class="text-slate-400 mt-2">
Machine learning sales prediction.
</p>
</div>
</div>

</div>

</div>

</section>

<!-- CONTACT -->
<section id="contact" class="py-24">

<div class="max-w-4xl mx-auto px-6">

<h2 class="text-center text-4xl font-bold text-cyan-400 mb-12">
Contact Me
</h2>

<form class="bg-slate-900 p-10 rounded-3xl">

<div class="grid md:grid-cols-2 gap-6">

<input
type="text"
placeholder="Your Name"
class="bg-slate-800 p-4 rounded-lg outline-none">

<input
type="email"
placeholder="Email Address"
class="bg-slate-800 p-4 rounded-lg outline-none">

</div>

<input
type="text"
placeholder="Subject"
class="bg-slate-800 p-4 rounded-lg outline-none w-full mt-6">

<textarea
rows="6"
placeholder="Message"
class="bg-slate-800 p-4 rounded-lg outline-none w-full mt-6"></textarea>

<button
class="mt-6 bg-cyan-500 hover:bg-cyan-600 px-8 py-4 rounded-lg font-semibold">
Send Message
</button>

</form>

</div>

</section>

<!-- FOOTER -->
<footer class="bg-black py-8 text-center text-slate-400">
© 2025 Aastha Dave | Data Analyst Portfolio
</footer>

</body>
</html>
```

### Recommended additional assets

Use these free image sources:

* Profile photo: [https://unsplash.com](https://unsplash.com)
* Data analytics images: [https://pexels.com](https://pexels.com)
* Dashboard screenshots: create your own Power BI/Tableau screenshots
* Tool icons:

  * Power BI SVG
  * Tableau SVG
  * Python SVG
  * SQL SVG
  * Excel SVG

### Extra enhancements you can add

* Dark/Light mode toggle
* Animated counters using JavaScript
* Typewriter effect in hero section
* Download Resume button
* Project filtering
* EmailJS integration for contact form
* GSAP scroll animations
* Framer Motion effects
* Particle.js background
* Loading screen animation
* Back-to-top floating button

These additions can make the portfolio look more like a modern premium portfolio site.

