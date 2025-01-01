
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Ana Sayfa</title>
    <style>
        /* Genel stil ayarları */
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Üst kısım */
        .header {
            display: flex;
            justify-content: flex-end;
            padding: 10px 20px;
            background-color: #f2f2f2;
        }

        .header img {
            width: 30px;
            height: 30px;
            border-radius: 50%; /* Fotoğrafın kenarlarını yuvarlama */
        }

        /* Logo ve arama alanı */
        .logo {
            margin: 50px auto 20px;
        }

        .search-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
        }

        .search-container input[type="text"] {
            width: 480px;
            height: 40px;
            border: none;
            border-radius: 20px;
            padding: 0 15px;
            box-shadow: 0 1px 6px rgba(32, 33, 36, 0.28);
            font-size: 16px;
            outline: none;
        }

        .search-container .search-icon {
            position: absolute;
            top: 50%;
            left: 10px;
            transform: translateY(-50%);
            width: 20px;
            height: 20px;
        }

        .search-container .voice-icon {
            position: absolute;
            top: 50%;
            right: 10px;
            transform: translateY(-50%);
            width: 20px;
            height: 20px;
        }

        /* Butonlar */
        .buttons {
            margin: 20px 0;
        }

        .buttons button {
            background-color: #f8f9fa;
            border: 1px solid #f2f2f2;
            border-radius: 4px;
            font-size: 14px;
            color: #5f6368;
            padding: 10px 20px;
            margin: 5px;
            cursor: pointer;
            box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
        }

        .buttons button:hover {
            background-color: #f1f3f4;
        }

        /* Alt kısım */
        footer {
            background-color: #f2f2f2;
            padding: 20px;
            margin-top: 50px;
        }

        footer ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        footer ul li {
            font-size: 14px;
        }

        footer ul li a {
            text-decoration: none;
            color: #5f6368;
        }
    </style>
</head>
<body>
    <!-- Üst kısım -->
    <div class="header">
        <img src="your-photo.jpg" alt="Profil Fotoğrafı">
    </div>

    <!-- Logo -->
    <div class="logo">
        <img src="google-logo.png" alt="Google Logo" width="300">
    </div>

    <!-- Arama alanı -->
    <div class="search-container">
        <img src="search-icon.png" alt="Arama Simgesi" class="search-icon">
        <input type="text" placeholder="Google'da Ara">
        <img src="voice-icon.png" alt="Sesli Arama" class="voice-icon">
    </div>

    <!-- Butonlar -->
    <div class="buttons">
        <button>Google'da Ara</button>
        <button>Kendimi Şanslı Hissediyorum</button>
    </div>

    <!-- Footer -->
    <footer>
        <ul>
            <li><a href="#">Hakkında</a></li>
            <li><a href="#">Reklam</a></li>
            <li><a href="#">İş</a></li>
            <li><a href="#">Gizlilik</a></li>
            <li><a href="#">Şartlar</a></li>
        </ul>
    </footer>
</body>
</html>
