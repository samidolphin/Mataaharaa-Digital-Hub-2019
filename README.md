<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mataaharaa Digital Hub 2.0</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        
        /* HEADER & HERO */
        header { display: flex; justify-content: space-between; padding: 20px 5%; background: #fff; align-items: center; position: sticky; top: 0; z-index: 1000; }
        .hero { height: 60vh; background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=1600'); background-size: cover; display: flex; align-items: center; justify-content: center; color: white; text-align: center; }
        
        /* NEWS TICKER */
        .ticker { background: #ff6600; color: white; padding: 10px; overflow: hidden; white-space: nowrap; font-weight: bold; }
        .ticker-text { display: inline-block; animation: marquee 20s linear infinite; }
        @keyframes marquee { 0% { transform: translate(100%, 0); } 100% { transform: translate(-100%, 0); } }

        /* FEATURED STORIES */
        .featured-grid { display: grid; grid-template-columns: 2fr 1fr; gap: 20px; padding: 40px 5%; }
        .main-card { background: #eee; height: 400px; border-radius: 10px; }
        .side-cards { display: flex; flex-direction: column; gap: 15px; }
        .small-card { background: #f0f0f0; height: 120px; border-radius: 5px; }

        /* SAMI-TUBE & GALLERY */
        .section-title { padding: 40px 5% 20px; font-size: 24px; }
        .video-grid, .gallery-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 0 5%; }
        .card { background: #ddd; height: 200px; border-radius: 8px; }

        footer { background: #333; color: white; text-align: center; padding: 40px; margin-top: 50px; }
    </style>
</head>
<body>

    <header>
        <div>🟡 <b>SAMI DOLPHIN</b> | Mataaharaa</div>
        <nav>News | Video | Tourism | Culture | Dev | Sports</nav>
        <div>AM | OR | EN</div>
    </header>

    <section class="hero">
        <div><h1>MATAAHARAA</h1><p>The City Where the Sun Never Sets</p></div>
    </section>

    <div class="ticker">
        <div class="ticker-text">🔴 Breaking: አዲሱ የመታሃራ ከተማ አስተዳደር አዲስ የመስኖ ልማት ፕሮጀክት ይፋ አድርጓል... | በቅርቡ በየውሃ መታሃራ ታላቅ የቱሪዝም ኤግዚቢሽን ይካሄዳል...</div>
    </div>

    <h2 class="section-title">Featured Story</h2>
    <section class="featured-grid">
        <div class="main-card"></div>
        <div class="side-cards">
            <div class="small-card"></div>
            <div class="small-card"></div>
            <div class="small-card"></div>
        </div>
    </section>

    <h2 class="section-title">Sami-Tube</h2>
    <section class="video-grid">
        <div class="card"></div><div class="card"></div><div class="card"></div>
    </section>

    <footer>
        <p>© 2026 Sami Dolphin Media | Mataaharaa Digital Hub 2.0</p>
    </footer>

</body>
</html>
