# Ex.06 Restaurant Website
## Date:23/12/2025

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
home.html

<html>
<head>
    <title>Restaurant WebPage</title>
    <link href="styles.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="main">
        <h1>STEP INSIDE - MAGIC IS SERVED HERE</h1>
        <h1 class="brand">MAGICAL HUB </h1>
        <h2>A magical blend of classic British feasts, wizarding delicacies, and enchanted flavors.</h2>
        <p>
            Discover enchanted flavors in our wizarding restaurant, where every dish tells a tale of magic and tradition. 
            From spell-crafted feasts to rich, potion-inspired sauces, our menu is designed to bring you the true taste of the wizarding world.
            Step in and enjoy an unforgettable magical dining experience.
        </p>
    </div>
    <div class="images">
        <img src="1.webp" alt="Image1">
        <img src="2.jpg" alt="Image2">
        <img src="3.jpg" alt="Image3">
        <img src="4.webp" alt="Image4">
    </div>
</div>
<div class="footer">
    <h4>VIJAYAPRATHISHA J (25008497)</h4>
</div>
</body>
</html>

style.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: cursive, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid gray;
    border-radius: 9px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    text-decoration: underline;
    font-weight: bold;
    color: black;
    font-size: 16px;
}
.main {
    text-align: center;
    color: bisque;
    margin-bottom: 40px;
}
.main h1 {
    font-size: 50px;
}
.main .brand {
    font-size: 68px;
    color: blanchedalmond;
    letter-spacing: 4px;
}
.main h2 {
    margin: 15px 0;
    font-weight: normal;
}
.main p {
    width: 70%;
    margin: 20px auto;
    font-size: 18px;
    line-height: 1.6;
}
.images {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin-bottom: 40px;
}
.images img {
    width: 220px;
    height: 160px;
    object-fit: cover;
    border: 5px solid white;
    border-radius: 10px;
}
.footer {
    background-color: beige;
    width: 100%;
    text-align: center;
    color: rgb(171, 68, 68);
    font-size: 14px;
    bottom: 0;
}

menu.html

<html>
<head>
    <title>Menu Page</title>
    <link href="menu.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="menu-container">
        <h1>MENU</h1>
        <div class="menu-items">

            <div class="menu-card">
                <img src="menu1.jpg">
                <h3>Butterbeer</h3>
                <p>Rs. 200</p>
            </div>

            <div class="menu-card">
                <img src="menu2.webp">
                <h3>Harry Potter Pumpkin Pasties</h3>
                <p>Rs. 320</p>
            </div>

            <div class="menu-card">
                <img src="menu3.webp">
                <h3>Hogwarts Roast Chicken</h3>
                <p>Rs. 600</p>
            </div>

            <div class="menu-card">
                <img src="menu4.webp">
                <h3>Shell Cottage Shepherd’s Pie</h3>
                <p>Rs. 300</p>
            </div>

            <div class="menu-card">
                <img src="menu5.webp">
                <h3>Polyjuice Potion Smoothie</h3>
                <p>Rs. 550</p>
            </div>

            <div class="menu-card">
                <img src="menu6.webp">
                <h3>Ham and Cheese Howlers</h3>
                <p>Rs. 345</p>
            </div>

            <div class="menu-card">
                <img src="menu7.jpg">
                <h3>Treacle Tart</h3>
                <p>Rs. 450</p>
            </div>

            <div class="menu-card">
                <img src="menu8.jpg">
                <h3>Harry Potter’s Eleventh Birthday Cake</h3>
                <p>Rs. 320</p>
            </div>
        </div>
    </div>

</div>
<div class="footer">
    <h4>VIJAYAPRATHISHA J (25008497)</h4>
</div>

</body>
</html>

menu.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: cursive, serif;
}

.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid gray;
    border-radius: 10px;
}

.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}

.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}

.item a {
    margin: 0 18px;
    font-weight: bold;
    color: black;
    text-decoration: underline;
    font-size: 16px;
}

.menu-container {
    width: 100%;
}

.menu-container h1 {
    font-size: 70px;
    color: whitesmoke;
    letter-spacing: 6px;
    margin-bottom: 35px;
    text-align: center;
    text-decoration: underline;
}

