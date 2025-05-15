# Flask Ecommerce
Fitstore - An E-commerce app made with Flask , SQLite and Gunicorn

Features :
 📌Customers can sign up and login
 📌Customers can reset their passwords
 📌Customers can search for goods
 📌Add them to their cart
 📌Payment Gateway Functionality
 📌Admins can regulate shop products e.g stock level
 📌Admins can change order status

The app is containerized using Docker.The lightweight python:3.8-slim base image ensures efficient and quick deployment.

HOW TO USE:

docker pull souravangre/flask-fitstore

docker run -p 4000:4000 souravangre/flask-fitstore

