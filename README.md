# Mi-pagina-Web
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alex - Página Web Personal</title>
  <style>
    /* Estilo general */
    body {
      background: linear-gradient(135deg, #1f1c2c, #928DAB);
      color: #ffffff;
      font-family: 'Roboto', sans-serif;
      text-align: center;
      padding: 50px;
      margin: 0;
      animation: fadeIn 2s ease-out;
    }
    
    h1 {
      font-size: 3em;
      margin: 20px 0;
      color: #ff6b81;
      animation: slideUp 1s ease-out;
    }

    p {
      font-size: 1.2em;
      margin-top: 20px;
      line-height: 1.5;
      animation: fadeInText 2s ease-out;
    }

    a {
      color: #ff6b81;
      text-decoration: none;
      font-size: 1.2em;
      margin-top: 20px;
      display: inline-block;
      padding: 10px 20px;
      border: 2px solid #ff6b81;
      border-radius: 5px;
      transition: 0.3s ease;
    }

    a:hover {
      background-color: #ff6b81;
      color: #fff;
      transform: scale(1.1);
    }

    /* Animaciones */
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    @keyframes slideUp {
      0% { transform: translateY(50px); opacity: 0; }
      100% { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeInText {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>¡Hola, soy Alex!</h1>
  <p>Me encanta la programación. Soy estudiante de preparatoria y me apasiona la tecnología.</p>
  <p>Si quieres ponerte en contacto conmigo, puedes escribirme a mi correo:</p>
  <a href="mailto:alexcarafloja@gmail.com">alexcarafloja@gmail.com</a>
</body>
</html>
