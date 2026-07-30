# Ex02 Commercial Website
## Date: 30-07-2026

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
```
index.html
```
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>EASY CART</title>

    <link rel="stylesheet" href="Ccomweb.css">

  <style>
    body { font-family: Arial; margin: 0; }
    header { background: #333; color: white; padding: 10px; text-align: center; }
    nav { background: #555; display: flex; justify-content: center; }
    nav a { color: white; padding: 10px 15px; text-decoration: none; }
    nav a:hover { background: #777; }
    .products { display: flex; flex-wrap: wrap; gap: 10px; padding: 10px; }
    .card { background: #f9f9f9; padding: 10px; flex: 1 1 200px; text-align: center; border: 1px solid #ccc; }
    img { max-width: 100%; height: auto; }
    footer { background: #333; color: white; text-align: center; padding: 10px; }
  </style>
</head>
<body>

<header>
  <h1>EASY CART</h1>
</header>

<nav>
    <h2 style="color: whitesmoke; padding: 10px;">Mobiles</h2>
    <h2 style="color: whitesmoke; padding: 10px;">Electronics</h2>
    <h2 style="color: whitesmoke; padding: 10px;">Appliances</h2>
</nav>

<section id="mobiles">
    <h2 style="padding:10px;">Mobiles</h2>
    <div class="products">
        <div class="card">
            <img src="img1.png">
            <h3>Smartphone X</h3>
            <p>₹20,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img2.png">
            <h3>Budget Phone</h3>
            <p>₹10,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img3.png">
            <h3>Pro 5G</h3>
            <p>₹28,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img4.png">
            <h3>Lite Edition</h3>
            <p>₹8,500</p>
            <button class="add-cart">Add to Cart</button>
        </div>
    </div>
</section>

<section id="electronics">
    <h2 style="padding:10px;">Electronics</h2>
    <div class="products">
        <div class="card">
            <img src="img5.png">
            <h3>Laptop Pro</h3>
            <p>₹50,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img6.png">
            <h3>Headphones</h3>
            <p>₹3,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img7.png">
            <h3>DSLR Camera</h3>
            <p>₹45,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img8.png">
            <h3>Smart Watch</h3>
            <p>₹5,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>
    </div>
</section>

<section id="appliances">
    <h2 style="padding:10px;">Home Appliances</h2>
    <div class="products">
        <div class="card">
            <img src="img9.png">
            <h3>Refrigerator</h3>
            <p>₹25,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img10.png">
            <h3>Washing Machine</h3>
            <p>₹15,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img11.png">
            <h3>Microwave Oven</h3>
            <p>₹7,500</p>
            <button class="add-cart">Add to Cart</button>
        </div>

        <div class="card">
            <img src="img12.png">
            <h3>Air Conditioner</h3>
            <p>₹32,000</p>
            <button class="add-cart">Add to Cart</button>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <h2 style="color: black; padding: 15px;">Email: vignesh@example.com</h2>
    <h2 style="color: black; padding: 15px;">Address: Chittoor,Andhra pradesh, India</h2>
    <h2 style="color: black; padding: 15px;">Phone: +91-9908061390</h2>
</section>

<footer>
Vignesh P 212224040066
<p>&copy; 2026 EASY CART. All rights reserved.</p>
</footer>

</body>
</html>
```
```
style.css
```
```
body { 
    font-family: Arial; 
    margin: 0; 
}

header { 
    background: #333; 
    color: white; 
    padding: 10px; 
    text-align: center; 
}

nav { 
    background: #555; 
    display: flex; 
    justify-content: center; 
}

nav a { 
    color: white; 
    padding: 10px 15px; 
    text-decoration: none; 
}

nav a:hover { 
    background: #777; 
}

.products { 
    display: flex; 
    flex-wrap: wrap; 
    gap: 10px; 
    padding: 10px; 
}

.card { 
    background: #f9f9f9; 
    padding: 10px; 
    flex: 1 1 200px; 
    text-align: center; 
    border: 1px solid #ccc; 
}

img { 
    max-width: 100%; 
    height: auto; 
}

footer { 
    background: #333; 
    color: white; 
    text-align: center; 
    padding: 10px; 
}
```

## OUTPUT
<img width="1536" height="960" alt="ex2img1" src="https://github.com/user-attachments/assets/37a970c9-39bf-4046-8649-5d42a159a94f" />

<img width="1536" height="960" alt="ex2img2" src="https://github.com/user-attachments/assets/f4a52df1-b8c2-440d-a74c-3f615b4a50f9" />

<img width="1403" height="476" alt="Screenshot 2026-07-30 133712" src="https://github.com/user-attachments/assets/c4d06cdd-e271-425c-8952-ba1d7674bc7d" />
<img width="1536" height="433" alt="Screenshot 2026-07-30 133618" src="https://github.com/user-attachments/assets/dd535da7-5c68-413b-aaa1-abfc0dcd209f" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
