# Popcorncafe - Coffee Network Solution

Welcome to Popcorncafe, a ready-made solution for a fictional coffee network designed to handle high loads. This README serves as an overview of the project's architecture. For detailed descriptions and setup instructions, please refer to each specific repository.

## Project Overview

### Backend

Our backend is organized within a monorepository and includes a group of microservices. These services can be categorized into two main components:

#### Environment:
- **config-server**: Manages configuration settings.
- **discovery-service**: Enables service discovery.
- **gateway-service**: Acts as a gateway for external requests.

#### Services:
- **employee-service**: Handles employee-related operations.
- **client-service**: Manages customer interactions.
- **store-service**: Facilitates store operations.

**Technology Stack**:
- Language: Java
- Frameworks: Spring Boot, Spring Cloud, Spring Cloud Config, Spring Cloud Netflix (Eureka), Spring Cloud Gateway, and others.
- Databases: Each service interacts with its dedicated PostgreSQL database.
- Data Caching: Redis is employed for caching frequently requested data.
- Continuous Integration and Continuous Deployment (CI/CD): We've set up CI/CD using GitHub Actions. With each tagged release, our pipeline runs tests, builds, and publishes Docker images for each microservice.
- Production Deployment: In production, we utilize Kubernetes to orchestrate the services.

<div>
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/java-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/spring-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/spring-cloud-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/postgres-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/docker-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/kuber-logo.png?raw=true" height="45">
</div>

- [Link to Backend Repository](https://github.com/popcorncafe/popcorncafe-backend)

---

### Frontend

Our frontend consists of a collection of single-page applications customized for different user roles:

- **HR Application**: Tailored for HR-related functions.
- **Warehouse Application**: Designed for warehouse employees.
- **Cashier Application**: Manages cashier duties.
- **Informational Displays**: Includes order pickup displays and kitchen order displays.

**Technology Stack**:
- Language: TypeScript
- Framework: Angular
- CI/CD: We've established CI/CD pipelines for each application to ensure up-to-date Docker images are available in their respective repositories.

<div>
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/ts-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/angular-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/docker-logo.png?raw=true" width="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/kuber-logo.png?raw=true" width="45">
</div>

- [Link to HR Application Repository](#)
- [Link to Warehouse Application Repository](#)
- [Link to Cashier Application Repository](#)
- [Link to Informational Displays Repository](#)

---

### Client Application

Our client application is a Telegram bot designed to enhance the customer experience:

- **Functionality**:
  - Retrieve the nearest cafe's address based on location (longitude and latitude).
  - Fetch menus, providing a list of available items at the selected store.
  - Enable order assembly and payment.

**Technology Stack**:
- Language: Java
- Framework: Spring Framework
- Data Management: The bot does not have a database but stores orders in a Redis cache during the selection phase.

<div>
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/java-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/spring-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/tg-logo.png?raw=true" height="45">
  <img src="https://github.com/popcorncafe/.github/blob/main/images/logo/docker-logo.png?raw=true" height="45">
</div>

---

## Getting Started

For detailed instructions on setting up and running each component of Popcorncafe, please refer to the respective repository's README.

Thank you for exploring Popcorncafe, and we look forward to your contributions and feedback.

## License

This project is distributed under the [MIT License](LICENSE).

Thank you for your interest in the **Popcorncafe** project! We hope it proves to be useful and engaging for you.

<!-- 
## Contact

If you have questions or suggestions for improving the project, feel free to contact us:

- Email: [your email]
- Website: [link to your website]
-->
