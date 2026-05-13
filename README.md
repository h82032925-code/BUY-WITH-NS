# BUY-WITH-NS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>H By With Ns - Premium Luxury Store</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a3e 50%, #2d1b69 100%);
            color: #fff;
            overflow-x: hidden;
        }
        
        /* Header */
        header { 
            background: rgba(0,0,0,0.9); 
            padding: 1rem 0; 
            position: fixed; 
            width: 100%; 
            top: 0; 
            z-index: 1000;
            backdrop-filter: blur(10px);
        }
        nav { 
            max-width: 1200px; 
            margin: 0 auto; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            padding: 0 2rem;
        }
        .logo { 
            font-size: 2rem; 
            font-weight: bold; 
            background: linear-gradient(45deg, #ffd700, #ff6b6b); 
            -webkit-background-clip: text; 
            -webkit-text-fill-color: transparent;
        }
        .nav-links { display: flex; gap: 2rem; }
        .nav-links a { color: #fff; text-decoration: none; font-weight: 500; transition: 0.3s; }
        .nav-links a:hover { color: #ffd700; }
        
        /* Hero Section */
        .hero { 
            height: 100vh; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            text-align: center; 
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 1000"><defs><radialGradient id="a" cx="50%" cy="50%"><stop offset="0%" stop-color="%23ffd700"/><stop offset="100%" stop-color="%23ff6b6b"/></radialGradient></defs><rect width="100%" height="100%" fill="url(%23a)"/></svg>') center/cover;
            position: relative;
        }
        .hero::before { 
            content: ''; 
            position: absolute; 
            top: 0; left: 0; 
            right: 0; bottom: 0; 
            background: rgba(0,0,0,0.6); 
        }
        .hero-content { position: relative; z-index: 2; }
        .india-flag { 
            font-size: 3rem; 
            margin-bottom: 1rem; 
            animation: pulse 2s infinite;
        }
        @keyframes pulse { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.1); } }
        .hero h1 { font-size: 4rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.5rem; margin-bottom: 2rem; }
        .cta-btn { 
            background: linear-gradient(45deg, #ffd700, #ff6b6b); 
            color: #000; 
            padding: 1rem 2rem; 
            border: none; 
            border-radius: 50px; 
            font-size: 1.2rem; 
            font-weight: bold; 
            cursor: pointer; 
            transition: 0.3s; 
            text-decoration: none; 
            display: inline-block;
        }
        .cta-btn:hover { transform: scale(1.05); box-shadow: 0 10px 30px rgba(255,215,0,0.5); }
        
        /* Products */
        .products { padding: 5rem 2rem; max-width: 1200px; margin: 0 auto; }
        .section-title { text-align: center; font-size: 3rem; margin-bottom: 3rem; }
        .products-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .product-card { 
            background: rgba(255,255,255,0.1); 
            border-radius: 20px; 
            padding: 2rem; 
            text-align: center; 
            backdrop-filter: blur(10px); 
            border: 1px solid rgba(255,255,255,0.2);
            transition: 0.3s;
        }
        .product-card:hover { transform: translateY(-10px); box-shadow: 0 20px 40px rgba(0,0,0,0.3); }
        .product-img { width: 100%; height: 200px; background: linear-gradient(45deg, #ffd700, #ff6b6b); border-radius: 15px; margin-bottom: 1rem; display: flex; align-items: center; justify-content: center; font-size: 3rem; }
        .product-price { font-size: 2rem; color: #ffd700; font-weight: bold; margin: 1rem 0; }
        .product-btn { 
            background: linear-gradient(45deg, #00d4ff, #0099cc); 
            color: white; 
            border: none; 
            padding: 0.8rem 1.5rem; 
            border-radius: 25px; 
            cursor: pointer; 
            font-weight: bold;
        }
        
        /* Footer */
        footer { background: rgba(0,0,0,0.9); padding: 2rem; text-align: center; }
        
        @media (max-width: 768px) { 
            .hero h1 { font-size: 2.5rem; }
            .nav-links { display: none; }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <div class="logo">H By With Ns</div>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#products">Shop</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <!-- Hero -->
    <section id="home" class="hero">
        <div class="hero-content">
            <div class="india-flag">🇮🇳</div>
            <h1>H By With Ns</h1>
            <p>Premium Luxury Products | Starting ₹500+</p>
            <a href="#products" class="cta-btn">SHOP PREMIUM COLLECTION</a>
        </div>
    </section>

    <!-- Products -->
    <section id="products" class="products">
        <h2 class="section-title">PREMIUM COLLECTION</h2>
        <div class="products-grid">
            <div class="product-card">
                <div class="product-img">👔</div>
                <h3>Luxury Designer Shirt</h3>
                <div class="product-price">₹1,299</div>
                <button class="product-btn">ADD TO CART</button>
            </div>
            <div class="product-card">
                <div class="product-img">⌚</div>
                <h3>Premium Watch</h3>
                <div class="product-price">₹5,999</div>
                <button class="product-btn">ADD TO CART</button>
            </div>
            <div class="product-card">
                <div class="product-img">👟</div>
                <h3>Luxury Sneakers</h3>
                <div class="product-price">₹3,499</div>
                <button class="product-btn">ADD TO CART</button>
            </div>
            <div class="product-card">
                <div class="product-img">💍</div>
                <h3>Diamond Ring</h3>
                <div class="product-price">₹12,999</div>
                <button class="product-btn">ADD TO CART</button>
            </div>
            <div class="product-card">
                <div class="product-img">👜</div>
                <h3>Designer Handbag</h3>
                <div class="product-price">₹8,799</div>
                <button class="product-btn">ADD TO CART</button>
            </div>
            <div class="product-card">
                <div class="product-img">👓</div>
                <h3>Premium Sunglasses</h3>
                <div class="product-price">₹2,199</div>
                <button class="product-btn">ADD TO CART</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 H By With Ns | Premium Luxury Store 🇮🇳 | All Rights Reserved</p>
    </footer>
</body>
</html>
