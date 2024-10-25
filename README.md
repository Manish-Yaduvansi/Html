<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Website</title>
    <link rel="stylesheet" href="styles.css">
    <style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
}

h1, h2, h3, h4, h5, h6 {
    color: #222;
    margin-bottom: 0.5em;
}

h1 {
    font-size: 2.5em;
}

h2 {
    font-size: 2em;
}

h3 {
    font-size: 1.75em;
}

h4 {
    font-size: 1.5em;
}

h5 {
    font-size: 1.25em;
}

h6 {
    font-size: 1em;
}

p {
    margin-bottom: 1em;
}

a {
    text-decoration: none;
    color: #337ab7;
}

a:hover {
    color: #23527c;
}

/* Header Styles */

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

header h1 {
    margin: 0;
}

/* Navigation Styles */

nav {
    background-color: #444;
    padding: 0.5em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

nav li {
    margin-right: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

nav a:hover {
    color: #ccc;
}

/* Main Content Styles */

main {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2em;
}

section {
    background-color: #fff;
    padding: 1em;
    margin-bottom: 1em;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section h2 {
    margin-top: 0;
}

/* Recipe Styles */

.recipe {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.recipe img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px 10px 0 0;
}

.recipe h3 {
    margin: 0;
}

.recipe p {
    margin-bottom: 1em;
}

/* Footer Styles */

footer {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
    clear: both;
}

footer ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

footer li {
    margin-right: 20px;
}

footer a {
    color: #fff;
    text-decoration: none;
}

footer a:hover {
    color: #ccc;
}
@media only screen and (max-width: 768px) {
    main {
        flex-direction: column;
    }
    
    section {
        margin-bottom: 2em;
    }
    
    .recipe {
        flex-direction: column;
    }
    
    .recipe img {
        width: 100%;
        height: 150px;
    }
}


@media only screen and (min-width: 769px) and (max-width: 1024px) {
    main {
        flex-direction: row;
    }
    
    section {
        margin-bottom: 1em;
    }
    
    .recipe {
        flex-direction: row;
    }
    
    .recipe img {
        width: 50%;
        height: 200px;
    }
}

@media only screen and (min-width: 1025px) {
    main {
        flex-direction: row;
    }
    
    section {
        margin-bottom: 1em;
    }
    
    .recipe {
```
</style>
</head>
<body>
    <header>
        <h1>Recipe Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#recipes">Recipes</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#search">Search</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Welcome to Our Recipe Website!</h2>
            <p>Explore our collection of delicious recipes!</p>
            <button>Get Started</button>
        </section>
        <section id="recipes">
            <h2>Recipes</h2>
            <ul>
                <li>
                    <img src="chicken-fajitas.jpg" alt="Chicken Fajitas">
                    <h3>Chicken Fajitas</h3>
                    <p>Spicy chicken and vegetable stir-fry served with warm flour tortillas.</p>
                    <button>View Recipe</button>
                </li>
                <li>
                    <img src="vegetable-stir-fry.jpg" alt="Vegetable Stir-Fry">
                    <h3>Vegetable Stir-Fry</h3>
                    <p>Quick and easy stir-fry with your favorite vegetables.</p>
                    <button>View Recipe</button>
                </li>
                <li>
                    <img src="chocolate-cake.jpg" alt="Chocolate Cake">
                    <h3>Chocolate Cake</h3>
                    <p>Moist and decadent chocolate cake perfect for special occasions.</p>
                    <button>View Recipe</button>
                </li>
            </ul>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>We're passionate about cooking and sharing recipes!</p>
            <p>Meet our team:</p>
            <ul>
                <li>
                    <img src="john-doe.jpg" alt="John Doe">
                    <h3>John Doe</h3>
                    <p>Founder and Head Chef</p>
                </li>
                <li>
                    <img src="jane-doe.jpg" alt="Jane Doe">
                    <h3>Jane Doe</h3>
                    <p>Recipe Developer and Food Stylist</p>
                </li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: [info@recipewebsite.com](mailto:info@recipewebsite.com)</p>
            <p>Phone: 555-555-5555</p>
            <p>Address: 123 Main St, Anytown, USA</p>
        </section>
        <section id="search">
            <h2>Search Recipes</h2>
            <form>
                <input type="search" placeholder="Search recipes...">
                <button>Search</button>
            </form>
            <ul>
                <li>
                    <img src="search-result-1.jpg" alt="Search Result 1">
                    <h3>Search Result 1</h3>
                    <p>Short description of search result 1.</p>
                    <button>View Recipe</button>
                </li>
                <li>
                    <img src="search-result-2.jpg" alt="Search Result 2">
                    <h3>Search Result 2</h3>
                    <p>Short description of search result 2.</p>
                    <button>View Recipe</button>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Recipe Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
