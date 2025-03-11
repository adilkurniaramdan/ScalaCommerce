# ScalaCommerce

ScalaCommerce is a **scalable, event-driven e-commerce platform** built using **Scala**, **Play Framework**, and **Akka Actor Model**. Designed for high concurrency and reactive architecture, ScalaCommerce leverages **event sourcing** and **CQRS** to provide a robust online shopping experience.

## Features
- **Play Framework**: Leverages Play for reactive web application development.
- **Akka Actor Model**: Utilizes actors for handling asynchronous processes efficiently.
- **Event-Driven Architecture**: Implements event sourcing to manage state changes and ensure consistency.
- **CQRS Pattern**: Separates read and write concerns for performance optimization.
- **Scalable & Fault-Tolerant**: Designed to handle a high volume of transactions.
- **API-First**: Provides RESTful APIs for seamless frontend integration.
- **Database Support**: Works with PostgreSQL, MySQL, or MongoDB (configurable) current DB is H2.
- **Authentication & Authorization**: Secure login and role-based access control.

## Tech Stack
- **Language**: Scala
- **Framework**: Play Framework
- **Concurrency**: Akka Actors
- **Database**: H2/ PostgreSQL / MySQL / MongoDB (configurable)
- **Event Processing**: Kafka / Akka Event Sourcing
- **Testing**: ScalaTest, Gatling for performance testing

## Getting Started

### Prerequisites
Ensure you have the following installed:
- JDK 11+
- sbt (Scala Build Tool)
- PostgreSQL (or preferred database)
- Docker (optional for containerization)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/adilkurniaramdan/ScalaCommerce.git
   cd ScalaCommerce
   ```
2. Install dependencies:
   ```sh
   sbt update
   ```
3. Run the application:
   ```sh
   sbt run
   ```
4. Access the API:
   ```
   http://localhost:9000

   Test Users
    - **Username**: user@user.com
    - **Password**: 123456
    
    Admin
    - **Username**: admin@admin.com
    - **Password**: 123456
  ```

## Integration Test
```
/test/functionalspec/OrderControllerFinishedSpec
```


## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new feature branch (`feature-xyz`).
3. Commit your changes with clear messages.
4. Open a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
