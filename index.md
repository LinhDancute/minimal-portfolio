# Portfolio

## AIRLINE RESERVATION MANAGEMENT WEBSITE [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/LinhDancute/Airline-IdentityServices-MVC)

### Introduction

Developed a comprehensive online flight ticket booking system utilizing a microservices architecture, with service communication managed through `HttpClientFactory`. The system is designed using the MVC pattern and supports operation across multiple local environments.

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

<table>
  <tr>
    <th>Frontend</th>
    <th>Backend</th>
    <th>Unit Testing</th>
    <th>Database</th>
    <th>Documentation</th>
  </tr>
  <tr>
    <td style="vertical-align:top; width:20%;">
      <ul>
        <li><b>Angular 17</b></li>
        <li><b>ASP.NET Razor</b></li>
        <li><b>TypeScript</b></li>
        <li><b>JavaScript</b></li>
        <li><b>Bootstrap 5</b></li>
        <li><b>HTML</b></li>
        <li><b>CSS</b></li>
      </ul>
    </td>
    <td style="vertical-align:top; width:20%;">
      <ul>
        <li><b>.NET/.NET Core Framework 7/8</b></li>
        <li><b>Code First MVC</b></li>
        <li><b>Duende IdentityServer6</b></li>
        <li><b>Microservices Architecture</b></li>
        <li><b>RESTful API</b></li>
        <li><b>JWT (JSON Web Tokens)</b></li>
        <li><b>Entity Framework Core (Fluent API)</b></li>
        <li><b>Entity Framework 7/8</b></li>
        <li><b>LINQ</b></li>
      </ul>
    </td>
    <td style="vertical-align:top; width:20%;">
      <ul>
        <li><b>xUnit</b></li>
        <li><b>Karma</b></li>
        <li><b>Jasmine</b></li>
        <li><b>Postman</b></li>
      </ul>
    </td>
    <td style="vertical-align:top; width:20%;">
      <ul>
        <li><b>Microsoft SQL Server</b></li>
      </ul>
    </td>
    <td style="vertical-align:top; width:20%;">
      <ul>
        <li><b>ERD (Entity-Relationship Diagram)</b></li>
        <li><b>Sequence Diagram</b></li>
        <li><b>Activity Diagram</b></li>
        <li><b>Use Case Diagram</b></li>
        <li><b>DFD (Data Flow Diagram)</b></li>
        <li><b>BFD (Business Flow Diagram)</b></li>
        <li><b>Test Cases</b></li>
      </ul>
    </td>
  </tr>
</table>

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

<br>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/Manage.png" width="60%">
</div>
<center><img src="images/flight.png" width="100%"></center>
<br>

<div style="display: flex; justify-content: space-between; margin: 20px;">
    <div style="display: flex; justify-content: space-between; margin: 20px;">
        <img src="images/KarmaAndJasmine.png" style="height: 400px; width: 50%;" />
        <img src="images/xunit.png" style="height: 400px; width: 49%"/>
    </div>
</div>
<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/unitTestAngular.png" width="100%">
</div>

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

This system has three modules: Admin, Employee, and Client.

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

<table>
  <tr>
    <th>Frontend</th>
    <th>Backend</th>
    <th>Database</th>
    <th>Libraries/Services</th>
  </tr>
  <tr>
    <td>
      <ul>
        <li><b>JavaScript</b></li>
        <li><b>AJAX</b></li>
        <li><b>jQuery</b></li>
        <li><b>Bootstrap</b></li>
        <li><b>HTML</b></li>
        <li><b>CSS</b></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><b>PHP</b></li>
        <li><b>SQL</b></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><b>MySQL Workbench</b></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><b>Twilio SMS</b></li>
        <li><b>PHPMailer</b></li>
        <li><b>OAuth 2.0</b></li>
      </ul>
    </td>
  </tr>
</table>

<div style="display: flex; justify-content: space-between; margin: 20px;">
    <img src="images/main-shoes.png" alt="Manage" width="100%">
</div>
<center><img src="images/add-success.png" alt="Flight" width="100%"></center>
<center><img src="images/shoes-details.png" alt="Flight" width="100%"></center>
<center><img src="images/statistics.png"/></center>

---

## WEB API ECOMMERCE [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/LinhDancute/Ecommerce-AspNet-WEBAPI/tree/main/API_ASP.NET/Ecomm/Ecomm)

Allows access, user authentication, use of services and features without needing to access the website's interface.

**Technologies Used:** ASP
