<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sweet Scoops</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- NAVBAR -->
<header>
    <nav class="navbar">
        <h1 class="logo">🍦 Sweet Scoops</h1>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">Flavors</a></li>
            <li><a href="#">About</a></li>
        </ul>
    </nav>
</header>

<!-- HERO -->
<section class="hero">
    <div class="hero-content">
        <h2>Delicious Ice Cream Made Daily</h2>
        <p>Fresh, creamy, and made with love 🍓</p>
        <button>Order Now</button>
    </div>
</section>

<!-- FLAVORS -->
<section class="flavors">
    <h2>Our Flavors</h2>

    <div class="flavor-grid">
        <div class="card">
            <h3>Strawberry Bliss</h3>
            <p>Sweet and fruity goodness</p>
        </div>

        <div class="card">
            <h3>Chocolate Dream</h3>
            <p>Rich and creamy chocolate</p>
        </div>

        <div class="card">
            <h3>Vanilla Classic</h3>
            <p>Simple, smooth, perfect</p>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section class="about">
    <h2>Why Choose Us?</h2>
    <p>
        We use fresh ingredients and create every scoop with passion. 
        Our mission is to bring joy with every bite.
    </p>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Sweet Scoops | Made with ❤️</p>
</footer>

</body>
</html>
/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* BODY */
body {
    font-family: Arial, sans-serif;
    background-color: #fff7f0;
    color: #333;
}

/* NAVBAR */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 40px;
    background-color: #ff8fab;
}

.logo {
    color: white;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* HERO */
.hero {
    height: 80vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: linear-gradient(to right, #ffccd5, #cdb4db);
}

.hero h2 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.hero p {
    margin-bottom: 20px;
    font-size: 1.2rem;
}

.hero button {
    padding: 12px 25px;
    border: none;
    background-color: #ff4d6d;
    color: white;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 25px;
}

/* FLAVORS */
.flavors {
    padding: 60px 40px;
    text-align: center;
}

.flavor-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    margin-top: 30px;
}

.card {
    background: white;
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

/* ABOUT */
.about {
    padding: 60px 40px;
    text-align: center;
    background-color: #ffe5ec;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background-color: #ff8fab;
    color: white;
}
