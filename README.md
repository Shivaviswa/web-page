<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Front Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to an external CSS file for styling -->
    <style>
        /* Inline CSS for basic styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            height: 100vh;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 10px 20px;
            display: inline-block;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        .main-content {
            text-align: center;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        img {
            max-width: 100%;
            height: auto;
        }

p{
    text-align:;
}    
h1{
    text-align: center;
}  
.about-us p {
            flex: 2 1 400px; /* Ensures text takes at least 400px width */
            text-align: justify;  
}
    </style>
</head>
<body>
    <nav>
        <a href="#">Home</a>
        <a href="#">About Us</a>
        <a href="#">Services</a>
        <a href="#">Products</a>
        <a href="#">Contact  Us</a>
    </nav>
    <div class="container">
            <img src="C:\Users\dhara\Downloads\house.jpg" alt="Centered Image">
    </div>
    
    <h1>About Us </h1>
    <br><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa fugiat deleniti voluptates reiciendis,
         dolore sapiente numquam iure nulla officiis pariatur exercitationem illo harum totam incidunt autem! Dolorum error 
         doloremque nostrum?</p>
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
