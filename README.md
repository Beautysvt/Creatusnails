<!DOCTYPE html>
<html lang="es">
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
                <li><a href="#">Creador de Diseños</a></li>
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
                <input type="color" id="colorPicker" value="#ff00000">
                <button id="clearCanvas">Limpiar</button>
            </div>
                <button id="undo">Deshacer</button>
            <div>
                <button id="redo">Rehacer</button>
            </div>
                <button id="saveDesign">Guardar</button>
            <div>
                <button id="loadDesign">Cargar</button>
            </ul>
        </nav>
    </header>
    <main>
        <section id="Galeria">
              <h2>Galeria de inspiración</h2>
            <canvas id="nailCanvas" width="400" height="400"></canvas>
            <div id="tools">
                <input type="color" id="colorPicker" value="#ff0000">
                <button id="clearCanvas">Ver más</button>
    </main>
</body>

</html>
