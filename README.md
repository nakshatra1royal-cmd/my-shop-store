# my-shop-store
/* style.css */
body { font-family: sans-serif; margin: 0; background: #f4f4f9; color: #333; text-align: center; }
header { background: #1f2937; color: white; padding: 20px; }
.product-container { display: flex; justify-content: center; padding: 40px; }
.product-card { background: white; padding: 30px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); max-width: 300px; }
.price { font-size: 1.5rem; color: #059669; font-weight: bold; margin: 10px 0; }
.buy-btn { background: #2563eb; color: white; border: none; padding: 10px 20px; border-radius: 4px; cursor: pointer; font-size: 1rem; }
.buy-btn:hover { background: #1d4ed8; }
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Online Shop</h1>
    </header>
    <main class="product-container">
        <div class="product-card">
            <h2>Premium Product</h2>
            <p class="price">$19.99</p>
            <p class="description">This is a sleek, coded storefront item ready for customers.</p>
            <button class="buy-btn">Add to Cart</button>
        </div>
    </main>
</body>
</html>
