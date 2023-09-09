<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .profile {
            text-align: center;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .profile h1 {
            font-size: 24px;
            margin: 0;
        }

        .profile p {
            font-size: 16px;
            margin: 10px 0;
        }

        .social-links {
            text-align: center;
            margin-top: 20px;
        }

        .social-links a {
            text-decoration: none;
            color: #333;
            font-size: 20px;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="profile-picture.jpg" alt="User Profile Picture">
            <h1>John Doe</h1>
            <p>Web Developer</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam vel consectetur turpis.</p>
        </div>
        <div class="social-links">
            <a href="https://www.facebook.com/johndoe" target="_blank">Facebook</a>
            <a href="https://twitter.com/johndoe" target="_blank">Twitter</a>
            <a href="https://www.linkedin.com/in/johndoe" target="_blank">LinkedIn</a>
            <a href="https://github.com/johndoe" target="_blank">GitHub</a>
        </div>
    </div>
</body>
</html>
