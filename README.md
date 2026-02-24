# Ex02 Commercial Website
## Date:24:2:2026
## name:mohan.m
## reg no:212224220064

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SPADE | Quality Products</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation Bar -->
    <header>
        <nav class="navbar">
            <div class="logo">SPADE</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="section">
        <div class="content">
            <h1>Welcome to SPADE</h1>
            <p>Your trusted store for quality products at affordable prices.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="section">
        <h2>Our Products</h2>

        <div class="product-container">
            <div class="product">
                <h3>Product 1</h3>
                <p>High-quality item for everyday use.</p>
                <p class="price">₹500</p>
                <button>Add to Cart</button>
            </div>

            <div class="product">
                <h3>Product 2</h3>
                <p>Reliable and affordable premium product.</p>
                <p class="price">₹700</p>
                <button>Add to Cart</button>
            </div>

            <div class="product">
                <h3>Product 3</h3>
                <p>Top-rated product loved by customers.</p>
                <p class="price">₹900</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>
            SPADE is a trusted company serving customers since 2020.
            We focus on delivering high-quality products with excellent customer service.
        </p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: mohan@gmail.com</p>
        <p>Phone:  9876543210</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 SPADE. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
style.css
```
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Navbar */
.navbar {
    background-color: #111;
    color: #fff;
    padding: 15px;
    text-align: center;
    font-size: 20px;
    font-weight: bold;
    position: sticky;
    top: 0;
}

/* Sections */
section {
    padding: 20px 15px;
    text-align: center;
}

h1, h2 {
    margin-bottom: 10px;
}

p {
    margin-bottom: 10px;
    color: #555;
}

/* Product Cards */
.product-container {
    display: flex;
    flex-direction: column; /* Mobile stacked */
    gap: 15px;
    margin-top: 15px;
}

.product {
    background: #fff;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.product h3 {
    margin-bottom: 8px;
}

.price {
    font-weight: bold;
    margin: 10px 0;
    font-size: 16px;
    color: #000;
}

/* Button */
button {
    width: 100%;
    padding: 10px;
    background-color: #111;
    color: white;
    border: none;
    border-radius: 6px;
    font-size: 16px;
    cursor: pointer;
}

button:active {
    background-color: #333;
}

/* Footer */
footer {
    background-color: #111;
    color: white;
    text-align: center;
    padding: 15px;
    font-size: 14px;
    margin-top: 20px;
}

/* Responsive for larger screens */
@media (min-width: 768px) {
    .product-container {
        flex-direction: row;
        justify-content: center;
    }

    .product {
        width: 250px;
    }
}
~~~

## OUTPUT

<img width="1886" height="1040" alt="Screenshot 2026-02-24 135057" src="https://github.com/user-attachments/assets/1daebe7c-8670-4a4d-b6df-7c56552a9e41" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
