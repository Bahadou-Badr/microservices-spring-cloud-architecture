## Overview  
This application is built on a microservices architecture, integrating three core business services:  

1. **Customer Service**  
2. **Inventory Service**  
3. **Billing Service**  

It uses Spring Security with JWT for authentication and role-based access control, along with Spring Cloud services for service orchestration.  

---

## Key Features  

### 1. **Authentication Service**  
- Token-based authentication using JWT.  
- User and role management with predefined roles (`USER`, `ADMIN`, `CUSTOMER_MANAGER`, `PRODUCT_MANAGER`, `BILLS_MANAGER`).  
- Flexible role assignments.  

### 2. **Core Business Services**  
- **Customer Service** for managing customer data.  
- **Inventory Service** for product and inventory management.  
- **Billing Service** for processing financial transactions.  

### 3. **Service Orchestration**  
- **Spring Cloud Gateway:** Proxy service and entry point.  
- **Eureka Registry:** Service registration and discovery.  
- **Hystrix Circuit Breaker:** Fault tolerance and resilience.  
- **Hystrix Dashboard:** Real-time monitoring of circuit breakers.  

---

## Architecture  
The microservices architecture ensures independent scalability and deployment for each service. Spring Cloud services facilitate seamless communication, fault tolerance, and monitoring.  
