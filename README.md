# Food Delivery System

A modern web-based food ordering and delivery platform built using Java Spring Boot and MySQL. The application allows customers to browse food items, place orders, and make payments while providing admins full control over menu management, orders, and users.

## Features

- Customer registration and login
- Browse food items by category
- Add items to cart and checkout
- Place orders and view order history
- Admin dashboard for managing:
  - Products
  - Categories
  - Orders
  - Payments
  - Customers

## Tech Stack

- Java 11
- Spring Boot (Web, JPA, Validation)
- Hibernate
- MySQL
- Thymeleaf
- Bootstrap 5

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/onlinefooddelivery/
│   │       ├── controller/
│   │       ├── model/
│   │       ├── repository/
│   │       ├── service/
│   │       └── OnlineFoodDelivery.java
│   └── resources/
│       ├── templates/
│       ├── static/
│       └── application.properties
```

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/food-delivery.git
   ```

2. Configure your MySQL credentials in `application.properties`

3. Build and run the app:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Access the app at `http://localhost:8080`

## Roles

- **Customer**: Can register, browse products, order food
- **Admin**: Can manage products, customers, orders, and payments

## 📄 License

This project is intended for personal portfolio and educational use.
