# Dusk-and-Dine
Final Project Coding and Bootstrap
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Homepage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #203350; }
        .container { max-width: 800px; margin: auto; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    img{max-width:100%; height: auto;}
        h1 { color: #333 };
        p { line-height: 1.6; }
        .contact { margin-top: 20px; }
        .contact a { color: #1A73E8; text-decoration: none; }
        .contact a:hover { text-decoration: underline; }
        .work-item {margin-bottom: 15px;}
        .work-item p{margin: 15px 0;}
    </style>
    <header>
        <div class="container">
            <h1>Delicious Recipes</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Recipes</a></li>
                    <li><a href="#">Categories</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section class="hero">
            <div class="container">
                <h2>Find Your Next Favorite Recipe</h2>
                <p>Explore a variety of recipes that are easy to make and delicious to eat.</p>
                <a href="#" class="btn">Browse Recipes</a>
            </div>
        </section>
        <section class="featured-recipes">
            <div class="container">
                <h2>Featured Recipes</h2>
                <div class="recipe-grid">
                    <!-- Recipe items will go here -->
                    <article class="recipe-item">
                        <img src="images/recipe1.jpg" alt="Recipe 1">
                        <h3>Recipe Title 1</h3>
                        <p>Short description of Recipe 1.</p>
                        <a href="#" class="btn">Read More</a>
                    </article>
                    <article class="recipe-item">
                        <img src="images/recipe2.jpg" alt="Recipe 2">
                        <h3>Recipe Title 2</h3>
                        <p>Short description of Recipe 2.</p>
                        <a href="#" class="btn">Read More</a>
                    </article>
                    <!-- More recipes can be added here -->
                </div>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2024 Delicious Recipes. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
