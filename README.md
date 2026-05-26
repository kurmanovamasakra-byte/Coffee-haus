<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title id="meta-title">Coffee Haus | Premium Late-Night Dessert, Coffee Lounge & Takeout</title>
    <meta id="meta-desc" name="description" content="Experience Coffee Haus in Schaumburg & South Elgin. An upscale, cozy lounge featuring artisan espresso, handcrafted bubble tea, and fresh signature Belgium Liège waffles. Available for dine-in or quick takeout open daily until midnight.">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://yourcustomdomain.com/">
    
    <meta property="og:type" content="website">
    <meta property="og:title" content="Coffee Haus | Premium Late-Night Dessert Lounge & Takeout">
    <meta property="og:description" content="A beautiful late-night dessert lounge space open daily until midnight. Perfect for a cozy dine-in experience or quick premium takeout to-go.">
    <meta property="og:image" content="https://yourcustomdomain.com/assets/branding/og-cover.jpg">

    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Bakery",
      "name": "Coffee Haus",
      "image": "https://yourcustomdomain.com/assets/branding/logo.png",
      "url": "https://yourcustomdomain.com",
      "telephone": "+18477551233",
      "priceRange": "$$",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "209 W. Golf Rd.",
        "addressLocality": "Schaumburg",
        "addressRegion": "IL",
        "postalCode": "60195",
        "addressCountry": "US"
      },
      "openingHoursSpecification": {
        "@type": "OpeningHoursSpecification",
        "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"],
        "opens": "11:00",
        "closes": "24:00"
      }
    }
    </script>

    <style>
        /* --- CORE VISUAL STYLE AND BRANDING PACKAGE SYSTEM --- */
        :root {
            --espresso: #2B1B17;
            --oatmilk: #F9F6F0;
            --matcha: #8F9E7B;
            --charcoal: #333333;
            --warm-cream: #EFE9DB;
            --bubbletea-blue: #D0E1F9;
            --smoothie-pink: #F3D1DC;
            --font-serif: 'Georgia', serif;
            --font-sans: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: var(--font-sans); line-height: 1.6; background-color: var(--oatmilk); color: var(--charcoal); overflow-x: hidden; }
        h1, h2, h3, h4 { color: var(--espresso); font-family: var(--font-serif); }
        .container { width: 92%; max-width: 1200px; margin: 0 auto; }

        /* --- STICKY NAVIGATION SYSTEM --- */
        header { background-color: var(--espresso); padding: 15px 0; position: sticky; top: 0; z-index: 1000; box-shadow: 0 4px 12px rgba(0,0,0,0.15); }
        nav { display: flex; justify-content: space-between; align-items: center; }
        .logo-group { display: flex; align-items: center; text-decoration: none; cursor: pointer; }
        .brand-logo-hook { height: 45px; width: auto; margin-right: 12px; border-radius: 50%; background-color: var(--matcha); padding: 5px; transition: transform 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); }
        .logo-group:hover .brand-logo-hook { transform: rotate(360deg) scale(1.1); }
        .logo-text { color: var(--oatmilk); font-size: 26px; font-weight: bold; font-family: var(--font-serif); letter-spacing: 1.5px; }
        .nav-links { display: flex; list-style: none; align-items: center; }
        .nav-links li { margin-left: 25px; }
        .nav-links a { color: var(--oatmilk); text-decoration: none; font-size: 16px; font-weight: 500; transition: color 0.3s; cursor: pointer; position: relative; padding-bottom: 4px; }
        .nav-links a:hover, .nav-links a.active { color: var(--matcha); }
        .nav-links a::after { content: ''; position: absolute; left: 0; bottom: 0; width: 0; height: 2px; background-color: var(--matcha); transition: width 0.3s ease; }
        .nav-links a:hover::after, .nav-links a.active::after { width: 100%; }

        /* --- MULTI-PAGE SPA VIEW CONTROLLER SYSTEM --- */
        .page-view { display: none; min-height: 80vh; opacity: 0; transform: translateY(20px); transition: opacity 0.5s ease, transform 0.5s cubic-bezier(0.16, 1, 0.3, 1); }
        .page-view.active-view { display: block; opacity: 1; transform: translateY(0); }

        /* --- FLEXIBLE SERVICE BANNER STRIP --- */
        .dine-in-banner { background-color: var(--matcha); color: white; text-align: center; padding: 12px 10px; font-weight: bold; font-size: 14px; letter-spacing: 0.5px; box-shadow: inset 0 -2px 5px rgba(0,0,0,0.05); position: relative; z-index: 10; animation: pulseBanner 4s infinite ease-in-out; }
        @keyframes pulseBanner { 0%, 100% { background-color: var(--matcha); } 50% { background-color: #7A8B66; } }

        /* --- HOME HERO DASHBOARD WITH MOTION CONTROLS --- */
        .hero-viewport { position: relative; overflow: hidden; background-color: var(--espresso); }
        .hero { 
            position: relative;
            background: linear-gradient(rgba(43,27,23,0.78), rgba(43,27,23,0.78)), url('https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&q=80&w=1600') no-repeat center center/cover; 
            padding: 140px 0; 
            text-align: center; 
            color: var(--oatmilk);
            transition: transform 0.1s ease-out;
            will-change: transform;
        }
        .hero-content { position: relative; z-index: 2; }
        .hero h1 { color: var(--oatmilk); font-size: 52px; margin-bottom: 25px; letter-spacing: -0.5px; animation: fadeInUp 0.8s ease forwards; }
        .hero p { font-size: 20px; max-width: 750px; margin: 0 auto 35px; color: #E0DCD3; font-weight: 300; animation: fadeInUp 1s ease forwards; }
        
        .btn { display: inline-block; padding: 14px 32px; text-decoration: none; font-weight: bold; border-radius: 4px; transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1); border: none; font-size: 15px; cursor: pointer; position: relative; overflow: hidden; z-index: 1; }
        .btn-primary { background-color: var(--matcha); color: white; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .btn-primary:hover { background-color: #7A8B66; transform: translateY(-3px); box-shadow: 0 6px 15px rgba(143,158,123,0.4); }
        .btn-secondary { background-color: transparent; color: var(--oatmilk); border: 2px solid var(--oatmilk); margin-left: 15px; }
        .btn-secondary:hover { background-color: var(--oatmilk); color: var(--espresso); transform: translateY(-3px); box-shadow: 0 6px 15px rgba(255,255,255,0.15); }
        .btn:active { transform: translateY(-1px); }

        /* --- LAYOUT WRAPPERS & UTILITIES --- */
        .section-padding { padding: 90px 0; }
        .section-title { text-align: center; font-size: 38px; margin-bottom: 50px; color: var(--espresso); }
        .section-title::after { content: ''; display: block; width: 0; height: 3px; background-color: var(--matcha); margin: 12px auto 0; transition: width 0.6s cubic-bezier(0.16, 1, 0.3, 1); }
        .active-view .section-title::after { width: 70px; }
        
        .grid-3 { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 35px; margin-top: 20px; }
        
        /* CARD MICRO-MOVEMENT ENGINE */
        .feature-card { background-color: white; padding: 45px 35px; border-radius: 6px; box-shadow: 0 4px 20px rgba(0,0,0,0.03); border: 1px solid rgba(0,0,0,0.02); text-align: center; transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0 4px cubic-bezier(0.16, 1, 0.3, 1); opacity: 0; transform: translateY(30px); }
        .active-view .feature-card { opacity: 1; transform: translateY(0); }
        .active-view .feature-card:nth-child(1) { transition-delay: 0.1s; }
        .active-view .feature-card:nth-child(2) { transition-delay: 0.2s; }
        .active-view .feature-card:nth-child(3) { transition-delay: 0.3s; }
        .feature-card:hover { transform: translateY(-8px); box-shadow: 0 12px 30px rgba(43,27,23,0.08); }
        .feature-card .icon { font-size: 45px; display: block; margin-bottom: 20px; transition: transform 0.3s ease; }
        .feature-card:hover .icon { transform: scale(1.15) rotate(5deg); }
        .feature-card h3 { margin-bottom: 15px; font-size: 22px; }

        /* --- MENU BOARD STYLING WITH SMOOTH FADE STAGGER --- */
        .menu-layout-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(360px, 1fr)); gap: 35px; }
        .menu-category-block { background-color: white; padding: 30px; border-radius: 8px; box-shadow: 0 5px 15px rgba(0,0,0,0.03); border-top: 6px solid var(--espresso); height: fit-content; transition: transform 0.4s ease, box-shadow 0.4s ease; opacity: 0; transform: scale(0.95); }
        .active-view .menu-category-block { opacity: 1; transform: scale(1); }
        .menu-category-block:hover { transform: translateY(-4px); box-shadow: 0 8px 25px rgba(0,0,0,0.06); }
        .menu-category-block.blue-accent { border-top-color: #5B84B1; }
        .menu-category-block.pink-accent { border-top-color: #E2A4B4; }
        
        .category-header { display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 15px; border-bottom: 2px solid var(--oatmilk); padding-bottom: 8px; }
        .category-header h3 { font-size: 24px; letter-spacing: -0.5px; }
        .size-legend-label { font-size: 13px; font-weight: 600; color: #777; font-family: var(--font-sans); }
        .category-subheader-label { font-size: 12px; font-weight: bold; color: #888; text-transform: uppercase; margin-top: -10px; margin-bottom: 15px; letter-spacing: 0.5px; }

        .menu-item-row { margin: 16px 0; padding: 2px 4px; border-radius: 4px; transition: background-color 0.2s ease; }
        .menu-item-row:hover { background-color: var(--oatmilk); }
        .item-main-line { display: flex; justify-content: space-between; align-items: baseline; font-weight: 700; font-size: 16px; color: var(--espresso); }
        .item-dots-separator { flex-grow: 1; border-bottom: 1px dotted #ccc; margin: 0 10px; position: relative; top: -4px; }
        .item-price-values { font-family: monospace; font-size: 15px; font-weight: bold; color: var(--espresso); }
        .item-desc-text { font-size: 13px; color: #666; margin-top: 3px; font-weight: 400; line-height: 1.4; }

        .nested-flavor-pool { background-color: var(--oatmilk); padding: 12px; border-radius: 4px; font-size: 13px; margin: 12px 0; border-left: 3px solid var(--matcha); line-height: 1.5; color: #444; transition: border-left-color 0.3s; }
        .menu-item-row:hover + .nested-flavor-pool, .nested-flavor-pool:hover { border-left-color: var(--espresso); }
        .menu-addon-footer-box { background-color: #F0EDE6; padding: 12px 15px; border-radius: 4px; font-size: 12px; margin-top: 15px; color: #555; border: 1px solid rgba(0,0,0,0.03); }

        /* --- ABOUT SPACE LAYOUT SLIDERS --- */
        .about-split { display: flex; align-items: center; gap: 60px; }
        .about-content-side { flex: 1; opacity: 0; transform: translateX(-30px); transition: opacity 0.6s ease, transform 0.6s ease; }
        .about-graphic-side { flex: 1; position: relative; opacity: 0; transform: translateX(30px); transition: opacity 0.6s ease, transform 0.6s ease; }
        .active-view .about-content-side, .active-view .about-graphic-side { opacity: 1; transform: translateX(0); transition-delay: 0.1s; }
        .about-content-side h3 { font-size: 26px; margin-bottom: 15px; }
        .about-content-side p { font-size: 17px; line-height: 1.8; color: #444; margin-bottom: 20px; }
        .about-img-frame { width: 100%; height: 450px; object-fit: cover; border-radius: 8px; box-shadow: 0 10px 30px rgba(0,0,0,0.08); transition: transform 0.5s ease; }
        .about-graphic-side:hover .about-img-frame { transform: scale(1.02) rotate(0.5deg); }

        /* --- CONTACT LOCATION PANELS --- */
        .location-matrix-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(340px, 1fr)); gap: 40px; }
        .location-profile-card { background: white; padding: 35px; border-radius: 8px; box-shadow: 0 5px 20px rgba(0,0,0,0.03); border: 1px solid var(--warm-cream); transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1); }
        .location-profile-card:hover { transform: translateY(-4px); }
        .location-profile-card h3 { font-size: 24px; margin-bottom: 20px; position: relative; padding-bottom: 8px; }
        .location-profile-card h3::after { content: ''; position: absolute; left: 0; bottom: 0; width: 40px; height: 2px; background-color: var(--matcha); transition: width 0.3s ease; }
        .location-profile-card:hover h3::after { width: 80px; }
        .info-detail-row { margin-bottom: 12px; font-size: 15px; }
        .info-detail-row strong { color: var(--espresso); }
        .embedded-map-frame { position: relative; padding-bottom: 52%; height: 0; overflow: hidden; border-radius: 6px; margin-top: 25px; box-shadow: inset 0 0 10px rgba(0,0,0,0.1); border: 1px solid #e0e0e0; transform: translateZ(0); }
        
        /* --- GLOBAL APPLICATION FOOTER --- */
        footer { background-color: #160E0C; color: #AFA5A2; padding: 75px 0 25px; font-size: 15px; position: relative; z-index: 2; }
        .footer-columns-wrapper { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 40px; margin-bottom: 50px; }
        .footer-column-cell h4 { color: var(--oatmilk); margin-bottom: 22px; font-size: 19px; letter-spacing: 0.5px; }
        .footer-column-cell p { line-height: 1.7; }
        .footer-bullet-list { list-style: none; }
        .footer-bullet-list li { margin-bottom: 10px; position: relative; padding-left: 15px; transition: transform 0.2s ease; }
        .footer-bullet-list li:hover { transform: translateX(4px); color: var(--oatmilk); }
        .footer-bullet-list li::before { content: '•'; color: var(--matcha); position: absolute; left: 0; }
        .bottom-copyright-strip { text-align: center; border-top: 1px solid #291E1C; padding-top: 25px; font-size: 13px; color: #736967; }

        /* --- GLOBAL ANIMATIONS KEYFRAMES --- */
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* --- RESPONSIVE MOBILE OVERRIDES --- */
        @media (max-width: 992px) {
            .about-split { flex-direction: column; gap: 40px; }
            .about-img-frame { height: 320px; }
            .hero h1 { font-size: 40px; }
        }
        @media (max-width: 768px) {
            .nav-links { display: none; }
            .hero h1 { font-size: 34px; }
            .menu-layout-grid { grid-template-columns: 1fr; }
            .hero { background-attachment: scroll !important; transform: none !important; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <nav>
                <a onclick="routeToView('home')" class="logo-group">
                    <img class="brand-logo-hook" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><circle cx='50' cy='50' r='35' fill='white'/><path d='M35,45 C35,60 45,65 55,65 C65,65 65,55 65,45 Z' fill='%232B1B17'/><path d='M65,45 C72,45 72,55 65,55' fill='none' stroke='%232B1B17' stroke-width='4'/></svg>" alt="Coffee Haus Logo">
                    <span class="logo-text">COFFEE HAUS</span>
                </a>
                <ul class="nav-links">
                    <li><a id="nav-link-home" onclick="routeToView('home')" class="active">Home</a></li>
                    <li><a id="nav-link-menu" onclick="routeToView('menu')">Menu</a></li>
                    <li><a id="nav-link-about" onclick="routeToView('about')">Our Space</a></li>
                    <li><a id="nav-link-contact" onclick="routeToView('contact')">Locations & Takeout</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="dine-in-banner">🛋️ NOW SERVING DINE-IN & TAKEOUT: Join us in our comfortable lounge, or call ahead to grab your favorite treats to-go!</div>

    <main>
        
        <div id="app-view-home" class="page-view active-view">
            <div class="hero-viewport">
                <section class="hero" id="parallax-hero-target">
                    <div class="container hero-content">
                        <h1>Your Favorite Late-Night Coffee Hangout</h1>
                        <p>Unwind inside an upscale lounge system optimized for deep concentration, direct conversation, and exceptional flavor profiles. Craft espresso, fresh bubble shakes, and signature Liège waffles served fresh daily until midnight—for dine-in or fast takeout.</p>
                        <a onclick="routeToView('menu')" class="btn btn-primary">Explore Full Menu</a>
                        <a onclick="routeToView('contact')" class="btn btn-secondary">Order Takeout Near You</a>
                    </div>
                </section>
            </div>
            
            <section class="section-padding">
                <div class="container">
                    <h2 class="section-title">The Perfect Late Night Fix</h2>
                    <div class="grid-3">
                        <div class="feature-card">
                            <span class="icon">🛍️</span>
                            <h3>Dine-In or Takeout</h3>
                            <p>Whether you want to relax with friends over traditional porcelain dishware or grab a bubble smoothie to-go, we accommodate your schedule seamlessly.</p>
                        </div>
                        <div class="feature-card">
                            <span class="icon">🔌</span>
                            <h3>Productivity-Friendly</h3>
                            <p>Equipped with broad, solid hardwood tables, accessible wall power configurations, and free premium ultra-fast fiber internet for our stay-in guests.</p>
                        </div>
                        <div class="feature-card">
                            <span class="icon">🌙</span>
                            <h3>Vibrant Late Nights</h3>
                            <p>No early closures. Whether you are prepping a project, closing out a date night, or picking up a midnight takeout craving, we remain open until midnight.</p>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <div id="app-view-menu" class="page-view">
            <section class="container section-padding">
                <h2 class="section-title">Crafted Fresh On-Demand</h2>
                <p style="text-align: center; margin-top: -30px; margin-bottom: 40px; color: #666; font-size: 15px;">Every drink and dessert is hand-assembled live to achieve pristine visual arts and textural crispness, available at your table or packed cleanly to-go.</p>
                
                <div id="live-dynamic-menu-target" class="menu-layout-grid">
                    <div class="menu-category-block">
                        <div class="category-header">
                            <h3>Espresso</h3>
                            <span class="size-legend-label">Single / Double</span>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Espresso</span><span class="item-dots-separator"></span><span class="item-price-values">$2.10 / $2.45</span></div>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Macchiato</span><span class="item-dots-separator"></span><span class="item-price-values">$2.35 / $2.65</span></div>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Con Panna</span><span class="item-dots-separator"></span><span class="item-price-values">$2.35 / $2.65</span></div>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Affogato</span><span class="item-dots-separator"></span><span class="item-price-values">$3.45 / $5.15</span></div>
                        </div>
                        
                        <div class="category-header" style="margin-top: 25px;">
                            <h3>Brewed Coffee</h3>
                            <span class="size-legend-label">Sm / Med / Lrg</span>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Americano</span><span class="item-dots-separator"></span><span class="item-price-values">$2.75 / $3.15 / $3.55</span></div>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Cappuccino</span><span class="item-dots-separator"></span><span class="item-price-values">$3.55 / $4.25 / $4.95</span></div>
                        </div>
                    </div>

                    <div class="menu-category-block">
                        <div class="category-header">
                            <h3>Latte <span style="font-family:sans-serif; font-size:14px; font-weight:normal; color:#666;">(Hot / Iced)</span></h3>
                            <span class="size-legend-label">12oz / 16oz / 20oz</span>
                        </div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Classic Latte</span><span class="item-dots-separator"></span><span class="item-price-values">$3.55 / $4.25 / $4.75</span></div>
                        </div>
                        <div class="nested-flavor-pool">
                            <strong>Flavor Options (+ $0.50):</strong> Vanilla, Caramel, French Vanilla, Hazelnut, Kona, Green Tea, Raspberry, Vanilla Caramel, Hazelnut Caramel, Vanilla White Chocolate, Hazelnut White Chocolate
                        </div>
                    </div>

                    <div class="menu-category-block">
                        <div class="category-header">
                            <h3>Mocha <span style="font-family:sans-serif; font-size:14px; font-weight:normal; color:#666;">(Hot / Iced)</span></h3>
                            <span class="size-legend-label">12oz / 16oz / 20oz</span>
                        </div>
                        <div class="category-subheader-label">Topped With Premium Whip Cream</div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Signature Flavors</span><span class="item-dots-separator"></span><span class="item-price-values">$4.25 / $5.05 / $5.45</span></div>
                        </div>
                        <div class="nested-flavor-pool" style="font-size:12px;">
                            • Mocha (Dark Chocolate)<br>
                            • White Mocha (White Chocolate)<br>
                            • Kona Mocha (Dark Cocoa)<br>
                            • Haus Mocha (White Chocolate & Caramel)<br>
                            • Tuxedo Mocha (White Chocolate & Dark Chocolate)<br>
                            • Caramel Mocha (Caramel & Dark Chocolate)<br>
                            • Hazelnut Mocha (Hazelnut & Dark Chocolate)<br>
                            • Raspberry Mocha (Raspberry & Dark Chocolate)<br>
                            • Hazelnut White Mocha (Hazelnut & White Chocolate)<br>
                            • Raspberry White Mocha (Raspberry & White Chocolate)
                        </div>
                    </div>

                    <div class="menu-category-block">
                        <div class="category-header">
                            <h3>Frappe</h3>
                            <span class="size-legend-label">Med / Lrg</span>
                        </div>
                        <div class="category-subheader-label">Topped With Premium Whip Cream</div>
                        <div class="menu-item-row">
                            <div class="item-main-line"><span>Blended Masterpieces</span><span class="item-dots-separator"></span><span class="item-price-values">$5.25 / $5.75</span></div>
                        </div>
                        <div class="nested-flavor-pool" style="font-size:12px; display: grid; grid-template-columns: 1fr 1fr; gap: 4px;">
                            <div>• Kona Mocha</div><div>• Mocha Caramel</div><div>• Raspberry Mocha</div><div>• Vanilla Caramel</div><div>• Vanilla White Choc</div><div>• Caramel White Choc</div><div>• Choc Peanut Butter</div><div>• Cookies & Cream</div><div>• Coffee Base</div><div>• Vanilla Base</div><div>• Caramel Base</div><div>• Java Chip</div><div>• Green Tea</div><div>• White Mocha</div><div>• Chocolate Mint</div><div>• Dirty Chai</div>
                        </div>
                    </div>

                    <div class="menu-category-block blue-accent">
                        <div class="category-header">
                            <h3>Bubble Tea</h3>
                            <span class="item-price-values" style="font-size: 16px; font-family:var(--font-sans);">$5.45</span>
                        </div>
                        <div class="category-subheader-label">Blended / Over Ice / Hot • Size: Large</div>
                        <div class="nested-flavor-pool" style="font-size:12px; display: grid; grid-template-columns: 1fr 1fr; gap: 4px;">
                            <div>• Taro</div><div>• Green Tea</div><div>• Milk Tea</div><div>• Thai Tea</div><div>• Chai Tea</div><div>• Coconut</div><div>• Almond</div><div>• Lychee</div><div>• Honeydew</div><div>• Lemon</div><div>• Avocado</div><div>• Coffee</div><div>• Mocha</div><div>• White Mocha</div><div>• Cookies & Cream</div><div>• Chocolate</div><div>• Vanilla</div><div>• Choc Peanut Butter</div><div>• Java Chip</div><div>• Chocolate Mint</div><div>• Caramel Macchiato</div><div>• Korean Coffee <span style="font-size:9px; color:#e06666;">(Iced Only)</span></div>
                        </div>
                        <div class="menu-addon-footer-box">
                            <strong>Milk Customization:</strong> Whole Milk, Skim Milk, Soy Milk (+ $0.75), Almond Milk (+ $0.75)<br><br>
                            <strong>Add-on Jellies & Boba (+ $0.75):</strong> Lychee, Mango, Green Apple, Coffee, Strawberry, Coconut, Rainbow, Brown Sugar, Passion Fruit, Blueberry
                        </div>
                    </div>

                    <div class="menu-category-block pink-accent">
                        <div class="category-header">
                            <h3>Bubble Smoothie</h3>
                            <span class="item-price-values" style="font-size: 16px; font-family:var(--font-sans);">$5.75</span>
                        </div>
                        <div class="category-subheader-label">Made with 100% Fresh Fruit • Size: Large</div>
                        <div class="nested-flavor-pool" style="font-size:12px; display: grid; grid-template-columns: 1fr 1fr; gap: 4px;">
                            <div>• Strawberry</div><div>• Banana</div><div>• Pineapple</div><div>• Honeydew</div><div>• Mango</div><div>• Watermelon</div><div>• Cantaloupe</div><div>• Blueberry</div><div>• Taro Blend</div><div>• Red Bean Blend</div><div>• Peach <span style="font-size:9px; color:green;">(Seasonal)</span></div><div>• Green Grape <span style="font-size:9px; color:green;">(Seasonal)</span></div><div>• Avocado <span style="font-size:9px; color:#555;">(Contains Milk)</span></div><div>• Mocha Banana <span style="font-size:9px; color:#555;">(Contains Milk)</span></div><div style="grid-column: span 2">• Choco Peanut Butter Banana <span style="font-size:9px; color:#555;">(Contains Milk)</span></div><div>• Piña Colada</div>
                        </div>
                        <div class="menu-addon-footer-box">
                            Includes choice of Boba or standard Add-in Jellies listed on bubble tea index profile. Extra toppings available for + $0.75.
                        </div>
                    </div>

                    <div class="menu-category-block blue-accent">
                        <div class="category-header">
                            <h3>Bing Soo</h3>
                            <span class="size-legend-label">Reg / Large</span>
                        </div>
                        <div class="category-subheader-label">Premium Korean Shaved Snow Ice</div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Red Bean Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / $9.25</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Oreo Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / — </span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Fruit Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values"> — / $9.25</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Mango Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / $9.25</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Strawberry Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / $9.25</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Coffee Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / $9.25</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Green Tea Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / $9.25</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Chocolate Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / — </span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Old Fashion Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values">$5.95 / — </span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Haus Bingsoo</span><span class="item-dots-separator"></span><span class="item-price-values"> — / $9.85</span></div></div>
                        <div class="menu-addon-footer-box">
                            <strong>Bing Soo Extras:</strong> Cereal (+ $0.75) | Mochi (+ $0.75) | Ice Cream (+ $1.85) | Extra Red Bean (+ $1.85) | Extra Fruit (+ $1.85)
                        </div>
                    </div>

                    <div class="menu-category-block pink-accent">
                        <div class="category-header">
                            <h3>Belgium Liège Waffle</h3>
                            <span class="size-legend-label">Fresh Baked</span>
                        </div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Plain Belgium Waffle</span><span class="item-dots-separator"></span><span class="item-price-values">$2.85</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle & Vanilla Ice Cream</span><span class="item-dots-separator"></span><span class="item-price-values">$4.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle & Chocolate Ice Cream</span><span class="item-prices">$4.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle & Green Tea Ice Cream</span><span class="item-prices">$4.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle & Coffee Ice Cream</span><span class="item-prices">$4.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle & Cookies n' Cream Ice Cream</span><span class="item-prices">$4.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle & Scoop of Fruit</span><span class="item-dots-separator"></span><span class="item-price-values">$4.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle, Strawberry & Ice Cream</span><span class="item-dots-separator"></span><span class="item-price-values">$5.55</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Waffle, Mango & Mango Ice Cream</span><span class="item-dots-separator"></span><span class="item-price-values">$5.55</span></div></div>
                    </div>

                    <div class="menu-category-block">
                        <div class="category-header">
                            <h3>Other Premium Drinks</h3>
                            <span class="size-legend-label">Sm / Med / Lrg</span>
                        </div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Daily Brewed Coffee</span><span class="item-dots-separator"></span><span class="item-price-values">$2.55 / $3.05 / $3.35</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>French Press</span><span class="item-dots-separator"></span><span class="item-price-values">$3.85 / $4.25 / $4.75</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Chai Latte</span><span class="item-dots-separator"></span><span class="item-price-values">$3.25 / $4.15 / $4.65</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Spiced Chai</span><span class="item-dots-separator"></span><span class="item-price-values">$3.25 / $4.15 / $4.65</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Hot Chocolate</span><span class="item-dots-separator"></span><span class="item-price-values">$3.25 / $4.15 / $4.65</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>White Hot Choco</span><span class="item-dots-separator"></span><span class="item-price-values">$3.85 / $4.25 / $4.75</span></div></div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Lemonade <span style="font-weight:normal; font-size:12px; color:#666;">(Pink or Regular)</span></span><span class="item-dots-separator"></span><span class="item-price-values"> — / $4.20 / — </span></div></div>

                        <div class="category-header" style="margin-top:20px;">
                            <h3>Loose Leaf Tea</h3>
                            <span class="size-legend-label">Med / Lrg</span>
                        </div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Hot / Iced Varietals</span><span class="item-dots-separator"></span><span class="item-price-values">$2.85 / $3.85 <span style="font-size:10px; color:#555;">(2 bags)</span></span></div></div>
                    </div>

                    <div class="menu-category-block">
                        <div class="category-header">
                            <h3>Korean Traditional Tea</h3>
                            <span class="size-legend-label">Med / Lrg</span>
                        </div>
                        <div class="menu-item-row"><div class="item-main-line"><span>Hot / Iced Traditional Blend</span><span class="item-dots-separator"></span><span class="item-price-values">$4.35 / $4.75</span></div></div>
                        <div class="nested-flavor-pool" style="font-size:13px;">
                            Citron Tea, Plum Tea, Ginger Tea, Jujube Tea, Ginseng Tea, Red Date Tea, Chrysanthemum Tea
                        </div>
                    </div>

                    <div class="menu-category-block blue-accent">
                        <div class="category-header">
                            <h3>Premium Ice Cream</h3>
                            <span class="item-price-values" style="font-family:var(--font-sans); font-size:16px;">$4.75</span>
                        </div>
                        <div class="item-desc-text" style="margin-bottom:10px;">Vanilla, Strawberry, Mango, Green Tea, Cookies & Cream, Coffee, Chocolate</div>
                        <div class="menu-addon-footer-box" style="margin-top:0; font-size:11px;">
                            <strong>Toppings (+ $0.50):</strong> Corn Flakes, Fruity Pebbles, Oreo, Nuts, Chocolate Syrup, Caramel, Strawberry Syrup, Tapioca, Jelly, Popping Boba, Mochi, Grain Powder, Fresh Fruit, Red Bean
                        </div>

                        <div class="category-header" style="margin-top:20px;">
                            <h3>Milk Splash</h3>
                            <span class="item-price-values" style="font-family:var(--font-sans); font-size:16px;">$5.45</span>
                        </div>
                        <div class="item-desc-text">Fresh, creamy specialty premium milk combinations layered with high-grade fruit profiles:</div>
                        <div class="nested-flavor-pool" style="font-size:12px;">Strawberry, Mango, Passion Fruit, Raspberry, Peach</div>
                    </div>

                    <div class="menu-category-block pink-accent">
                        <div class="category-header">
                            <h3>New Arrivals</h3>
                            <span class="size-legend-label">Hot / Iced</span>
                        </div>
                        <div class="nested-flavor-pool" style="font-size:13px; font-weight:bold; background:#fff;">
                            • Green Tea Latte<br>
                            • Misutgaru Latte<br>
                            • Haus Choco<br>
                            • Peppermint Hot Choco / White Choco<br>
                            • Pumpkin Spiced Chai Latte <span style="font-size:10px; color:green; font-weight:normal;">(Seasonal)</span>
                        </div>
                    </div>

                </div>
            </section>
        </div>

        <div id="app-view-about" class="page-view">
            <section class="container section-padding">
                <h2 class="section-title">Cozy Vibes. Open Late.</h2>
                <div class="about-split">
                    <div class="about-content-side">
                        <h3>Our Story & Philosophy</h3>
                        <p>Established in 2011, Coffee Haus was founded to give Chicago-area night owls, students, and flavor enthusiasts an alternative to sterile corporate coffee operations. We pair a warm, relaxing lounge layout with prompt, friendly takeout service for customers on the move.</p>
                        <p>Our philosophy focuses on combining classic espresso recipes with premium, authentic East Asian street dessert traditions. We build each plate live to optimize sensory crispness and beautiful visual arts. Whether you are studying under our targeted work lighting grids or swinging by to grab a late-night treat to-go, we make it simple to satisfy your cravings.</p>
                    </div>
                    <div class="about-graphic-side">
                        <img class="about-img-frame" src="https://images.unsplash.com/photo-154118811-1e0d58224f24?auto=format&fit=crop&q=80&w=800" alt="Coffee Haus Work Tables">
                    </div>
                </div>
            </section>
        </div>

        <div id="app-view-contact" class="page-view">
            <section class="container section-padding">
                <h2 class="section-title">Visit Us or Order To-Go</h2>
                <div class="location-matrix-grid">
                    
                    <div class="location-profile-card">
                        <h3>Schaumburg HQ</h3>
                        <div class="info-detail-row"><strong>Address:</strong> 209 W. Golf Rd, Schaumburg, IL 60195</div>
                        <div class="info-detail-row"><strong>Phone Support / Takeout:</strong> (847) 755-1233</div>
                        <div class="info-detail-row"><strong>Hours:</strong> Mon - Sun: 11:00 AM – 12:00 AM (Midnight)</div>
                        <div style="margin-top: 15px;"><a href="tel:+18477551233" class="btn btn-primary" style="padding: 8px 20px; font-size: 13px; text-align: center; display: block;">Call to Order Takeout</a></div>
                        <div class="embedded-map-frame">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2962.6738914041793!2d-88.0827118234199!3d42.04902195462529!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x880faf6913c48cd9%3A0xc3f80bc40be357e6!2s209%20W%20Golf%20Rd%2C%20Schaumburg%2C%20IL%2060195!5e0!3m2!1sen!2sus!4v1716760000000!5m2!1sen!2sus" allowfullscreen="" loading="lazy"></iframe>
                        </div>
                    </div>

                    <div class="location-profile-card">
                        <h3>South Elgin Branch</h3>
                        <div class="info-detail-row"><strong>Address:</strong> 406 Randall Rd, South Elgin, IL 60177</div>
                        <div class="info-detail-row"><strong>Phone Support / Takeout:</strong> Call Location Direct</div>
                        <div class="info-detail-row"><strong>Hours:</strong> Mon - Sun: 11:00 AM – 12:00 AM (Midnight)</div>
                        <div style="margin-top: 15px;"><span class="btn btn-secondary" style="padding: 8px 20px; font-size: 13px; text-align: center; display: block; border-color: var(--espresso); color: var(--espresso);">Counter Pickup Available</span></div>
                        <div class="embedded-map-frame">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2969.417242278453!2d-88.33785122342598!3d41.90541176371701!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x880f1aa4b91fb83b%3A0x2db4df44be0fe0cb!2s406%20Randall%20Rd%2C%20South%20Elgin%2C%20IL%2060177!5e0!3m2!1sen!2sus!4v1716760000000!5m2!1sen!2sus" allowfullscreen="" loading="lazy"></iframe>
                        </div>
                    </div>

                </div>
            </section>
        </div>

    </main>

    <footer>
        <div class="container">
            <div class="footer-columns-wrapper">
                <div class="footer-column-cell">
                    <h4>COFFEE HAUS</h4>
                    <p>Providing premium specialty espresso extraction, gourmet bubble smoothies, and authentic handcrafted Korean shaved snow arts across Illinois since 2011.</p>
                </div>
                <div class="footer-column-cell">
                    <h4>Lounge Standards</h4>
                    <ul class="footer-bullet-list">
                        <li>Flexible Dine-In & Quick Takeout Fulfillment</li>
                        <li>High-Capacity Academic Charging Infrastructure</li>
                        <li>Ultra High-Speed Symmetric Fiber Wi-Fi Connection</li>
                        <li>Warm, Low-Fatigue Ambient Acoustic Environment</li>
                    </ul>
                </div>
                <div class="footer-column-cell">
                    <h4>Legal & SEO Engine</h4>
                    <p>© 2026 Coffee Haus Lounge System. All Rights Reserved.</p>
                    <p style="font-size:12px; margin-top:12px; color:#5c5452;">Production Distribution Build v3.2 • Premium Motion Engine SPA</p>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // MULTI-PAGE SPA ENGINE WITH MOTION HOOKS
        function routeToView(viewId) {
            const currentActive = document.querySelector('.page-view.active-view');
            if(currentActive) {
                currentActive.classList.remove('active-view');
            }
            
            document.querySelectorAll('.nav-links a').forEach(link => link.classList.remove('active'));
            
            const nextTarget = document.getElementById(`app-view-${viewId}`);
            
            // Short timeout lets layouts unmount safely before fading back up
            setTimeout(() => {
                nextTarget.classList.add('active-view');
                const targetLink = document.getElementById(`nav-link-${viewId}`);
                if(targetLink) targetLink.classList.add('active');
            }, 50);
            
            window.scrollTo({top: 0, behavior: 'smooth'});
            
            const titleTag = document.getElementById('meta-title');
            const descTag = document.getElementById('meta-desc');
            
            if(viewId === 'home') {
                titleTag.innerText = "Coffee Haus | Premium Late-Night Dessert, Coffee Lounge & Takeout";
                descTag.setAttribute("content", "Experience Coffee Haus in Schaumburg & South Elgin. An upscale, cozy lounge featuring artisan espresso, handcrafted bubble tea, and waffles available for dine-in or quick takeout.");
            } else if(viewId === 'menu') {
                titleTag.innerText = "Our Complete Dessert & Takeout Menu | Coffee Haus";
                descTag.setAttribute("content", "Browse our complete dessert and coffee lineup. Replicated exactly in deep detail with all bubble smoothie fresh fruit combos and Liege waffle sets.");
            } else if(viewId === 'about') {
                titleTag.innerText = "Our Philosophy & Space | Coffee Haus Lounge";
                descTag.setAttribute("content", "Learn about our premium story and workspace focus. Intentionally open until midnight daily for dine-in lounge spaces and quick takeout options.");
            } else if(viewId === 'contact') {
                titleTag.innerText = "Takeout Locations & Midnight Operating Hours | Coffee Haus";
                descTag.setAttribute("content", "View direct Google Map embedded modules and takeout support details for both our Schaumburg on Golf Rd and South Elgin on Randall Rd branches.");
            }
        }

        // PRE-REQUISITE MOUSE PARALLAX CONTROLLER FOR HOME HERO
        const heroWrapper = document.getElementById('parallax-hero-target');
        if(heroWrapper) {
            window.addEventListener('mousemove', (e) => {
                if(window.innerWidth > 768 && document.getElementById('app-view-home').classList.contains('active-view')) {
                    const xOffset = (e.clientX / window.innerWidth - 0.5) * 15;
                    const yOffset = (e.clientY / window.innerHeight - 0.5) * 15;
                    heroWrapper.style.transform = `translate(${xOffset}px, ${yOffset}px) scale(1.02)`;
                }
            });
        }

        const OPTIONAL_GOOGLE_SHEETS_CSV_URL = ''; 

        async function initDynamicCMS() {
            if(!OPTIONAL_GOOGLE_SHEETS_CSV_URL) return;
            try {
                const response = await fetch(OPTIONAL_GOOGLE_SHEETS_CSV_URL);
                const data = await response.text();
            } catch(e) { console.log("System running on precise default native layout engine.", e); }
        }
        
        window.addEventListener('DOMContentLoaded', initDynamicCMS);
    </script>
</body>
</html>
