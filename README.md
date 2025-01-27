<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cricket Store</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background: #004d00;
            color: white;
            padding: 15px 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 30%;
            margin: 15px;
            padding: 15px;
            border: 1px solid #ddd;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        button {
            background: #004d00;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
        }
        button:hover {
            background: #003300;
        }
        footer {
            background: #004d00;
            color: white;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cricket Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Welcome to the Best Cricket Store</h2>
        <p>Find the best quality cricket bats, balls, and other accessories.</p>
    </section>
    
    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="C:\Users\Hassan Nisar\Desktop\bat.jpg" alt="Cricket Bat">
            <h3>Cricket Bat</h3>
            <p>High-quality wooden bats for professional and amateur players.</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="C:\Users\Hassan Nisar\Desktop\ball.jpg" alt="Cricket Ball">
            <h3>Cricket Ball</h3>
            <p>Durable leather balls for matches and practice sessions.</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="C:\Users\Hassan Nisar\Desktop\gloves.jpg" alt="Gloves">
            <h3>Cricket Gloves</h3>
            <p>Comfortable and protective gloves for better grip and safety.</p>
            <button>Buy Now</button>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: hassannisar330@gmail.com</p>
        <p>Phone: 03370851959</p>
    </section>
    
    <footer>
        <p>&copy; HASSAN Cricket Store.</p>
    </footer>
</body>
</html>
