<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Inventario 8 Secciones</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        display: flex;
        height: 100vh;
    }

    /* Contenedor del menú lateral izquierdo */
    .sidebar {
        width: 300px; /* Ancho del menú */
        background-color: #f4f4f4;
        display: grid;
        grid-template-columns: 1fr 1fr; /* Dos columnas */
        gap: 10px; /* Espacio entre cuadros */
        padding: 10px;
        box-sizing: border-box;
        border-right: 2px solid #ddd;
    }

    /* Estilo de cada cuadro/sección */
    .box {
        background-color: #007bff;
        color: white;
        text-decoration: none;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        border-radius: 8px;
        font-weight: bold;
        transition: background-color 0.3s;
        /* Para que tengan forma cuadrada basada en el ancho */
        aspect-ratio: 1 / 1; 
    }

    .box:hover {
        background-color: #0056b3;
    }

    /* Contenido principal al lado derecho */
    .main-content {
        flex: 1;
        padding: 20px;
    }
</style>
</head>
<body>

    <!-- MENÚ LATERAL -->
    <div class="sidebar">
        <a href="pagina1.html" class="box">Sección 1</a>
        <a href="pagina2.html" class="box">Sección 2</a>
        <a href="pagina3.html" class="box">Sección 3</a>
        <a href="pagina4.html" class="box">Sección 4</a>
        <a href="pagina5.html" class="box">Sección 5</a>
        <a href="pagina6.html" class="box">Sección 6</a>
        <a href="pagina7.html" class="box">Sección 7</a>
        <a href="pagina8.html" class="box">Sección 8</a>
    </div>

    <!-- CONTENIDO -->
    <div class="main-content">
        <h1>Esta primera pagina web en internet&nbsp;</h1>
        <p>Haga clic en uno de los cuadros del menú izquierdo.</p>
</div>

</body>
</html>
