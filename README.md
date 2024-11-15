<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Warkop numani</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
   <style>
   .gallery {
  padding: 50px 20px;
  background-color: #fff;
  text-align: center;
}

.gallery h2 {
  font-size: 2.5rem;
  color: #2a2a2a;
  margin-bottom: 40px;
}

.gallery-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
  justify-items: center;
}

.gallery-item {
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.gallery-item img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.gallery-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
}

.gallery-item img:hover {
  transform: scale(1.05);
}
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
      }
      
      body {
        background-color: #f9f9f9;
        color: #333;
        line-height: 1.6;
        font-size: 16px;
      }
      
      header {
        background: linear-gradient(45deg, #3a2c39, #a15c55);
        padding: 1.5rem 0;
      }
      
      nav ul {
        list-style: none;
        display: flex;
        justify-content: center;
        gap: 30px;
      }
      
      nav ul li {
        margin: 0;
      }
      
      nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 1.1rem;
        font-weight: 600;
        text-transform: uppercase;
        transition: color 0.3s ease;
      }
      
      nav ul li a:hover {
        color: #ffd700;
      }
      
      .hero {
        background: url('kopi-hero.jpg') no-repeat center center/cover;
        color: white;
        text-align: center;
        padding: 150px 20px;
        position: relative;
      }
      
      .hero:before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.4);
      }
      
      .hero-content {
        position: relative;
        z-index: 1;
      }
      
      .hero h1 {
        font-size: 3.5rem;
        font-weight: 600;
        margin-bottom: 15px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
      }
      
      .hero p {
        font-size: 1.3rem;
        margin-bottom: 30px;
        font-weight: 300;
      }
      
      .btn {
        background-color: #ffd700;
        padding: 12px 30px;
        font-size: 1.2rem;
        text-decoration: none;
        color: #2a2a2a;
        border-radius: 30px;
        font-weight: 500;
        letter-spacing: 1px;
        transition: background-color 0.3s ease, transform 0.2s ease;
      }
      
      .btn:hover {
        background-color: #ffb300;
        transform: scale(1.1);
      }
      
      .menu {
        padding: 50px 20px;
        background-color: #fff;
        text-align: center;
      }
      
      .menu h2 {
        font-size: 2.5rem;
        color: #2a2a2a;
        margin-bottom: 40px;
      }
      
      .menu-items {
        display: flex;
        justify-content: center;
        gap: 20px;
      }
      
      .menu-item {
        background-color: #fafafa;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        width: 280px;
        text-align: center;
      }
      
      .menu-item:hover {
        transform: translateY(-10px);
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
      }
      
      .menu-item img {
        width: 100%;
        border-radius: 8px;
        transition: transform 0.3s ease;
      }
      
      .menu-item img:hover {
        transform: scale(1.05);
      }
      
      .menu-item h3 {
        margin-top: 15px;
        font-size: 1.6rem;
        font-weight: 500;
        color: #333;
      }
      
      .menu-item p {
        font-size: 1.2rem;
        color: #555;
      }
      
      .contact {
        background-color: #3a2c39;
        color: white;
        padding: 60px 20px;
        text-align: center;
      }
      
      .contact h2 {
        font-size: 2.5rem;
        margin-bottom: 25px;
      }
      
      .contact p {
        font-size: 1.2rem;
        margin-bottom: 25px;
      }
      
      .contact ul {
        list-style: none;
      }
      
      .contact ul li {
        margin: 10px 0;
        font-size: 1.1rem;
      }
      
      footer {
        background-color: #2a2a2a;
        color: white;
        padding: 20px;
        text-align: center;
      }
      
      footer p {
        font-size: 1rem;
        margin: 0;
      }
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
      }
      
      body {
        background-color: #f9f9f9;
        color: #333;
        line-height: 1.6;
        font-size: 16px;
      }
      
      header {
        background: linear-gradient(45deg, #3a2c39, #a15c55);
        padding: 1.5rem 0;
      }
      
      nav ul {
        list-style: none;
        display: flex;
        justify-content: center;
        gap: 30px;
      }
      
      nav ul li {
        margin: 0;
      }
      
      nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 1.1rem;
        font-weight: 600;
        text-transform: uppercase;
        transition: color 0.3s ease;
      }
      
      nav ul li a:hover {
        color: #ffd700;
      }
      
      .hero {
        background: url('kopi-hero.jpg') no-repeat center center/cover;
        color: white;
        text-align: center;
        padding: 150px 20px;
        position: relative;
      }
      
      .hero:before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.4);
      }
      
      .hero-content {
        position: relative;
        z-index: 1;
      }
      
      .hero h1 {
        font-size: 3.5rem;
        font-weight: 600;
        margin-bottom: 15px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
      }
      
      .hero p {
        font-size: 1.3rem;
        margin-bottom: 30px;
        font-weight: 300;
      }
      
      .btn {
        background-color: #ffd700;
        padding: 12px 30px;
        font-size: 1.2rem;
        text-decoration: none;
        color: #2a2a2a;
        border-radius: 30px;
        font-weight: 500;
        letter-spacing: 1px;
        transition: background-color 0.3s ease, transform 0.2s ease;
      }
      
      .btn:hover {
        background-color: #ffb300;
        transform: scale(1.1);
      }
      
      .menu {
        padding: 50px 20px;
        background-color: #fff;
        text-align: center;
      }
      
      .menu h2 {
        font-size: 2.5rem;
        color: #2a2a2a;
        margin-bottom: 40px;
      }
      
      .menu-items {
        display: flex;
        justify-content: center;
        gap: 20px;
      }
      
      .menu-item {
        background-color: #fafafa;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        width: 280px;
        text-align: center;
      }
      
      .menu-item:hover {
        transform: translateY(-10px);
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
      }
      
      .menu-item img {
        width: 100%;
        border-radius: 8px;
        transition: transform 0.3s ease;
      }
      
      .menu-item img:hover {
        transform: scale(1.05);
      }
      
      .menu-item h3 {
        margin-top: 15px;
        font-size: 1.6rem;
        font-weight: 500;
        color: #333;
      }
      
      .menu-item p {
        font-size: 1.2rem;
        color: #555;
      }
      
      .contact {
        background-color: #3a2c39;
        color: white;
        padding: 60px 20px;
        text-align: center;
      }
      
      .contact h2 {
        font-size: 2.5rem;
        margin-bottom: 25px;
      }
      
      .contact p {
        font-size: 1.2rem;
        margin-bottom: 25px;
      }
      
      .contact ul {
        list-style: none;
      }
      
      .contact ul li {
        margin: 10px 0;
        font-size: 1.1rem;
      }
      
      footer {
        background-color: #2a2a2a;
        color: white;
        padding: 20px;
        text-align: center;
      }
      
      footer p {
        font-size: 1rem;
        margin: 0;
      }
      .div1{
      background-position-x: ;
      }
      iframe{
        border-radius: 50px;
        margin-top: 10px;
      }
 

