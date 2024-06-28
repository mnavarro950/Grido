# Grido
Sorteo Grido Copa America
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sucursales de Heladerías Grido</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        button {
            display: block;
            width: 200px;
            margin: 10px auto;
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Elige tu sucursal</h1>
    <button onclick="enviarMensaje('Sucursal 1', '549123456789')">Sucursal 1</button>
    <button onclick="enviarMensaje('Sucursal 2', '549987654321')">Sucursal 2</button>
    <button onclick="enviarMensaje('Sucursal 3', '549112233445')">Sucursal 3</button>
    <button onclick="enviarMensaje('Sucursal 4', '549223344556')">Sucursal 4</button>
    <button onclick="enviarMensaje('Sucursal 5', '549334455667')">Sucursal 5</button>
    <button onclick="enviarMensaje('Sucursal 6', '549445566778')">Sucursal 6</button>
    <button onclick="enviarMensaje('Sucursal 7', '549556677889')">Sucursal 7</button>
    <button onclick="enviarMensaje('Sucursal 8', '549667788990')">Sucursal 8</button>

    <script>
        function enviarMensaje(sucursal, numero) {
            var mensaje = "Hola, quiero hacer un pedido a la " + sucursal;
            var url = "https://wa.me/" + numero + "?text=" + encodeURIComponent(mensaje);
            window.location.href = url;
        }
    </script>
</body>
</html>
