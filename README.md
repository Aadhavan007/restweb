# Ex.06 Restaurant Website
## Date:18-12-2025

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
resturant.html

<html>
<head>
    <title>Marandha Suvai</title>

    <link rel="stylesheet" href="resturant.css">
</head>
<body>

    <nav class="navigation-bar">
        <div class="navigation-menu">
            <a href="resturant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Admin</a>
        </div>
    </nav>

    <div class="restaurant-section">
        <h1 class="restaurant-title">Marandha Suvai</h1>

        <p class="restaurant-description">
            "Marandha Suvai" means <b>Forgotten Taste</b>.  
            Our restaurant celebrates traditional South Indian cuisine by reviving forgotten recipes,  
            offering simple, wholesome food prepared the traditional way.
        </p>
    </div>

    <footer class="page-footer">
        <p class="footer-content">
            Designed by M Aadhavan Nagarajan &copy; 2025
        </p>
    </footer>

</body>
</html>

resturant.css

body 
{
    margin: 0;
    font-family: Georgia, serif;
    background-color: #f5f1ea;
    color: #3b2f2f;
}

.navigation-bar 
{
    background-color: #3b2f2f;
    padding: 15px;
    text-align: left;
}

.navigation-menu a 
{
    color: #f5f1ea;
    text-decoration: none;
    margin: 0 20px;
    font-size: 18px;
}

.navigation-menu a:hover 
{
    text-decoration: underline;
}

.restaurant-section 
{
    max-width: 800px;
    margin: 80px auto;
    text-align: left;
    padding: 130px;
}

.restaurant-title 
{
    font-size: 48px;
    margin-bottom: 20px;
}

.restaurant-description 
{
    font-size: 20px;
    line-height: 1.8;
}

.page-footer 
{
    background-color: #3b2f2f;
    color: #f5f1ea;
    text-align: center;
    padding: 1px;
}

menu.html
<html>
<head>
    <title>Marandha Suvai - Menu</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>

    <nav class="navigation-bar">
        <div class="navigation-menu">
            <a href="resturant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Admin</a>
        </div>
    </nav>

    <div class="menu-section">
        <h1 class="menu-title">Our Traditional Menu</h1>

        <p class="menu-description">
            A thoughtfully curated selection of traditional South Indian dishes,
            prepared using native ingredients and time-honoured cooking methods.
        </p>

        <div class="menu-list">

            <div class="menu-item">
                <img src="kolaurundai.jpg" class="menu-image">
                <h3 class="item-name">Chettinad Mutton Kola Urundai</h3>
                <p class="item-description">
                    Spicy minced mutton balls prepared in the Chettinad style,
                    rich with aromatic spices and deep flavours.
                </p>
            </div>

            <div class="menu-item">
                <img src="milagukozhi.png" class="menu-image">
                <h3 class="item-name">Milagu Kozhi Varuval</h3>
                <p class="item-description">
                    Country chicken gently stir-fried with black pepper, garlic,
                    and traditional South Indian spices.
                </p>
            </div>

            <div class="menu-item">
                <img src="elaneerpayasam.jpg" class="menu-image">
                <h3 class="item-name">Elaneer Payasam</h3>
                <p class="item-description">
                    A light and refreshing dessert made with tender coconut
                    and natural jaggery.
                </p>
            </div>

            <div class="menu-item">
                <img src="ragikoozh.png" class="menu-image">
                <h3 class="item-name">Ragi Koozh</h3>
                <p class="item-description">
                    Fermented finger millet porridge, traditionally enjoyed
                    as a cooling and nourishing meal.
                </p>
            </div>

            <div class="menu-item">
                <img src="samaiupma.jpg" class="menu-image">
                <h3 class="item-name">Samai Milagu Upma</h3>
                <p class="item-description">
                    Little millet upma seasoned with black pepper, ginger,
                    and fresh curry leaves.
                </p>
            </div>

        </div>
    </div>

    <footer class="page-footer">
        <p class="footer-content">
            Designed by M Aadhavan Nagarajan &copy; 2025
        </p>
    </footer>

</body>
</html>

menu.css
body {
    margin: 0;
    font-family: Georgia, serif;
    background-color: #fffaf3;
    color: #3b2f2f;
}

.navigation-bar {
    background-color: #3b2f2f;
    padding: 15px 30px;
}

.navigation-menu a {
    color: #fffaf3;
    text-decoration: none;
    margin-right: 25px;
    font-size: 18px;
}

.navigation-menu a:hover {
    text-decoration: underline;
}

.menu-section {
    width: 90%;
    margin: 60px auto;
    text-align: center;
}

.menu-title {
    font-size: 42px;
    margin-bottom: 10px;
}

.menu-description {
    font-size: 18px;
    margin-bottom: 40px;
    line-height: 1.6;
}



.menu-list {
    text-align: left;
}

.menu-item {
    width: 46%;
    background-color: #f5f1ea;
    margin: 2%;
    float: left;
    box-sizing: border-box;
}

.menu-item img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}


.item-name {
    font-size: 20px;
    margin: 10px;
}

.item-description {
    font-size: 15px;
    line-height: 1.5;
    margin: 0 10px 12px;
}

.page-footer {
    clear: both;
    background-color: #3b2f2f;
    color: #fffaf3;
    text-align: center;
    padding: 10px;
    font-size: 14px;
}

contact.html

