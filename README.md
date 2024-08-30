//html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Muu Furniture Store</title>
    <link rel="stylesheet" href="/CSS/register.css"> <!-- Link to your CSS file for styling -->
</head>
<body>

<header>
    <div class="container">
        <h1><a href="Home.html">Muu Furniture Store</a></h1>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="login.html">Login</a></li>
            </ul>
        </nav>
    </div>
</header>

<section class="register">
    <div class="container">
        <h2>Register</h2>
        <form action="/submit-register" method="POST">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <label for="confirm-password">Confirm Password:</label>
                <input type="password" id="confirm-password" name="confirm-password" required>
            </div>
            <button type="submit" class="btn">Register</button>
        </form>
        <p>Already have an account? <a href="login.html">Login here</a>.</p>
    </div>
</section>

</body>
</html>




//css code


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


header h1 a {

    color: #fff;
    text-decoration: none;}
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}
header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Register Section */
.register {
    padding: 50px 0;
    text-align: center;
}

.register .container {
    max-width: 400px;
    margin: 0 auto;
    padding: 0 20px;
}

.register h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

.register form {
    display: flex;
    flex-direction: column;
}

.register .form-group {
    margin-bottom: 15px;
    text-align: left;
}

.register .form-group label {
    display: block;
    margin-bottom: 5px;
    color: #666;
}

.register .form-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

.register .btn {
    padding: 10px 20px;
    background-color: #f39c12;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 1em;
    cursor: pointer;
}

.register .btn:hover {
    background-color: #e67e22;
}

.register p {
    margin-top: 20px;
    color: #3c3434;
}

.register p a {
    color: #e67e22;
    text-decoration: none;
}

.register p a:hover {
    text-decoration: underline;
}



body{
    background-image: url('/Source/WhatsApp\ Image\ 2024-07-26\ at\ 20.54.49_3dddd8fe.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
