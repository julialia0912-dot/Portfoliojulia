<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio Djulia</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
body{background:linear-gradient(to bottom,#d99595,#dfb6c1);color:#333;}
.container{width:90%;margin:auto;}
header{background:rgba(228,199,199,.9);backdrop-filter:blur(10px);padding:15px 0;position:sticky;top:0;z-index:100;}
.nav{display:flex;justify-content:space-between;align-items:center;}
.logo{color:#e76f8a;font-weight:bold;}
nav a{margin:0 10px;text-decoration:none;color:#555;transition:.3s;}
nav a:hover{color:#e76f8a;}
.btn{background:linear-gradient(45deg,#e76f8a,#ff9eb5);color:#fff;border:none;padding:10px 18px;border-radius:25px;cursor:pointer;transition:.3s;}
.btn:hover{transform:scale(1.05);}
.btn-outline{border:1px solid #e76f8a;color:#e76f8a;padding:10px 18px;border-radius:25px;background:transparent;cursor:pointer;transition:.3s;}
.btn-outline:hover{background:#e76f8a;color:#fff;}
.hero{height:90vh;background:linear-gradient(rgba(255,255,255,.7),rgba(255,255,255,.9)),url("foto.jpg.jpeg") center/cover;display:flex;align-items:center;}
.hero-content{display:flex;justify-content:space-between;align-items:center;}
.hero h1{font-size:50px;color:#e76f8a;}
.hero h3{font-size:22px;}
.hero .desc{margin:15px 0;max-width:500px;}
.hero img{width:320px;border-radius:20px;box-shadow:0 10px 30px rgba(0,0,0,.1);}
.about{display:flex;gap:40px;margin:80px auto;align-items:center;}
.about img{width:220px;border-radius:20px;}
.about-text h2,.skills h2,.project h2{color:#e76f8a;margin-bottom:20px;}
.about-info{margin-top:20px;}
.about-info div,.skill-box div{background:#fff;padding:10px;border-radius:10px;margin-bottom:10px;box-shadow:0 5px 15px rgba(0,0,0,.05);}
.skills,.project{margin:60px auto;text-align:center;}
.skill-box{display:flex;justify-content:center;gap:15px;flex-wrap:wrap;}
.skill-box div{padding:20px;min-width:120px;transition:.3s;}
.skill-box div:hover,.card:hover{transform:translateY(-5px);}
.project-box{display:flex;gap:20px;justify-content:center;}
.card{background:#fff;padding:15px;border-radius:15px;width:280px;box-shadow:0 10px 25px rgba(0,0,0,.05);transition:.3s;}
.card img{width:100%;border-radius:10px;}
.contact{background:linear-gradient(45deg,#fdf2f5,#ffe4ec);padding:30px;margin-top:60px;}
.contact-box{display:flex;justify-content:space-around;text-align:center;}
footer{text-align:center;padding:15px;background:#e76f8a;color:#e0bebe;}
</style>
</head>
<body>
<header><div class="container nav"><h2 class="logo">Djulia</h2><nav><a href="#">Home</a><a href="#">Tentang</a><a href="#">Skill</a><a href="#">Project</a><a href="#">Kontak</a></nav><button class="btn">Download CV</button></div></header>
<section class="hero"><div class="container hero-content"><div class="text"><h3>Halo, Saya</h3><h1>Djulia</h1><p>Mahasiswa Bisnis Digital | Kreatif | Analitis</p><p class="desc">Saya adalah mahasiswa Bisnis Digital yang tertarik pada dunia teknologi, digital marketing, dan pengembangan web.</p><div><button class="btn">Hubungi Saya</button> <button class="btn-outline">Lihat Project</button></div></div><div class="image"><img src="fotojulia.jpg.jpeg" alt="foto"></div></div></section>
<section class="about container"><div><img src="foto.jpg.jpeg"></div><div class="about-text"><h2>Tentang Saya</h2><p>Saya merupakan mahasiswa program studi Bisnis Digital yang memiliki minat besar dalam bidang teknologi, pemasaran digital, dan desain. Saya senang belajar hal baru dan bekerja dalam tim.</p><div class="about-info"><div>🎓 Mahasiswa Bisnis Digital</div><div>💡 Kreatif & Teknologi</div><div>🎯 Fokus Hasil</div></div></div></section>
<section class="skills container"><h2>Skill</h2><div class="skill-box"><div>Digital Marketing</div><div>Database</div><div>Canva</div><div>Microsoft Office</div></div></section>
<section class="project container"><h2>Project</h2><div class="project-box"><div class="card"><img src="https://via.placeholder.com/300"><h3>Website Sederhana</h3><p>Membuat website e-commerce sederhana menggunakan HTML dan CSS</p><button class="btn-outline">Lihat Detail</button></div><div class="card"><img src="https://via.placeholder.com/300"><h3>Desain Branding</h3><p>Membuat desain logo dan konsep brand</p><button class="btn-outline">Lihat Detail</button></div></div></section>
<section class="contact"><div class="container contact-box"><p>📧 julialia0912@email.com</p><p>📱 0881-0237-48746</p><p>📍 Indonesia</p></div></section>
<footer><p>© 2026 Julia Lia | All Rights Reserved</p></footer>
</body></html>
