# Ex.07 Restaurant Website
## Date:14.12.2024

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
```
rest.html

<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>THE MANASA RESTURANT</title>
    
    </head>
    <style>
        body{
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 80%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:italic;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: black;
        }
        .nav-list a:hover{
            color: red;
        }
    </style>
        <div class="nav-list">
        
        <a href="rest.html">Home</a>
        <a href="contact.html">contact</a>
        <a href="menu.html">menu</a>
        <a href="admin.html">Administration</a>

        </div>
    <body style="color:black;">
        <center>
       
        </center>
        <center>
            <h1 style= "color:black; font-size: 50px;">THE MANASA RESTURANT</h1>
    <table> 
        <center>
        <tr>
            <td><img src="biriyani.jpg"" style="width: 300px; height: 250px;"></td>
            <td><img src="noodles.jpg" style="width:300px; height: 250px;"></td>
            <td><img src="ragi mudde.jpg" style="width:300px; height: 250px;"></td>
            <td><img src="parota.jpg" style="width:300px; height: 250px;"></td>
            <td><img src="veg biriyani.jpg" style="width:300px; height: 250px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:black;"><center>BIRIYANI</center></h3></td>
            <td><h3 style="color:black;"><center>NOODLES</center></h3></td>
            <td><h3 style="color:black;"><center>RAGI MUDDE</center></h3></td>
            <td><h3 style="color:black;"><center>PAROTA</center></h3></td>
            <td><h3 style="color:black;"><center>VEG BIRIYANI</center></h3></td>
        </tr>
    </table>
    <h2>About us:
        <h2><center></center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>At Gourmet Delight, we bring you a fusion of flavors from around the world, crafted with love and the freshest ingredients. 
            Our restaurant offers a warm and inviting atmosphere, perfect for family gatherings, romantic dinners, or casual outings with friends. 
            Indulge in our chef's specialties and let us take you on a culinary journey you will never forget. Your satisfaction is our priority!

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>SAVOUR THE FLAVOURS:A CULINARY PARADAISE AWAITS</center></h4></td>
        </tr>
        <footer allign="centre" id="copy erite"
            Designed and developed by SELVARANI & copy 2024
        </footer>
    </body>        
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - THE MANASA RESTAURANT</title>
  <style>
    body { font-family: Arial, georgia; background: RED; margin: 0; color: #333; }
    .header, .footer { background: purple; color:red; text-align: center; padding: 1rem; }
    .header nav ul { list-style: none; display: flex; justify-content: center; padding: 0; }
    .header nav ul li { margin: 0 1rem; }
    .header nav ul li a { color:orange; text-decoration: none; font-size: 1.1rem; }
    .menu { padding: 2rem; text-align: center; }
    .menu ul { list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; }
    .menu ul li { background: orange; border: 1px solid red; padding: 1rem; border-radius: 5px; }
    .menu ul li:hover { transform: scale(1.05); transition: transform 0.3s; }
  </style>
</head>
<body>
  <header class="header">
    <h1>DELICIOUS MENU</h1>
    <nav>
      <ul>
        <li><a href="rest.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
<section class="menu">
    <h2>Our Menu</h2>
    <ul>
        <li>
            <img src="choc dessert.jpg" alt="Chocolate dessert" width="150" height="125">
            Dessert - $150
        </li>
        <li>
            <img src="honey cake.jpg" alt="Honey cake" width="150" height="125">
            FALLODA - $90
        </li>
        <li>
            <img src="salad.jpg" alt="Fruit Salad" width="150" height="125">
            Fruit Salad- $120
        </li>
        <li>
            <img src="strawb.jpg" alt="Strawberry Milkshake" width="150" height="100">
            Strawberry Milkshake- $40
        </li>
        <li>
            <img src="brownie.jpg" alt="Browny Cake" width="150" height="125">
            CREAMY CAKE - $350
        </li>
        <li>
            <img src="pizza.jpg" alt="Pizza" width="150" height="125">
            PIZZA - $999
        </li>
        <li>
            <img src="biriyani.jpg" alt="Chicken Biriyani " width="150" height="125">
            CHICKEN BIRIYANI - $200
        </li>
        
    </ul>
    </section>

    admin.html

    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE MANASA - Administration</title>

    <style>
        body {
            margin: 0;
            font-family:Georgia, 'Times New Roman', Times, serif;
            line-height: 1.6;
            color: black;
            background-color:whitesmoke;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: aquamarine;
            color:blue;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px red;
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color:blue;
        }

        .admin-container {
            padding: 40px 20px;
            background:violet;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: blue;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: rgb(180, 185, 153);
            border-radius: 10px;
            box-shadow: 0 4px 6px red;
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color:whitesmoke;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: whitesmoke;
            margin-bottom: 10px;
        }

        footer {
            background: whitesmoke;
            color: red;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: yellow;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: white;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    

<header>
        <h1>THE MANASA RESTURANT</h1>
        <nav>
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>OUR BACKBONES</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="manasa.jpg" alt="CEO">
                <div class="admin-details">
                    <h3>Manasa</h3>
                    <p>CEO of THE MANASA RESTURANT</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="sam.jpg" alt="Manager">
                <div class="admin-details">
                    <h3>Samantha</h3>
                    <p>Manager of THE MANASA RESTURANT</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="chitra.jpg" alt="Master Chef">
                <div class="admin-details">
                    <h3>Chithra</h3>
                    <p>Master Chef of THE  MANASA RESTURANT</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="swathi.jpg" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>Sawathi</h3>
                    <p>Assistant Managing Director of THE MANASA RESTURANT</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 THE MANASA RESTURANT. All rights reserved. | <a href="rest.html">Back to Home</a></p>
    </footer>

</body>
</html>
 contact.hml

 <html>
    <head>
        <title> CONTACT </title>
    </head>
    <style>
        
        body{
        
            background-image: url("bg.pg.jpg");
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:Georgia;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: blue;
            position:absolute;
            top: 200px;
        }
    </style>
    <div class="nav-list">
        
        

        </div>
    
        <section id="contact">  
            <h1 style="color:black">contact<h1>
            <h4  style="color:black">+91 8124623588<br> Manasa resuturant@gmail.com</h4>
            <P  style="color:black">3/28 kovil street  veerthangal vellore-632520 <br>
                <br> contact us to place the order<br>
            <hr> SAVOUR THE FLAVOUR
            </P>
         </section> 
    </center>
</body>
</html><html>
    <head>
        <title> CONTACT </title>
    </head>
    <style>
        
        body{
        
            background-image: url("bg.pg.jpg");
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:Georgia;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: blue;
            position:absolute;
            top: 200px;
        }
    </style>
    <div class="nav-list">
        
        

        </div>
    
        <section id="contact">  
            <h1 style="color:black">contact<h1>
            <h4  style="color:black">+91 8124623588<br> Manasa resuturant@gmail.com</h4>
            <P  style="color:black">3/28 kovil street  veerthangal vellore-632520 <br>
                <br> contact us to place the order<br>
            <hr> SAVOUR THE FLAVOUR
            </P>
         </section> 
    </center>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (40)-1.png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (39).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
