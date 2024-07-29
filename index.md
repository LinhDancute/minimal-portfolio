# Portfolio

## AIRLINE RESERVATION MANAGEMENT WEBSITE [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/LinhDancute/Airline-IdentityServices-MVC)

### Introduction

Designed and implemented an online flight ticket booking system, reducing system response time by 25% through the use of a microservices architecture with HttpClientFactory for efficient service communication. The system is designed using the MVC pattern and supports operation across multiple local environments.


**Key Components**

- **WebClient (localhost:7000):** Built with Blazor Web, this component handles administrative management and system configuration, providing a robust interface for backend operations.
- **SPAClient (localhost:4200):** Developed with Angular, this single-page application (SPA) facilitates end-user interactions for booking flights, managing tickets, and viewing itineraries.
- **AuthAPI (localhost:7002):** Manages authentication and authorization using JWT tokens to secure access across the system.
- **ScheduleAPI (localhost:7003):** Provides functionalities for managing flight schedules, including availability and timetable management.
- **CouponAPI (localhost:7004):** Handles ticket booking processes and voucher issuance, integrating seamlessly with other system components.
- **ApiGateway (localhost:7005):** Acts as a secure entry point, managing and routing requests to AuthAPI, ScheduleAPI, and CouponAPI to ensure robust security and efficient request handling.
- **Duende IdentityServer6 (localhost:7006):** Implements OpenID Connect (OIDC) for authentication and authorization, enabling secure user access and integration with the WebClient.
- **Unit Testing:** Ensured reliability and code quality with xUnit for backend services and Karma/Jasmine for the Angular SPAClient.

### Technologies Used
- **Front-End:**  Angular 17, ASP.NET Razor, TypeScript, JavaScript, Bootstrap 5, HTML, CSS
- **Back-End:**   .NET/.NET Core Framework 7/8, Code First MVC, Duende IdentityServer6, Microservices, Restful API, JWT,
Entity Framework Core Fluent API, LINQ
- **Unit Testing:**  XUnit, Karma, Jasmine, Postman
- **Database:**   Microsoft SQL Server/Azure Data Studio
- **Documentation:** Produced comprehensive documentation, including ERD, Sequence Diagrams, Activity Diagrams, Use Cases, DFD, BFD,
and Test Cases, ensuring clear communication and project clarity.

### Demo

**SPAClient(Angular)/localhost: 4200**

<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/header.png" width="100%">
</div>
<center><img src="images/flightSearch.png" width="100%"></center>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/flightList.png" width="100%">
</div>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/orderConfirm.png" width="100%">
</div>

**WebClient(Blazor Web)/localhost: 7000**

<br>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/Manage.png" width="60%">
</div>
<center><img src="images/flight.png" width="100%"></center>
<br>

**Unit Testing (backend services by XUnit and SPA Angular by Karma/Jasmine/localhost:9876)**

<div style="display: flex; justify-content: space-between; margin: 20px;">
    <div style="display: flex; justify-content: space-between; margin: 20px;">
        <img src="images/KarmaAndJasmine.png" style="height: 400px; width: 50%;" />
        <img src="images/xunit.png" style="height: 400px; width: 49%"/>
    </div>
</div>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/unitTestAngular.png" width="100%">
</div>

**The document includes diagrams for system analysis**

<br>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/usecase.png" style="width: 48%; object-fit: cover;">
    <img src="images/sequence.png" style="width: 48%; object-fit: cover;">
</div>
<center><img src="images/activity.png"/></center>
<br>

---

## ONLINE SHOES SHOPPING SYSTEM [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/LinhDancute/Online-Shoes-Shopping-System_PHP/tree/main/Web2)

See website at [***Shoes Website***](https://ld-shoe-php.000webhostapp.com/).

### Introduction

Developed a comprehensive e-commerce platform for online shoe shopping, enhancing the customer experience with a
responsive front-end and robust back-end. Increased user engagement by improving site responsiveness and streamlining the checkout
process in a fast-paced development environment. This system has three modules: Admin, Employee, and Client.

- **Admin:** 
  - Can perform CRUD operations on products.
  - Add new employees.
  - Grant permissions for employees to view/edit/create.

- **Employee:** 
  - Manage orders and product information.

- **Client:**
  - Users can sign up/sign in (via external provider: Google or regular login by authenticating account via Gmail).
  - Shop and store products in the shopping cart even if the website is turned off.
  - View purchase history.

### Technologies Used

- **Front-End:** JavaScript, AJAX, JQuery, Bootstrap 5, HTML, CSS
- **Back-End:** PHP, SQL
- **Database:** MySQL Workbench, PhpmyAdmin
- **Third-Party Integration:**  Twilio SMS, PHPMailer, OAuth 2.0 (Implemented Twilio SMS for customer notifications, PHPMailer for seamless email communication, and OAuth 2.0 for secure user authentication, boosting customer satisfaction by 20%.)

### Demo

<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/main-shoes.png" alt="Manage" width="100%">
</div>
<center><img src="images/add-success.png" alt="Flight" width="100%"></center>
<center><img src="images/shoes-details.png" alt="Flight" width="100%"></center>
<center><img src="images/statistics.png"/></center>

---

## EQUIPMENT LENDING AND MANAGEMENT WEBSITE [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/LinhDancute/Spring-member-MVC/tree/master/spring-member-mvc)

### Introduction

Developed a comprehensive platform for equipment lending and management, increasing user efficiency by 30% by
streamlining the process with a user-friendly interface and robust back-end using Spring MVC and Spring Data JPA.

**Technologies Used:** 

- **Front-End:** Thymeleaf, JavaScript, AJAX, Bootstrap 5, HTML, CSS
- **Back-End:** Spring MVC, Spring Data JPA, Hibernate, MySQL
- **Database:** PhpmyAdmin
- **Additional Details:** : Implemented Hibernate ORM for optimal database management, leveraging MySQL with PhpMyAdmin for seamless data
handling and administration. Applied best practices in design and development to ensure scalability and maintainability.
