# Car Booking System

This is a Spring Boot-based Car Booking System application. It allows users to book cars, manage users, and handle car-related operations with a RESTful API.

## Features
- User and Car management
- Booking functionality
- Exception handling
- JPA repository integration
- RESTful API endpoints
 A simple Java Spring Boot application for managing car bookings, users, and related operations. This project demonstrates a layered architecture using controllers, services, DAOs, JPA repositories, and custom exception handling.
- `jpaRepo/` - Spring Data JPA repositories
- `entity/` - JPA entity classes
 ```
 CarBookingSystem/
 ├── src/
 │   ├── main/
 │   │   ├── java/com/CarBookingSystem/
 │   │   │   ├── controller/         # REST controllers
 │   │   │   ├── service/            # Business logic
 │   │   │   ├── Dao/                # Data access objects
 │   │   │   ├── jpaRepo/            # JPA repositories
 │   │   │   ├── entity/             # Entity classes
 │   │   │   ├── exceptions/         # Custom exceptions
 │   │   │   └── CarBookingSystemApplication.java
 │   │   └── resources/
 │   │       └── application.properties
 │   └── test/java/com/CarBookingSystem/
 │       └── CarBookingSystemApplicationTests.java
 ├── pom.xml
 └── README.md
 ```
- Maven 3.6+

### Build and Run
1. Clone the repository:
   ```
2. Navigate to the project directory:
   ```sh
   cd CarBookingSystem
   ```
3. Build the project using Maven:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```

### Configuration
Edit `src/main/resources/application.properties` to configure database and other settings.

## API Endpoints
Refer to the controller classes in `src/main/java/com/CarBookingSystem/controller/` for available endpoints.

## License
This project is licensed under the MIT License.
