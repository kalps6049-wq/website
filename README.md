# Ex.07 Restaurant Website
# Date:05.10.2025
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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - MY RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: darksalmon;">
    <header>
        <h1>MY RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="section">
            <h2>Welcome to DELICIOUE DINE RESTAURANT</h2>
           <center>
            <img src="restuarant background.jpeg" alt="photo of homepage" width="1200px" height="500px">
           </center>
            <p>Experience the finest dining in a cozy atmosphere. We are dedicated to providing fresh, delicious food and exceptional service.</p>
            <p>Visit our Menu page to see our offerings!</p>
        </section>

        <section class="section">
            <h2>Our Specials</h2>
            <p>Try our highly-rated Signature Dish and our seasonal dessert!</p>
            </section>
    </main>

    <footer>
        <p>&copy; 2025 My Restaurant. | Designed and Developed by KALPANA</p>
    </footer>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="text-align: center;background-color:rgb(224, 210, 237)">
    <header>
        <h1>DELICIOUS DINE RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="section">
            <h2>Our Delicious Menu</h2>
            <div class="me">
            <div class="menu-grid">
                <div class="menu-item">
                    <h4>Biriyani</h4>
                    <img src="biriyani.png" alt="photo of panner tikka" width="250px" height="100px" >
                    
                </div>
                <div class="menu-item">
                    <h4>Pizza</h4>
                    <img src="pizza.png" alt="photo of veg manchurian" width="250px" height="100px">
                </div>
                <div class="menu-item">
                    <h4>Dragon Chicken</h4>
                    <img src="dragon chicken.png" alt="photo of dragon chicken" width="250px" height="100px">
                </div>
                <div class="menu-item">
                    <h4>Noodles</h4>
                    <img src="noodles.png" alt="photo of chicken biriyani" width="250px" height="100px">
                    </div>
                </div>
                <div class="menu-item">
                    <h4>Veg Fried Rice</h4>
                    <img src="fried rice.png" alt="photo of burger" width="250px" heigth="100px">
                    
                </div>
                <div class="menu-item">
                    <h4>Veg Meals</h4>
                    <img src="veg meals.png" alt="photo of noodles" width="250px" height="180px">
                    
                </div>
                <div class="menu-item">
                    <h4>Nuggets</h4>
                    <img src="nuggets.png" alt="photo of nuggets" width="250px" height="150px">
                    
                </div>
                <div class="menu-item">
                    <h4>Panner Butter Masala</h4>
                    <img src="pnner.png" alt="photo of butter masala" width="250px" height="150px">
                    
                </div>
                <div class="menu-item">
                    <h4>Chola Pori</h4>
                    <img src="chola pori.png" alt="photo of pizza" width="250px" height="150px">
                    
                </div>
                <div class="menu-item">
                    <h4>Chiken Soup</h4>
                    <img src="chicken soup.png" alt="photo of soup" width="220px" height="150px">
                    
                </div>
                <div class="menu-item">
                    <h4>Chiken Fried Rice</h4>
                     <img src="chicken rice .png" alt="photo of mocktail" width="220px" height="150px">
                    
                </div>
                <div class="menu-item">
                    <h4>Gulab Jamun</h4>
                    <img src="gulab.png" alt="photo of cake" width="220px" height="150px">
                    
                </div>
                </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Restaurant. | Designed and Developed by KALPANA</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(186, 243, 243);text-align:center">
    <header>
        <h1>DELICIOUS DINE RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="section">
            <h2>Our Leadership Team</h2>
            
            <div class="admin-grid">
                <div class="admin-card">
                    <img src="person 1.jpeg" alt="Photo of CEO">
                    <h4>Mr.Arun</h4>
                    <p>Chief Executive Officer (CEO)</p>
                </div>
                
                <div class="admin-card">
                    <img src="person 2.jpeg" alt="Photo of Head Chef">
                    <h4>Mr.Ravi</h4>
                    <p>Head Chef & Culinary Director</p>
                </div>
                
                <div class="admin-card">
                    <img src="person 3.jpeg" alt="Photo of Operations Manager">
                    <h4>Mr.JOHN</h4>
                    <p>Operations Manager</p>
                </div>
                
                <div class="admin-card">
                    <img src="person 4.jpeg" alt="Photo of Finance Director">
                    <h4>Mr.SANJAY</h4>
                    <p>Finance Director</p>
                </div>
                
                <div class="admin-card">
                    <img src="person 5.jpeg" alt="Photo of Marketing Manager">
                    <h4>Ms.MARIE</h4>
                    <p>Marketing Manager</p>
                </div>
                
                <div class="admin-card">
                    <img src="person 6.jpeg" alt="Photo of HR Manager">
                    <h4>EVANGELINE</h4>
                    <p>Human Resources Manager</p>
                </div>
                
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Restaurant. | Designed and Developed by KALPANA</p>
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - My Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: rgb(233, 181, 205);text-align:center">
    <header>
        <h1>DELICIOUS DINE RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="section contact-info">
            <h2>Get in Touch</h2>
            <p><i>We'd love to hear from you! Please find our contact details below.</i></p>
            
            <h3>Location:</h3>
            <p><strong>Address:</strong> Akkaiyah naidu street,chennai</p>

            <h3>Contact Details:</h3>
            <p><strong>Phone:</strong> <a href="tel:+15551234567">9952855207</a></p>
            <p><strong>E-mail:</strong> <a href="mailto:info@myrestaurant.com">kalps6049@gmail.com</a></p>
            
            <h3>Hours of Operation:</h3>
            <p>Monday - Friday: 11:00 AM - 10:00 PM</p>
            <p>Saturday - Sunday: 10:00 AM - 11:00 PM</p>
        </section>
        
        </main>

    <footer>
        <p>&copy; 2025 My Restaurant. | Designed and Developed by KALPANA</p>
    </footer>
</body>
</html>

```

# OUTPUT:
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/15ff2229-9809-4f41-a9b4-d07fcdcbfedb" />
<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/3d2183cf-cab0-411b-ae87-813846bce80a" />
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/0c5be1b1-754e-468d-999d-8dbb1d110d83" />
<img width="1920" height="1080" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/70ff159a-3b1d-40cb-a1af-3da11f0aee99" />
<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/87045d89-b1b6-4ea2-956f-56ab87939f1a" />
<img width="1920" height="1080" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/d3af05ec-e207-453d-b520-1ecc325c5969" />
<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/7b6f6961-7276-4933-a17f-94c6ae47640b" />











# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