.menu-items {
    display: flex;
    gap: 20px;
    justify-content: center;   
    align-items: flex-start;
    flex-wrap: nowrap;
}

.menu-card {
    background-color: blanchedalmond;
    width: 180px;
    padding: 12px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(137, 72, 116, 0.35);
}

.menu-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 12px;
    margin-bottom: 10px;
}

.menu-card h3 {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5px;
}

.menu-card p {
    font-size: 14px;
    color: rebeccapurple;
}
@media (max-width: 1200px) {
    .menu-items {
        flex-wrap: wrap;
        justify-content: center;
    }
}
.footer {
    background-color:beige;
    width: 100%;
    text-align: center;
    color: rgb(171, 68, 68);
    font-size: 14px;
    bottom: 0%;
}

admin.html

<html>
<head>
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <h1 class="admin-title">ADMIN'S</h1>
    <div class="team-container">

        <div class="team-card">
            <img src="photo.jpg">
            <h3>Vijayaprathisha J</h3>
            <p>CEO</p>
        </div>

        <div class="team-card">
            <img src="admin2.webp">
            <h3>Mr.Harry Potter</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="team-card">
            <img src="admin3.png">
            <h3>Mr.Darco Malfoy</h3>
            <p>Operations Manager</p>
        </div>

        <div class="team-card">
            <img src="admin4.webp">
            <h3>Ms.Hermoine Granger</h3>
            <p>HR Manager</p>
        </div>

        <div class="team-card">
            <img src="admin5.png">
            <h3>Mr.Ron Weasley</h3>
            <p>Executive Chef</p>
        </div>

        <div class="team-card">
            <img src="admin6.jpg">
            <h3>Ms.Ginny Weasley</h3>
            <p>Customer Service Manager</p>
        </div>

        <div class="team-card">
            <img src="adminn7.jpg">
            <h3>Mr.Cedric Diggory</h3>
            <p>Managing Director</p>
        </div>

    </div>
</div>
<div class="footer">
    <p>&copy;VIJAYAPRATHISHA J (25008497)</p>
</body>
</html>

admin.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: cursive, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid gray;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}
.item {
    background-color:#eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: black;
    text-decoration: underline;
}
.admin-title {
    font-size: 80px;
    color: whitesmoke;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.team-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}
.team-card {
    background-color: blanchedalmond;
    width: 200px;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    color: rebeccapurple;
    box-shadow: 0 8px 18px rgb(103, 94, 113);
}
.team-card img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}
.team-card h3 {
    font-size: 18px;
    margin-bottom: 5px;
}
.team-card p {
    font-size: 14px;
}
.footer {
    background-color: beige;
    width: 100%;
    text-align: center;
    color: rgb(171, 68, 68);
    font-size: 14px;
    bottom: 0%;
}

contact.html

<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="contact-content">
        <h1 class="contact-title">CONTACT</h1>
        <div class="contact-details">
            <h2>Come And Visit us at:</h2>
            <p>
                MAGICAL HUB<br>
                7, Z-183, 5th Ave, Z Block<br>
                T-Nagar, Chennai 600017,TN<br>
                India
            </p>
            <h2>Phone:+91 98621 07092</h2>
            <h2>Email ID:</h2>
            <p>magicalhuboffcial@gmail.com</p>
        </div>
    </div>
</div>
<div class="footer">
    <p>&copy;VIJAYAPRATHISHA J (25008497)</p>
</div>
</body>
</html>

contact.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: cursive, serif;
}
.container {
    background: url("restbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid gray;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: black;
    text-decoration: underline;
}
.contact-content {
    color: honeydew;
    margin-top: 40px;
}
.contact-title {
    font-size: 90px;
    color: honeydew;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.contact-details h2 {
    font-size: 24px;
    margin: 24px 0 10px;
    text-align: center;
}
.contact-details p {
    font-size: 18px;
    line-height: 1.2;
    text-align: center;
}
.footer {
    background-color: beige;
    width: 100%;
    text-align: center;
    color: rgb(171, 68, 68);
    font-size: 14px;
    bottom: 0%;
}


```
## OUTPUT:

![alt text](<Screenshot (61).png>)

![alt text](<Screenshot (62).png>)

![alt text](<Screenshot (63).png>)

![alt text](<Screenshot (64).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
