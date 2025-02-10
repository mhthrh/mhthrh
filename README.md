
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![REST](https://img.shields.io/badge/REST-005571?style=for-the-badge&logo=rest&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=grpc&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Testify](https://img.shields.io/badge/Testify-FF5733?style=for-the-badge&logo=go&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)


---
# X-bank project

This project is currently **under production** and is built using the following technologies:

- **Programming Language**: Go (Golang)
- **Database**: PostgreSQL and Redis
- **Messaging**: Apache Kafka (for asynchronous messaging between microservices)
- **Communication**: gRPC (for synchronous request and response between services)
- **Authentication**: Hydra (for JWT management)
- **End User Communication**: HTTPS REST (for communication with end users)

---

## Microservices Architecture

- **Microservices**: The application is designed using a microservices architecture, where each service is independent, has its own database, and can communicate asynchronously via Kafka and synchronously via gRPC.
- **API Management**: An API management layer is used to expose APIs securely to end users through HTTPS REST. This layer ensures easy access to services and handles routing, load balancing, and API versioning.
- **Independent Databases**: Each microservice has its own independent database (PostgreSQL), which ensures better isolation, scalability, and flexibility.
---
### Microservices

- **customer-service**: Manages customer data and performs customer-related operations like registration, update, and retrieval.
- **address-service**: Manages customer addresses and provides functionality for adding, updating, and retrieving address details.
- **account-service**: manage accounts.
- **loan-service**: manage loan.
- **x-bank-db**:The database structure, migration tool, and data seeding for X-Bank.
- **vault**: manage security and config data.
- **GoNest**: Handles package management, model management, and includes a **common library** for shared functionality and utilities across the services.  
  - **Package Management**: Manages data related to packages.
  - **Model Management**: Handles models used across microservices for consistent data representation.
  - **Common Library**: A shared library that contains common code used by other microservices.


---
### 📫 Contact
📧 **Email:** m.rozbehani@outlook.com  
🔗 **LinkedIn:** [m-rozbehani](https://www.linkedin.com/in/m-rozbehani/)

---

⭐ **Let’s connect and build amazing software together!** 🚀  
