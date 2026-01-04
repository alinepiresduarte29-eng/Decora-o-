<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Encanto Festas</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(90deg, #ff9a9e, #fad0c4);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 10px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .container {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }
    .card h3 {
      margin: 10px 0 5px;
    }
    .card p {
      font-size: 0.9rem;
    }
    .card button {
      margin-top: 10px;
      padding: 10px 15px;
      border: none;
      border-radius: 8px;
      background: #ff9a9e;
      cursor: pointer;
      font-weight: bold;
    }
    .card button:hover {
      background: #f77f88;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
