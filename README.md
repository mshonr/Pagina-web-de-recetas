<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recetas Deliciosas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }
        .recipe-card {
            background-color: #fff;
            border: 1px solid #ddd;
            width: 30%;
            margin: 15px;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .recipe-card img {
            width: 100%;
            border-radius: 8px;
        }
        .recipe-card h2 {
            font-size: 1.5em;
            color: #333;
        }
        .recipe-card p {
            font-size: 1.1em;
            color: #666;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Recetas Deliciosas</h1>
        <p>Descubre nuevas recetas para sorprender a tu paladar</p>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Recetas</a>
        <a href="#">Sobre Nosotros</a>
        <a href="#">Contacto</a>
    </nav>

    <div class="container">
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Imagen de receta 1">
            <h2>Ensalada Fresca</h2>
            <p>Una ensalada deliciosa y saludable, ideal para acompañar tus comidas.</p>
            <a href="#">Ver receta</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Imagen de receta 2">
            <h2>Pastel de Chocolate</h2>
            <p>El pastel de chocolate perfecto para una ocasión especial.</p>
            <a href="#">Ver receta</a>
        </div>
        <div class="recipe-card">
            <img src="https://via.placeholder.com/300x200" alt="Imagen de receta 3">
            <h2>Spaghetti al Pesto</h2>
            <p>Una receta rápida y deliciosa para una comida reconfortante.</p>
            <a href="#">Ver receta</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Recetas Deliciosas. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
