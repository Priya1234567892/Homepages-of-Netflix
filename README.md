# Homepages-of-Netflix
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <img src="netflix-logo.png" alt="Netflix Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">TV Shows</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">New & Popular</a></li>
                <li><a href="#">My List</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Unlimited movies, TV shows, and more.</h1>
            <p>Watch anywhere. Cancel anytime.</p>
            <button class="cta-button">Join Now</button>
        </div>
    </section>

    <!-- Featured Content -->
    <section class="featured">
        <h2>Featured Titles</h2>
        <!-- Featured movie or TV show cards go here -->
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>
</html>
/* styles.css */

/* Reset some default styles */
body, ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

/* Header Styles */
header {
    background-color: #111;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
}

.logo img {
    width: 100px;
    height: auto;
}

nav ul {
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Hero Section Styles */
.hero {
    background-image: url('hero-image.jpg');
    background-size: cover;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.cta-button {
    background-color: #e50914;
    color: #fff;
    padding: 15px 40px;
    font-size: 1.2rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

/* Featured Section Styles */
.featured {
    padding: 40px 0;
}

.featured h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

/* Footer Styles */
footer {
    background-color: #111;
    text-align: center;
    padding: 20px 0;
    color: #fff;
    font-size: 0.9rem;
}
