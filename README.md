# Sweet
Cheesecake and more 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Ordering Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Foodie Delight</div>
        <nav>
            <ul>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#cart">Cart</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#register">Register</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="hero">
        <h1>Welcome to Foodie Delight</h1>
        <p>Order your favorite meals quickly and easily!</p>
        <button onclick="scrollToMenu()">Explore the Menu</button>
    </section>

    <section id="menu" class="menu-section">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="food-card">
                <img src="food-item1.jpg" alt="Food Item">
                <h3>Pizza Margherita</h3>
                <p>A classic Italian pizza with fresh basil and mozzarella.</p>
                <p class="price">$12.99</p>
                <div class="ratings">★★★★☆</div>
                <button onclick="addToCart('Pizza Margherita', 12.99)">Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="cart" class="cart-section">
        <h2>Your Cart</h2>
        <div id="cart-items"></div>
        <button onclick="checkout()">Checkout</button>
    </section>

    <section id="register" class="register-section">
        <h2>Register</h2>
        <form id="registration-form">
            <input type="text" id="phone" placeholder="Enter your phone number" required>
            <button type="submit">Register</button>
        </form>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>Email: support@foodiedelight.com</p>
        <p>Phone: +123 456 7890</p>
        <p>Location: 123 Foodie St, Flavor Town</p>
    </section>

    <script src="script.js"></script>
</body>
</html>
