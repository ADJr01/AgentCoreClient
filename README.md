# AgentCoreClient
### Ember.js Frontend for the AgentCore Local Multi-Agent System

AgentCoreClient is the official UI layer for **AgentCore**, a fully local multi-model agent orchestration engine powered by Ollama.  
This client provides a clean, developer-friendly interface for interacting with agents, monitoring workflows, browsing project files, and visualizing memory/state.

---

## 🚀 Features

### 🔹 Multi-Agent Workflow Viewer  
View each agent (Leader, Coder, Tester, Critic, Vision) as they execute tasks sequentially.

### 🔹 Project Workspace Explorer  
Live view of the file system controlled by the Manager Agent.

### 🔹 Agent Chat Interface  
Interact directly with the Leader Agent through a conversation UI.

### 🔹 Visual Debugging (Qwen3-VL)  
Upload screenshots, inspect UI issues, and get visual explanations.

### 🔹 Model Controls  
Choose or Configure local models, update settings, and manage AgentCore backend preferences.

---

## 🧠 Architecture Overview

AgentCoreClient communicates with the backend AgentCore service using:

- **REST APIs** (FastAPI)
- **WebSockets** for real-time agent updates
- Fully local execution (no cloud requirements)

**Tech Stack:**
- Ember.js
- TailwindCSS (optional)
- Local Ollama models
- FastAPI backend (AgentCore)

---

## 📦 Getting Started

### Prerequisites
- Node.js 18+
- Ember CLI
- AgentCore backend running locally (default: `http://localhost:8000`)

### Install Dependencies
```bash
npm install
