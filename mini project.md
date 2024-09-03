<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Pribadi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            text-align: center;
        }
        header {
            background-color: #82e947;
            color: white;
            padding: 20px;
        }
        .container {
            padding: 20px;
        }
        img.profile {
            border-radius: 50%;
            max-width: 150px;
            height: auto;
        }
        .social-links {
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            color: #4CAF50;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Halo, Saya Adhiyaksha Danar K </h1>
    </header>
    <div class="container">
        <img src="image.jpeg.jpg" alt="gambar saya" alt="Foto Profil" class="profile">
        <p>Selamat datang di halaman profil pribadi saya! Saya seorang lulusan dari Universitas Diponegoro Fakultas Hukum,meskipun saya lulusan dari hukum tapi saya tertarik untuk menjadi web developer yang profesional terutama di bidang Frontend Developers dan saya suka hobi fotografi berupa Black&White.</p>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/adhiyaksha-danar-karendrarswara-17049531b/" target="_blank">linkedin</a>
            <a href="https://www.instagram.com/ethanmiles00/" target="_blank">instagram</a>
        </div>
    </div>
    <h2>Kontak Saya</h2>
<form action="mailto:emailkamu@example.com" method="post" enctype="text/plain">
    <label for="name">Nama:</label>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>
    
    <label for="message">Pesan:</label><br>
    <textarea id="message" name="message" rows="4" required></textarea><br><br>
    
    <input type="submit" value="Kirim">
    <input type="reset" value="Reset">
</form>
    <footer>
        &copy; 2024 Adhyaksha Danar K
    </footer>
</body>
</html>
