<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EduSpark Academy</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#0f172a;
color:white;
}

header{
position:fixed;
width:100%;
top:0;
background:rgba(15,23,42,.9);
backdrop-filter:blur(10px);
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

.logo{
font-size:28px;
font-weight:700;
color:#38bdf8;
}

nav a{
color:white;
text-decoration:none;
margin-left:25px;
font-weight:500;
}

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:
linear-gradient(rgba(15,23,42,.8),rgba(15,23,42,.8)),
url('https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=1600&q=80');
background-size:cover;
background-position:center;
}

.hero-content h1{
font-size:4rem;
margin-bottom:20px;
}

.hero-content span{
color:#38bdf8;
}

.hero-content p{
font-size:1.2rem;
max-width:700px;
margin:auto;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:15px 35px;
background:#38bdf8;
color:#000;
text-decoration:none;
border-radius:50px;
font-weight:600;
transition:.3s;
}

.btn:hover{
transform:translateY(-5px);
}

section{
padding:100px 8%;
}

.title{
text-align:center;
font-size:2.5rem;
margin-bottom:50px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:rgba(255,255,255,.08);
backdrop-filter:blur(15px);
padding:30px;
border-radius:20px;
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card h3{
color:#38bdf8;
margin-bottom:15px;
}

.about{
text-align:center;
max-width:900px;
margin:auto;
line-height:1.8;
}

.stats{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
text-align:center;
margin-top:40px;
}

.stat{
background:rgba(255,255,255,.08);
padding:30px;
border-radius:20px;
}

.stat h2{
color:#38bdf8;
font-size:2rem;
}

.contact{
text-align:center;
}

footer{
background:#020617;
text-align:center;
padding:25px;
}

@media(max-width:768px){
.hero-content h1{
font-size:2.5rem;
}
nav{
display:none;
}
}
</style>
</head>

<body>

<header>
<div class="logo">EduSpark</div>
<nav>
<a href="#home">Home</a>
<a href="#courses">Courses</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<div class="hero-content">
<h1>Ignite Your <span>Learning Journey</span></h1>
<p>
Future-ready education platform offering industry-focused training
in Cyber Security, AI, Web Development, Cloud Computing and more.
</p>
<a href="#courses" class="btn">Explore Courses</a>
</div>
</section>

<section id="courses">
<h2 class="title">Popular Courses</h2>

<div class="cards">

<div class="card">
<h3>Cyber Security</h3>
<p>Ethical Hacking, Network Security, Penetration Testing and Digital Defense.</p>
</div>

<div class="card">
<h3>Artificial Intelligence</h3>
<p>Machine Learning, Deep Learning and AI-powered applications.</p>
</div>

<div class="card">
<h3>Web Development</h3>
<p>HTML, CSS, JavaScript, React and Full Stack Development.</p>
</div>

<div class="card">
<h3>Python Programming</h3>
<p>Learn Python from beginner to advanced with practical projects.</p>
</div>

<div class="card">
<h3>Cloud Computing</h3>
<p>AWS, Azure and Google Cloud fundamentals with real projects.</p>
</div>

<div class="card">
<h3>Data Science</h3>
<p>Data Analysis, Visualization and Predictive Analytics.</p>
</div>

</div>
</section>

<section id="about">
<h2 class="title">About EduSpark Academy</h2>

<div class="about">
<p>
EduSpark Academy is a modern educational platform dedicated to helping
students build future-ready skills. We provide expert-led training,
hands-on projects, certifications and career guidance to prepare learners
for real-world success.
</p>

<div class="stats">
<div class="stat">
<h2>10K+</h2>
<p>Students</p>
</div>

<div class="stat">
<h2>100+</h2>
<p>Courses</p>
</div>

<div class="stat">
<h2>95%</h2>
<p>Success Rate</p>
</div>

<div class="stat">
<h2>50+</h2>
<p>Expert Mentors</p>
</div>
</div>

</div>
</section>

<section id="contact">
<h2 class="title">Contact Us</h2>

<div class="contact">
<p>Email: info@edusparkacademy.com</p>
<br>
<p>Phone: +91 9876543210</p>
<br>
<a href="#" class="btn">Enroll Today</a>
</div>

</section>

<footer>
<p>© 2026 EduSpark Academy. All Rights Reserved.</p>
</footer>

</body>
</html>
