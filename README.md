<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title></title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="main.css" />
    <script src="main.js"></script>
    <style>
        body {
            background-color: #e0f7fa;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        table {
            background-color: #ffffff;
            border: 2px solid #00838f;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #006064;
            margin-bottom: 20px;
        }
        td {
            padding: 10px;
        }
        a {
            text-decoration: none;
            color: #004d40;
            font-weight: bold;
            background-color: #b2ebf2;
            padding: 8px 15px;
            border-radius: 4px;
            display: inline-block;
            transition: background-color 0.3s;
        }
        a:hover {
            background-color: #4dd0e1;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td>
            <h1>OPCIONES</h1>
            </td>
        </tr>
        <tr>
            <td><a href="insertar.php">Insertar</a></td>
        </tr>
        <tr>
            <td><a href="consultar.php">Consultar</a></td>
        </tr>
        <tr>
            <td><a href="actualizar.php">Actualizar</a></td>
        </tr>
        <tr>
        <td><a href="borrar.php">Borrar</a></td>
        </tr>
    </table>
</body>
</html>
