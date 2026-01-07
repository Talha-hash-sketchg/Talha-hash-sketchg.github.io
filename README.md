<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Talha Salman | Portfolyo</title>
    <style>
        /* Sayfanın genel ayarları */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            min-height: 100vh;
            /* İstediğin 4 köşeli renkli arka plan */
            background: 
                radial-gradient(circle at top left, rgba(128, 0, 128, 0.7), transparent 50%),
                radial-gradient(circle at top right, rgba(255, 255, 0, 0.6), transparent 50%),
                radial-gradient(circle at bottom left, rgba(255, 0, 0, 0.7), transparent 50%),
                radial-gradient(circle at bottom right, rgba(0, 0, 255, 0.7), transparent 50%);
            background-color: #0f0f0f; /* Renklerin birleştiği orta kısım için koyu tema */
            background-attachment: fixed;
            line-height: 1.6;
        }

        /* Menü çubuğu */
        nav {
            display: flex;
            justify-content: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.2);
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #ffeb3b; /* Fareyle üzerine gelince sarı olur */
        }

        /* Ana başlık bölümü */
        #hero {
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .highlight {
            color: #ffeb3b;
            text-shadow: 2px 2px 10px rgba(255, 235, 59, 0.5);
        }

        /* Bölüm ayarları */
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            backdrop-filter: blur(10px); /* Modern buzlu cam efekti */
            border: 1px solid rgba(255, 255, 255, 0.1);
            text-align: center;
        }

        h2 {
            margin-bottom: 20px;
            border-bottom: 2px solid rgba(255, 255, 255, 0.2);
            display: inline-block;
            padding-bottom: 5px;
        }

        /* Yetenek kartları */
        .skills-grid {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .skill-card {
            background: rgba(0, 0, 0, 0.3);
            padding: 15px 25px;
            border-radius: 8px;
            font-weight: bold;
            letter-spacing: 1px;
            border: 1px solid #ffeb3b;
        }

        /* Alt kısım */
        footer {
            text-align: center;
            padding: 40px;
            margin-top: 50px;
            background: rgba(0, 0, 0, 0.4);
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#about">Hakkımda</a></li>
                <li><a href="#skills">Yetenekler</a></li>
                <li><a href="#contact">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Merhaba, Ben <span class="highlight">Talha</span></h1>
        <p>Arduino kodlama ve teknoloji bağımlısıyım.</p>
        <p>En yakın arkadaşım Mirza ile projeler geliştiriyorum!</p>
    </section>

    <section id="about" class="container">
        <h2>Hakkımda</h2>
        <p>Ben Osmaniye Bahçe'de yaşayan bir 6. sınıf öğrencisiyim. <br> 
        Elektronik parçalarla oynamayı ve yeni kodlar yazmayı çok seviyorum.</p>
    </section>

    <section id="skills" class="container">
        <h2>Yeteneklerim</h2>
        <div class="skills-grid">
            <div class="skill-card">ARDUINO</div>
            <div class="skill-card">KODLAMA</div>
            <div class="skill-card">ELEKTRONİK</div>
        </div>
    </section>

    <footer id="contact">
        <h2>İletişim</h2>
        <p>📧 talhasalman1402@gmail.com</p>
        <p><strong>TALHA SALMAN</strong></p>
    </footer>

</body>
</html>
 
