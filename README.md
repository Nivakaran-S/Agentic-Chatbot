# 🤖 Agentic AI Assistant App

**Agentic AI Assistant** is a **Streamlit-based, multi-functional AI application** powered by **LangGraph and LangChain**. It offers an interactive, user-friendly interface for natural language conversation, real-time web search, and AI-generated news summaries. This project demonstrates **full-stack AI deployment skills**, integrating **state-of-the-art NLP tools** with a clean front-end for real-world usage.

---

## ✨ Key Features

* **🔎 Basic Chatbot** – A robust AI assistant capable of handling everyday queries intelligently and contextually.  
* **🔰 Chatbot + Travily Web Search Tool** – Extends the chatbot with live web search functionality to fetch up-to-date information from the internet.  
* **📰 AI News Generator** – Produces summarized news content daily, weekly, or yearly. Users can also **save and download summaries** for reference.  
* **💡 Customizable Agent Graphs** – Visualize and configure AI decision-making graphs using **LangGraph Studio** for better understanding and experimentation.  

---

## 🚀 Tech Stack

* **Frontend:** Streamlit – Interactive web interface for AI interaction.  
* **Backend & AI Orchestration:** LangGraph + LangChain – Powerful NLP pipelines and agent orchestration.  
* **Utilities & Data:** Python (for API integration, data handling, and AI processing).  

This stack demonstrates expertise in building **interactive AI applications** with **real-time inference** and **multi-agent orchestration**.

---

## 📁 Project Structure

```text
.
├── app.py                         # Main Streamlit application script
├── requirements.txt               # Python dependencies
├── .env                           # Environment variables (API keys)
├── src
│   └── graphs
│       └── graph_builder.py       # Configure and load custom agent graphs in LangGraph Studio
└── assets
    ├── basic_chatbot_graph.png    # Visualization of the Basic Chatbot graph
    ├── travily_tool_graph.png     # Visualization of Chatbot + Travily Web Search graph
    └── ai_news_graph.png          # Visualization of AI News Generator graph
```

---

## 🏗️ Installation & Setup
### 1️⃣ Clone the Repository

```bash

git clone https://github.com/yourusername/agentic-ai-streamlit.git
cd agentic-ai-streamlit

```

### 2️⃣ Install Dependencies

```bash

pip install -r requirements.txt

```

### 3️⃣ Configure Environment Variables

Create a .env file in the project root:
```bash

LANGCHAIN_API_KEY=your_langchain_api_key
TRAVILY_API_KEY=your_travily_key   # Required only if using Travily search tool

```

These keys allow the AI assistant to fetch real-time data and interact with external APIs securely.

### 4️⃣ Optional: Visualize Agent Graphs
LangGraph Studio allows visualizing AI decision-making graphs:

```bash

langgraph dev

```

Modify ./src/graphs/graph_builder.py to select and customize which agent graphs to explore. This demonstrates your ability to build and manage complex multi-agent AI workflows.

### 5️⃣ Run the App

Launch the Streamlit app:

```bash

python app.py

```

Open http://localhost:8501 in your browser to interact with the AI assistant. The app provides:

- Real-time conversational AI responses
- On-demand web search results integration
- Dynamic AI-generated news summaries

---

## 🖼️ Graph Visualizations

- Basic Chatbot Graph – Handles general user queries.

- Chatbot with Travily Web Search Graph – Integrates live web search for current information.

- AI News Generator Graph – Produces concise, structured news summaries.

Each graph is designed for modular AI workflows, allowing you to expand functionality by adding new nodes, tools, or agents.

---

## 💡 Why This Project Matters

This project highlights:
1. End-to-End AI App Development – From backend AI logic to interactive front-end.
2. Multi-Agent Orchestration – Using LangGraph and LangChain for complex AI decision-making.
3. Real-Time Data Integration – Fetches live web data for enriched AI responses.
4. Scalable & Modular Design – Graph-based architecture allows easy addition of new tools or agents.
5. User-Focused UX – Streamlit interface ensures a smooth experience for technical and non-technical users alike.
6. 
It demonstrates your ability to bridge advanced AI concepts with practical application deployment, making it a standout portfolio project.

---

## ✊ Contribution
We welcome contributions!
- Fork the repository
- Make changes or add features
- Submit a pull request

