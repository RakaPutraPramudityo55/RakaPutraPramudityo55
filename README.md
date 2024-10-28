<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Pribadi Raka Putra Pramudityo</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(to right, #a8dadc, #457b9d);
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #1d3557;
            padding: 20px;
            text-align: center;
            color: white;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: #f1faee;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #e63946;
        }
        .container {
            max-width: 600px;
            width: 90%;
            margin: 20px auto;
            padding: 20px;
            background-color: #f1faee;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            border: 1px solid #ddd;
        }
        h2 {
            text-align: center;
            color: #457b9d;
            margin-bottom: 20px;
        }
        .biodata-list, .hobi-list {
            list-style: none;
            padding: 0;
        }
        .biodata-list li, .hobi-list li {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .label {
            font-weight: bold;
            color: #457b9d;
        }
        img {
            display: block;
            margin: 10px auto;
            border-radius: 8px;
            width: 100%;
            max-width: 300px; /* Maksimal lebar gambar */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        footer {
            text-align: center;
            margin-top: 20px;
            color: #1d3557;
            background-color: #f1faee;
            padding: 10px;
        }
        .contact-list {
            list-style: none;
            padding: 0;
            text-align: center;
        }
        .contact-list li {
            padding: 10px;
            font-size: 1.1em;
        }
        .icon {
            margin-right: 10px;
            color: #457b9d;
        }
    </style>
</head>
<body>

    <header>
        <h1>Biodata Pribadi</h1>
        <nav>
            <a href="#bio">Tentang Saya</a> | 
            <a href="#hobi">Hobi</a> | 
            <a href="#kontak">Kontak</a>
        </nav>
    </header>

    <div class="container" id="bio">
        <img src="fotoku.jpg" alt="Foto Profil">
        <h2>Biodata Pribadi Raka Putra Pramudityo</h2>
        <ul class="biodata-list">
            <li><span class="label">NPM:</span> 202243500353</li>
            <li><span class="label">Nama:</span> Raka Putra Pramudityo</li>
            <li><span class="label">Alamat:</span> Jl. Tanah Merdeka No. 62A</li>
            <li><span class="label">Telepon:</span> 085771678515</li>
            <li><span class="label">Agama:</span> Islam</li>
            <li><span class="label">Jenis Kelamin:</span> Laki-laki</li>
        </ul>
    </div>

    <div class="container" id="hobi">
        <h2>Hobi Saya</h2>
        <p>Saya memiliki beberapa hobi yang saya nikmati di waktu luang:</p>
        <ul class="hobi-list">
            <li>
                <img src="image_game.jpg" alt="Bermain Game">
                <strong>Bermain Game:</strong> Saya suka bermain game untuk bersantai dan bersenang-senang.
            </li>
            <li>
                <img src="image_editor.jpg" alt="Editing">
                <strong>Editor:</strong> Mengedit video dan gambar adalah salah satu hobi saya yang menyenangkan.
            </li>
            <li>
                <img src="image_healing.jpg" alt="Healing">
                <strong>Healing:</strong> Aktivitas healing membantu saya untuk merelaksasi pikiran dan tubuh.
            </li>
            <li>
                <img src="image_olahraga.jpg" alt="Olahraga">
                <strong>Olahraga:</strong> Olahraga adalah bagian penting dari gaya hidup sehat saya.
            </li>
        </ul>
    </div>

    <div class="container" id="kontak">
        <h2>Hubungi Saya</h2>
        <ul class="contact-list">
            <li><i class="fas fa-envelope icon"></i><span class="label">Email:</span> rakasahputra453@email.com</li>
            <li><i class="fas fa-phone-alt icon"></i><span class="label">Telepon:</span> 085771678515</li>
            <li><i class="fab fa-instagram icon"></i><span class="label">Instagram:</span> @wakattcha</li>
            <li><i class="fab fa-discord icon"></i><span class="label">Discord:</span> Wakattcha55</li>
            <li><i class="fab fa-youtube icon"></i><span class="label">YouTube:</span> WakattChan*-_-*</li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2024 Raka Putra Pramudityo. Semua hak cipta dilindungi.</p>
    </footer>

</body>
</html>