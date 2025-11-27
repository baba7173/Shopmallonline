<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Product Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Product Gallery</h1>
    </header>

    <section id="gallery">
        <!-- Example product -->
        <div class="product-card" onclick="interactProduct(this)">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <p>Product 1 description here</p>
        </div>

        <div class="product-card" onclick="interactProduct(this)">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <p>Product 2 description here</p>
        </div>

        <!-- Add more products like above -->
    </section>

    <button id="bye-btn">Bye</button>

    <script src="script.js"></script>
</body>
</html>
