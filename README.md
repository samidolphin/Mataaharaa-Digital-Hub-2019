<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mataaharaa Digital Hub 2.0</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
        }

        /* --- Header Section --- */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 5%;
            background: #ffffff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo-area {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo-icon {
            font-size: 24px;
        }

        .logo-text h2 {
            font-size: 18px;
            color: #111;
            font-weight: 700;
            letter-spacing: 0.5px;
        }

        .logo-text span {
            font-size: 12px;
            color: #666;
            display: block;
        }

        nav.nav-links {
            display: flex;
            gap: 25px;
        }

        nav.nav-links a {
            text-decoration: none;
            color: #444;
            font-weight: 500;
            font-size: 14px;
            transition: color 0.3s;
        }

        nav.nav-links a:hover {
            color: #ff6600;
        }

        .header-utils {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .search-btn {
            background: none;
            border: none;
            font-size: 18px;
            cursor: pointer;
            color: #444;
        }

        .lang-selector {
            font-size: 13px;
            font-weight: 600;
            color: #555;
        }

        .lang-selector span {
            cursor: pointer;
            padding: 2px 5px;
            transition: color 0.2s;
        }

        .lang-selector span:hover {
            color: #ff6600;
        }

        /* --- Hero Section --- */
        .hero {
            height: 75vh;
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            font-weight: 700;
            letter-spacing: 2px;
            margin-bottom: 10px;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }

        .hero-content p {
            font-size: 1.2rem;
            font-weight: 300;
            letter-spacing: 1px;
            color: #f1f1f1;
        }

        /* --- Responsive Design --- */
        @media(max-width: 900px) {
            nav.nav-links {
                display: none; /* በኋላ ለ Mobile Menu እንሰራዋለን */
            }
            .hero-content h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <header>
        <div class="logo-area">
            <span class="logo-icon">🟡</span>
            <div class="logo-text">
                <h2>SAMI DOLPHIN</h2>
                <span>መታሃራ / Mataaharaa</span>
            </div>
        </div>

        <nav class="nav-links">
            <a href="#news">News</a>
            <a href="#video">Video</a>
            <a href="#tourism">Tourism</a>
            <a href="#culture">Culture</a>
            <a href="#dev">Development</a>
            <a href="#sports">Sports</a>
        </nav>

        <div class="header-utils">
            <button class="search-btn" title="Search">🔍</button>
            <div class="lang-selector">
                <span onclick="changeLang('am')">AM</span> | 
                <span onclick="changeLang('or')">OR</span> | 
                <span onclick="changeLang('en')">EN</span>
            </div>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="hero">
        <div class="hero-content">
            <h1>MATAAHARAA</h1>
            <p>The City Where the Sun Never Sets</p>
        </div>
    </section>

    <script>
        function changeLang(lang) {
            // ለቀጣዩ የቋንቋ ዝግጅት የሚሆን ፋንክሽን
            console.log("Language changed to: " + lang);
        }
    </script>
</body>
</html>
