# 🌍 AI Travel Planner Agent

> An **LLM-powered AI travel planning application** that generates personalized travel itineraries using **Groq LLM**, built with **Streamlit**, deployed using **Docker & Kubernetes**, and equipped with **centralized logging using the ELK stack**.

---

## 🚀 Problem Statement

Planning a trip involves researching destinations, budgets, accommodations, transport, and daily itineraries across multiple platforms.

Traditional travel planning tools:
- are not conversational  
- lack personalization  
- cannot adapt dynamically to follow-up requests  

This project solves the problem by building an **AI-powered travel planner** that generates **custom itineraries in real time** based on user preferences.

---

## 🧠 Solution Overview

The AI Travel Planner uses a **Large Language Model (Groq)** to generate intelligent, context-aware travel plans based on inputs such as destination, duration, budget, and interests.

### High-level Flow:
1. User provides travel requirements  
2. Request is sent to the AI Travel Planner  
3. Groq LLM generates a personalized itinerary  
4. User can refine the plan using follow-up queries  
5. Application logs are centrally collected for observability  

---

## 🏗️ Architecture

**User**  
↓  
**Streamlit Web UI**  
↓  
**AI Travel Planner (Groq LLM)**  
↓  
**Dockerized Application**  
↓  
**Kubernetes (GCP / Minikube)**  
↓  
**Filebeat (Log Collection)**  
↓  
**Logstash (Log Processing)**  
↓  
**Elasticsearch (Log Storage)**  
↓  
**Kibana (Log Visualization)**

---

## 🛠️ Tech Stack

### AI / LLM
- **Groq LLM** – ultra-fast inference

### Frontend
- **Streamlit** – interactive web UI

### Backend & Deployment
- **Docker**
- **Kubernetes (Minikube / GCP)**
- **kubectl**

### Observability (Logs)
- **Filebeat** – log shipping  
- **Logstash** – log processing  
- **Elasticsearch** – centralized log storage  
- **Kibana** – log visualization  

### Version Control
- **GitHub**

---

## ✨ Key Features

- 🧳 AI-generated personalized travel itineraries  
- 💬 Conversational planning with follow-up support  
- ⚡ Low-latency responses using Groq LLM  
- 🎨 Simple and interactive Streamlit UI  
- 🐳 Fully containerized application  
- ☸️ Kubernetes-based scalable deployment  
- 📊 Centralized logging with ELK stack  
- 🔍 Debuggable, observable AI system  

---

## 📌 Example Use Cases

- “Plan a 5-day trip to Goa under ₹30,000”  
- “Modify the itinerary to include adventure sports”  
- “Suggest budget-friendly hotels”  
- “Optimize travel plan for a family trip”  

➡ The system adapts intelligently to user refinements.

---

## 📈 Production Readiness

Designed with real-world deployment considerations:

- Stateless containerized services  
- Kubernetes orchestration for scalability  
- Centralized logging using ELK stack  
- Clear separation of application and infrastructure concerns  

---

## 🧠 What I Learned

- Designing **LLM-based AI applications**
- Building **interactive AI tools with Streamlit**
- Deploying AI systems using **Docker & Kubernetes**
- Implementing **centralized logging** with Filebeat & ELK  
- Debugging real-world deployment and runtime issues  
- Understanding production observability for AI systems  

---

## 🔮 Future Improvements

- Add RAG for travel document ingestion  
- Integrate real-time APIs (hotels, flights, weather)  
- Add metrics monitoring (Prometheus / Grafana)  
- Improve UI/UX  
- Deploy on managed Kubernetes (GKE)  

---

## 👤 Author

**Devendra Umesh Chavan**  
**AI Engineer**  
Founder – *Saavo Avinya Pvt Ltd*

---

## ⭐ Why This Project Matters

This project demonstrates:

- LLM-powered application design  
- Cloud-native AI deployment  
- Centralized logging & observability  
- Production-first engineering mindset  
- End-to-end AI system implementation  

> *A practical example of building and deploying AI applications with real-world operational considerations.*
