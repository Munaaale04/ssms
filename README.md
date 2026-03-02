<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aroma Bliss - Perfumes & Fragrance Oils</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background: #fff8f5;
            color: #333;
        }

        /* Header */
        header {
            background: #f7e6f0;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            color: #b045a6;
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
            color: #6a4a7b;
        }

        /* Navigation */
        nav {
            background: #e7cfe3;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav a {
            text-decoration: none;
            color: #4a1a5e;
            margin: 0 15px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #fff;
            background: #b045a6;
            padding: 5px 10px;
            border-radius: 5px;
        }

        /* Banner */
        .banner {
            background: url('https://images.unsplash.com/photo-1581579183093-0ff64b7f14b7?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTc2N3wwfDF8c2VhcmNofDJ8fHBlcmZ1bWV8ZW58MHx8fHwxNjgyMjcwODQx&ixlib=rb-4.0.3&q=80&w=1080') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-shadow: 2px 2px 8px rgba(0,0,0,0.7);
        }

        .banner h2 {
            font-size: 3em;
            background: rgba(180, 69, 166, 0.4);
            padding: 20px 40px;
            border-radius: 10px;
        }

        /* Products Section */
        .products {
            padding: 50px 20px;
            text-align: center;
        }

        .products h2 {
            color: #b045a6;
            margin-bottom: 30px;
            font-size: 2em;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: #fff0f5;
            border-radius: 15px;
            padding: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }

        .product-card img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .product-card h3 {
            color: #4a1a5e;
            margin-bottom: 10px;
        }

        .product-card p {
            color: #6a4a7b;
        }

        /* Footer */
        footer {
            background: #f7e6f0;
            padding: 20px;
            text-align: center;
            margin-top: 50px;
            color: #4a1a5e;
        }

        /* Button */
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #b045a6;
            color: #fff;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: #4a1a5e;
        }
    </style>
</head>
<body>

    <header>
        <h1>Aroma Bliss</h1>
        <p>Luxury Perfumes & Fragrance Oils</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="banner" id="home">
        <h2>Feel the Essence of Bliss</h2>
    </section>

    <section class="products" id="products">
        <h2>Our Featured Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1590073240074-0cb92de03f12?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Lavender Perfume">
                <h3>Lavender Delight</h3>
                <p>Refreshing lavender fragrance for a calming experience.</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1615554819793-25a8ff7c8494?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Rose Perfume">
                <h3>Rose Elegance</h3>
                <p>Romantic rose aroma that lasts all day.</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1621716748296-3f144d66c3cf?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Jasmine Perfume">
                <h3>Jasmine Bliss</h3>
                <p>Exquisite jasmine fragrance that lifts your mood.</p>
                <a href="#" class="btn">Buy Now</a>
            </div>
        </div>
    </section>

    <section class="about" id="about" style="padding:50px 20px; text-align:center; background:#fceef5;">
        <h2 style="color:#b045a6;">About Aroma Bliss</h2>
        <p style="max-width:800px; margin:20px auto; color:#6a4a7b;">
            Aroma Bliss is your ultimate destination for premium perfumes and fragrance oils. Our scents are crafted to bring luxury, relaxation, and joy into your daily life. Each bottle is designed with love, quality, and elegance.
        </p>
    </section>

    <section class="contact" id="contact" style="padding:50px 20px; text-align:center;">
        <h2 style="color:#b045a6;">Contact Us</h2>
        <p>Email: contact@aromabliss.com</p>
        <p>Phone: +977 9801234567</p>
        <p>Location: Kathmandu, Nepal</p>
        <a href="#" class="btn">Send Message</a>
    </section>

    <footer>
        &copy; 2026 Aroma Bliss. All rights reserved.
    </footer>

</body>
</html>