</style>      
  <!-- Navbar -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">Beranda</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#contact">Kontak</a></li>
        <li><a href="#lokasi">lokasi</a></li>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Selamat Datang di Warkop Hangat</h1>
      <p>Nikmati secangkir kopi hangat dan suasana yang nyaman.</p>
      <a href="#menu" class="btn">Lihat Menu</a>
    </div>
  </section>

  <!-- Menu Section -->
  <section id="menu" class="menu">
    <img src=""c:\Users\Haris\.vscode\img\background 3 senja.jbg.jpg
    <h2>Best seller</h2>
    <div class="menu-items">
      <div class="menu-item">

        <h3>Kopi hijau</h3>
        <p>Rp 5.000</p>
      </div>
      <div class="menu-item">
        <h3>Kopi racik</h3>
        <p>Rp 3.500</p>
      </div>
      <div class="menu-item">
        <h3>wedang jahe</h3>
        <p>Rp 4.000</p>
      </div>
    </div>
    dan banyak menu lainya langsung saja datang dan rasakan sensasi kopi ternikmat<p>"bisa lihat lokasi di bawah"</p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Kontak Kami</h2>
    <p>Hubungi kami untuk pertanyaan atau pemesanan:</p>
    <ul>
      <li>Telepon: 0812-1773-8800</li>
      <li>Alamat: Banjar Sari, Kec. Bandarkedungmulyo, Kabupaten Jombang, Jawa Timur</li>
    </ul>
  </section>

  <!-- Footer -->

  <section id="gallery" class="gallery">
    <h2>Galeri</h2>
    <div class="gallery-container">
      <div class="gallery-item">
        <img src="MOBIL.JBG.jpeg" alt="Foto 1">
      </div>
      <div class="gallery-item">
        <img src="MALAM.JBG.jpeg" alt="Foto 2">
      </div>
      <div class="gallery-item">
        <img src="SENJA.JBG.jpeg">
      </div>
      <div class="gallery-item">
        <img src="NOBAR.JBG.jpeg" alt="Foto 4">
      </div>
      <!-- Add more items as needed -->
    </div>
  </section>
</body>
</html>
<CENTER><H2>LOKASI</H2></CENTER>
<div id="lokasi" class="map-container">
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d620.0937006701072!2d112.15458871005042!3d-7.560610479233137!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e7840b7ff0110d1%3A0xbbc9bf5bbde2823c!2sKspps%20Bmt%20Nu%20Jombang!5e0!3m2!1sid!2sid!4v1730836568972!5m2!1sid!2sid" 
    width="620" 
    height="200" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
  <footer>
    <p>&copy; warkop numani@2024.</p>
  </footer>
</div>
