# 👋 Hi, I'm AmirHossein Shamsi

### AI Engineer · Backend Engineer · Geospatial Systems

I build **AI-powered backend systems and intelligent geospatial applications** with a focus on turning complex real-world problems into reliable, production-oriented software.

My work sits at the intersection of:

**Artificial Intelligence · Backend Engineering · Geospatial Systems · Routing & Optimization**

---

## 🧠 What I Build

I’m particularly interested in systems where software engineering and AI have to work together.

Some of the problems I work on include:

- 🧠 **Machine Learning & NLP** — classification, information extraction, retrieval, and AI-assisted decision systems
- 📍 **Address Understanding & Geocoding** — resolving noisy real-world addresses into reliable geographic coordinates
- 🗺️ **Geospatial Systems** — road networks, map data, spatial analysis, and offline mapping
- 🚚 **Routing & Logistics** — TSP, route optimization, delivery sequencing, and courier-oriented systems
- 🚦 **Traffic Modeling** — time-dependent routing costs and ML-based traffic prediction
- ⚡ **Backend Engineering** — asynchronous APIs, distributed components, real-time communication, and scalable services
- 🤖 **LLM & Agentic Systems** — RAG, LangChain, LangGraph, MCP, and AI-powered workflows

---

# 🚚 Intelligent Courier & Geospatial Platform

One of my main engineering projects is an end-to-end intelligent courier system designed around a real delivery workflow.

The system covers multiple stages of the delivery lifecycle:

```text
Address Understanding
        ↓
Geocoding
        ↓
Branch Assignment
        ↓
Routing
        ↓
Traffic Modeling
        ↓
Delivery Optimization
```

## Address Resolution

One of the core challenges is converting messy, real-world Persian addresses into reliable geographic locations.

The architecture combines:

- Elasticsearch for high-confidence address retrieval
- Persian text normalization and preprocessing
- SymSpell-based typo correction
- Machine Learning for branch classification
- Candidate branch generation
- Geographic validation
- Geo-point based spatial search

Instead of relying on a single model or a single search strategy, the system uses a **hybrid ML + Search architecture** where each component handles the type of problem it is best suited for.

```text
Raw Address
     │
     ▼
Text Normalization
     │
     ▼
Typo / Noise Handling
     │
     ▼
Elasticsearch
     │
     ├── High-confidence match ──► Coordinates
     │
     ▼
Branch Classifier
     │
     ▼
Candidate Branches
     │
     ▼
Targeted Search
     │
     ▼
Coordinates
```

## Machine Learning

I experimented with multiple approaches for branch classification, starting from a lightweight MLP baseline and progressively improving the feature pipeline and model architecture.

The evolution included:

```text
Baseline MLP
    ↓
TF-IDF
    ↓
Character + Word N-grams
    ↓
Feature Engineering
    ↓
MLP / SVM / Logistic Regression
    ↓
Soft Voting & Candidate Generation
    ↓
Bi-GRU / Transformer-based Experiments
```

The dataset was also significantly expanded and cleaned, with additional noisy and typo-like samples introduced to make the models more robust to real-world address input.

The goal is not simply to maximize benchmark accuracy, but to build a model that behaves reliably when the input is incomplete, inconsistent, or noisy.

---

# 🗺️ Routing & Geospatial Infrastructure

For routing, I work with real OpenStreetMap road-network data and self-hosted routing infrastructure.

### Core components

- **OSM / Geofabrik**
- **OSRM**
- **MapLibre**
- **OpenStreetMap**
- **GeoPandas**
- **NetworkX**
- **Spatial / GeoJSON data**

The routing infrastructure is designed to operate without depending on external online map services.

```text
OpenStreetMap Data
        ↓
    OSM / PBF
        ↓
   Routing Engine
        ↓
 Distance / ETA / Geometry
        ↓
 Optimization Layer
        ↓
 Courier Route
```

## Route Optimization

I have implemented **TSP-based delivery sequencing** where the objective is to determine the order in which a courier should visit assigned delivery points.

The routing cost does not have to be simple geographic distance.

It can incorporate:

```text
Distance
+
Travel Time
+
Traffic-dependent Cost
```

This creates a foundation for more advanced optimization modules such as VRP and vehicle-aware delivery optimization.

---

# 🚦 Traffic Modeling

Another part of the system focuses on making routing more realistic by considering traffic conditions.

Instead of treating every road segment as having a fixed cost, the system can model the cost as a function of:

