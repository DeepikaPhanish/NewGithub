<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #24292e;
            color: #ffffff;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            margin: 0;
        }
        nav a {
            color: #ffffff;
            text-decoration: none;
            margin-left: 20px;
        }
        .container {
            padding: 20px;
        }
        .repo {
            background: #ffffff;
            margin: 10px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #24292e;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>My GitHub</h1>
        <nav>
            <a href="#repositories">Repositories</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container" id="repositories">
        <h2>Repositories</h2>
        <div class="repo">
            <h3>Project 1</h3>
            <p>A simple project description goes here.</p>
        </div>
        <div class="repo">
            <h3>Project 2</h3>
            <p>Another project description goes here.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 My GitHub</p>
    </footer>
</body>
</html>

