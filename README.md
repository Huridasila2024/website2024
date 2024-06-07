<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Products</title>
    <link rel="stylesheet" href="styles.css">
    <style>
    *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background-color: white; 
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    line-height: 1.6;
}
nav {
    background-color: grey;
    padding: 20px 0;
    text-align: center;
} 
nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}
nav ul li {
    display: inline-block;
    margin-right: 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

.products {
    padding: 40pt;
    text-align: center;
}
.products h1{
    color: pink;
    font-size: 36px;
    margin-bottom: 30px;
}
.products h2 {
    color: gold;
    font-size: 36px;
    margin-bottom: 30px;
}
.product-description {
    display: flex;
    max-width: 200px;
    text-align: center;
    margin-bottom: 20px; 
}
.image-container {
    display:flex;
    justify-content:space-between;
    flex-wrap: wrap; 
    gap: 20px;
    padding: 20px;
}
    img {
            max-width: 200px; 
            height: auto; 
            border: 1px solid#ccc;
            transition: transform 0.3s ease;
            cursor: pointer;
        }

    img:hover {
            transform: scale(10.3s)
        }


.footer {
    background-color: #333;
    color: #fff;
    padding: 50px 0;
    text-align: center;
}

.footer .container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.footer-col {
    width: calc(33.33% - 30px);
    margin: initial 20px;
    text-align: center;
}

.footer-col h4 {
    font-size: 20px;
    margin-bottom: 20px;
    color: #fff;
}

.footer-col ul {
    list-style: none;
    padding: 0;
}

.footer-col ul li {
    margin-bottom: 10px;
}

.footer-col ul li a {
    color: #bbb;
    text-decoration: none;
    transition: color 0.3s ease;
}

.footer-col ul li a:hover {
    color: #fff;
}
  </style>

 </head>
<body>
    <nav>   
        <ul>
            <li><a href="toys.html">HOME</a></li>  
            <li><a href="products.html">Products</a></li>
            <li><a href="contacts.html">Contact Us</a></li>
        
        </ul>
    </nav>

    <div class="container services">
        <h1>Our Products</h1>
        <div class="image-container">
            <div class="procduct-description">
                <h2>Bricks</h2>
                <p></p>
                <img src="img\pexels-pixabay-163036.jpg"alt="prod1.jpg">
            </div>

            <div class="service-description">
                <h2>Ladders</h2>
                 
                <img src="img\pexels-polesietoys-6129704.jpg" alt="prod2.jpg">
            </div>

            <div class="product-description"></div>
                <h2>Climbers</h2>
                <p></p>
                <img src="img\pexels-polesietoys-5997695.jpg" alt="prod3.jpg">
            </div>
            <div class="product-description">
              <h2>Markins</h2>
              <p></p>
              <img src="img\pexels-polesietoys-5997582.jpg" alt="prod4.jpg">
          </div>
          <div class="product-description">
          <h2>Grips</h2>
            <p></p>
              <img src="img\pexels-yankrukov-8612928.jpg" alt="prod5.jpg">
          </div>
          <div class="product-description">
            <h2>Titins</h2>
            <p></p>
            <img src="img\pexels-karolina-grabowska-4887257.jpg" alt="prod6.jpg">
        </div>
        
        </div>
    </div>
    
        <footer class="footer">
            <p>&copy; 2024 Toyland. All rights reserved</p>
          </footer>
    </footer>
</body>
</html>
