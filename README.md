<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bapaknya Pisang - Pisang Goreng Coklat Keju</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdfde3;
        }
        header {
            background-color: #f4a261;
            color: white;
            padding: 1rem 0;
            text-align: center;
            position: relative;
        }
        header img {
            position: absolute;
            top: 10px;
            left: 10px;
            height: 50px;
            width: auto;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2a9d8f;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 2rem;
            background-color: #e9c46a;
            color: #333;
        }
        .hero img {
            max-width: 100%;
            height: auto;
        }
        .section {
            padding: 2rem;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .product {
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 1rem;
            text-align: center;
            width: 200px;
            background-color: #fff;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/50" alt="Logo Bapaknya Pisang">
        <h1>Bapaknya Pisang</h1>
        <p>Spesialis Pisang Goreng Coklat Keju</p>
    </header>

    <nav>
        <a href="#tentang">Tentang</a>
        <a href="#produk">Produk</a>
        <a href="#kontak">Kontak</a>
    </nav>

    <section class="hero">
        <h2>Lezat, Gurih, dan Manis</h2>
        <img src="https://via.placeholder.com/800x400" alt="Pisang Goreng Coklat Keju">
        <p>Pisang goreng dengan topping coklat dan keju terbaik untuk Anda!</p>
    </section>

    <section id="tentang" class="section">
        <h2>Tentang Kami</h2>
        <p>Bapaknya Pisang adalah usaha lokal dari Tangerang yang menyediakan pisang goreng berkualitas tinggi dengan topping pilihan seperti coklat, keju, dan lainnya. Kami berkomitmen memberikan rasa terbaik dengan bahan berkualitas.</p>
    </section>

    <section id="produk" class="section">
        <h2>Produk Kami</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Pisang Goreng Coklat">
                <h3>Pisang Goreng Coklat</h3>
                <p>Rp 15.000 / porsi</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Pisang Goreng Keju">
                <h3>Pisang Goreng Keju</h3>
                <p>Rp 17.000 / porsi</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200" alt="Pisang Goreng Coklat Keju">
                <h3>Pisang Goreng Coklat Keju</h3>
                <p>Rp 20.000 / porsi</p>
            </div>
        </div>
    </section>

    <section id="kontak" class="section">
        <h2>Kontak Kami</h2>
        <p>📞 <strong>0812-3456-7890</strong></p>
        <p>📧 <strong>bapakyapisang@gmail.com</strong></p>
        <p>📍 <strong>Tangerang, Indonesia</strong></p>
        <p>🌐 <a href="https://tokopedia.com/bapaknya_pisang" target="_blank">Tokopedia: Bapaknya Pisang</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Bapaknya Pisang. All rights reserved.</p>
    </footer>
</body>
</html>
