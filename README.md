<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Para Ti ❤️</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      position: relative;
      color: #f8e3a3;
      z-index: 1;   
    }

    /* Fondo GIF animado */
    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url('https://i.pinimg.com/originals/9f/65/fa/9f65fa4741fbf0750544bf7c0fb7ae4d.gif');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      z-index: -1;
    }

    h1 {
      font-size: 2.5em;
      color: #ffe8a8;
      margin-bottom: 0.2em;
    }

    p {
      font-size: 1.2em;
      color: #f8e3a3;
      max-width: 600px;
      margin: 20px;
    }

    .corazon {
      font-size: 3em;
      animation: latido 1s infinite;
    }

    @keyframes latido {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    img {
      border-radius: 70%;
      margin-top: 25px;
      width: 300px;
      height: 300px;
      border: 2px solid #f8e3a3;
    }
  </style>
</head>
<body>
  <div>
    <h1>Hola mi amor ❤️</h1>
    <div class="corazon">💖</div>
    <p>
      Quería decirte cuánto te amo y lo importante que eres para mí. Cada día a tu lado es un regalo, y no hay palabras suficientes para expresar lo agradecido que estoy por tenerte en mi vida.
      <br /><br />
      Gracias por estar a mi lado. Eres mi alegría, mi calma y mi mundo.
    </p>
<img src="https://i.pinimg.com/originals/58/d3/3b/58d33b3be053f507a0e54779d6ed49b8.jpg" alt="cielo" />

</body>
</html>
