<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Gowtham D | Digital Marketing Portfolio</title>

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #0b0b0b;
    color: white;
    line-height: 1.6;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 22px 8%;
    background: #111;
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-size: 25px;
    font-weight: bold;
    color: #d4af37;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
    font-size: 14px;
}

nav a:hover {
    color: #d4af37;
}

section {
    padding: 90px 10%;
}

.hero {
    min-height: 90vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
}

.hero h1 {
    font-size: 55px;
    margin-bottom: 15px;
}

.hero h1 span {
    color: #d4af37;
}

.hero h3 {
    color: #d4af37;
    margin-bottom: 20px;
}

.hero p {
    color: #bbb;
    max-width: 550px;
}

.btn {
    display: inline-block;
    background: #d4af37;
    color: black;
    padding: 13px 28px;
    margin-top: 25px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.btn:hover {
    background: white;
}

.heading {
    font-size: 35px;
    text-align: center;
    margin-bottom: 40px;
}

.heading span {
    color: #d4af37;
}

.about p {
    color: #bbb;
    max-width: 850px;
    margin: auto;
    text-align: center;
}

.skills-container,
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background: #171717;
    padding: 30px;
    border-radius: 10px;
    border: 1px solid #333;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
    border-color: #d4af37;
}

.card h3 {
    color: #d4af37;
    margin-bottom: 12px;
}

.card p {
    color: #bbb;
}

.experience {
    max-width: 800px;
    margin: auto;
}

.experience .card {
    margin-bottom: 20px;
}

.contact {
    text-align: center;
}

.contact p {
    color: #bbb;
    margin: 12px;
}

footer {
    text-align: center;
    padding: 25px;
    background: #111;
    color: #aaa;
}

@media(max-width: 768px) {

    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        margin: 7px;
        display: inline-block;
    }

    .hero {
        text-align: center;
        justify-content: center;
    }

    .hero h1 {
        font-size: 38px;
    }

    section {
        padding: 65px 6%;
    }
}

</style>
</head>

<body>

<header>

<div class="logo">GOWTHAM D.</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#experience">Experience</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

</header>

<!-- HOME -->

<section class="hero" id="home">

<div>

<h3>WELCOME TO MY PORTFOLIO</h3>

<h1>Hi, I'm <span>Gowtham D</span></h1>

<h3>Digital Marketing Professional</h3>

<p>
MBA Graduate with practical experience in Digital Marketing,
SEO, Google Ads, Meta Ads and Social Media Marketing.
Passionate about helping businesses grow through digital strategies.
</p>

<a href="#contact" class="btn">Contact Me</a>

</div>

</section>

<!-- ABOUT -->

<section class="about" id="about">

<h2 class="heading">About <span>Me</span></h2>

<p>
I am Gowtham D, an MBA graduate with a strong interest in
Digital Marketing and business growth strategies.

I completed a six-month Digital Marketing internship at
WHY Global Services, where I gained practical experience
in SEO, Google Ads, Meta Ads, Social Media Marketing
and Content Creation.

Additionally, I have 1 year and 6 months of professional
experience as a Data Entry Executive at FCS Pvt. Ltd.
I developed skills in data management, documentation
and record maintenance.

I am passionate about digital marketing, online brand
development and performance-driven marketing strategies.
My goal is to contribute to business growth while
continuously developing my professional skills.
</p>

</section>

<!-- SKILLS -->

<section id="skills">

<h2 class="heading">My <span>Skills</span></h2>

<div class="skills-container">

<div class="card">
<h3>SEO</h3>
<p>Keyword Research, On-Page SEO, Off-Page SEO and Website Optimization.</p>
</div>

<div class="card">
<h3>Google Ads</h3>
<p>Campaign Setup, Keyword Planning and Search Advertising.</p>
</div>

<div class="card">
<h3>Meta Ads</h3>
<p>Facebook Advertising, Instagram Ads and Campaign Management.</p>
</div>

<div class="card">
<h3>Social Media</h3>
<p>Social Media Management, Content Planning and Engagement.</p>
</div>

<div class="card">
<h3>Content Creation</h3>
<p>Creative Content, Canva Designs and Marketing Copywriting.</p>
</div>

<div class="card">
<h3>Analytics</h3>
<p>Google Analytics and Google Search Console.</p>
</div>

</div>

</section>

<!-- EXPERIENCE -->

<section id="experience">

<h2 class="heading">Work <span>Experience</span></h2>

<div class="experience">

<div class="card">

<h3>Digital Marketing Intern</h3>

<p><strong>WHY Global Services</strong></p>

<p>Duration: 6 Months</p>

<p>
Worked on SEO, Google Ads, Meta Ads, Social Media Marketing
and Digital Content Creation.
</p>

</div>

<div class="card">

<h3>Data Entry Executive</h3>

<p><strong>Fluoro Carbon Seals Pvt. Ltd.</strong></p>

<p>Duration: 1 Year and 8 Months</p>

<p>
Handled data management, company records,
documentation, dispatch reporting and data accuracy.
</p>

</div>

</div>

</section>

<!-- PROJECTS -->

<section id="projects">

<h2 class="heading">My <span>Projects</span></h2>

<div class="projects-container">

<div class="card">

<h3>GM Sports Shop</h3>

<p>
E-commerce Digital Marketing Project.
Worked on website content, SEO keyword research,
Google Ads planning and social media promotions.
</p>

</div>

<div class="card">

<h3>Social Media Marketing</h3>

<p>
Created social media content ideas,
marketing creatives and promotional campaigns.
</p>

</div>

<div class="card">

<h3>SEO Practice</h3>

<p>
Practiced keyword research, website optimization,
SEO content writing and Google Search Console.
</p>

</div>

</div>

</section>

<!-- CONTACT -->

<section class="contact" id="contact">

<h2 class="heading">Contact <span>Me</span></h2>

<p>Email: YOUR EMAIL ADDRESS</p>

<p>Phone: YOUR PHONE NUMBER</p>

<p>Location: Chennai, Tamil Nadu</p>

<p>
LinkedIn:
<a href="https://www.linkedin.com/in/gowtham-d-972007417/"
style="color:#d4af37">
View My LinkedIn
</a>
</p>

<a href="mailto:YOUR EMAIL ADDRESS" class="btn">
Hire Me
</a>

</section>

<footer>

<p>© <span id="year"></span> Gowtham D. All Rights Reserved.</p>

<p>Digital Marketing Portfolio</p>

</footer>

<script>
document.getElementById("year").textContent =
new Date().getFullYear();
</script>

</body>
</html>
