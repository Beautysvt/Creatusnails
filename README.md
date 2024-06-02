<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <header>
        <h1>Crea tus uñas</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Editor de Diseños</a></li>
                <li><a href="#">Galería de inspiración</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="editor">
            <h2>Crea tu diseño</h2>
            <canvas id="nailCanvas" width="400" height="400"></canvas>
            <div id="tools">
                <input type="color" id="colorPicker" value="#ff0000">
                <button id="clearCanvas">Limpiar<button>
            </div>
        </section>
    </main>
</body>
</html>
