Step 1: Development Environment Setup
-------------------------------------
* Install JDK: Obtain JDK 17 or later from a reputable source.
* Install IDE: Choose and install an IDE like IntelliJ IDEA, Eclipse, or VS Code.
* Install Maven: Get Maven from its official site.
  
Step 2: Spring Boot Project Initialization
------------------------------------------
* Spring Initializr: Visit the Spring Initializr portal.
* Project Configuration: Select Maven, Java, and Spring Boot 3.3.0. Fill in your project details and choose dependencies like Spring Web, JPA, H2 Database, and Actuator.
* Project Generation: Generate and extract the project ZIP.
* IDE Setup: Import the project as a Maven project in your IDE.
  
Step 3: Microservices Creation
------------------------------
* UserService Setup: In a new package, create the main class and a REST controller for user operations.
* OrderService Setup: In another package, set up the main class and a REST controller for order management.
  
Step 4: Application Configuration
---------------------------------
* Properties Files: Create application.properties for each service with unique server ports and database settings.
  
Step 5: Running and Testing Services
------------------------------------
* Start Services: Run the main classes in your IDE or use Maven commands.
* Testing: Utilize tools like Postman to interact with the services’ endpoints and confirm their operational status.

  Reference link : https://spring.io/guides/gs/rest-service
