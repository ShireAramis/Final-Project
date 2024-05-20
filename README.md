<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Soccer Equipment</title>
    <style>
        body {
            background-color: #f0fff0; /* Light green background */
            font-family: Arial, sans-serif;
            font-size: 20px;
            color: #006400; /* Dark green text */
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            background-color: #006400; /* Dark green background for nav */
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: white; /* White text for nav links */
            font-size: 20px;
            cursor: pointer;
        }
        h1 {
            color: #006400; /* Dark green for headings */
        }
        .section {
            display: none;
        }
        .active {
            display: block;
        }
    </style>
    <script>
        function showSection(sectionId) {
            document.getElementById('home').classList.remove('active');
            document.getElementById('products').classList.remove('active');
            document.getElementById('contact').classList.remove('active');
            document.getElementById(sectionId).classList.add('active');
        }
    </script>
</head>
<body onload="showSection('home')">
    <nav>
        <ul>
            <li><a onclick="showSection('home')">Home</a></li>
            <li><a onclick="showSection('products')">Products</a></li>
            <li><a onclick="showSection('contact')">Contact Us</a></li>
        </ul>
    </nav>
    <div id="home" class="section">
        <h1>Welcome to Soccer Equipment Store</h1>
       
    </div>
    <div id="products" class="section">
        <h1>Our Products</h1>
        
    </div>
    <div id="contact" class="section">
        <h1>Contact Us</h1>
        
    </div>
</body>
</html>


