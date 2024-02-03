# HTML-Structure-for-web-app
Source code for web app structure 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="Google developer example" content="width=device-width, initial-scale=1.0">
    <title>Campus Chronicle Title</title>
    <!-- Include your CSS files and external stylesheets here -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header section -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main content section -->
    <main>
        <section>
            <h1>Welcome to Campus chronicles</h1>
            <p>This is the main content.</p>
        </section>
    </main>

    <!-- Footer section -->
    <footer>
        <p>&copy; 2023 Campus chronicle </p>
    </footer>

 //end by using Javascript//
    <script src="script.js"></script>
</body>
</html>

````

#using html and CSS to adjust page and style 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .login-container {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 300px;
        }

        .login-container h2 {
            text-align: center;
            color: #333333;
        }

        .login-form {
            display: flex;
            flex-direction: column;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            font-size: 14px;
            color: #666666;
            margin-bottom: 5px;
        }

        .form-group input {
            width: 100%;
            padding: 8px;
            border: 1px solid #cccccc;
            border-radius: 4px;
            font-size: 14px;
        }

        .form-group button {
            background-color: #3498db;
            color: #ffffff;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
    </style>
</head>
<body>

#login page for web app using css

<div class="login-container">
    <h2>Login</h2>
    <form class="login-form" action="" method="post">
        <div class="form-group">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
        </div>
        <div class="form-group">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
        </div>
        <div class="form-group">
            <button type="submit">Login</button>
        </div>
    </form>
</div>

</body>
</html>

#style the page using PHP 
````
````



