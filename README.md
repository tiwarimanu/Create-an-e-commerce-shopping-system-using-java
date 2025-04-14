# E-Commerce Shopping System

A comprehensive e-commerce shopping system built with Java and Spring Boot, featuring product browsing, cart management, checkout, and order processing.

## Features

- **User Management**: Registration, login, profile management
- **Product Catalog**: Browse products by category, search functionality
- **Shopping Cart**: Add, update, remove items
- **Checkout Process**: Shipping information, payment methods
- **Order Management**: View orders, order details, cancel orders
- **Admin Dashboard**: Manage products, categories, orders

## Technologies Used

- **Backend**: Java 11, Spring Boot 2.7.0
- **Frontend**: Thymeleaf, Bootstrap 5, HTML, CSS
- **Database**: H2 Database (embedded)
- **Security**: Spring Security
- **Build Tool**: Maven

## Project Structure

```
e-commerce-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── ecommerce/
│   │   │               ├── config/
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               ├── repository/
│   │   │               ├── security/
│   │   │               ├── service/
│   │   │               └── EcommerceApplication.java
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       └── application.properties
│   └── test/
└── pom.xml
```

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/ecommerce-system.git
cd ecommerce-system
```

2. Build the project
```bash
mvn clean install
```

3. Run the application
```bash
mvn spring-boot:run
```

4. Access the application
```
http://localhost:8080
```

## Default User Accounts

The system comes with pre-configured user accounts for testing:

- **Admin**:
  - Email: admin@example.com
  - Password: admin123

- **Regular User**:
  - Email: user@example.com
  - Password: user123

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Spring Boot for the framework
- Bootstrap for the UI components
- H2 Database for the embedded database

