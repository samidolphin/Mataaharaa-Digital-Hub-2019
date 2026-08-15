<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mataaharaa Digital Hub 2.0</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { background-color: #f9f9f9; color: #333; line-height: 1.6; }

        /* Header */
        header { display: flex; justify-content: space-between; padding: 20px 5%; background: #fff; align-items: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        nav { font-weight: bold; cursor: pointer; }
        
        /* Hero */
        .hero { height: 60vh; background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=1600') center/cover; display: flex; align-items: center; justify-content: center; color: white; text-align: center; }
        .hero h1 { font-size: 3.5rem; }

        /* News Ticker */
        .ticker { background: #ff6600; color: white; padding: 12px; overflow: hidden; white-space: nowrap; font-weight: bold; }
        .ticker-text { display: inline-block; animation: marquee 25s linear infinite; }
        @keyframes marquee { 0% { transform: translate(100%, 0); } 100% { transform: translate(-100%, 0); } }

        /* Content Sections */
        .section-title { padding: 40px 5% 20px; font-size: 24px; color: #111; }
        .featured-grid { display: grid; grid-template-columns: 2fr 1fr; gap: 20px; padding: 0 5%; }
        .main-card { height: 400px; border-radius: 10px; display: flex; align-items: flex-end; padding: 20px; color: white; background: linear-gradient(rgba(0,0,0,0.1), rgba(0,0,0,0.8)), url('https://upload.wikimedia.org/wikipedia/commons/e/e0/Lake_Beseka.jpg') center/cover; }
        .side-cards { display: flex; flex-direction: column; gap: 15px; }
        .small-card { padding: 15px; border-left: 4px solid #ff6600; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); cursor: pointer; }

        /* Gallery */
        .gallery-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); gap: 15px; padding: 0 5%; }
        .gallery-item { position: relative; height: 250px; border-radius: 10px; overflow: hidden; }
        .gallery-item img { width: 100%; height: 100%; object-fit: cover; transition: 0.5s; }
        .gallery-item:hover img { transform: scale(1.1); }
        .gallery-item span { position: absolute; bottom: 10px; left: 10px; background: rgba(0,0,0,0.6); color: white; padding: 5px 10px; border-radius: 5px; }

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
        <div class="ticker-text">🔴 Breaking News: የመታሃራ ከተማ አስተዳደር አዲስ የልማት ፕሮጀክት ይፋ አድርጓል! | በቅርቡ በየውሃ መታሃራ ታላቅ የቱሪዝም ኤግዚቢሽን ይካሄዳል!</div>
    </div>

    <h2 class="section-title">የመታሃራ ትኩረት</h2>
    <section class="featured-grid">
        <div class="main-card"><h3>የበሰቃ ሐይቅ የልማት ፕሮጀክት ተጀመረ</h3></div>
        <div class="side-cards">
            <div class="small-card"><h5>Mount Fentale የወደፊት እቅድ</h5></div>
            <div class="small-card"><h5>የከተማዋ የግብርና ዘመናዊነት</h5></div>
            <div class="small-card"><h5>የኢትዮ-ጅቡቲ ባቡር መስመር</h5></div>
        </div>
    </section>

    <h2 class="section-title">የቱሪዝም መስህቦች</h2>
    <section class="gallery-grid">
        <div class="gallery-item"><img src="https://images.unsplash.com/photo-1542273917363-3b1817f69a2d?w=800" alt="Lake"><span>Lake Beseka</span></div>
        <div class="gallery-item"><img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=800" alt="Mount"><span>Mount Fentale</span></div>
        <div class="gallery-item"><img src="https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05?w=800" alt="Orchards"><span>Local Orchards</span></div>
        <div class="gallery-item"><img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?w=800" alt="Railway"><span>Railway Station</span></div>
    </section>

    <footer>
        <p>© 2026 Sami Dolphin Media | Mataaharaa Digital Hub 2.0</p>
    </footer>

</body>
</html>
