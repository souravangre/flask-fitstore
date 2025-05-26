<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"
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
