# Ex.07 Restaurant Website
## Date:03-01-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

....

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #4107ef;
            color: #333;
        }

        a {
            text-decoration: none;
            color: #007BFF;
        }

        a:hover {
            text-decoration: underline;
        }

        header {
            background-color: #008080;
            padding: 20px;
            text-align: center;
            color: #09f224;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }

        nav a {
            margin: 0 15px;
            color: #ea0606;
        }

        nav a:hover {
            color: #FFD700;
        }

        .banner {
            position: relative;
            background-image: url('new-banner.jpg'); /* Replace with your banner image */
            background-size: cover;
            background-position: center;
            height: 300px;
            color: #ef0c0c;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .banner h1 {
            font-size: 2.5em;
            margin: 0;
        }

        .banner p {
            font-size: 1.2em;
            margin-top: 10px;
            max-width: 600px;
            text-align: center;
        }

        .container {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }

        .card {
            background-color: #09fa62;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 15px;
            width: 30%;
            text-align: center;
        }

        .card img {
            width: 100%;
            border-radius: 8px;
        }

        .footer {
            text-align: center;
            background-color: #008080;
            color: #eb5a06;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <img src="c:\Users\admin\Pictures\images.png" >

</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h1>30% Off This Weekend</h1>
    <p>Come and enjoy our delicious meals with an exclusive weekend discount. Visit us now!</p>
</div>

<div class="container">
    <div class="card">
        <h2>Our New Menu</h2>
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-01-03 185620.png" alt="New Menu"> 
        <p>Explore our latest additions to the menu. Delicious food awaits you.</p>
        <a href="menu.html">See our newly added menu</a>
    </div>

    <div class="card">
        <h2>Book a Table</h2>
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-01-03 182608.png" alt="Book a Table">
        <p>Reserve your table online to ensure your spot at our restaurant.</p>
        <a href="reservation.html">Book your table now</a>
    </div>

    <div class="card">
        <h2>Opening Hours</h2>
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-01-03 184310.png" alt="Opening Hours"> 
        <p>Mon - Fri: 11am - 10pm<br>Sat: 12am - 11pm<br>Sun: 2pm - 9pm</p>
    </div>
</div>

<footer class="footer">
    <p>Designed and Developed by DIVAKARAN L</p>
</footer>

</body>
</html>

....

## OUTPUT:
![alt text](<Screenshot 2025-01-03 190613-1.png>)
![alt text](<Screenshot 2025-01-03 190648-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
