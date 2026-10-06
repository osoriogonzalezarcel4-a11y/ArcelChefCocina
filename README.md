index.html<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ArcelChefCocina</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #fff8f0;
      color: #333;
      text-align: center;
    }

    header {
      background: #8b0000;
      color: white;
      padding: 25px;
    }

    h1 {
      margin: 0;
      font-size: 32px;
    }

    .contenido {
      padding: 30px 20px;
    }

    button {
      background: #8b0000;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
    }

    button:hover {
      background: #b22222;
    }

    #mensaje {
      margin-top: 25px;
      font-size: 20px;
      font-weight: bold;
    }
  </style>
</head>

<body>

  <header>
    <h1>👩‍🍳 ArcelChefCocina</h1>
    <p>Sabores cubanos con presentación gourmet</p>
  </header>

  <div class="contenido">
    <h2>Bienvenido a mi cocina</h2>
    <p>Descubre recetas, platos criollos y nuevas ideas de cocina.</p>

    <button onclick="mostrarMensaje()">Ver receta</button>

    <div id="mensaje"></div>
  </div>

  <script>
    function mostrarMensaje() {
      document.getElementById("mensaje").innerHTML =
        "🍽️ ¡Próximamente tendrás deliciosas recetas cubanas gourmet!";
    }
  </script>

</body>
</html>
