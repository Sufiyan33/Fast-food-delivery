# Fast-food-delivery
Fast Food Delivery : Creating Java &amp; Spring boot based application where a user can search restaurant as per his choice, select food post that order.
Once a user placed order then delivery boy will pick that parcel and will deliver to the customers.

# Application - Task Management
- [ ] login/signup
- [ ] Create user profile
- [ ] Search Restaurants
- [ ] Select Menu
- [ ] Add in cart
- [ ] Select address
- [ ] Select coupon code
- [ ] Do payment
- [ ] Order placed
- [ ] Deliver order

# Architecture
- **Micro-service** architecture
- **Config** : for swagger, logs, security etc
- **Entities** : Represents a table ina database (pojo)
- **Models** : Represents the Business Logic
- **Controllers** : handlers or endpoints
- **Helpers** : functions (Date, Strings, Conversions, Uploads, ...)
- **Enums** : constant, keyword, ...

# Components
- Api Gateway
- Service Registry
- Admin Service
- Retaurant Service
- User Service
- Location Service
- Delivery Service
- Cart Service
- Payment Service
- Notification Service

# Dependencies
- Spring web starter
- Spring data JPA starter
- Mysql
- H2 databse
- lomboc
- Spring cloud
- Eureka server
- Eureka client
- Histrix or Resilience4j
- Devetools
- Apache Kafka
- Rest Template

# Installation
- Mysql database
- Apache kafka (offset explorer)
- Git
- Maven
- Clone git repository :
