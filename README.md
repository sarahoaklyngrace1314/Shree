# Shree
Shree Jewelry Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shree Jewelry</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f9f9f9; color: #333; }
        header { background-color: #d4af37; color: white; padding: 20px; text-align: center; }
        nav { background-color: #333; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        .hero { background-image: url('https://via.placeholder.com/1200x400?text=Shree+Jewelry+Hero'); background-size: cover; height: 400px; display: flex; align-items: center; justify-content: center; color: white; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .section { padding: 40px; max-width: 1200px; margin: auto; }
        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .product { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
        .product img { width: 100%; height: 200px; object-fit: cover; }
        footer { background-color: #333; color: white; text-align: center; padding: 20px; }
        form { max-width: 500px; margin: auto; }
        input, textarea { width: 100%; padding: 10px; margin: 10px 0; }
        button { background-color: #d4af37; color: white; padding: 10px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Shree Jewelry</h1>
        <p>Elegant Designs for Every Occasion</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="home" class="hero">
        <div>
            <h2>Welcome to Shree Jewelry</h2>
            <p>Discover timeless pieces crafted with care.</p>
        </div>
    </section>
    
    <section id="products" class="section">
        <h2>Our Collection</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/250x200?text=Gold+Necklace" alt="Gold Necklace">
                <h3>Gold Necklace</h3>
                <p>$299.99</p>
                <button onclick="alert('Added to cart!')">Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x200?text=Diamond+Earrings" alt="Diamond Earrings">
                <h3>Diamond Earrings</h3>
                <p>$199.99</p>
                <button onclick="alert('Added to cart!')">Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x200?text=Silver+Bracelet" alt="Silver Bracelet">
                <h3>Silver Bracelet</h3>
                <p>$149.99</p>
                <button onclick="alert('Added to cart!')">Add to Cart</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </section>
    
    <section id="about" class="section">
        <h2>About Shree</h2>
        <p>Shree Jewelry has been crafting exquisite pieces since 1990. We specialize in gold, silver, and gemstone jewelry, ensuring quality and elegance.</p>
    </section>
    
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2023 Shree Jewelry. All rights reserved.</p>
    </footer>
    
    <script>
        // Simple form submission alert (replace with real backend if needed)
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message!');
        });
    </script>
</body>
</html>
