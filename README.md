

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        /* Common style for all pages */
        body {
            font-family: Arial, sans-serif; /* Set font family to Arial */
            font-size: 20px; /* Set font size to 20px */
            background-color: green; /* Set background color to green */
            color: white; /* Set text color to white */
        }

        /* Style for the navigation links */
        nav a {
            text-decoration: none;
            color: white; /* Set text color to white */
            font-size: 20px; /* Set font size to 20px */
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Style for page content */
        #home, #about, #contact {
            margin: 20px;
        }

        #home h1, #about h1, #contact h1 {
            font-size: 28px; /* Larger heading size for emphasis */
        }
    </style>
</head>
<body>

    <!-- Home Page -->
    <div id="home">
        <h1>Welcome to My Website</h1>
        <p>Soccer Equipment.</p>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </div>

    <!-- About Page -->
    <div id="about" style="display: none;">
        <h1>About Us</h1>
        <p>Young producers that work with all the major soccer clubs to provide all the soccer equipment you need.</p>
        <a href="index.html">Home</a>
        <a href="contact.html">Contact</a>
    </div>

    <!-- Contact Page -->
    <div id="contact" style="display: none;">
        <h1>Contact Us</h1>
        <p>267 454 1482.</p>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
    </div>

</body>
</html>

