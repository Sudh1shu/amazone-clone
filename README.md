<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #364f6d;
            color: rgb(231, 227, 237);
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        header .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            display: flex;
            gap: 15px;
        }
        nav a {
            color: rgba(245, 237, 237, 0.35);
            text-decoration: none;
            font-size: 16px;
        }
        .search-bar {
            display: flex;
            gap: 5px;
        }
        .search-bar input {
            padding: 5px;
            width: 300px;
        }
        .search-bar button {
            padding: 5px 10px;
            background-color: #febd69;
            border: none;
            cursor: pointer;
        }
        .product-section {
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #dbdee2;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">Amazon </div>
    <div class="search-bar">
        <input type="text" placeholder="Search products">
        <button>Search</button>
    </div>
    <nav>
        <a href="#">Sign In</a>
        <a href="#">Orders</a>
        <a href="#">Cart</a>
        <a href="#">buy</a>
    </nav>
</header>

<section class="product-section">
    <div class="product">
        <img src="https://in.puma.com" alt="Running Shoes">
        <h3>puma Shoes</h3>
        <p>200.00</p>
        <button>Add to Cart</button>
    </div>
    <div class="product">
        <img src="https://www.nike.com/" alt="Sports Shoes">
        <h3>nike Shoes</h3>
        <p>500.00</p>
        <button>Add to Cart</button>
    </div>
    <div class="product">

            <img src="https://www bata.com" alt="formal Shoes">
        <h3>bata Shoes</h3>
        <p>300.00</p>
        <button>Add to Cart</button>
    </div>
</section>

<footer>
    <p>&copy; 2025 Amazon Clone. All rights reserved.</p>
</footer>

</body>
</html>

