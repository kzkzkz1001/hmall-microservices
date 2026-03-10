# hmall-microservices

An e-commerce microservices project based on **Spring Cloud Alibaba**, featuring core modules such as products, orders, payments, shopping carts, and user management.

---

## 🛠 Technology Stack 

* **Spring Boot**: 2.7.12
* **Spring Cloud**: 2021.0.x + **Alibaba**
* **Nacos**: 2.x (**Service Discovery** & **Configuration Management**)
* **OpenFeign** + **LoadBalancer**
* **MyBatis-Plus** + **MySQL**
* **Knife4j** + **Swagger** (API Documentation)
* **Lombok** + **Hutool**

---

## 📂 Module Description 

| Module | Description |
| :--- | :--- |
| **hm-common** | Shared utilities, exceptions, and constants |
| **hm-api** | Feign interface definitions and **DTOs**  |
| **item-service** | Product and Item management service  |
| **trade-service** | Order and transaction service  |
| **pay-service** | Payment processing service |
| **cart-service** | Shopping cart service |
| **user-service** | User authentication and profile service |

---

## 🚀 Quick Start 

1.  **Start Nacos**: Run Nacos in **standalone** mode .
2.  **Configure Nacos**: Update the `nacos server-addr` in the `application.yml` of each service.
3.  **Run Services**: Start each microservice in sequence .

---

## 🔗 Access

* **Swagger UI**: `http://localhost:PORT/swagger-ui.html`
* **Nacos Console**: `http://localhost:8848/nacos`

---
