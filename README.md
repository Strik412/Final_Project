# OFISMART


Overview

Paper Chain is a highly scalable and distributed e-commerce system designed for a stationery store. It is built using a microservices architecture, ensuring flexibility, scalability, and high availability. The project is fully deployed on AWS using services like EC2, S3, RDS, MongoDB, Load Balancer, and Auto Scaling.


Project Structure

The system is divided into multiple domains, each containing specific microservices:

User Management 
- `create-user-service` ➝ Handles new user registration.
- `login-service` ➝ Manages user authentication.
- `logout-service` ➝ Handles user logout.


Products Management 
- `create-product-service` ➝ Creates new products.
- `list-product-service` ➝ Lists available products.


Catalog
- `search-product-service` ➝ Searches for products.
- `detail-product-service` ➝ Fetches product details.


Orders 

Cart 

Inventory 



