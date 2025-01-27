<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fizen Delights</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8e1;
            color: #4a4a4a;
        }

        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
            background-color: #ff6f61;
            color: white;
        }

        header img {
            height: 60px;
        }

        header h1 {
            margin: 0;
            font-size: 2rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 50px;
            background-image: url('dessert-shop.jpg'); /* Replace with your image file */
            background-size: cover;
            background-position: center;
            color: white;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .product {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: auto;
        }

        .product h3 {
            margin: 10px 0;
            font-size: 1.5rem;
        }

        .product p {
            margin: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #ff6f61;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="fizen delights logo03.png" alt="Fizen Delights Logo"> 
        <h1>Fizen Delights</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
      
    <section style="background-color: #ffcccb; padding: 20px; color: goldenrod" class="hero" id="home"; >
        <h2>Welcome to Fizen Delights</h2>
        <p>Your one-stop shop for heavenly desserts!</p>
    </section>
    

    <section class="products" id="products">`
        <div class="product">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQ7S_813XCcYk709ruNLH72DF_B99F8SsQNw&s" alt="Delicious Cake"> 
            <h3>Chocolate Cake</h3>
            <p>Rich and moist chocolate cake topped with creamy frosting.</p>
        </div>
        <div class="product">
            <img src="https://images.aws.nestle.recipes/resized/5b069c3ed2feea79377014f6766fcd49_Original_NTH_Chocolate_Chip_Cookie_1080_850.jpg" alt="Tasty Cookies"> 
            <h3>Assorted Cookies</h3>
            <p>Crunchy and delicious cookies in a variety of flavors.</p>
        </div>
        <div class="product">
            <img src="https://carveyourcraving.com/wp-content/uploads/2021/06/chocolate-icecream-in-an-icecream-maker.jpg" alt="Ice Cream"> 
            <h3>Ice Cream Sundae</h3>
            <p>Cool and creamy ice cream topped with chocolate syrup and nuts.</p>
        </div>
    </section>

    <footer id="contact">
        <p>Contact us at <a href="mailto:info@fizendelights.com">info@fizendelights.com</a></p>
        <p>&copy; 2025 Fizen Delights. All rights reserved.</p>
    </footer>
</body>
</html>
