# Operador Marcianos

**Operador Marcianos** is a distributed, event-driven microservices system designed for scalable and modular operations. The architecture follows a multi-repository approach, with each service independently developed and deployed.

## 🧩 Repositories

### 📄 Document Modules

- [consumer-lotso-documents](https://github.com/jdvalencir/consumer-lotso-documents)
- [marcianos_documents](https://github.com/jdvalencir/marcianos_documents)
- [bridge-lotso-documents](https://github.com/jdvalencir/bridge-lotso-documents)

### 🔄 Transfer Module

- [Forky-TransferCitizen](https://github.com/jdvalencir/Forky-TransferCitizen)
- [Bridge-Forky-TransferCitizen](https://github.com/jdvalencir/Bridge-Forky-TransferCitizen)

### 🔐 Authentication

- [Lightyear-Auth](https://github.com/jdvalencir/Lightyear-Auth)
- [Bridge-Lightyear-Auth](https://github.com/jdvalencir/Bridge-Lightyear-Auth)

### 🖥️ Frontend

- [BoPeep-Frontend](https://github.com/jdvalencir/BoPeep-Frontend)

## ⚙️ Tech Stack

- **Languages & Frameworks:** Node.js, FastAPI, Spring Boot
- **Database:** PostgreSQL
- **Authentication:** Firebase
- **Orchestration & Containers:** Kubernetes, Docker, Helm
- **Gateway:** Traefik
- **Messaging:** RabbitMQ
- **CI/CD:** Automated pipelines for continuous integration and deployment with Github Actions
- **Cloud:** Google Cloud Platform (GCP)

## 🚀 Deployment

Each microservice is containerized and deployed on Kubernetes clusters using Helm charts. Traefik serves as API Gateway, managing routing, SSL termination and JWT Validation. CI/CD pipelines ensure automated testing, building, and deployment processes.

## 📄 License

This project is licensed under the [Apache 2.0 License](LICENSE).
