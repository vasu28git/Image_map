# Ex04 Places Around Me
# Date:08-11-2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
map:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
    <h1>Image map</h1>
    <h2>24900796</h2>
    <img src="newmap.png" usemap="#mymap">
    <map name="mymap">
        <area shape="circle" coords="999,168,15" href="pheonix2.html" alt="_blank" target="_blank" >
        <area shape="rect" coords="1038,655,1069,684" href="titan2.html" alt="_blank" target="_blank">
        <area shape="rect" coords="850,347,881,377" href="californiab.html" alt="_blank" target="_blank">
        <area shape="circle" coords="1421,157,16" href="gurucollege.html" alt="_blank" target="_blank">
        <area shape="rect" coords="126,613,590,755" href="vel.html" alt="_blank" target="_blank">
    </map>
</body>
</html>
~~~
pheonix2.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phoenix Mall Chennai</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #575757;
        }
        .main {
            text-align: center;
            padding: 2rem 1rem;
            background-color: #f4f4f4;
        }
        .main img {
            width: 1200px;
            height: 700px;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .main h1 {
            font-size: 2.5rem;
            margin: 1rem 0;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Phoenix Mall Chennai</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="main">
        <img src="pheonixfull.jpg" alt="Phoenix Mall Chennai">
        <h1>Your Ultimate Shopping Destination</h1>
        <p>Shop | Dine | Entertain</p>
    </div>
    <div id="about" class="section">
        <h2>About Us</h2>
        <p>Phoenix Mall Chennai is a premier shopping and entertainment destination in the heart of the city. Explore a variety of stores, restaurants, and attractions for the entire family.</p>
    </div>
    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: info@phoenixmallchennai.com | Phone: +91 12345 67890</p>
        <p>Address: Velachery Main Road, Chennai, Tamil Nadu</p>
    </div>
    <footer>
        <p>&copy; 2024 Phoenix Mall Chennai. All Rights Reserved.</p>
    </footer>
</body>
</html>

~~~
titan2.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Titan Watches</title>
    <style>
             body {
        margin: 0;
        font-family: 'Arial', sans-serif;
        color: #333;
        line-height: 1.6;
    }
    
    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 50px;
        background: #000;
        color: #fff;
    }
    
    .logo {
        font-size: 24px;
        font-weight: bold;
    }
    
    .navbar a {
        color: #fff;
        text-decoration: none;
        margin: 0 15px;
    }
    
    .navbar a:hover {
        text-decoration: underline;
    }
    
    .main {
        height: 80vh;
        background: url('titanbanner.jpeg') no-repeat center center/cover;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        color: #fff;
    }
    
    .main-content h1 {
        font-size: 50px;
        margin-bottom: 20px;
    }
    
    .main-content p {
        font-size: 18px;
        margin-bottom: 20px;
    }
    
    .btn {
        background: #f8b400;
        color: #fff;
        padding: 10px 20px;
        text-decoration: none;
        font-size: 16px;
        border-radius: 5px;
    }
    
    .btn:hover {
        background: #f39c12;
    }
    
    .about {
        padding: 50px;
        background: #f4f4f4;
        text-align: center;
    }
    
    .about h2 {
        margin-bottom: 20px;
    }
    
    .collection {
        padding: 50px;
        text-align: center;
    }
    
    .collection h2 {
        margin-bottom: 30px;
    }
    
    .watch-card {
        display: inline-block;
        width: 300px;
        margin: 10px;
        text-align: center;
        background: #fff;
        border: 1px solid #ddd;
        border-radius: 10px;
        overflow: hidden;
    }
    
    .watch-card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }
    
    .watch-card h3 {
        margin: 15px 0 10px;
    }
    
    .watch-card p {
        padding: 0 15px 20px;
        color: #555;
    }
    
    .footer {
        text-align: center;
        padding: 20px;
        background: #000;
        color: #fff;
    }
    </style>
    
</head>
<body>
    <header class="header">
        <div class="logo">Titan</div>
        <nav class="navbar">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#collection">Collection</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home" class="main">
        <div class="main-content">
            <h1>Timeless Elegance</h1>
            <p>Discover watches that define your style and sophistication.</p>
            <a href="#collection" class="btn">Explore Collection</a>
 
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Titan</h2>
        <p>
            Titan is a pioneer in the watchmaking industry, blending innovation with elegance.
            Each timepiece reflects craftsmanship and a commitment to quality.
        </p>
    </section>

    <section id="collection" class="collection">
        <h2>Our Collection</h2>
        <div class="watch-card">
            <img src="watch1.jpeg" alt="Watch 1">
            <h3>Classic Series</h3>
            <p>Elegant and timeless designs for every occasion.</p>
        </div>
        <div class="watch-card">
            <img src="watch2.jpeg" alt="Watch 2">
            <h3>Class 2 Series</h3>
            <p>Durable and stylish watches for an active lifestyle.</p>
        </div>
        <div class="watch-card">
            <img src="watch3.jpeg" alt="Watch 3">
            <h3>Luxury Series</h3>
            <p>Exquisite craftsmanship with premium materials.</p>
        </div>
    </section>

    <footer class="footer">
        <p>© 2024 Titan Watches. All rights reserved.</p>
    </footer>
