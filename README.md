# starmatter-shop
Online shop starmatter for 3D-printed fanart
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3D Printed Fanart Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: white;
            margin-bottom: 20px;
            padding: 15px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 0;
            padding: 10px 0;
        }
        .product p {
            margin: 10px 0;
        }
        .product button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to the 3D Printed Fanart Shop</h1>
    <p>Find your favorite fanart in 3D printed form!</p>
</header>

<div class="container">
    <div class="product">
        <img src="product1.jpg" alt="Product 1">
        <h3>Product 1</h3>
        <p>Awesome 3D printed figure of your favorite character.</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="product2.jpg" alt="Product 2">
        <h3>Product 2</h3>
        <p>High-quality 3D printed sculpture for fans.</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="product3.jpg" alt="Product 3">
        <h3>Product 3</h3>
        <p>Unique 3D printed artwork for your collection.</p>
        <button>Add to Cart</button>
    </div>
</div>

<footer>
    <p>&copy; 2024 3D Printed Fanart Shop. All rights reserved.</p>
</footer>

</body>
</html>
