- 👋 Hi, I’m @hassan0121
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple E-Commerce Website</title>
    <style>
        /* Basic styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            width: 30%;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            margin: 10px 0;
            color: #666;
        }
        .product .price {
            font-size: 1.2em;
            font-weight: bold;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>My Online Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <div class="container">
        <h2>Featured Products</h2>
        <div class="products">
            <!-- Product 1 -->
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 1">
                <h3>Product 1</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <p class="price">$19.99</p>
                <button>Add to Cart</button>
            </div>
            <!-- Product 2 -->
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 2">
                <h3>Product 2</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <p class="price">$29.99</p>
                <button>Add to Cart</button>
            </div>
            <!-- Product 3 -->
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 3">
                <h3>Product 3</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <p class="price">$39.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>Copyright &copy; 2024 My Online Store. All rights reserved.</p>
    </footer>

</body>
</html>
