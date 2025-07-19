# llm-comparison-ai
Compare OpenAI and Ollama LLMs side-by-side using Spring Boot and React.

# LLM Comparison AI App

A full-stack web application for comparing responses from multiple Large Language Models (LLMs) including **OpenAI**, **Gemma (via Ollama)**, and others using a unified interface.

---

## 🔧 Tech Stack

| Frontend | Backend |
|----------|---------|
| React + Vite | Spring Boot 3 |
| Tailwind CSS | Spring AI |
| Axios | OpenAI API & Ollama |

---

## 📂 Project Structure

llm-comparison-ai/
├── backend/
│   └── SpringAiDemo/
│       ├── SpringAiDemo/
│       │   ├── src/
│       │   │   ├── main/
│       │   │   │   ├── java/com/telusko/SpringAiDemo/
│       │   │   │   │   ├── SpringAiDemoApplication.java
│       │   │   │   │   ├── OpenAIController.java
│       │   │   │   │   └── OllamaController.java
│       │   │   └── resources/
│       │   │       └── application.properties
│       │   ├── pom.xml
│       │   └── ...
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── assets/
│   ├── public/
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
└── README.md


---

## ⚙️ Features

- 🔁 Compare responses from OpenAI vs Ollama (Gemma)
- ⚡ Fast interaction using Spring AI
- 🎨 Clean UI built with Tailwind + React
- 🌐 Easy to extend with more LLMs

---

## 🚀 Running Locally

### 1. Backend (Spring Boot)

```bash
cd backend/SpringAiDemo/SpringAiDemo
./mvnw spring-boot:run
