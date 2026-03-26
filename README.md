# Accessories-gallery-
Primume and high value mobile covers
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CoverHub - Premium Mobile Covers & Accessories</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <!-- Navigation -->
  <nav class="navbar">
    <div class="container">
      <div class="logo">
        <i class="fas fa-shield-alt"></i>
        <span>CoverHub</span>
      </div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Shop</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="cart-icon">
        <i class="fas fa-shopping-cart"></i>
        <span class="cart-count">0</span>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Protect Your Phone in Style</h1>
      <p>Premium mobile covers and accessories for every device</p>
      <button class="cta-button" onclick="document.getElementById('products').scrollIntoView({behavior: 'smooth'})">
        Shop Now
      </button>
    </div>
  </section>

  <!-- Products Section -->
  <section id="products" class="products">
    <div class="container">
      <h2>Our Collection</h2>
      
      <!-- Filter -->
      <div class="filters">
        <button class="filter-btn active" data-filter="all">All Products</button>
        <button class="filter-btn" data-filter="case">Cases</button>
        <button class="filter-btn" data-filter="screen-protector">Screen Protectors</button>
        <button class="filter-btn" data-filter="charger">Chargers</button>
        <button class="filter-btn" data-filter="stand">Stands</button>
      </div>

      <!-- Product Grid -->
      <div class="product-grid" id="productGrid">
        <!-- Products will be loaded here by JavaScript -->
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <div class="container">
      <h2>Why Choose CoverHub?</h2>
      <div class="features-grid">
        <div class="feature-card">
          <i class="fas fa-shield-alt"></i>
          <h3>Premium Quality</h3>
          <p>All products are made from high-quality, durable materials.</p>
        </div>
        <div class="feature-card">
          <i class="fas fa-truck"></i>
          <h3>Fast Shipping</h3>
          <p>Free shipping on orders over $50. Delivery in 2-5 business days.</p>
        </div>
        <div class="feature-card">
          <i class="fas fa-undo"></i>
          <h3>Easy Returns</h3>
          <p>30-day money-back guarantee. No questions asked.</p>
        </div>
        <div class="feature-card">
          <i class="fas fa-headset"></i>
          <h3>Customer Support</h3>
          <p>24/7 customer support to help you with any questions.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <div class="container">
      <h2>Get In Touch</h2>
      <form class="contact-form" id="contactForm">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button type="submit" class="submit-btn">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Cart Modal -->
  <div class="cart-modal" id="cartModal">
    <div class="cart-content">
      <span class="close">&times;</span>
      <h2>Shopping Cart</h2>
      <div class="cart-items" id="cartItems">
        <p class="empty-cart">Your cart is empty</p>
      </div>
      <div class="cart-summary">
        <p>Total: $<span id="cartTotal">0.00</span></p>
        <button class="checkout-btn">Proceed to Checkout</button>
      </div>
    </div>
  </div>

  <!-- Product Detail Modal -->
  <div class="product-modal" id="productModal">
    <div class="modal-content">
      <span class="close">&times;</span>
      <div class="modal-body">
        <img id="modalImage" src="" alt="">
        <div class="modal-info">
          <h2 id="modalTitle"></h2>
          <p id="modalDescription"></p>
          <p class="modal-price">$<span id="modalPrice"></span></p>
          <div class="quantity-selector">
            <button id="decreaseQty">-</button>
            <input type="number" id="quantity" value="1" min="1">
            <button id="increaseQty">+</button>
          </div>
          <button class="add-to-cart-btn">Add to Cart</button>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <div class="footer-content">
        <div class="footer-section">
          <h3>CoverHub</h3>
          <p>Your trusted source for premium mobile covers and accessories.</p>
        </div>
        <div class="footer-section">
          <h3>Quick Links</h3>
          <ul>
            <li><a href="#products">Shop</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#">Privacy Policy</a></li>
          </ul>
        </div>
        <div class="footer-section">
          <h3>Follow Us</h3>
          <div class="social-links">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; 2026 CoverHub. All rights reserved.</p>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