<html>
<head>
    <title>Marandha Suvai - Contact</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

    <nav class="navigation-bar">
        <div class="navigation-menu">
            <a href="resturant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Admin</a>
        </div>
    </nav>

    <div class="contact-section">
        <h1 class="contact-title">Contact Us</h1>

        <p class="contact-description">
            We would be happy to hear from you.  
            Reach out to us for enquiries, feedback, or table reservations.
        </p>

        <div class="contact-details">
            <p><strong>Phone:</strong> +91 89393 88202</p>
            <p><strong>Email:</strong> MarandhaSuvai@gmail.com</p>
        </div>

        <div class="contact-form-section">
            <form class="contact-form">
                <input class="contact-input" type="text" placeholder="Your Name">
                <input class="contact-input" type="email" placeholder="Your Email">
                <textarea class="contact-textarea" placeholder="Your Message"></textarea>
                <button class="contact-submit-button">Send Message</button>
            </form>
        </div>
    </div>

    <footer class="page-footer">
        <p class="footer-content">
            Designed by M Aadhavan Nagarajan &copy; 2025
        </p>
    </footer>

</body>
</html>

contact.css

body {
    margin: 0;
    font-family: Georgia, serif;
    background-color: #fffaf3;
    color: #3b2f2f;
}



.navigation-bar {
    background-color: #3b2f2f;
    padding: 15px;
    text-align: left;
}

.navigation-menu a {
    color: #fffaf3;
    text-decoration: none;
    margin: 0 22px;
    font-size: 18px;
}

.navigation-menu a:hover {
    text-decoration: underline;
}



.contact-section {
    max-width: 800px;
    margin: 70px auto;
    padding: 10px;
    text-align: center;
}

.contact-title {
    font-size: 42px;
    margin-bottom: 15px;
}

.contact-description {
    font-size: 18px;
    line-height: 1.7;
    margin-bottom: 35px;
}

.contact-details {
    margin-bottom: 40px;
    font-size: 18px;
}



.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-input{
    padding: 12px;
    font-size: 16px;
    font-family: Georgia, serif;
    border: 1px solid #c8bfb6;
}

.contact-textarea {
    padding: 12px;
    font-size: 16px;
    font-family: Georgia, serif;
    border: 1px solid #c8bfb6;
}

.contact-textarea {
    min-height: 120px;
}

.contact-submit-button {
    background-color: #3b2f2f;
    color: #fffaf3;
    padding: 12px;
    border: none;
    font-size: 16px;
    cursor: pointer;
}

.contact-submit-button:hover {
    background-color: #2f2525;
}


.page-footer {
    background-color: #3b2f2f;
    color: #fffaf3;
    text-align: center;
    padding: 1px;
    font-size: 15px;
}


admin.html
<html>
<head>
    <title>Marandha Suvai - Administration</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>

    <nav class="navigation-bar">
        <div class="navigation-menu">
            <a href="resturant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>

        </div>
    </nav>

    <div class="admin-section">
        <h1 class="admin-title">Administration Team</h1>

        <p class="admin-description">
            The team responsible for managing and supporting the operations of
            Marandha Suvai.
        </p>

        <div class="admin-list">

            <div class="admin-card">
                <img src="admin1.jpeg">
                <h3>Aadhavan</h3>
                <p>Founder & Manager</p>
            </div>

            <div class="admin-card">
                <img src="admin2.png">
                <h3>Robert Downey Jr</h3>
                <p>Operations Head</p>
            </div>

            <div class="admin-card">
                <img src="admin3.png">
                <h3>Tom Cruise</h3>
                <p>Quality Control Manager</p>
            </div>

            <div class="admin-card">
                <img src="admin4.jpg">
                <h3>Brad Pitt</h3>
                <p>Customer Relations Manager</p>
            </div>

            <div class="admin-card">
                <img src="admin5.jpg">
                <h3>Christian Bale</h3>
                <p>Creative Director</p>
            </div>

        </div>
    </div>

    <footer class="page-footer">
        <p>Designed by M Aadhavan Nagarajan &copy; 2025</p>
    </footer>

</body>
</html>

admin.css

body {
    margin: 0;
    font-family: Georgia, serif;
    background-color: #fffaf3;
    color: #3b2f2f;
}

.navigation-bar {
    background-color: #3b2f2f;
    padding: 15px 30px;
}

.navigation-menu a {
    color: #fffaf3;
    text-decoration: none;
    margin-right: 25px;
    font-size: 18px;
}

.navigation-menu a:hover {
    text-decoration: underline;
}

.admin-section {
    width: 90%;
    margin: 60px auto;
    text-align: center;
}

.admin-title {
    font-size: 42px;
    margin-bottom: 10px;
}

.admin-description {
    font-size: 18px;
    margin-bottom: 40px;
    line-height: 1.6;
}

.admin-list {
    text-align: left;
}

.admin-card {
    width: 30%;
    background-color: #f5f1ea;
    margin: 1.5%;
    float: left;
    text-align: center;
    box-sizing: border-box;
    padding-bottom: 15px;
}

.admin-card img {
    padding-top: 20px;
    width: 50%;
    height: 250px;
    object-fit: cover;
}


.admin-card h3 {
    margin: 10px 0 5px;
    font-size: 20px;
}

.admin-card p {
    margin: 0;
    font-size: 15px;
}

.page-footer {
    clear: both;
    background-color: #3b2f2f;
    color: #fffaf3;
    text-align: center;
    padding: 1px;
    font-size: 14px;
}

```

## OUTPUT:

```
![alt text](<Screenshot (125).png>)
![alt text](<Screenshot (126).png>)
![alt text](<Screenshot (127).png>)
![alt text](<Screenshot (128).png>)
![alt text](<Screenshot (129).png>)
```

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
