<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Lemon Bowl | Luxury Platters & Bespoke Catering in Gurugram</title>
    <meta name="description" content="Luxury catering and ready-to-serve gourmet platters in Gurugram & Delhi NCR. Multi-cuisine menus, grazing tables, and bespoke event catering.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --lemon: #E8C547;
            --lemon-bright: #F4D03F;
            --gold: #C9A227;
            --gold-deep: #B8941F;
            --cream: #F5F0E8;
            --black: #020202;
            --black-elevated: #0a0a0a;
            --black-card: #0f0f0f;
            --surface: #141414;
            --surface-hover: #1a1a1a;
            --border: rgba(255,255,255,0.06);
            --border-hover: rgba(232,197,71,0.2);
            --text-primary: #f5f5f5;
            --text-secondary: #9a9a9a;
            --text-tertiary: #666666;
            --gradient-gold: linear-gradient(135deg, var(--lemon), var(--gold));
            --gradient-dark: linear-gradient(180deg, var(--black) 0%, var(--black-elevated) 100%);
            --shadow-gold: 0 0 40px rgba(232,197,71,0.15);
            --shadow-deep: 0 25px 50px rgba(0,0,0,0.5);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }

        body {
            font-family: 'Poppins', sans-serif;
            background: var(--black);
            color: var(--text-primary);
            overflow-x: hidden;
            cursor: none;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }

        h1, h2, h3, h4, h5, h6 { font-family: 'Playfair Display', serif; font-weight: 600; }

        ::-webkit-scrollbar { width: 4px; }
        ::-webkit-scrollbar-track { background: var(--black); }
        ::-webkit-scrollbar-thumb { background: var(--gradient-gold); border-radius: 2px; }

        /* ========== NOISE OVERLAY ========== */
        .noise {
            position: fixed; inset: 0;
            z-index: 9998; pointer-events: none;
            opacity: 0.03;
            background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)'/%3E%3C/svg%3E");
            background-repeat: repeat;
            background-size: 256px 256px;
        }

        /* ========== CUSTOM CURSOR ========== */
        .cursor-dot {
            width: 8px; height: 8px;
            background: var(--lemon);
            border-radius: 50%;
            position: fixed; pointer-events: none;
            z-index: 100000; mix-blend-mode: difference;
            transition: transform 0.08s;
            box-shadow: 0 0 20px var(--lemon), 0 0 40px var(--gold);
        }
        .cursor-ring {
            width: 40px; height: 40px;
            border: 1.5px solid rgba(232,197,71,0.4);
            border-radius: 50%;
            position: fixed; pointer-events: none;
            z-index: 99999;
            transition: transform 0.15s ease-out, width 0.3s, height 0.3s, border-color 0.3s;
        }
        .cursor-ring.hover {
            width: 60px; height: 60px;
            border-color: var(--lemon);
            background: rgba(232,197,71,0.05);
        }
        .cursor-ring.click {
            transform: scale(0.8);
        }
        @media (max-width: 768px) { .cursor-dot, .cursor-ring { display: none; } body { cursor: auto; } }

        /* ========== SCROLL PROGRESS ========== */
        .scroll-progress {
            position: fixed; top: 0; left: 0; height: 2px;
            background: var(--gradient-gold);
            z-index: 100001;
            transition: width 0.1s;
            box-shadow: 0 0 20px rgba(232,197,71,0.4);
        }

        /* ========== PARTICLE CANVAS ========== */
        #particle-canvas {
            position: fixed; top: 0; left: 0;
            width: 100%; height: 100%;
            z-index: 0; pointer-events: none;
        }

        /* ========== LOADER ========== */
        .loader {
            position: fixed; inset: 0;
            background: var(--black);
            z-index: 100002;
            display: flex; align-items: center; justify-content: center;
            flex-direction: column;
            transition: opacity 1.2s cubic-bezier(0.4, 0, 0.2, 1), visibility 1.2s;
        }
        .loader.hidden { opacity: 0; visibility: hidden; }
        .loader-lemon {
            width: 70px; height: 70px;
            background: var(--gradient-gold);
            border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
            animation: loaderBounce 1.2s ease-in-out infinite;
            box-shadow: 0 0 50px rgba(232,197,71,0.4), 0 0 100px rgba(232,197,71,0.2);
            position: relative;
        }
        .loader-lemon::after {
            content: ''; position: absolute; inset: -10px;
            border: 1px solid rgba(232,197,71,0.2);
            border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
            animation: loaderPulse 2s ease-in-out infinite;
        }
        @keyframes loaderBounce {
            0%,100%{transform:translateY(0) rotate(0deg)}
            50%{transform:translateY(-25px) rotate(180deg)}
        }
        @keyframes loaderPulse {
            0%,100%{transform:scale(1); opacity:1}
            50%{transform:scale(1.2); opacity:0.3}
        }
        .loader-brand {
            font-family: 'Playfair Display', serif;
            font-size: 1.8rem; color: var(--cream);
            margin-top: 2.5rem; letter-spacing: 6px;
            text-transform: uppercase;
        }
        .loader-brand span { color: var(--lemon); }
        .loader-track {
            width: 180px; height: 2px;
            background: var(--border);
            border-radius: 2px; margin-top: 1.5rem;
            overflow: hidden; position: relative;
        }
        .loader-fill {
            height: 100%; width: 0;
            background: var(--gradient-gold);
            border-radius: 2px;
            animation: loaderFill 2.5s cubic-bezier(0.4, 0, 0.2, 1) forwards;
            box-shadow: 0 0 10px var(--lemon);
        }
        @keyframes loaderFill { to { width: 100%; } }

        /* ========== NAVIGATION ========== */
        nav {
            position: fixed; top: 0; width: 100%;
            z-index: 1000; padding: 1.5rem 5%;
            display: flex; justify-content: space-between; align-items: center;
            transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }
        nav.scrolled {
            background: rgba(2,2,2,0.85);
            backdrop-filter: blur(30px) saturate(150%);
            padding: 0.8rem 5%;
            border-bottom: 1px solid var(--border);
        }
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 1.6rem; font-weight: 700;
            color: var(--lemon); text-decoration: none;
            display: flex; align-items: center; gap: 0.5rem;
            transition: transform 0.3s;
        }
        .logo:hover { transform: scale(1.05); }
        .logo span { color: var(--cream); }
        .nav-links { display: flex; gap: 2.5rem; list-style: none; }
        .nav-links a {
            color: var(--text-secondary); text-decoration: none;
            font-size: 0.85rem; font-weight: 500;
            letter-spacing: 1px; text-transform: uppercase;
            position: relative; transition: all 0.4s;
            padding: 0.3rem 0;
        }
        .nav-links a::after {
            content: ''; position: absolute; bottom: 0; left: 0;
            width: 0; height: 1px;
            background: var(--gradient-gold);
            transition: width 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .nav-links a:hover { color: var(--lemon); }
        .nav-links a:hover::after { width: 100%; }
        .nav-cta {
            background: var(--gradient-gold);
            color: var(--black) !important;
            padding: 0.7rem 1.8rem;
            border-radius: 50px;
            font-weight: 600 !important;
            transition: all 0.4s;
            box-shadow: 0 4px 20px rgba(232,197,71,0.25);
            position: relative; overflow: hidden;
        }
        .nav-cta::after { display: none !important; }
        .nav-cta::before {
            content: ''; position: absolute; inset: 0;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transform: translateX(-100%);
            transition: transform 0.6s;
        }
        .nav-cta:hover::before { transform: translateX(100%); }
        .nav-cta:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 30px rgba(232,197,71,0.4);
        }
        .mobile-menu-btn {
            display: none; background: none; border: none;
            color: var(--lemon); font-size: 1.5rem; cursor: pointer;
        }

        /* ========== HERO ========== */
        .hero {
            min-height: 100vh; position: relative;
            display: flex; align-items: center; justify-content: center;
            overflow: hidden; perspective: 1200px;
        }
        .hero-bg-img {
            position: absolute; inset: 0;
            background: url('FRONT.png') center/cover;
            transform: scale(1.1);
            transition: transform 8s ease;
        }
        .hero.loaded .hero-bg-img { transform: scale(1); }
        .hero-overlay {
            position: absolute; inset: 0;
            background: linear-gradient(180deg,
                rgba(2,2,2,0.7) 0%,
                rgba(2,2,2,0.4) 40%,
                rgba(2,2,2,0.6) 70%,
                var(--black) 100%);
        }
        .hero-vignette {
            position: absolute; inset: 0;
            background: radial-gradient(ellipse at center, transparent 0%, rgba(2,2,2,0.4) 100%);
        }
        .hero-content {
            position: relative; z-index: 2;
            text-align: center; max-width: 900px; padding: 0 2rem;
            transform-style: preserve-3d;
        }
        .hero-tag {
            display: inline-flex; align-items: center; gap: 0.6rem;
            background: rgba(232,197,71,0.08);
            border: 1px solid rgba(232,197,71,0.15);
            padding: 0.6rem 1.5rem;
            border-radius: 50px;
            font-size: 0.75rem; color: var(--lemon);
            letter-spacing: 3px; text-transform: uppercase;
            margin-bottom: 2rem;
            backdrop-filter: blur(10px);
            animation: tagFade 1s 0.5s both;
        }
        @keyframes tagFade {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .hero h1 {
            font-size: clamp(3rem, 7vw, 6rem);
            line-height: 1.05; font-weight: 800;
            margin-bottom: 1.5rem;
            background: linear-gradient(135deg, #fff 0%, var(--cream) 50%, var(--lemon) 100%);
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
        }
        .hero h1 .word {
            display: inline-block; opacity: 0;
            transform: translateY(80px) rotateX(-40deg);
            animation: wordIn 1s cubic-bezier(0.4, 0, 0.2, 1) forwards;
        }
        @keyframes wordIn {
            to { opacity: 1; transform: translateY(0) rotateX(0); }
        }
        .hero-subtitle {
            font-size: clamp(1rem, 2vw, 1.2rem);
            color: var(--text-secondary);
            max-width: 550px; margin: 0 auto 2.5rem;
            line-height: 1.7;
            opacity: 0;
            animation: fadeUp 1s 0.8s both;
        }
        @keyframes fadeUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .hero-actions {
            display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;
            opacity: 0; animation: fadeUp 1s 1s both;
        }
        .btn {
            padding: 1rem 2.5rem; border-radius: 50px;
            font-family: 'Poppins', sans-serif; font-size: 0.9rem;
            font-weight: 600; cursor: none;
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            text-decoration: none; display: inline-flex;
            align-items: center; gap: 0.6rem; border: none;
            position: relative; overflow: hidden;
        }
        .btn-gold {
            background: var(--gradient-gold);
            color: var(--black);
            box-shadow: 0 10px 40px rgba(232,197,71,0.25);
        }
        .btn-gold:hover {
            transform: translateY(-4px) scale(1.05);
            box-shadow: 0 20px 50px rgba(232,197,71,0.4);
        }
        .btn-outline {
            background: transparent;
            border: 1px solid var(--border);
            color: var(--text-primary);
            backdrop-filter: blur(10px);
        }
        .btn-outline:hover {
            border-color: var(--lemon);
            background: rgba(232,197,71,0.05);
            transform: translateY(-4px);
        }
        .hero-stats {
            display: flex; justify-content: center;
            gap: 4rem; margin-top: 4rem;
            flex-wrap: wrap; opacity: 0;
            animation: fadeUp 1s 1.2s both;
        }
        .stat-item {
            text-align: center; padding: 1rem;
            transition: all 0.4s;
        }
        .stat-item:hover { transform: translateY(-5px); }
        .stat-num {
            font-family: 'Playfair Display', serif;
            font-size: 3rem; font-weight: 800;
            background: var(--gradient-gold);
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
            line-height: 1;
        }
        .stat-label {
            font-size: 0.7rem; color: var(--text-tertiary);
            text-transform: uppercase; letter-spacing: 2px;
            margin-top: 0.5rem;
        }
        .scroll-hint {
            position: absolute; bottom: 2rem; left: 50%;
            transform: translateX(-50%);
            display: flex; flex-direction: column;
            align-items: center; gap: 0.5rem;
            color: var(--text-tertiary);
            font-size: 0.7rem; letter-spacing: 2px;
            text-transform: uppercase;
            animation: bounceDown 2s infinite;
        }
        .scroll-hint i { font-size: 1.2rem; }
        @keyframes bounceDown {
            0%,100%{transform:translateX(-50%) translateY(0)}
            50%{transform:translateX(-50%) translateY(10px)}
        }

        /* ========== SECTIONS ========== */
        section { padding: 8rem 5%; position: relative; }
        .section-tag {
            display: inline-block; color: var(--lemon);
            font-size: 0.75rem; letter-spacing: 4px;
            text-transform: uppercase; margin-bottom: 1rem;
        }
        .section-title {
            font-size: clamp(2.5rem, 5vw, 4rem);
            color: var(--text-primary); line-height: 1.1;
            margin-bottom: 1.5rem;
        }
        .section-title span {
            background: var(--gradient-gold);
            -webkit-background-clip: text; -webkit-text-fill-color: transparent;
        }
        .section-desc {
            color: var(--text-secondary); font-size: 1.1rem;
            line-height: 1.8; max-width: 600px;
        }
        .gold-line {
            width: 60px; height: 2px;
            background: var(--gradient-gold);
            margin: 1.5rem 0;
            position: relative; overflow: hidden;
        }
        .gold-line::after {
            content: ''; position: absolute;
            top: 0; left: -100%; width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.6), transparent);
            animation: shine 3s infinite;
        }
        @keyframes shine { to { left: 100%; } }

        /* ========== ABOUT ========== */
        .about { background: var(--gradient-dark); }
        .about-grid {
            display: grid; grid-template-columns: 1fr 1fr;
            gap: 5rem; align-items: center;
            max-width: 1200px; margin: 0 auto;
        }
        .about-visual {
            position: relative;
            transform-style: preserve-3d;
            perspective: 1000px;
        }
        .about-img-main {
            position: relative; border-radius: 20px;
            overflow: hidden;
            transform: rotateY(-5deg);
            transition: transform 0.8s;
            box-shadow: var(--shadow-deep);
            border: 1px solid var(--border);
        }
        .about-visual:hover .about-img-main {
            transform: rotateY(0deg) scale(1.02);
        }
        .about-img-main img {
            width: 100%; height: 550px; object-fit: cover;
            transition: transform 0.8s;
        }
        .about-img-main:hover img { transform: scale(1.1); }
        .about-img-float {
            position: absolute; bottom: -30px; right: -30px;
            width: 200px; height: 200px;
            border-radius: 16px; overflow: hidden;
            border: 2px solid var(--border);
            box-shadow: var(--shadow-deep);
            transform: translateZ(60px);
            transition: transform 0.5s;
        }
        .about-visual:hover .about-img-float {
            transform: translateZ(80px) rotateY(5deg);
        }
        .about-img-float img {
            width: 100%; height: 100%; object-fit: cover;
        }
        .about-img-badge {
            position: absolute; top: -20px; left: -20px;
            background: var(--gradient-gold);
            color: var(--black); padding: 1rem 1.5rem;
            border-radius: 16px; font-weight: 700;
            font-size: 0.85rem; transform: translateZ(40px);
            box-shadow: var(--shadow-gold);
        }
        .about-text h2 { margin-bottom: 1.5rem; }
        .about-text p {
            color: var(--text-secondary); line-height: 1.9;
            margin-bottom: 1.5rem; font-size: 1.05rem;
        }
        .about-highlights {
            display: grid; grid-template-columns: 1fr 1fr;
            gap: 1rem; margin-top: 2rem;
        }
        .about-hl {
            display: flex; align-items: center; gap: 0.8rem;
            padding: 1rem; background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 12px;
            transition: all 0.4s;
        }
        .about-hl:hover {
            border-color: var(--border-hover);
            transform: translateX(5px);
            background: var(--surface-hover);
        }
        .about-hl i { color: var(--lemon); font-size: 1.1rem; }
        .about-hl span { font-size: 0.85rem; font-weight: 500; }

        /* ========== SERVICES ========== */
        .services { background: var(--black); }
        .services-header { text-align: center; margin-bottom: 4rem; }
        .services-header .gold-line { margin: 1.5rem auto; }
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem; max-width: 1200px; margin: 0 auto;
        }
        .service-card {
            background: var(--black-card);
            border: 1px solid var(--border);
            border-radius: 24px; overflow: hidden;
            transition: all 0.6s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
        }
        .service-card::before {
            content: ''; position: absolute; inset: 0;
            background: linear-gradient(180deg, rgba(232,197,71,0.03) 0%, transparent 60%);
            opacity: 0; transition: opacity 0.4s;
            pointer-events: none; z-index: 1;
        }
        .service-card:hover::before { opacity: 1; }
        .service-card:hover {
            transform: translateY(-12px);
            border-color: var(--border-hover);
            box-shadow: 0 30px 60px rgba(0,0,0,0.4), var(--shadow-gold);
        }
        .service-img {
            height: 200px; overflow: hidden; position: relative;
        }
        .service-img img {
            width: 100%; height: 100%; object-fit: cover;
            transition: transform 0.6s;
        }
        .service-card:hover .service-img img { transform: scale(1.1); }
        .service-img::after {
            content: ''; position: absolute; inset: 0;
            background: linear-gradient(to top, var(--black-card) 0%, transparent 60%);
        }
        .service-body { padding: 1.5rem 2rem 2rem; position: relative; z-index: 2; }
        .service-icon {
            width: 50px; height: 50px;
            background: var(--gradient-gold);
            border-radius: 14px;
            display: flex; align-items: center; justify-content: center;
            margin-bottom: 1rem; font-size: 1.2rem; color: var(--black);
            box-shadow: var(--shadow-gold);
            transition: transform 0.4s;
        }
        .service-card:hover .service-icon {
            transform: scale(1.1) rotate(-5deg);
        }
        .service-body h3 {
            font-size: 1.3rem; margin-bottom: 0.6rem;
            color: var(--text-primary);
        }
        .service-body p {
            color: var(--text-secondary); font-size: 0.9rem;
            line-height: 1.7;
        }

        /* ========== MENU ========== */
        .menu-section { background: var(--black-elevated); }
        .menu-header { text-align: center; margin-bottom: 3rem; }
        .menu-header .gold-line { margin: 1.5rem auto; }
        .menu-categories {
            display: flex; justify-content: center;
            gap: 0.8rem; margin-bottom: 3rem;
            flex-wrap: wrap;
        }
        .menu-pill {
            padding: 0.8rem 1.8rem;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 50px;
            color: var(--text-secondary);
            font-family: 'Poppins', sans-serif;
            font-size: 0.8rem; font-weight: 500;
            letter-spacing: 0.3px;
        }
        .menu-pill.active {
            background: var(--gradient-gold);
            color: var(--black);
            border-color: transparent;
            font-weight: 600;
            box-shadow: 0 8px 25px rgba(232,197,71,0.3);
        }
        .menu-overview {
            max-width: 900px;
            margin: 0 auto 3rem;
            text-align: center;
        }
        .menu-overview p {
            color: var(--text-secondary);
            font-size: 1rem;
            line-height: 1.9;
        }
        .menu-summary-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.4rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .menu-summary-card {
            background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
            border: 1px solid var(--border);
            border-radius: 22px;
            overflow: hidden;
            transition: transform 0.4s, border-color 0.4s, box-shadow 0.4s;
        }
        .menu-summary-card:hover {
            transform: translateY(-6px);
            border-color: var(--border-hover);
            box-shadow: 0 20px 45px rgba(0,0,0,0.28);
        }
        .menu-summary-media {
            height: 220px;
            position: relative;
            overflow: hidden;
        }
        .menu-summary-media img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.8s ease;
        }
        .menu-summary-card:hover .menu-summary-media img { transform: scale(1.06); }
        .menu-summary-media::after {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(to top, rgba(2,2,2,0.8) 0%, rgba(2,2,2,0.15) 55%, transparent 100%);
        }
        .menu-summary-body {
            padding: 1.6rem;
        }
        .menu-summary-body h3 {
            font-size: 1.45rem;
            color: var(--text-primary);
            margin-bottom: 0.75rem;
        }
        .menu-summary-body p {
            color: var(--text-secondary);
            font-size: 0.92rem;
            line-height: 1.8;
        }

        /* ========== WHY US ========== */
        .why-us { background: var(--black); }
        .why-header { text-align: center; margin-bottom: 4rem; }
        .why-header .gold-line { margin: 1.5rem auto; }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem; max-width: 1200px; margin: 0 auto;
        }
        .feature-card {
            background: var(--black-card);
            border: 1px solid var(--border);
            border-radius: 20px; padding: 2.5rem;
            text-align: center;
            transition: all 0.5s;
            position: relative; overflow: hidden;
        }
        .feature-card::before {
            content: ''; position: absolute; inset: 0;
            background: radial-gradient(circle at 50% 0%, rgba(232,197,71,0.06) 0%, transparent 60%);
            opacity: 0; transition: opacity 0.4s;
        }
        .feature-card:hover::before { opacity: 1; }
        .feature-card:hover {
            border-color: var(--border-hover);
            transform: translateY(-10px);
            box-shadow: 0 20px 50px rgba(0,0,0,0.3);
        }
        .feature-icon {
            width: 70px; height: 70px;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 50%;
            display: flex; align-items: center; justify-content: center;
            margin: 0 auto 1.5rem;
            font-size: 1.6rem; color: var(--lemon);
            transition: all 0.5s;
        }
        .feature-card:hover .feature-icon {
            background: var(--gradient-gold);
            color: var(--black);
            transform: scale(1.1);
            box-shadow: var(--shadow-gold);
        }
        .feature-card h3 {
            font-size: 1.2rem; margin-bottom: 0.6rem;
            color: var(--text-primary);
        }
        .feature-card p {
            color: var(--text-secondary); font-size: 0.9rem;
            line-height: 1.7;
        }

        /* ========== GALLERY ========== */
        .gallery { background: var(--black-elevated); }
        .gallery-header { text-align: center; margin-bottom: 4rem; }
        .gallery-header .gold-line { margin: 1.5rem auto; }
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-auto-rows: 240px;
            gap: 1rem; max-width: 1200px; margin: 0 auto;
        }
        .gallery-item {
            position: relative; border-radius: 16px;
            overflow: hidden; cursor: pointer;
            border: 1px solid var(--border);
            transition: all 0.5s;
        }
        .gallery-item img {
            width: 100%; height: 100%; object-fit: cover;
            transition: transform 0.7s;
        }
        .gallery-item:hover {
            z-index: 10;
            border-color: var(--border-hover);
            box-shadow: 0 30px 60px rgba(0,0,0,0.5);
        }
        .gallery-item:hover img { transform: scale(1.15); }
        .gallery-item::after {
            content: ''; position: absolute; inset: 0;
            background: linear-gradient(to top, rgba(2,2,2,0.8) 0%, transparent 50%);
            opacity: 0; transition: opacity 0.4s;
        }
        .gallery-item:hover::after { opacity: 1; }
        .gallery-item span {
            position: absolute; bottom: 1rem; left: 1rem;
            z-index: 2; font-family: 'Playfair Display', serif;
            font-size: 1.1rem; color: #fff;
            opacity: 0; transform: translateY(10px);
            transition: all 0.4s;
        }
        .gallery-item:hover span { opacity: 1; transform: translateY(0); }
        .gallery-item.tall { grid-row: span 2; }
        .gallery-item.wide { grid-column: span 2; }

        /* ========== TESTIMONIALS ========== */
        .testimonials { background: var(--black); }
        .testimonials-header { text-align: center; margin-bottom: 4rem; }
        .testimonials-header .gold-line { margin: 1.5rem auto; }
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem; max-width: 1200px; margin: 0 auto;
        }
        .testimonial-card {
            background: var(--black-card);
            border: 1px solid var(--border);
            border-radius: 24px; padding: 2.5rem;
            position: relative; overflow: hidden;
            transition: all 0.5s;
        }
        .testimonial-card::before {
            content: '"';
            font-family: 'Playfair Display', serif;
            font-size: 6rem; color: var(--lemon);
            opacity: 0.06; position: absolute;
            top: 0; left: 20px; line-height: 1;
        }
        .testimonial-card:hover {
            border-color: var(--border-hover);
            transform: translateY(-8px);
            box-shadow: 0 20px 50px rgba(0,0,0,0.3);
        }
        .stars { color: var(--lemon); margin-bottom: 1rem; font-size: 0.85rem; }
        .testimonial-text {
            font-size: 1.05rem; color: var(--text-secondary);
            line-height: 1.8; margin-bottom: 1.5rem;
            font-style: italic;
        }
        .testimonial-author {
            display: flex; align-items: center; gap: 1rem;
        }
        .author-avatar {
            width: 48px; height: 48px; border-radius: 50%;
            background: var(--gradient-gold);
            display: flex; align-items: center; justify-content: center;
            font-weight: 700; color: var(--black); font-size: 1.1rem;
        }
        .author-info h4 { font-size: 1rem; color: var(--text-primary); margin-bottom: 0.2rem; }
        .author-info p { font-size: 0.8rem; color: var(--text-tertiary); }

        /* ========== CONTACT ========== */
        .contact { background: var(--black-elevated); }
        .contact-grid {
            display: grid; grid-template-columns: 1fr 1fr;
            gap: 4rem; max-width: 1200px; margin: 0 auto;
        }
        .contact-info h2 { margin-bottom: 1rem; }
        .contact-info > p {
            color: var(--text-secondary); margin-bottom: 2rem;
            line-height: 1.8;
        }
        .contact-item {
            display: flex; align-items: flex-start; gap: 1rem;
            margin-bottom: 1.2rem; padding: 1.2rem;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 14px;
            transition: all 0.4s;
        }
        .contact-item:hover {
            border-color: var(--border-hover);
            transform: translateX(6px);
            background: var(--surface-hover);
        }
        .contact-item i { color: var(--lemon); font-size: 1.1rem; margin-top: 0.2rem; }
        .contact-item div strong { color: var(--text-primary); display: block; margin-bottom: 0.2rem; font-size: 0.9rem; }
        .contact-item div span, .contact-item div a {
            color: var(--text-secondary); text-decoration: none;
            font-size: 0.9rem; transition: color 0.3s;
        }
        .contact-item div a:hover { color: var(--lemon); }
        .whatsapp-btn {
            display: inline-flex; align-items: center; gap: 0.6rem;
            background: linear-gradient(135deg, #25D366, #128C7E);
            color: #fff; padding: 1rem 2rem;
            border-radius: 50px; text-decoration: none;
            font-weight: 600; margin-top: 1rem;
            transition: all 0.4s;
            box-shadow: 0 10px 30px rgba(37,211,102,0.2);
        }
        .whatsapp-btn:hover {
            transform: translateY(-3px) scale(1.03);
            box-shadow: 0 15px 40px rgba(37,211,102,0.3);
        }
        .social-links {
            display: flex; gap: 0.8rem; margin-top: 1.5rem;
        }
        .social-links a {
            width: 44px; height: 44px; border-radius: 50%;
            background: var(--surface);
            border: 1px solid var(--border);
            display: flex; align-items: center; justify-content: center;
            color: var(--text-secondary); text-decoration: none;
            transition: all 0.4s;
            font-size: 1rem;
        }
        .social-links a:hover {
            background: var(--gradient-gold);
            color: var(--black); border-color: transparent;
            transform: translateY(-4px) rotate(360deg);
            box-shadow: var(--shadow-gold);
        }
        .social-links a[aria-disabled="true"] {
            opacity: 0.65;
            cursor: default;
        }
        .social-links a[aria-disabled="true"]:hover {
            background: var(--surface);
            color: var(--text-secondary);
            border-color: var(--border);
            transform: none;
            box-shadow: none;
        }
        .contact-form {
            background: var(--black-card);
            border: 1px solid var(--border);
            border-radius: 24px; padding: 2.5rem;
            transition: all 0.4s;
        }
        .contact-form:hover {
            border-color: var(--border-hover);
            box-shadow: 0 20px 50px rgba(0,0,0,0.3);
        }
        .form-group { margin-bottom: 1.3rem; }
        .form-group label {
            display: block; margin-bottom: 0.4rem;
            color: var(--text-primary); font-size: 0.85rem;
            font-weight: 500;
        }
        .form-group input, .form-group textarea, .form-group select {
            width: 100%; padding: 0.9rem 1rem;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 12px; color: var(--text-primary);
            font-family: 'Poppins', sans-serif;
            font-size: 0.9rem;
            transition: all 0.3s;
        }
        .form-group input:focus, .form-group textarea:focus, .form-group select:focus {
            outline: none; border-color: var(--lemon);
            background: rgba(232,197,71,0.03);
            box-shadow: 0 0 20px rgba(232,197,71,0.05);
        }
        .form-group textarea { resize: vertical; min-height: 100px; }
        .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
        .form-status {
            margin-top: 1rem;
            color: var(--text-secondary);
            font-size: 0.85rem;
            line-height: 1.6;
        }

        /* ========== FOOTER ========== */
        footer {
            background: var(--black);
            border-top: 1px solid var(--border);
            padding: 4rem 5% 1.5rem;
        }
        .footer-grid {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr 1fr;
            gap: 3rem; max-width: 1200px; margin: 0 auto 3rem;
        }
        .footer-brand .logo { margin-bottom: 1rem; display: inline-flex; }
        .footer-brand p { color: var(--text-tertiary); font-size: 0.9rem; line-height: 1.8; }
        .footer-links h4 {
            color: var(--lemon); font-size: 1rem;
            margin-bottom: 1.5rem; font-family: 'Playfair Display', serif;
        }
        .footer-links ul { list-style: none; }
        .footer-links li { margin-bottom: 0.7rem; }
        .footer-links a {
            color: var(--text-tertiary); text-decoration: none;
            font-size: 0.85rem; transition: all 0.3s;
            display: inline-block;
        }
        .footer-links a:hover { color: var(--lemon); transform: translateX(4px); }
        .footer-bottom {
            text-align: center; padding-top: 2rem;
            border-top: 1px solid var(--border);
            color: var(--text-tertiary); font-size: 0.8rem;
        }

        /* ========== REVEAL ANIMATIONS ========== */
        .reveal {
            opacity: 0; transform: translateY(40px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .reveal.active { opacity: 1; transform: translateY(0); }
        .reveal-d1 { transition-delay: 0.1s; }
        .reveal-d2 { transition-delay: 0.2s; }
        .reveal-d3 { transition-delay: 0.3s; }
        .reveal-d4 { transition-delay: 0.4s; }

        /* ========== MAGNETIC BUTTON ========== */
        .magnetic {
            transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        /* ========== TEXT SCRAMBLE ========== */
        .scramble { display: inline-block; }

        /* ========== MARQUEE ========== */
        .marquee {
            overflow: hidden; white-space: nowrap;
            position: relative;
        }
        .marquee-content {
            display: inline-block;
            animation: marquee 30s linear infinite;
        }
        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }

        /* ========== AMBIENT GLOW ========== */
        .ambient-glow {
            position: absolute; border-radius: 50%;
            filter: blur(120px); pointer-events: none;
            z-index: 0;
        }
        .glow-1 {
            width: 500px; height: 500px;
            background: rgba(232,197,71,0.04);
            top: 10%; left: -10%;
            animation: glowMove 20s ease-in-out infinite;
        }
        .glow-2 {
            width: 400px; height: 400px;
            background: rgba(201,162,39,0.03);
            bottom: 10%; right: -5%;
            animation: glowMove 25s ease-in-out infinite reverse;
        }
        @keyframes glowMove {
            0%,100%{transform:translate(0,0) scale(1)}
            50%{transform:translate(60px,-40px) scale(1.2)}
        }

        /* ========== MOBILE ========== */
        @media (max-width: 1024px) {
            .about-grid, .contact-grid { grid-template-columns: 1fr; }
            .about-visual { order: -1; }
            .gallery-grid { grid-template-columns: repeat(2, 1fr); }
            .gallery-item.wide { grid-column: span 2; }
            .footer-grid { grid-template-columns: 1fr 1fr; }
        }
        @media (max-width: 768px) {
            .nav-links {
                display: none; position: absolute;
                top: 100%; left: 0; right: 0;
                background: rgba(2,2,2,0.98);
                flex-direction: column; padding: 2rem;
                gap: 1.5rem; border-top: 1px solid var(--border);
                backdrop-filter: blur(20px);
            }
            .nav-links.active { display: flex; }
            .mobile-menu-btn { display: block; }
            .hero-stats { gap: 2rem; }
            .about-highlights { grid-template-columns: 1fr; }
            .gallery-grid { grid-template-columns: 1fr; }
            .gallery-item.wide, .gallery-item.tall { grid-column: span 1; grid-row: span 1; }
            .footer-grid { grid-template-columns: 1fr; gap: 2rem; }
            .form-row { grid-template-columns: 1fr; }
            .menu-summary-grid { grid-template-columns: 1fr; }
            .hero-actions { flex-direction: column; align-items: center; }
            .btn { width: 100%; max-width: 280px; justify-content: center; cursor: pointer; }
            body { cursor: auto; }
            .cursor-dot, .cursor-ring { display: none; }
            .about-img-float { display: none; }
            .about-img-badge { display: none; }
        }
    </style>
</head>
<body>
    <div class="noise"></div>
    <div class="cursor-dot" id="cursorDot"></div>
    <div class="cursor-ring" id="cursorRing"></div>
    <div class="scroll-progress" id="scrollProgress"></div>
    <canvas id="particle-canvas"></canvas>

    <!-- Loader -->
    <div class="loader" id="loader">
        <div class="loader-lemon"></div>
        <div class="loader-brand">The Lemon <span>Bowl</span></div>
        <div class="loader-track"><div class="loader-fill"></div></div>
    </div>

    <!-- Nav -->
    <nav id="navbar">
        <a href="#home" class="logo"><i class="fas fa-lemon"></i> The Lemon <span>Bowl</span></a>
        <ul class="nav-links" id="navLinks">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#contact" class="nav-cta magnetic">Book Event</a></li>
        </ul>
        <button class="mobile-menu-btn" id="mobileMenuBtn"><i class="fas fa-bars"></i></button>
    </nav>

    <!-- Hero -->
    <section class="hero" id="home">
        <div class="hero-bg-img"></div>
        <div class="hero-overlay"></div>
        <div class="hero-vignette"></div>
        <div class="ambient-glow glow-1"></div>
        <div class="ambient-glow glow-2"></div>
        <div class="hero-content">
            <div class="hero-tag"><i class="fas fa-star"></i> Premium Catering & Cafe</div>
            <h1 id="heroTitle"></h1>
            <p class="hero-subtitle">Multi-cuisine ready-to-serve platters crafted for intimate gatherings, parties, and celebrations across Delhi NCR.</p>
            <div class="hero-actions">
                <a href="#menu" class="btn btn-gold magnetic"><i class="fas fa-utensils"></i> Explore Menu</a>
                <a href="#contact" class="btn btn-outline magnetic"><i class="fas fa-calendar-check"></i> Book Catering</a>
            </div>
            <div class="hero-stats">
                <div class="stat-item" data-target="20" data-suffix="+">
                    <div class="stat-num">0</div>
                    <div class="stat-label">Cuisines</div>
                </div>
                <div class="stat-item" data-target="500" data-suffix="+">
                    <div class="stat-num">0</div>
                    <div class="stat-label">Events Catered</div>
                </div>
                <div class="stat-item" data-target="4.8" data-suffix="" data-decimal="true">
                    <div class="stat-num">0</div>
                    <div class="stat-label">Rating</div>
                </div>
            </div>
        </div>
        <div class="scroll-hint"><span>Scroll</span><i class="fas fa-chevron-down"></i></div>
    </section>

    <!-- About -->
    <section class="about" id="about">
        <div class="about-grid">
            <div class="about-text reveal">
                <div class="section-tag">About Us</div>
                <h2 class="section-title">Welcome to <span>The Lemon Bowl</span></h2>
                <div class="gold-line"></div>
                <p>A luxury catering and platter experience curated by <strong style="color:var(--lemon)">Aakriti Todi</strong>. From Indian classics to global gourmet cuisines, every platter is designed to create memorable dining moments.</p>
                <p>Based in Gurugram, we deliver across Delhi NCR, bringing restaurant-quality presentation and flavors to your doorstep. Whether it's an intimate dinner or a grand celebration, we craft experiences that linger.</p>
                <div class="about-highlights">
                    <div class="about-hl reveal reveal-d1"><i class="fas fa-globe"></i><span>20+ Cuisines</span></div>
                    <div class="about-hl reveal reveal-d2"><i class="fas fa-utensils"></i><span>Gourmet Catering</span></div>
                    <div class="about-hl reveal reveal-d1"><i class="fas fa-table"></i><span>Grazing Tables</span></div>
                    <div class="about-hl reveal reveal-d2"><i class="fas fa-building"></i><span>Corporate Events</span></div>
                    <div class="about-hl reveal reveal-d3"><i class="fas fa-home"></i><span>Home Events</span></div>
                    <div class="about-hl reveal reveal-d4"><i class="fas fa-paint-brush"></i><span>Elegant Presentations</span></div>
                </div>
            </div>
            <div class="about-visual reveal reveal-d2">
                <div class="about-img-main">
                    <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/ebcf6418d0a4e40044c9fbe538ba34f8ab37c6de.jpg" alt="Chef Plating">
                </div>
                <div class="about-img-float">
                    <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/37de8c759897ffbdc8363389fe37b46f4c4c7f8d.jpg" alt="Gourmet Detail">
                </div>
                <div class="about-img-badge">Since 2018</div>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section class="services" id="services">
        <div class="services-header reveal">
            <div class="section-tag">What We Do</div>
            <h2 class="section-title">Our <span>Services</span></h2>
            <div class="gold-line"></div>
            <p class="section-desc" style="margin:0 auto">End-to-end culinary solutions for every occasion</p>
        </div>
        <div class="services-grid">
            <div class="service-card reveal">
                <div class="service-img">
                    <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/b96e607200c729e98c53b152b5023eac192fe466.jpg" alt="Ready to Serve Platters">
                </div>
                <div class="service-body">
                    <div class="service-icon"><i class="fas fa-box-open"></i></div>
                    <h3>Ready-to-Serve Platters</h3>
                    <p>Beautiful curated platters delivered to your doorstep. Perfect for house parties, brunches, and intimate gatherings.</p>
                </div>
            </div>
            <div class="service-card reveal reveal-d1">
                <div class="service-img">
                    <img src="https://kimi-web-img.moonshot.cn/img/thecheeseman.ae/b1bcf730d97f5fce4391f53a08bfb04dfbe78fb1.jpg" alt="Grazing Tables">
                </div>
                <div class="service-body">
                    <div class="service-icon"><i class="fas fa-table"></i></div>
                    <h3>Grazing Tables</h3>
                    <p>Luxury table styling with gourmet food setup. A visual and culinary masterpiece for weddings and corporate events.</p>
                </div>
            </div>
            <div class="service-card reveal reveal-d2">
                <div class="service-img">
                    <img src="https://kimi-web-img.moonshot.cn/img/thumbs.dreamstime.com/46ae0f4437783e1fcf0b3b6dcee489213bb22c87.jpg" alt="Catering Services">
                </div>
                <div class="service-body">
                    <div class="service-icon"><i class="fas fa-glass-cheers"></i></div>
                    <h3>Catering Services</h3>
                    <p>Full-service catering for parties and corporate events. From setup to service, we handle everything.</p>
                </div>
            </div>
            <div class="service-card reveal reveal-d3">
                <div class="service-img">
                    <img src="https://kimi-web-img.moonshot.cn/img/media-api.xogrp.com/439ebff4323eb6fb3ea6bcf4f130a1aebbc53363.1000" alt="Festive Gifting">
                </div>
                <div class="service-body">
                    <div class="service-icon"><i class="fas fa-gift"></i></div>
                    <h3>Festive Gifting</h3>
                    <p>Custom gourmet gifting experiences. Delight your loved ones with curated hampers and specialty platters.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu -->
    <section class="menu-section" id="menu">
        <div class="menu-header reveal">
            <div class="section-tag">Discover</div>
            <h2 class="section-title">Our <span>Menu</span></h2>
            <div class="gold-line"></div>
            <p class="section-desc" style="margin:0 auto">A simple look at the cuisines and platter experiences we serve</p>
        </div>
        <div class="menu-categories reveal">
            <span class="menu-pill">Chaat Platters</span>
            <span class="menu-pill">Appetizers</span>
            <span class="menu-pill active">Indian Main Course</span>
            <span class="menu-pill">Global Cuisine</span>
            <span class="menu-pill">BBQ & Grill</span>
            <span class="menu-pill">Desserts</span>
        </div>
        <div class="menu-overview reveal reveal-d1">
            <p>Our food is designed around celebrations, sharing, and elegant presentation. From lively Indian favorites to refined global platters, we curate menus that feel festive, generous, and beautifully styled for every gathering.</p>
        </div>
        <div class="menu-summary-grid">
            <article class="menu-summary-card reveal">
                <div class="menu-summary-media">
                    <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/45ab12e9261164b2ae78d5f1a1cf45b89e3abd55.jpg" alt="Chaat Platters">
                </div>
                <div class="menu-summary-body">
                    <h3>Chaat Platters</h3>
                    <p>Colorful, nostalgic street-style flavors served with vibrant chutneys, layered textures, and a playful presentation that always energizes the table.</p>
                </div>
            </article>
            <article class="menu-summary-card reveal reveal-d1">
                <div class="menu-summary-media">
                    <img src="https://kimi-web-img.moonshot.cn/img/t4.ftcdn.net/e5424983f95205c742f863dabd8202312d4f245c.jpg" alt="Appetizers">
                </div>
                <div class="menu-summary-body">
                    <h3>Appetizers</h3>
                    <p>Elegant bite-sized starters crafted for mingling, welcome tables, and cocktail-style service with a balance of comfort and sophistication.</p>
                </div>
            </article>
            <article class="menu-summary-card reveal reveal-d2">
                <div class="menu-summary-media">
                    <img src="https://kimi-web-img.moonshot.cn/img/thumbs.dreamstime.com/2873ed8673bdac95077cc8cbac7440d0e658439d.jpg" alt="Indian Main Course">
                </div>
                <div class="menu-summary-body">
                    <h3>Indian Main Course</h3>
                    <p>Rich regional classics and comforting favorites prepared with depth, warmth, and the kind of presentation that feels special for family-style celebrations.</p>
                </div>
            </article>
            <article class="menu-summary-card reveal">
                <div class="menu-summary-media">
                    <img src="https://kimi-web-img.moonshot.cn/img/img.freepik.com/4a0d214fbdbeb97ded3d2e41eda3f9b076a3e75e.jpg" alt="Global Cuisine">
                </div>
                <div class="menu-summary-body">
                    <h3>Global Cuisine</h3>
                    <p>International flavors interpreted with a gourmet touch, bringing Mediterranean, Asian, Italian, and modern fusion influences into one polished spread.</p>
                </div>
            </article>
            <article class="menu-summary-card reveal reveal-d1">
                <div class="menu-summary-media">
                    <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/a31bde1c2124bcf085f430bb5b86f9e7d2f32878.jpg" alt="BBQ and Grill">
                </div>
                <div class="menu-summary-body">
                    <h3>BBQ & Grill</h3>
                    <p>Smoky grills, tandoor-inspired selections, and bold savory flavors that add a hearty, interactive element to parties and outdoor gatherings.</p>
                </div>
            </article>
            <article class="menu-summary-card reveal reveal-d2">
                <div class="menu-summary-media">
                    <img src="https://kimi-web-img.moonshot.cn/img/media-api.xogrp.com/a8c164facba3daa37cb5b03a0d957f707a1bb4ca.750" alt="Desserts">
                </div>
                <div class="menu-summary-body">
                    <h3>Desserts</h3>
                    <p>Decadent sweet endings that blend classic indulgence with graceful styling, perfect for gifting, celebrations, and memorable dessert tables.</p>
                </div>
            </article>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section class="why-us" id="whyus">
        <div class="why-header reveal">
            <div class="section-tag">Why Us</div>
            <h2 class="section-title">The Lemon Bowl <span>Difference</span></h2>
            <div class="gold-line"></div>
            <p class="section-desc" style="margin:0 auto">What sets us apart in luxury catering</p>
        </div>
        <div class="features-grid">
            <div class="feature-card reveal">
                <div class="feature-icon"><i class="fas fa-gem"></i></div>
                <h3>Premium Ingredients</h3>
                <p>We source only the finest and freshest ingredients for every dish we prepare.</p>
            </div>
            <div class="feature-card reveal reveal-d1">
                <div class="feature-icon"><i class="fas fa-palette"></i></div>
                <h3>Elegant Presentation</h3>
                <p>Every platter is a work of art, designed to impress before the first bite.</p>
            </div>
            <div class="feature-card reveal reveal-d2">
                <div class="feature-icon"><i class="fas fa-shield-alt"></i></div>
                <h3>Hygiene & Quality</h3>
                <p>Certified kitchen practices ensuring the highest standards of food safety.</p>
            </div>
            <div class="feature-card reveal">
                <div class="feature-icon"><i class="fas fa-shipping-fast"></i></div>
                <h3>Fast Delivery</h3>
                <p>On-time delivery across Gurugram and Delhi NCR with temperature-controlled packaging.</p>
            </div>
            <div class="feature-card reveal reveal-d1">
                <div class="feature-icon"><i class="fas fa-sliders-h"></i></div>
                <h3>Customization Options</h3>
                <p>Tailor-made menus to suit your dietary preferences and event theme.</p>
            </div>
            <div class="feature-card reveal reveal-d2">
                <div class="feature-icon"><i class="fas fa-users"></i></div>
                <h3>Professional Team</h3>
                <p>Experienced chefs and service staff dedicated to making your event perfect.</p>
            </div>
        </div>
    </section>

    <!-- Gallery -->
    <section class="gallery" id="gallery">
        <div class="gallery-header reveal">
            <div class="section-tag">Portfolio</div>
            <h2 class="section-title">Our <span>Gallery</span></h2>
            <div class="gold-line"></div>
            <p class="section-desc" style="margin:0 auto">A glimpse into our culinary world</p>
        </div>
        <div class="gallery-grid">
            <div class="gallery-item wide reveal">
                <img src="https://kimi-web-img.moonshot.cn/img/c8.alamy.com/2a713bc9edd12c0c56d0a266d5326c73f8538e5d.jpg" alt="Corporate Events">
                <span>Corporate Events</span>
            </div>
            <div class="gallery-item reveal reveal-d1">
                <img src="https://kimi-web-img.moonshot.cn/img/bohopartyplatter.com/5921b48eaf04a8c4f0e73ad9296d2289d669454e.png" alt="Chaat Platters">
                <span>Chaat Platters</span>
            </div>
            <div class="gallery-item reveal reveal-d2">
                <img src="https://kimi-web-img.moonshot.cn/img/ribbonstopastas.com/6e0843b22e837f662e05e6b2a105966c356bc6f4.jpg" alt="Chaat Boards">
                <span>Chaat Boards</span>
            </div>
            <div class="gallery-item tall reveal">
                <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/b96e607200c729e98c53b152b5023eac192fe466.jpg" alt="Gourmet Platters">
                <span>Gourmet Platters</span>
            </div>
            <div class="gallery-item reveal reveal-d1">
                <img src="https://kimi-web-img.moonshot.cn/img/www.shutterstock.com/9862e00fdc5336ad2082c57f8921d17213c42242.jpg" alt="Fine Dining">
                <span>Fine Dining</span>
            </div>
            <div class="gallery-item reveal reveal-d2">
                <img src="https://kimi-web-img.moonshot.cn/img/thumbs.dreamstime.com/6bab437112f84ecaffc64d82f7c84c7324245726.jpg" alt="Artistic Plating">
                <span>Artistic Plating</span>
            </div>
            <div class="gallery-item wide reveal">
                <img src="https://kimi-web-img.moonshot.cn/img/www.brides.com/e1236b733214a779b9601892671d5c90053437e7.jpg" alt="Grazing Tables">
                <span>Grazing Tables</span>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials" id="testimonials">
        <div class="testimonials-header reveal">
            <div class="section-tag">Testimonials</div>
            <h2 class="section-title">What Our <span>Clients Say</span></h2>
            <div class="gold-line"></div>
            <p class="section-desc" style="margin:0 auto">Real experiences from real celebrations</p>
        </div>
        <div class="testimonials-grid">
            <div class="testimonial-card reveal">
                <div class="stars"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                <p class="testimonial-text">Beautiful presentation and amazing flavors. Perfect for our family gathering. The chaat platter was the highlight of the evening!</p>
                <div class="testimonial-author">
                    <div class="author-avatar">P</div>
                    <div class="author-info"><h4>Priya Sharma</h4><p>Family Event, Gurgaon</p></div>
                </div>
            </div>
            <div class="testimonial-card reveal reveal-d1">
                <div class="stars"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></div>
                <p class="testimonial-text">One of the best premium catering experiences in Gurugram. The grazing table was absolutely stunning and the food was divine.</p>
                <div class="testimonial-author">
                    <div class="author-avatar">R</div>
                    <div class="author-info"><h4>Rahul Mehta</h4><p>Corporate Event, Cyber Hub</p></div>
                </div>
            </div>
            <div class="testimonial-card reveal reveal-d2">
                <div class="stars"><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star-half-alt"></i></div>
                <p class="testimonial-text">We ordered the Chaat Ka Thela for our housewarming party. Our guests couldn't stop raving about the golgappas and dahi bhalla!</p>
                <div class="testimonial-author">
                    <div class="author-avatar">A</div>
                    <div class="author-info"><h4>Ananya Gupta</h4><p>Housewarming, DLF Phase 5</p></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section class="contact" id="contact">
        <div class="contact-grid">
            <div class="contact-info reveal">
                <div class="section-tag">Contact</div>
                <h2 class="section-title">Let's Plan Your <span>Event</span></h2>
                <div class="gold-line"></div>
                <p>Whether it's an intimate dinner or a grand celebration, we'd love to be a part of your special moments.</p>
                <div class="contact-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <div><strong>Location</strong><span>Gurugram, Haryana<br>Delhi NCR</span></div>
                </div>
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <div><strong>Phone</strong><a href="tel:+919711971606">+91 97119 71606</a><br><a href="tel:+918800023397">+91 88000 23397</a></div>
                </div>
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <div><strong>Email</strong><a href="mailto:hello@thelemonbowl.in">hello@thelemonbowl.in</a></div>
                </div>
                <div class="contact-item">
                    <i class="fas fa-clock"></i>
                    <div><strong>Hours</strong><span>Mon - Sun: 10:00 AM - 10:00 PM</span></div>
                </div>
                <a href="https://wa.me/919711971606" class="whatsapp-btn magnetic" target="_blank" rel="noopener noreferrer"><i class="fab fa-whatsapp"></i> Order on WhatsApp</a>
                <div class="social-links">
                    <a href="#" aria-label="Instagram" aria-disabled="true" title="Instagram link coming soon"><i class="fab fa-instagram"></i></a>
                    <a href="#" aria-label="Facebook" aria-disabled="true" title="Facebook link coming soon"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" aria-label="Twitter" aria-disabled="true" title="Twitter link coming soon"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
            <div class="contact-form reveal reveal-d1">
                <h3 style="font-family:'Playfair Display',serif;margin-bottom:1.5rem;color:var(--text-primary);font-size:1.4rem;">Book Your Event</h3>
                <form id="contactForm" action="" method="POST" data-recipient="hello@thelemonbowl.in">
                    <div class="form-row">
                        <div class="form-group"><label>First Name</label><input type="text" name="firstname" placeholder="John" required></div>
                        <div class="form-group"><label>Last Name</label><input type="text" name="lastname" placeholder="Doe" required></div>
                    </div>
                    <div class="form-group"><label>Email</label><input type="email" name="email" placeholder="john@example.com" required></div>
                    <div class="form-group"><label>Phone</label><input type="tel" name="phone" placeholder="+91 98765 43210" required></div>
                    <div class="form-row">
                        <div class="form-group"><label>Event Date</label><input type="date" name="date" required></div>
                        <div class="form-group"><label>Guests</label><select name="guests" required><option value="">Select</option><option>10-20</option><option>20-50</option><option>50-100</option><option>100+</option></select></div>
                    </div>
                    <div class="form-group"><label>Event Type</label><select name="event_type" required><option value="">Select Event Type</option><option>Birthday Party</option><option>Corporate Event</option><option>Wedding / Reception</option><option>Housewarming</option><option>Other</option></select></div>
                    <div class="form-group"><label>Message</label><textarea name="message" placeholder="Tell us about your event..."></textarea></div>
                    <button type="submit" class="btn btn-gold magnetic" style="width:100%;justify-content:center;"><i class="fas fa-paper-plane"></i> Send Inquiry</button>
                    <p class="form-status" id="formStatus" role="status" aria-live="polite"></p>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-grid">
            <div class="footer-brand">
                <a href="#home" class="logo"><i class="fas fa-lemon"></i> The Lemon <span>Bowl</span></a>
                <p>Luxury platters and bespoke catering experiences in Gurugram & Delhi NCR. Crafted with passion, served with elegance.</p>
                <div class="social-links">
                    <a href="#" aria-label="Instagram" aria-disabled="true" title="Instagram link coming soon"><i class="fab fa-instagram"></i></a>
                    <a href="#" aria-label="Facebook" aria-disabled="true" title="Facebook link coming soon"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" aria-label="Twitter" aria-disabled="true" title="Twitter link coming soon"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
            <div class="footer-links">
                <h4>Quick Links</h4>
                <ul><li><a href="#home">Home</a></li><li><a href="#about">About Us</a></li><li><a href="#menu">Menu</a></li><li><a href="#gallery">Gallery</a></li></ul>
            </div>
            <div class="footer-links">
                <h4>Services</h4>
                <ul><li><a href="#services">Ready-to-Serve Platters</a></li><li><a href="#services">Grazing Tables</a></li><li><a href="#services">Catering Services</a></li><li><a href="#services">Festive Gifting</a></li></ul>
            </div>
            <div class="footer-links">
                <h4>Contact</h4>
                <ul><li><a href="tel:+919711971606">+91 97119 71606</a></li><li><a href="tel:+918800023397">+91 88000 23397</a></li><li><a href="mailto:hello@thelemonbowl.in">hello@thelemonbowl.in</a></li><li><span>Gurugram, Haryana</span></li></ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 The Lemon Bowl. All rights reserved. | Crafted with <i class="fas fa-heart" style="color:var(--lemon)"></i> in Gurugram</p>
        </div>
    </footer>

    <script>
        // ========== CUSTOM CURSOR ==========
        const dot = document.getElementById('cursorDot');
        const ring = document.getElementById('cursorRing');
        let dx = 0, dy = 0, rx = 0, ry = 0;

        document.addEventListener('mousemove', (e) => {
            dx = e.clientX; dy = e.clientY;
            dot.style.left = dx - 4 + 'px';
            dot.style.top = dy - 4 + 'px';
        });

        function loopCursor() {
            rx += (dx - rx) * 0.12;
            ry += (dy - ry) * 0.12;
            ring.style.left = rx - 20 + 'px';
            ring.style.top = ry - 20 + 'px';
            requestAnimationFrame(loopCursor);
        }
        loopCursor();

        document.querySelectorAll('a, button, .menu-pill, .menu-summary-card, .gallery-item, .service-card, .feature-card, .testimonial-card, .contact-item, .about-hl').forEach(el => {
            el.addEventListener('mouseenter', () => ring.classList.add('hover'));
            el.addEventListener('mouseleave', () => ring.classList.remove('hover'));
        });
        document.addEventListener('mousedown', () => ring.classList.add('click'));
        document.addEventListener('mouseup', () => ring.classList.remove('click'));

        // ========== MAGNETIC BUTTONS ==========
        document.querySelectorAll('.magnetic').forEach(btn => {
            btn.addEventListener('mousemove', (e) => {
                const rect = btn.getBoundingClientRect();
                const x = e.clientX - rect.left - rect.width / 2;
                const y = e.clientY - rect.top - rect.height / 2;
                btn.style.transform = `translate(${x * 0.3}px, ${y * 0.3}px)`;
            });
            btn.addEventListener('mouseleave', () => {
                btn.style.transform = 'translate(0,0)';
            });
        });

        // ========== SCROLL PROGRESS ==========
        const progressBar = document.getElementById('scrollProgress');
        window.addEventListener('scroll', () => {
            const st = window.scrollY;
            const dh = document.documentElement.scrollHeight - window.innerHeight;
            progressBar.style.width = (st / dh * 100) + '%';
        });

        // ========== PARTICLES ==========
        const canvas = document.getElementById('particle-canvas');
        const ctx = canvas.getContext('2d');
        let pts = [], mx = 0, my = 0;

        function resize() { canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
        resize(); window.addEventListener('resize', resize);

        class P {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.s = Math.random() * 2 + 0.5;
                this.vx = (Math.random() - 0.5) * 0.3;
                this.vy = (Math.random() - 0.5) * 0.3;
                this.o = Math.random() * 0.4 + 0.1;
                this.c = Math.random() > 0.5 ? '232,197,71' : '201,162,39';
            }
            update() {
                this.x += this.vx; this.y += this.vy;
                const dx = mx - this.x, dy = my - this.y;
                const d = Math.sqrt(dx*dx + dy*dy);
                if (d < 200) { const f = (200-d)/200; this.x -= dx*f*0.01; this.y -= dy*f*0.01; }
                if (this.x < 0 || this.x > canvas.width) this.vx *= -1;
                if (this.y < 0 || this.y > canvas.height) this.vy *= -1;
            }
            draw() {
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.s, 0, Math.PI*2);
                ctx.fillStyle = `rgba(${this.c},${this.o})`;
                ctx.fill();
            }
        }

        for (let i = 0; i < 80; i++) pts.push(new P());

        function connect() {
            for (let i = 0; i < pts.length; i++) {
                for (let j = i+1; j < pts.length; j++) {
                    const dx = pts[i].x - pts[j].x, dy = pts[i].y - pts[j].y;
                    const d = Math.sqrt(dx*dx + dy*dy);
                    if (d < 130) {
                        ctx.beginPath();
                        ctx.strokeStyle = `rgba(232,197,71,${0.06*(1-d/130)})`;
                        ctx.lineWidth = 0.5;
                        ctx.moveTo(pts[i].x, pts[i].y);
                        ctx.lineTo(pts[j].x, pts[j].y);
                        ctx.stroke();
                    }
                }
            }
        }

        function anim() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            pts.forEach(p => { p.update(); p.draw(); });
            connect();
            requestAnimationFrame(anim);
        }
        anim();
        document.addEventListener('mousemove', (e) => { mx = e.clientX; my = e.clientY; });

        // ========== LOADER ==========
        window.addEventListener('load', () => {
            setTimeout(() => {
                document.getElementById('loader').classList.add('hidden');
                document.querySelector('.hero').classList.add('loaded');
            }, 2500);
        });

        // ========== NAVBAR ==========
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            navbar.classList.toggle('scrolled', window.scrollY > 50);
        });

        // ========== MOBILE MENU ==========
        document.getElementById('mobileMenuBtn').addEventListener('click', () => {
            document.getElementById('navLinks').classList.toggle('active');
        });
        document.querySelectorAll('.nav-links a').forEach(a => {
            a.addEventListener('click', () => document.getElementById('navLinks').classList.remove('active'));
        });

        // ========== HERO WORD SPLIT ==========
        const heroTitle = document.getElementById('heroTitle');
        const words = 'Luxury Platters & Bespoke Catering Experiences'.split(' ');
        words.forEach((w, i) => {
            const s = document.createElement('span');
            s.className = 'word';
            s.textContent = w + ' ';
            s.style.animationDelay = (0.4 + i * 0.1) + 's';
            heroTitle.appendChild(s);
        });

        // ========== SCROLL REVEAL ==========
        const revealObs = new IntersectionObserver((entries) => {
            entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('active'); });
        }, { threshold: 0.1 });
        document.querySelectorAll('.reveal').forEach(el => revealObs.observe(el));

        // ========== ANIMATED COUNTERS ==========
        const countObs = new IntersectionObserver((entries) => {
            entries.forEach(e => {
                if (e.isIntersecting) {
                    const el = e.target;
                    const target = parseFloat(el.dataset.target);
                    const dec = el.dataset.decimal === 'true';
                    const suf = el.dataset.suffix || '';
                    const num = el.querySelector('.stat-num');
                    let cur = 0;
                    const inc = target / 50;
                    const timer = setInterval(() => {
                        cur += inc;
                        if (cur >= target) { cur = target; clearInterval(timer); }
                        num.textContent = (dec ? cur.toFixed(1) : Math.floor(cur)) + suf;
                    }, 30);
                    countObs.unobserve(el);
                }
            });
        }, { threshold: 0.5 });
        document.querySelectorAll('.stat-item').forEach(el => countObs.observe(el));

        // ========== SMOOTH SCROLL ==========
        document.querySelectorAll('a[href^="#"]').forEach(a => {
            a.addEventListener('click', function(e) {
                const href = this.getAttribute('href');
                if (!href || href === '#') {
                    e.preventDefault();
                    return;
                }
                const t = document.querySelector(href);
                if (!t) return;
                e.preventDefault();
                t.scrollIntoView({ behavior: 'smooth', block: 'start' });
            });
        });

        // ========== STATIC FORM FALLBACK ==========
        const contactForm = document.getElementById('contactForm');
        const formStatus = document.getElementById('formStatus');
        if (contactForm) {
            contactForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const data = new FormData(contactForm);
                const eventType = data.get('event_type') || 'Event Inquiry';
                const recipient = contactForm.dataset.recipient || 'hello@thelemonbowl.in';
                const body = [
                    'Hello The Lemon Bowl,',
                    '',
                    'I would like to book an event. Here are my details:',
                    '',
                    `Name: ${data.get('firstname') || ''} ${data.get('lastname') || ''}`.trim(),
                    `Email: ${data.get('email') || ''}`,
                    `Phone: ${data.get('phone') || ''}`,
                    `Event date: ${data.get('date') || ''}`,
                    `Guests: ${data.get('guests') || ''}`,
                    `Event type: ${eventType}`,
                    `Message: ${data.get('message') || 'No additional details provided.'}`
                ].join('\n');

                if (formStatus) {
                    formStatus.textContent = 'Opening your email app with a pre-filled inquiry.';
                }

                window.location.href = `mailto:${recipient}?subject=${encodeURIComponent(`Event Inquiry - ${eventType}`)}&body=${encodeURIComponent(body)}`;
            });
        }

        // ========== TEXT SCRAMBLE ON NAV HOVER ==========
        const chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz';
        document.querySelectorAll('.nav-links a:not(.nav-cta)').forEach(link => {
            const original = link.textContent;
            link.addEventListener('mouseenter', () => {
                let iter = 0;
                const interval = setInterval(() => {
                    link.textContent = original.split('').map((c, i) => {
                        if (i < iter) return original[i];
                        return chars[Math.floor(Math.random() * chars.length)];
                    }).join('');
                    if (iter >= original.length) clearInterval(interval);
                    iter += 1/2;
                }, 30);
            });
            link.addEventListener('mouseleave', () => { link.textContent = original; });
        });
    </script>
</body>
</html>
