# Proyecto : Manipulación y gestión del DOM 
---
## Resumen de la tarea

Crear una mini-aplicación web que pueda **crear**, **editar** y **eliminar** tarjetas (“cards”) de producto dinámicamente manipulando el DOM con JavaScript. Deberán gestionar el proyecto con Git, subirlo a un repositorio en GitHub y documentar tanto el código como el proceso en un README.md profesional.

---
### Codigo HTML:

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarjetas de Productos</title>
    <link rel="stylesheet" href="style.css">
    <script src="tarjetas.js" defer></script>
</head>
<body>
    <h1>Tarjetas</h1>
    
    <form id="formulario" class="contenedor">
        <input type="text" id="titulo" placeholder="Título" required class="input" size="30"><br>
        <input type="text" id="imagen" placeholder="URL de la imagen" required class="input" size="30"><br>
        <textarea id="descripcion" placeholder="Descripción" class="input" size="30"></textarea><br>
        <button type="submit" class="boton">Crear Tarjeta</button>
    </form>
    <br>
    <div id="contenedor-tarjetas">
    </div>
</body>