```text
Road Segment × Time
        ↓
Predicted Travel Cost
```

I have also worked with **Graph Neural Network (GNN)** approaches for learning traffic-related weights over road networks.

This allows the routing layer to move from:

> "What is the shortest path?"

toward:

> "What is the most efficient path under current or predicted conditions?"

---

# ⚙️ Backend Engineering

My main backend stack is Python, with a strong focus on **FastAPI** and asynchronous service design.

I work with:

- FastAPI
- Python
- Pydantic
- Elasticsearch
- MongoDB
- Redis
- Docker
- REST APIs
- WebSockets
- AsyncIO

I care about keeping backend services:

**Modular · Observable · Testable · Maintainable · Production-oriented**

---

# 🤖 AI & LLM Systems

Beyond traditional Machine Learning, I also build applications around modern LLM architectures.

Areas I've worked with include:

- Retrieval-Augmented Generation (RAG)
- LangChain
- LangGraph
- MCP
- AI Agents
- Vector Search
- Prompt Engineering
- LLM-powered APIs

I’m particularly interested in moving beyond simple chatbot applications and building **AI systems that can interact with real services, tools, data, and workflows.**

---

# 🔬 Selected Projects

### 🚚 Real-Time Geo-Tracking Application

**FastAPI · MongoDB · Redis · WebSockets · OSRM · Folium**

A real-time delivery tracking prototype combining live location updates, route management, and interactive geospatial visualization.

[View Project →](https://github.com/Amir-Hossein-shamsi/Real-Time-Geo-Tracking-Application)

---

### 🗺️ TehranNavigator

**OSMnx · NetworkX · GeoPandas · ipyleaflet**

An experimental geospatial routing project built around Tehran's real road network.

It explores:

- Geocoding
- Road-network modeling
- Shortest-path algorithms
- Interactive route visualization

[View Project →](https://github.com/Amir-Hossein-shamsi/TehranNavigator)

---

### 🥑 VitaGuide

**RAG · GPT · Pinecone · Streamlit**

An AI-powered nutrition assistant built around retrieval-augmented generation and a collection of scientific nutrition resources.

[View Project →](https://github.com/Amir-Hossein-shamsi/vitaguide)

---

### ❄️ Icebreaker AI

**LangChain · LLMs · Agents**

An experimental AI system for collecting profile information and generating structured professional summaries.

[View Project →](https://github.com/Amir-Hossein-shamsi/icebreaker)

---

### 🎨 Art Gallery API

**FastAPI · GraphQL · MongoDB · Pydantic · Docker**

A backend project exploring GraphQL API design, data modeling, and containerized deployment.

[View Project →](https://github.com/Amir-Hossein-shamsi/Art-gallery-api)

---

# 🛠️ Technology Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=csharp&logoColor=white)

### Backend

![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?logo=socketdotio&logoColor=white)

### AI / Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)

### Data & Infrastructure

![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

### Geospatial

![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?logo=openstreetmap&logoColor=white)
![OSRM](https://img.shields.io/badge/OSRM-000000?logo=openstreetmap&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?logo=geopandas&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-333333?logo=python&logoColor=white)

---

# 🧩 Engineering Philosophy

I enjoy working on problems where there isn't a single library or algorithm that solves everything.

The interesting part is usually the **system around the model**:

```text
Real-World Problem
        ↓
Problem Decomposition
        ↓
Data & Domain Understanding
        ↓
Architecture
        ↓
ML / Algorithms
        ↓
Backend Integration
        ↓
Infrastructure
        ↓
Production System
```

I believe good engineering is not about using the most technologies.

It's about choosing the right technologies to solve the right problem.

---

## 📚 Currently Exploring

I'm continuously expanding my work toward:

- Advanced Geospatial Systems
- Intelligent Routing & Optimization
- Graph Neural Networks
- LLM Agents
- LangGraph
- MCP
- Distributed Backend Systems
- .NET / Enterprise Backend Engineering
- Kubernetes & Cloud-Native Architecture

---

## 📫 Let's Connect

I'm interested in **AI Engineering, Backend Engineering, Geospatial Systems, Intelligent Logistics, and applied Machine Learning**.

If you're working on a challenging engineering problem, feel free to reach out.

📧 **shamsiamirhossein1@gmail.com**

---

> **Build systems that solve real problems.**
>
> **Use AI where it creates value.**
>
> **And make the engineering underneath it reliable.**
