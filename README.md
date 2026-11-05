<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Actividad Formularios</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <form action="#" method="POST">
        <h2>Registro de Usuario</h2>
        
        <label for="nombre">Nombre completo:</label>
        <input type="text" id="nombre" name="nombre" placeholder="Ej. Alexander" required>

        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email" required>

        <label for="pass">Contraseña:</label>
        <input type="password" id="pass" name="pass" required>

        <label for="modulo">Módulo favorito:</label>
        <select id="modulo" name="modulo">
            <option value="marcas">Lenguajes de Marcas</option>
            <option value="sistemas">Sistemas Informáticos</option>
            <option value="programacion">Programación</option>
        </select>

        <input type="submit" value="Enviar Datos">
    </form>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    background-color: #e9efe9;
    padding: 50px;
}

form {
    background-color: white;
    width: 300px;
    margin: 0 auto;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    display: flex;
    flex-direction: column;
}

h2 {
    color: #2f5d46;
    margin-top: 0;
    text-align: center;
}

label {
    margin-bottom: 5px;
    font-weight: bold;
    font-size: 0.9em;
}

input, select {
    margin-bottom: 20px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

input[type="submit"] {
    background-color: #f08a24;
    color: white;
    border: none;
    font-weight: bold;
    cursor: pointer;
}
