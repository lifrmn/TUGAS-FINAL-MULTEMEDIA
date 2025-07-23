Program Pertama

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wisata Kebun Gowa</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #4caf50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #388e3c;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      margin-bottom: 20px;
      color: #2e7d32;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    .yt-video {
      margin-top: 20px;
      display: flex;
      justify-content: center;
    }
    .yt-video iframe {
      width: 100%;
      max-width: 800px;
      height: 450px;
      border: none;
      border-radius: 10px;
    }
    ul li {
      margin-bottom: 10px;
    }
    footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    iframe.map {
      width: 100%;
      height: 300px;
      border: 0;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Wisata Kebun Gowa</h1>
    <p>Tempat Rekreasi dan Edukasi Keluarga di Gowa</p>
  </header>

  <nav>
    <a href="#beranda">Beranda</a>
    <a href="#galeri">Galeri</a>
    <a href="#informasi">Informasi</a>
    <a href="#video">Video</a>
    <a href="#lokasi">Lokasi</a>
  </nav>

  <section class="section" id="beranda">
    <h2>Beranda</h2>
    <p>Wisata Kebun Gowa merupakan tempat wisata yang menggabungkan konsep agrowisata dan rekreasi keluarga. Tersedia berbagai fasilitas menarik seperti kolam renang, kebun buah, wahana anak-anak, dan restoran keluarga. Kunjungan kami disusun dalam bentuk video yang dapat diakses melalui tugas mata kuliah Pemrograman Multimedia.</p>
  </section>

  <section class="section" id="galeri">
    <h2>Galeri Foto</h2>
    <div class="gallery">
      <img src="https://salsawisata.com/wp-content/uploads/2022/11/pemancingan-Wisata-Kebun-Gowa.jpg" alt="Kolam Pancing">
      <img src="https://salsawisata.com/wp-content/uploads/2022/11/waterboom-Wisata-Kebun-Gowa.jpg" alt="Kolam Renang">
      <img src="https://salsawisata.com/wp-content/uploads/2022/11/playground-Wisata-Kebun-Gowa.jpg" alt="Wahana Anak">
      <img src="dokumentasi wisata.jpg" alt="Dokumentasi Wisata">
    </div>
  </section>

  <section class="section" id="informasi">
    <h2>Informasi Wisata</h2>
    <ul>
      <li><strong>Jam Operasional:</strong> 08.00 – 17.00 WITA</li>
      <li><strong>Harga Tiket:</strong> Rp 15.000 (Weekday), Rp 25.000 (Weekend)</li>
      <li><strong>Fasilitas:</strong> Kolam Renang, Kebun Buah, Wahana Anak, Kolam Pancing, Gazebo, Restoran, Mushola, Area Parkir</li>
      <li><strong>Alamat:</strong> Jl. Malino, Bontomanai, Kec. Bontomarannu, Kab. Gowa</li>
    </ul>
  </section>

  <section class="section" id="video">
    <h2>Video Review</h2>
    <p>Berikut adalah video review Wisata Kebun Gowa yang telah kami unggah di YouTube:</p>
    <div class="yt-video">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID" title="YouTube video player" allowfullscreen></iframe>
    </div>
  </section>

  <section class="section" id="lokasi">
    <h2>Lokasi</h2>
    <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d997.6725521121943!2d119.4788269695518!3d-5.238256998864251!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dbefc51d5aa2c3f%3A0xf6bb7fc82bc34c89!2sWisata%20Kebun%20Gowa!5e0!3m2!1sen!2sid!4v1655557779796" allowfullscreen=""></iframe>
  </section>

  <footer>
    <p>&copy; 2025 Kelompok 1 - Pemrograman Multimedia</p>
  </footer>
</body>
</html>

Program Kedua