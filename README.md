<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <title>Sate Ayam Berkah Ilahi</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #0f100f;
            background-color: #f4f5db;
        }
        header {
            background-color: #027e23;
            color: rgba(255, 255, 255, 0);
            text-align: center;
            padding: 20px;
        }
        .logo img {
            width: 100px;
            height: auto;
        }
        .cta-button {
            background-color: #048b04;
            color: rgba(253, 245, 245, 0.954);
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
            display: inline-block;
            transition: background-color 0.3s;
        }
        .cta-button:hover {
            background-color: #0c0404;
        }
        .keunggulan, .menu, #contact, .galeri {
            padding: 20px;
            text-align: center;
        }
        .keunggulan-container, .menu-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .keunggulan-item, .menu-item {
            border: 1px solid #690c0c;
            border-radius: 5px;
            padding: 15px;
            margin: 10px;
            width: 30%;
            box-shadow: 0 2px 5px rgba(234, 133, 18, 0.945);
            transition: transform 0.3s;
        }
        .keunggulan-item:hover, .menu-item:hover {
            transform: scale(1.05);
        }
        .order-button {
            background-color: #c0392b;
            color: rgb(252, 253, 254);
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            transition: background-color 0.3s;
        }
        .order-button:hover {
            background-color: #e74c3c;
        }
        footer {
            background-color: #333;
            color: rgb(239, 237, 245);
            text-align: center;
            padding: 15px 0;
        }
        #map {
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo-placeholder.png" alt="Logo Sate Ayam Berkah Ilahi">
        </div>
        <h1>Sate Ayam Berkah Ilahi</h1>
        <p>Cita Rasa Khas Racikan Pak De Ali, Bumbunya Meresap Sampai ke Hati!</p>
        <a href="https://wa.me/6285875490915" class="cta-button">Pesan Sekarang via WhatsApp</a>
    </header>

    <section class="keunggulan">
        <h2>Kenapa Sate Pak De Ali Juara?</h2>
        <div class="keunggulan-container">
            <div class="keunggulan-item">
                <h3>Bumbu Rahasia Legendaris</h3>
                <p>Resep warisan keluarga yang membuat setiap gigitan begitu istimewa.</p>
            </div>
            <div class="keunggulan-item">
                <h3>100% Daging Ayam Segar</h3>
                <p>Kami hanya menggunakan daging ayam pilihan berkualitas terbaik setiap hari.</p>
            </div>
            <div class="keunggulan-item">
                <h3>Bumbu Kacang Melimpah</h3>
                <p>Saus kacang kental, gurih, dan sedikit pedas yang bikin ketagihan.</p>
            </div>
        </div>
    </section>

    <section class="menu">
        <h2>Pilih Menu Favoritmu</h2>
        <div class="menu-container">
            <div class="menu-item">
                <h3>Sate Ayam</h3>
                <a href="https://wa.me/6285875490915" class="order-button">Pesan</a>
            </div>
            <div class="menu-item">
                <h3>Sate Ayam + Lontong</h3>
                <a href="https://wa.me/6285875490915" class="order-button">Pesan</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Kontak & Lokasi</h2>
        <p>Hubungi kami untuk pemesanan atau tanya-tanya langsung.</p>
        <div id="map">
            <!-- Google Maps Embed -->
            <iframe src="https://www.google.com/maps/embed?pb=YOUR_MAP_EMBED_LINK" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </section>

    <section class="galeri">
        <h2>Dapur Pak De Ali</h2>
        <img src="file:///C:/Users/ACER/Downloads/al.jpeg" alt="Dapur Pak De Ali">
        <div class="galeri-container">
            <!-- Galeri images can be added here -->
        </div>
    </section>

    <footer>
        <p>Lokasi: Warung Sate Berkah Ilahi, Jln. Pasar Rebek, Curug, Kedungbokor, Brebes</p>
        <p>Jam Buka: Buka Setiap Hari: 15.00 - 22.00 WIB</p>
        <p>© 2025 Sate Ayam Berkah Ilahi. Dibuat dengan ❤️.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
