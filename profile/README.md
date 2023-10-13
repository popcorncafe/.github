# Popcorncafe

**Popcorncafe** is a pet project of a fictional coffee network presented in the form of repositories related to the backend, frontend, and client application.

## Backend

The **Popcorncafe** backend consists of a group of microservices written in Java and utilizing the Spring Framework. These microservices use the following technologies:

- **Spring Boot**: for creating standalone microservices.
- **Spring Cloud**: for implementing shared infrastructure.
- **Spring Cloud Config**: for centralized configuration management.
- **Spring Cloud Netflix (Eureka)**: for service discovery and registration.
- **Spring Cloud Gateway**: for request management and routing.

Each microservice interacts with its own PostgreSQL database.

## Frontend

The **Popcorncafe** frontend comprises several single-page applications (SPAs) written in TypeScript and using the Angular framework. The main SPAs include:

- **HR Application**: An interface for managing HR activities.
- **Warehouse Workers Application**: An interface for managing warehouse operations.
- **Cashiers Application**: An interface for order processing and payment.
- **Information Displays**: These include order pickup displays and kitchen order displays.

## Client Application

**Popcorncafe** also provides a client application in the form of a Telegram bot for convenient customer interaction. Key features include:

- Retrieving the nearest cafe's address based on location (longitude and latitude).
- Accessing menus and information about available dishes.
- Building orders and making payments through the bot.

## Installation and Running

To run the components of **Popcorncafe**, please follow the instructions in the respective backend, frontend, and client application repositories.

## License

This project is distributed under the [MIT License](LICENSE).

Thank you for your interest in the **Popcorncafe** project! We hope it proves to be useful and engaging for you.
<!-- 
## Contact

If you have questions or suggestions for improving the project, feel free to contact us:

- Email: [your email]
- Website: [link to your website]
--!>

