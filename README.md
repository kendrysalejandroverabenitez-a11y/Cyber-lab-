# Cyber-lab-<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cyber Lab</title>

  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #080b12;
      color: #00eaff;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    .box {
      width: 85%;
      max-width: 500px;
      padding: 30px;
      border: 1px solid #00eaff;
      border-radius: 15px;
      box-shadow: 0 0 25px #00eaff55;
      background: #0d111c;
    }

    h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    p {
      color: #b8c7d9;
    }

    button {
      margin-top: 20px;
      padding: 12px 25px;
      border: none;
      border-radius: 8px;
      background: #00eaff;
      color: #061018;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      box-shadow: 0 0 15px #00eaff;
    }
  </style>
</head>

<body>

  <div class="box">
    <h1>CYBER LAB</h1>
    <p>Bienvenido al Laboratorio Cibernético</p>

    <button onclick="alert('Sistema funcionando correctamente ⚡')">
      INICIAR
    </button>
  </div>

</body>
</html>
