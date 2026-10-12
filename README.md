# 🏋️‍♂️ AI-Powered Health & Fitness Challenge Platform — Backend API

A robust **Java Spring Boot RESTful API** powering the Health & Fitness Challenge platform. Designed with Clean Layered Architecture, it handles secure authentication, challenge workflows, user progress tracking, and **AI Agent Services with Prompt Engineering**.

🔗 **Frontend Repository:** [https://github.com/titirot/fitness-challenges-client](https://github.com/titirot/fitness-challenges-client)

---

## 🛠️ Tech Stack & Architecture

- **Language & Framework:** Java 17+, Spring Boot 3
- **AI & LLM Integration:** OpenAI API Integration, Custom Prompt Engineering & Context-Aware AI Agent Logic
- **Database & Persistence:** H2 In-Memory Database, Spring Data JPA / Hibernate
- **Security:** Spring Security, JWT (JSON Web Tokens) stateless authentication & RBAC
- **Architecture:** Layered Architecture (Controllers, Services, DTOs, Repositories, Mappers)
- **Build Tool:** Apache Maven

---

## ✨ Key Capabilities & Features

- **🤖 AI Agent & Prompt Engineering Service:** Backend service orchestrating LLM queries, system instructions, and structured context payload formatting for smart fitness recommendations.
- **🔐 Authentication & Authorization:** Secure JWT token generation, payload validation, and protected REST endpoints via Spring Security filters.
- **🏆 Challenge Workflow Engine:** Full CRUD functionality for challenge lifecycle, user enrollments, and status updates.
- **📊 Participant Progress Tracking:** Business logic calculating user metrics, score updates, and completion achievements.


## 🚀 Getting Started

### Prerequisites
- JDK 17 or higher
- Apache Maven

### Local Setup & Execution

### Local Setup & Execution

```bash
# 1. Clone the repository
git clone https://github.com/titirot/project-java.git
cd project-java

# 2. Build and run the Spring Boot application
mvn clean install
mvn spring-boot:run
```

![App Screenshot](https://github.com/user-attachments/assets/0eea54f2-9d61-478e-b197-3fbf0d9f87e1)

