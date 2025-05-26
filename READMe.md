<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Fitstore - Flask E-commerce App</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      padding: 30px;
      max-width: 800px;
      margin: auto;
    }
    h1 {
      color: #2c3e50;
      font-size: 2em;
      margin-bottom: 0;
    }
    h2 {
      color: #34495e;
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
      margin-top: 40px;
    }
    p {
      font-size: 1.1em;
    }
    ul {
      list-style-type: "📌 ";
      padding-left: 1.2em;
      font-size: 1.05em;
    }
    code {
      background-color: #eee;
      padding: 2px 6px;
      border-radius: 4px;
      font-size: 0.95em;
    }
    pre {
      background-color: #272822;
      color: #f8f8f2;
      padding: 15px;
      border-radius: 5px;
      overflow-x: auto;
      font-family: 'Courier New', monospace;
    }
    a {
      color: #0077cc;
      text-decoration: none;
    }
    .highlight {
      background-color: #e6f7ff;
      border-left: 5px solid #1890ff;
      padding: 10px 15px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <h1>🛍️ Flask Ecommerce - Fitstore</h1>
  <p class="highlight">
    <strong>Fitstore</strong> is a lightweight and fast e-commerce web application built using Flask, SQLite, and Docker. Designed for simplicity and scalability, it's ideal for learning, prototyping, or launching a basic online shop.
  </p>

  <h2>✨ Features</h2>
  <ul>
    <li>Customers can sign up and login</li>
    <li>Password reset functionality</li>
    <li>Search for goods</li>
    <li>Add items to cart</li>
    <li>Integrated payment gateway</li>
    <li>Admin product management (e.g., stock updates)</li>
    <li>Admin order status control</li>
  </ul>

  <h2>📦 Deployment</h2>
  <p>The app is containerized using Docker. It uses a minimal base image: <code>python:3.8-slim</code> for fast, lightweight deployment.</p>

  <h2>🚀 How to Use</h2>
  <p>To pull and run the Docker image locally:</p>

  <pre><code>docker pull souravangre/flask-fitstore
docker run -p 4000:4000 souravangre/flask-fitstore</code></pre>

  <p>Then open your browser and visit: <a href="http://localhost:4000" target="_blank">http://localhost:4000</a></p>

</body>
</html>
