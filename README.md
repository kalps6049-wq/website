# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Home | Delicious Dine</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="contact.css">
</head>

<body style="text-align: center;background-color:cornflowerblue">

  <header>
    <h1>Delicious Dine Restaurant</h1>
  </header>

  <nav>
    <a href="home.html" class="active">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html">Our Team</a>
    <a href="product.html">Products</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section class="horizontal-gallery">
    <h2>Welcome to Delicious Dine</h2>
  </section>

  <section class="gallery-items">
    <h2>Our Special Menu</h2>
    <div class="menu-items">
      <div class="menu-item">
        <img src="pizza.png" alt="Pizza">
        <h3>Cheese Burst Pizza</h3>
        <p>Hot and fresh pizza loaded with mozzarella cheese.</p>
        <p class="price">₹299</p>
      </div>
      <div class="">
        <img src="biriyani.png" alt="Biryani">
        <h3>Hyderabadi Biryani</h3>
        <p>Authentic biryani with aromatic spices and tender meat.</p>
        <p class="price">₹349</p>
      </div>
      <div class="gallery-items">
        <img src="pasta.png" alt="Pasta">
        <h3>Creamy Alfredo Pasta</h3>
        <p>Delicious white sauce pasta with fresh herbs.</p>
        <p class="price">₹249</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Delicious Dine Restaurant | Designed by Kalpana</p>
  </footer>

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Menu | Delicious Dine</title>
  <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(236, 209, 190);text-align:center">

  <header>
    <h1>Delicious Dine Restaurant</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html" class="active">Menu</a>
    <a href="people.html">Our Team</a>
    <a href="product.html">Products</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section class="menu">
    <h2>Our Full Menu</h2>
    <div class="menu-items">
      <div class="menu-item">
        <img src="pizza.png" alt="Pizza">
        <h3>Cheese Burst Pizza</h3>
        <p>Hot and fresh pizza loaded with mozzarella cheese.</p>
        <p class="price">₹299</p>
      </div>
      <div class="menu-item">
        <img src="biriyani.png" alt="Biryani">
        <h3>Hyderabadi Biryani</h3>
        <p>Authentic biryani with aromatic spices and tender meat.</p>
        <p class="price">₹349</p>
      </div>
      <div class="menu-item">
        <img src="pasta.png" alt="Pasta">
        <h3>Creamy Alfredo Pasta</h3>
        <p>Delicious white sauce pasta with fresh herbs.</p>
        <p class="price">₹249</p>
      </div>
      <div class="menu-item">
        <img src="burger.png" alt="Burger">
        <h3>Classic Burger</h3>
        <p>Juicy beef patty with lettuce, tomato, and cheese.</p>
        <p class="price">₹199</p>
      </div>
      <div class="menu-item">
        <img src="fried rice.png" alt="Fried Rice">
        <h3>Veg Fried Rice</h3>
        <p>Stir-fried rice with fresh vegetables and spices.</p>
        <p class="price">₹179</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Delicious Dine Restaurant | Designed by Kalpana</p>
  </footer>

</body>
</html>

people.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Team | Delicious Dine</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="people.css">
</head>
<body style="background-color: cornflowerblue;text-align:center">

  <header>
    <h1>Delicious Dine Restaurant</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html" class="active">Our Team</a>
    <a href="product.html">Products</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section class="team-section">
    <h2>Meet Our Team</h2>
    <div class="team-container">
      <div class="team-member">
        <img src="person 1.jpeg" alt="Chef Arun">
        <h3>Chef Arun Kumar</h3>
        <p class="role">Head Chef</p>
        <p class="bio">Expert in traditional South Indian cuisine and modern presentation.</p>
      </div>
      <div class="team-member">
        <img src="person 2.jpeg" alt="Manager Priya">
        <h3>Priya Sharma</h3>
        <p class="role">Restaurant Manager</p>
        <p class="bio">Ensures a delightful dining experience and smooth operations.</p>
      </div>
      <div class="team-member">
        <img src="person 3.jpeg" alt="Chef Ravi">
        <h3>Chef Ravi</h3>
        <p class="role">Pastry Specialist</p>
        <p class="bio">Crafts delicious desserts to complete every meal.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Delicious Dine Restaurant | Designed by Kalpana</p>
  </footer>

</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products | Delicious Dine</title>
  <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(201, 170, 230);text-align:center">

  <header>
    <h1>Delicious Dine Restaurant</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html">Our Team</a>
    <a href="product.html" class="active">Products</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section class="horizontal-gallery">
    <h2>Our Products</h2>
    <div class="gallery-items">
      <div class="gallery-items">
        <img src="burger.png" alt="Classic Burger">
        <h3>Classic Burger</h3>
        <p>Juicy beef patty with lettuce, tomato, and cheese.</p>
        <p class="price">₹199</p>
        <button class="add-btn">Add to Cart</button>
      </div>
      <div class="gallery-items">
        <img src="fried rice.png" alt="Veg Fried Rice">
        <h3>Veg Fried Rice</h3>
        <p>Stir-fried rice with fresh vegetables.</p>
        <p class="price">₹179</p>
        <button class="add-btn">Add to Cart</button>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Delicious Dine Restaurant | Designed by Kalpana</p>
  </footer>

</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | Delicious Dine</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="contact.css">
</head>
<body style="background-color: rgb(243, 194, 218);text-align:center">

  <header>
    <h1>Delicious Dine Restaurant</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="people.html">Our Team</a>
    <a href="product.html">Products</a>
    <a href="contact.html" class="active">Contact</a>
  </nav>

  <section class="contact-section">
    <div class="contact-info">
      <h2>Contact Us</h2>
      <p>Visit us or reach out for reservations and catering services.</p>
      <p><i class="fas fa-map-marker-alt"></i> 123 Food Street, Madurai, TN</p>
      <p><i class="fas fa-phone-alt"></i> +91 98765 43210</p>
      <p><i class="fas fa-envelope"></i> contact@deliciousdine.com</p>
    </div>

    <div class="contact-form">
      <h3>Send a Message</h3>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Delicious Dine Restaurant | Designed by Kalpana</p>
  </footer>

</body>
</html>
```

# OUTPUT:

![alt text](<Screenshot (33).png>)

![alt text](<Screenshot (34).png>)

![alt text](<Screenshot (35).png>)

![alt text](<Screenshot (36).png>)

![alt text](<Screenshot (37).png>)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

