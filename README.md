<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Natural Treasures Export</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: linear-gradient(to right, #28a745, #a8e063);
            color: white;
            padding: 20px 10%;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 10px 0 0;
            font-size: 1.2em;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #f8f9fa;
            padding: 10px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            text-decoration: none;
            color: #28a745;
            margin: 0 15px;
            font-size: 1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x900/?fruits,herbs') no-repeat center/cover;
            height: 50vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            text-align: center;
        }
        .hero h2 {
            font-size: 3em;
            margin: 0;
        }
        section {
            padding: 20px 10%;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            width: 30%;
            margin: 15px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
            background: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0;
            font-size: 1.5em;
            color: #28a745;
        }
        .product p {
            font-size: 1em;
            color: #555;
        }
        .contact {
            background: #f8f9fa;
            padding: 20px;
            text-align: center;
        }
        .contact h2 {
            color: #28a745;
        }
        footer {
            background: #28a745;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Natural Treasures Export</h1>
        <p>Fried Fruits, Chamomile, and Herbal Essences Directly from Nature</p>
    </header>
    <nav>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h2>Pure Nature in Every Drop and Bite</h2>
    </div>
    <section id="products">
        <h2>Our Products</h2>
        <div class="products">
            <div class="product">
                <img src="https://source.unsplash.com/400x300/?dried-fruits" alt="Fried Fruits">
                <h3>Fried Fruits</h3>
                <p>Deliciously crispy and naturally sweet dried fruits.</p>
            </div>
            <div class="product">
                <img src="https://source.unsplash.com/400x300/?chamomile" alt="Chamomile">
                <h3>Chamomile</h3>
                <p>Soothing chamomile flowers for teas and natural remedies.</p>
            </div>
            <div class="product">
                <img src="https://source.unsplash.com/400x300/?herbs" alt="Herbal Essences">
                <h3>Herbal Essences</h3>
                <p>Premium herbal extracts for health and beauty.</p>
            </div>
        </div>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We specialize in bringing the finest natural products from our homeland to your doorstep. With a commitment to quality and sustainability, our fried fruits, chamomile, and herbal essences are sourced directly from nature.</p>
    </section>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: export@naturaltreasures.com</p>
        <p>Phone: +98 123 456 7890</p>
        <p>Address: Soochahri Village, Khorramdarreh, Zanjan, Iran</p>
    </section>
    <footer>
        <p>&copy; 2024 Natural Treasures Export. All Rights Reserved.</p>
    </footer>
</body>
</html>
