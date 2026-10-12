# 🏋️‍♂️ AI-Powered Health & Fitness Challenge Platform — Backend API

A robust, enterprise-grade RESTful API built with Java and Spring Boot to power the Health & Fitness Challenge platform. Features a custom AI Agent engine with LLM integration, secure JWT authentication, and structured challenge logic.

🔗 **Frontend Repository:** [https://github.com/titirot/health-fitness-tracker-frontend](https://github.com/titirot/health-fitness-tracker-frontend)

---

## 🛠️ Tech Stack & AI Architecture

- **Language & Framework:** Java 17+, Spring Boot
- **AI & LLM Integration:** OpenAI API Integration, Prompt Engineering, Function Calling & Structured JSON Parsing
- **Security:** Spring Security, JWT (JSON Web Tokens) Authentication & Role-Based Access Control
- **Database & ORM:** H2 In-Memory Database, Spring Data JPA / Hibernate
- **Build & Dependency Tool:** Apache Maven

---

## ✨ Key Capabilities & Features

- **🧠 Custom AI Agent Engine:** Integrates with LLM APIs using tailored prompt engineering techniques to process user fitness goals, generate personalized workout advice, and output structured payload responses.
- **🔐 Secure Authentication:** JWT generation, token validation, dynamic Security Context handling, and protected REST endpoints.
- **🏆 Challenge Management & Logic:** Complete CRUD services for creating, managing, and tracking multi-user fitness challenges.
- **📊 Participant Progress Tracking:** Scalable business logic to calculate scoring, track user milestones, and record challenge completion.
- **🏗️ Clean Layered Architecture:** Strict separation of concerns following DTO, Controller, Service, Repository, and Entity design patterns.

---

## 🚀 Getting Started

### Prerequisites
- **JDK 17** or higher
- **Apache Maven**
- **OpenAI API Key** (Set as environment variable `OPENAI_API_KEY`)

### Local Setup & Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/titirot/health-fitness-tracker-backend.git](https://github.com/titirot/health-fitness-tracker-backend.git)
   cd health-fitness-tracker-backend
