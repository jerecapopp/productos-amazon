# productos-amazon
Página web para recomendar productos de Amazon
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Los mejores productos de Amazon recomendados por expertos en tecnología. Encuentra gadgets, dispositivos y más.">
  <title>Productos Más Recomendados de Amazon</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .intro {
      padding: 20px;
      background: #fff;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .product {
      background: #fff;
      border: 1px solid #ccc;
      border-radius: 10px;
      width: 250px;
      padding: 15px;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .product h3 {
      font-size: 18px;
      margin: 10px 0;
    }
    .product p {
      font-size: 14px;
      color: #555;
    }
    .product a {
      display: block;
      text-align: center;
      margin-top: 10px;
      background: #007bff;
      color: #fff;
      padding: 10px;
      border-radius: 5px;
      text-decoration: none;
    }
    .product a:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>

  <header>
    <h1>Productos Más Recomendados de Amazon</h1>
  </header>

  <section class="intro">
    <h2>Descubre los gadgets más populares y recomendados de este mes</h2>
    <p>Aquí te comparto una lista de productos de Amazon que realmente valen la pena. Todos los artículos han sido cuidadosamente seleccionados por su calidad y popularidad. ¡Haz clic y compra con confianza!</p>
  </section>

  <section class="products">
    <!-- Producto 1 -->
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Auriculares Inalámbricos XYZ">
      <h3>Auriculares Inalámbricos XYZ</h3>
      <p>Con sonido nítido y buena duración de batería. Perfectos para música, llamadas y ejercicio.</p>
      <a href="https://www.amazon.com/dp/B07DGLM6QT" target="_blank">Ver en Amazon</a>
    </div>

    <!-- Producto 2 -->
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Smartphone ABC">
      <h3>Smartphone ABC</h3>
      <p>Un teléfono potente con cámara increíble y pantalla AMOLED de alta definición.</p>
      <a href="https://www.amazon.com/dp/B08VJNK9YX" target="_blank">Ver en Amazon</a>
    </div>

    <!-- Producto 3 -->
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Cámara Digital XYZ">
      <h3>Cámara Digital XYZ</h3>
      <p>Captura fotos en 4K con una cámara compacta y fácil de usar. Ideal para viajes.</p>
      <a href="https://www.amazon.com/dp/B07M9JJYVG" target="_blank">Ver en Amazon</a>
    </div>

    <!-- Producto 4 -->
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Smartwatch PQR">
      <h3>Smartwatch PQR</h3>
      <p>Reloj inteligente con monitor de actividad, notificaciones y una batería de larga duración.</p>
      <a href="https://www.amazon.com/dp/B08L9C9TQ8" target="_blank">Ver en Amazon</a>
    </div>
  </section>

</body>
</html>
    