</body>
</html>
~~~
california.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>California Burrito</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #FF5722;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #575757;
        }
        .main {
            text-align: center;
            padding: 2rem 1rem;
            background-color: #fff;
        }
        .main img {
            width: 1200px;
            height: 700px;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .main h1 {
            font-size: 2.5rem;
            margin: 1rem 0;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to California Burrito</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="main">
        <img src="california burrioto.jpeg" alt="California Burrito Restaurant">
        <h1>Your Favorite Mexican Experience</h1>
        <p>Fresh, Flavorful, and Fun</p>
    </div>
    <div id="about" class="section">
        <h2>About Us</h2>
        <p>At California Burrito, we serve authentic Mexican-inspired dishes made with fresh, high-quality ingredients. Whether you're craving a classic burrito, a bowl, or loaded nachos, we’ve got you covered!</p>
    </div>
    <div id="menu" class="section" style="background-color: #eee;">
        <h2>Our Menu</h2>
        <p>Explore our delicious range of burritos, tacos, quesadillas, bowls, and more. Every dish is customizable to your taste!</p>
    </div>
    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: info@californiaburrito.com | Phone: +91 98765 43210</p>
        <p>Address: 123 Mexican Street, Your City, Your State</p>
    </div>
    <footer>
        <p>&copy; 2024 California Burrito. All Rights Reserved.</p>
    </footer>
</body>
</html>

~~~
gurucollege.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guru Nanak College Chennai</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00509E;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #003366;
        }
        .main {
            text-align: center;
            padding: 2rem 1rem;
            background-color: #fff;
        }
        .main img {
            width: 1200px;
            height: 700px;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .main h1 {
            font-size: 2.5rem;
            margin: 1rem 0;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Guru Nanak College, Chennai</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#academics">Academics</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="main">
        <img src="college 3.jpg" alt="Guru Nanak College Campus">
        <h1>Empowering Education Since 1971</h1>
        <p>Inspiring Learning | Fostering Excellence | Building Character</p>
    </div>
    <div id="about" class="section">
        <h2>About Us</h2>
        <p>Guru Nanak College, Chennai, is a premier institution offering world-class education with a strong emphasis on character building, academic excellence, and societal contribution. We aim to nurture responsible global citizens.</p>
    </div>
    <div id="academics" class="section" style="background-color: #eee;">
        <h2>Academics</h2>
        <p>We offer a wide range of undergraduate, postgraduate, and doctoral programs in arts, science, and commerce. With experienced faculty and state-of-the-art facilities, we ensure a vibrant learning experience.</p>
    </div>
    <div id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: info@gurunanakcollege.edu | Phone: +91 98765 43210</p>
        <p>Address: Guru Nanak Salai, Velachery, Chennai, Tamil Nadu</p>
    </div>
    <footer>
        <p>&copy; 2024 Guru Nanak College Chennai. All Rights Reserved.</p>
    </footer>
</body>
</html>

~~~
vel.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Velachery Lake Chennai</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
        }
        header {
            background-color: #00796B;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #004D40;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #00796B;
        }
        .main {
            text-align: center;
            padding: 2rem 1rem;
            background-color: #fff;
        }
        .main img {
            width: 1200px;
            height: 700px;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .main h1 {
            font-size: 2.5rem;
            margin: 1rem 0;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background-color: #004D40;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Velachery Lake, Chennai</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#activities">Activities</a>
    </nav>
    <div class="main">
        <img src="vela.jpg" alt="Velachery Lake Chennai">
        <h1>A Serene Urban Oasis</h1>
        <p>Relax | Rejuvenate | Explore Nature</p>
    </div>
    <div id="about" class="section">
        <h2>About Velachery Lake</h2>
        <p>Velachery Lake is a scenic freshwater lake in Chennai, Tamil Nadu. It serves as a recreational spot for locals and visitors, offering stunning views, peaceful surroundings, and a connection to nature.</p>
    </div>
    <div id="activities" class="section" style="background-color: #e8f5e9;">
        <h2>Activities</h2>
        <p>Visitors can enjoy walking along the lake, birdwatching, and experiencing nature. The lake is also a great spot for photography and spending quality time with family and friends.</p>
    </div>
  
</body>
</html>

~~~
# OUTPUT
![screencapture-127-0-0-1-5500-imagemap-html-2024-12-07-10_08_00 - Copy](https://github.com/user-attachments/assets/116a875a-79b3-41f8-877a-5bdfeef51d32)

![screencapture-127-0-0-1-5500-pheonix2-html-2024-12-07-10_02_10](https://github.com/user-attachments/assets/2e0778ce-3ed7-404d-8f46-331ee603c38d)

![screencapture-127-0-0-1-5500-titan2-html-2024-12-07-10_04_18](https://github.com/user-attachments/assets/5dece9cc-b031-40e9-97ab-8de3e7c187e4)

![screencapture-127-0-0-1-5500-californiab-html-2024-12-07-10_02_59](https://github.com/user-attachments/assets/53462781-ce29-4d18-ba70-1baabd4c921b)

![screencapture-127-0-0-1-5500-gurucollege-html-2024-12-07-10_03_38](https://github.com/user-attachments/assets/f4154cb1-c49a-4137-8103-a142475769d0)

![screencapture-127-0-0-1-5500-vel-html-2024-12-07-10_04_03](https://github.com/user-attachments/assets/1c3fd109-787c-48ec-868d-5ba00ee67d25)

# RESULT
The program for implementing image maps using HTML is executed successfully.
