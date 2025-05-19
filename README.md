Farmwheel/
│
├── index.html <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farmwheel - Precision. Power. Productivity.</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Farmwheel</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="product.html">Products</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Precision. Power. Productivity.</h2>
        <button>Explore Machines</button>
    </section>

    <section class="features">
        <div class="feature">
            <h3>Durability</h3>
            <p>Built to last in the toughest conditions.</p>
        </div>
        <div class="feature">
            <h3>Efficiency</h3>
            <p>Get more done in less time.</p>
        </div>
        <div class="feature">
            <h3>Innovation</h3>
            <p>Leading technology for modern farming.</p>
        </div>
    </section>

    <footer>
        <p>© 2025 Farmwheel. All rights reserved.</p>
    </footer>
</body>
</html>

├── about.html
├── product.html
├── contact.html
│
└── css/
    └── styles.css/* Basic Reset */
body, h1, h2, h3, p, a, button {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 10%;
    background-color: #f8f8f8;
}

header h1 {
    font-weight: bold;
}

header nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #333;
    font-weight: 500;
}

header nav a:hover {
    color: #666;
}

/* Hero Section */
.hero {
    background: url('../images/tractor.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 10%;
}

.hero h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.hero button {
    background-color: #333;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 1em;
}

.hero button:hover {
    background-color: #555;
}

/* Features */
.features {
    display: flex;
    justify-content: space-around;
    padding: 50px 10%;
    background-color: #f0f0f0;
}

.features .feature {
    flex: 1;
    text-align: center;
    margin: 20px;
}

.features h3 {
    font-size: 1.5em;
    margin-bottom: 15px;
}

.features p {
    color: #555;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 10%;
}
│
└── images/
