[Uploading Rockys webpa<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocky's World</title>
    <style>
        /* Reset default margin and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Full-page background */
        body { 
            background-image: url(Rockys\ webpage\ Background.jpg);
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        /* Navbar styling */
        .navbar {
            position: absolute;
            top: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.7);
            padding: 15px 0;
            text-align: center;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 18px;
            transition: 0.3s;
        }

        .navbar a:hover {
            background: white;
            color: black;
            border-radius: 5px;
        }

        /* Header */
        h1 {
            color: white;
            text-shadow: 2px 2px 10px black;
            margin-top: -15px;
        }

        /* Center image with animation */
        .center {
            position: absolute;
            top: 70%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 200px;
            height: 200px;
            animation: blink 1.0s infinite alternate;
        }

        /* Blink effect */
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0.3; }
            100% { opacity: 1; }
        }

        /* Hover effect */
        .center:hover {
            transform: translate(-50%, -50%) scale(1.1);
            transition: 0.3s;
        }

        /* Top-left logo */
        .top-left {
            position: absolute;
            top: 10px;
            left: 10px;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            transition: 0.3s;
        }

        .top-left:hover {
            transform: scale(1.2);
        }

        /* Responsive design */
        @media (max-width: 768px) {
            h1 {
                font-size: 20px;
                text-align: center;
            }
            .center {
                width: 150px;
                height: 150px;
            }
            .navbar a {
                font-size: 16px;
                padding: 8px;
            }
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Gallery</a>
        <a href="#">Contact</a>
    </div>

    <!-- Page Title -->
    <h1>Welcome to Rocky's World</h1>

    <!-- Top-left Image (Logo) -->
    <img src="AmmuEkkush.jpeg" alt="Top-left Logo" class="top-left">

    <!-- Center Image with Blink Animation -->
    <img src="Pachis Logo.jpeg" alt="Center Image" class="center">

</body>
</html>ge.html…]()
