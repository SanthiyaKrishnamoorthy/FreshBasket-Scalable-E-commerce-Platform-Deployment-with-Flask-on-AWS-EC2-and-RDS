# FreshBasket-Scalable-E-commerce-Platform-Deployment-with-Flask-on-AWS-EC2-and-RDS

Table of Contents
Project Overview
Features
Architecture


Project Overview
FreshBasket is a scalable, cloud-based e-commerce platform built with Flask and deployed on AWS using EC2 for hosting and Amazon RDS for database management. The platform supports basic e-commerce functionalities and provides a modular, scalable framework ideal for expanding the platform as user demand increases.

Features
User Management: Registration, authentication, and profile management.
Product Management: Add, edit, and delete products with images and descriptions.
Shopping Cart: Allows users to add/remove products, view totals, and checkout.
Order Management: View order history and track statuses.
Scalable Architecture: Designed to handle growing user and product data on AWS infrastructure.


Architecture
The FreshBasket platform is designed with a client-server architecture, using:
AWS EC2 to host the application server (Flask-based backend).
AWS RDS to handle the MySQL database, managing user and product data.
AWS S3 (optional) for static file storage (e.g., product images).
Prerequisites
Python 3.8+
AWS Account with IAM permissions to create EC2, RDS, and optionally S3 resources
AWS CLI configured with necessary credentials
