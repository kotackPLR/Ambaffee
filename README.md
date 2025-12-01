# Ambaffee
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ambaffee</title>
<style>
    body {
        font-family: 'Segoe UI', sans-serif;
        margin: 0;
        padding: 0;
        background: #fdf6f0;
        color: #3e2c1c;
    }
    header {
        background: #6b4f3f;
        color: #fff;
        text-align: center;
        padding: 2rem 1rem;
        background-image: url('https://images.unsplash.com/photo-1511920170033-f8396924c348?fit=crop&w=1200&q=80');
        background-size: cover;
        background-position: center;
        position: relative;
    }
    header::after {
        content: "";
        position: absolute;
        top: 0; left: 0;
        width: 100%; height: 100%;
        background: rgba(107,79,63,0.6);
    }
    header h1 {
        position: relative;
        margin: 0;
        font-size: 2.5rem;
    }
    nav {
        display: flex;
        justify-content: center;
        gap: 2rem;
        padding: 1rem 0;
        background: #8c5e3c;
    }
    nav a {
        color: #fff;
        text-decoration: none;
        font-weight: bold;
    }
    section {
        padding: 2rem 1rem;
        max-width: 900px;
        margin: auto;
    }
    h2 {
        text-align: center;
        margin-bottom: 1.5rem;
        color: #6b4f3f;
    }
    .menu {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 1rem;
    }
    .menu-item {
        background: #fff8f0;
        padding: 1rem;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        text-align: center;
        transition: transform 0.2s;
    }
    .menu-item:hover {
        transform: scale(1.05);
    }
    .menu-item img {
        max-width: 100%;
        border-radius: 10px;
        margin-bottom: 0.5rem;
    }
    footer {
        text-align: center;
        padding: 1rem 0;
        background: #6b4f3f;
        color: #fff;
        margin-top: 2rem;
    }
    @media(max-width: 600px) {
        .menu {
            grid-template-columns: 1fr;
        }
    }
</style>
</head>
<body>

<header>
    <h1>CAmbaffee</h1>
</header>

<nav>
    <a href="#about">Tentang</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Kontak</a>
</nav>

<section id="about">
    <h2>Tentang Kami</h2>
    <p>Ambaffee hadir untuk pecinta kopi dengan suasana nyaman dan pilihan kopi terbaik. Nikmati espresso, latte, cappuccino, dan menu spesial kami. Tempatnya cozy, cocok buat nongkrong sambil santai.</p>
</section>

<section id="menu">
    <h2>Menu Unggulan</h2>
    <div class="menu">
        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?fit=crop&w=400&q=80" alt="Espresso">
            <h3>Espresso</h3>
            <p>Rp15.000</p>
        </div>
        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348?fit=crop&w=400&q=80" alt="Latte">
            <h3>Latte</h3>
            <p>Rp20.000</p>
        </div>
        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1521305916504-4a1121188589?fit=crop&w=400&q=80" alt="Cappuccino">
            <h3>Cappuccino</h3>
            <p>Rp20.000</p>
        </div>
        <div class="menu-item">
            <img src="https://images.unsplash.com/photo-1510626176961-4bfc3c3c0b5c?fit=crop&w=400&q=80" alt="Americano">
            <h3>Americano</h3>
            <p>Rp18.000</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Kontak</h2>
    <p>📍 Jl. muani No. 123, Kota jomokkerto</p>
    <p>📞 0831-3845-0450</p>
    <p>💌 Ambaffee@email.com</p>
</section>

<footer>
    &copy; 2025 Ambaffee
</footer>

</body>
</html>
