# 💸 Momentum Banking Application

**Momentum** is a financial services web application built with a microservices architecture using Spring Boot.  
It provides core banking features like money transfers, digital wallets, cashback, and transaction tracking.

---

## 🧩 Features

- 🔐 **User Service** – User registration, authentication, profile
- 💳 **Wallet Service** – Wallet creation, balance tracking, and wallet-to-wallet transfers
- 💰 **Cashback Service** – Cashback logic on eligible transactions
- 💸 **Transaction Service** – Transaction history, debit/credit tracking
- 📢 **Notification Service** – Notify users on successful transactions or updates
- 🔁 **API Gateway** – Routes all client requests
- 🧭 **Eureka Server** – Service discovery for microservices

---

## 🛠️ Tech Stack

| Layer         | Technology                |
|---------------|----------------------------|
| Backend       | Java 17, Spring Boot       |
| Microservices | REST API, Feign Client     |
| Service Reg.  | Eureka Server              |
| Gateway       | Spring Cloud Gateway       |
| Build Tool    | Maven                      |
| DB (Optional) | MySQL / H2 (for demo)      |
| Others        | Lombok, Spring Data JPA, Hibernate |

---

## ⚙️ How to Run the Project (Locally)

1. Clone the repo:
   ```bash
   git clone https://github.com/tejaswinidumbare/momentum-banking-app.git


<pre> <code> ```text momentum-banking-app │ ├── eureka-server ├── api-gateway ├── user-service ├── wallet-service ├── transaction-service ├── cashback-service ├── notification-service └── README.md ``` </code> </pre>
