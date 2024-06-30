<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h3>M. Yanuar kasanudin</h1>
            <p>Seorang pria lugu yang yang baik hati dan Desainer Grafis yang bersemangat.</p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#about">Tentang Saya</a></li>
            <li><a href="#skills">Keahlian</a></li>
            <li><a href="#projects">Proyek</a></li>
            <li><a href="#contact">Kontak</a></li>
        </ul>
    </nav>
    <section id="about">
        <div class="container">
            <h2>Tentang Saya</h2>
            <div class="about-content">
            
<p><img src="kasan05.png" alt="Foto Saya">
<br>
<br>
<br>
 Saya adalah seorang pengembang grafik
     serta animasi. Saya tertarik pada
     desain grafis, animasi, dan selalu
     berusaha untuk belajar teknologi baru.</p>
        </div>
    </section>
    <section id="skills">
        <div class="container">
            <h2>Keahlian</h2>
            <ul>
                <li>Design grafis</li>
                <li>Animasi sederhana</li></li>
            </ul>
        </div>
    </section>
    <section id="projects">
        <div class="container">
            <h2>Proyek</h2>
            <div class="project">
                <h3>Sistem Manajemen Konten</h3>
                <p>Saya mengembangkan sistem manajemen konten (CMS) untuk akun saya, yang memungkinkan saya untuk mengelola konten situs web dengan mudah dan efisien.</p>
            </div>
             <div class="project">
                <h3>Berikut Beberapa Design Saya</h3>
                <div class="about-content01">
                <p>
                    <img src="kasan04.png" alt="Foto Saya">
                    <img src="kasan02.png" alt="Foto Saya">
             <!--       <img src="kasan03.png" alt="Foto Saya"> -->
                     <img src="kasan06.png" alt="Foto Saya">
                    
                    
                    
                    
                    </p>
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Kontak</h2>
<p>Email: <a href="mailto:kasankacink49.com">kasankacink49.com</a></p>
<p>Telepon:
<a href="tel:+6285887274544">+62 8588-7274-544</a></p>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2024 muhammad yanuar kasanudin.</p>
        </div>
    </footer>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    color: #89C2C4;
    margin: 0;
    padding: 0;
    background-color: #123031;
}

header {
    background-color: #333;
    color: #89C2C4;
    padding: 20px 0;
    text-align: center;
}

nav {
    background-color: #255C5F;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    text-align: center;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: #89C2C4;
    padding: 10px 15px;
    display: inline-block;
}

nav ul li a:hover {
    background-color: #123031;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px 0;
}

section {
    margin: 20px 0;
    background-color: #255C5F;
    padding: 20px;
    border-radius: 4%;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

section h2 {
    margin-top: 0;
}
.about-content {
    display: flex;
    align-items: flex-start;
}
.about-content img {
    max-width: 30%;
    width: 100%;
    height: auto;
    margin-right: 5px;
    margin-left: 95px;
    border-radius: 40%;
}


.about-content01 {
    display: flex;
    align-items: flex-start;
}
.about-content01 img {
    max-width: 100%;
    width: 100%;
    height: auto;
    margin-right: 5%;
    margin-left: 5%;
    border-radius: 20%;
}
}
.
.about-content p {
    flex: 3;
}


