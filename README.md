
# 🤖 Agentic AI Assistant App

This project is a Streamlit-based Agentic AI application that includes multiple tools powered by LangGraph. It provides a clean, interactive interface for natural language conversation, real-time web search integration, and AI-generated news summaries.

## ✨ Features

* 🔎 Basic Chatbot — A simple intelligent assistant for everyday queries.
* 🔰 Chatbot + Travily Web Search Tool — Enhanced AI chatbot with live web search capabilities.
* 📰 AI News Generator — Generates and displays daily, weekly, or yearly news summaries. News can also be saved for later use.

## 📅 Built With

* Streamlit
* LangGraph
* LangChain
* uv (Optional but recommended for managing dependencies)

## 📁 Project Structure

```
.
├── app.py                         # Streamlit application
├── requirements.txt              # All required Python packages
├── .env                          # Store environment variables
├── src
│   └── graphs
│       └── graph_builder.py      # Customize which graph to load in LangGraph Studio
└── assets
    ├── basic_chatbot_graph.png
    ├── travily_tool_graph.png
    └── ai_news_graph.png
```

## 🚀 Getting Started

### ✅ Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/agentic-ai-streamlit.git
cd agentic-ai-streamlit
```

### 🔧 Step 2: Install Dependencies

If you're using uv:

```bash
uv pip install -r requirements.txt
```
Or use regular pip:
```bash
pip install -r requirements.txt
```

### 🔐 Step 3: Set Up Environment Variables

Create a .env file and include your API keys:

```bash
LANGCHAIN_API_KEY=your_langchain_api_key
TRAVILY_API_KEY=your_travily_key  # Only if using Travily search tool
```

### 🎓 LangGraph Studio (Optional)

To open and visualize the agent graphs in LangGraph Studio, run:

```bash
langgraph dev
```

You can modify the file ./src/graphs/graph_builder.py to select which graph to explore.

## 🌟 Run the App

After setting up the environment, launch the app using:

python app.py

## 📈 Graph Visuals

Basic Chatbot Graph



Chatbot with Travily Tool Graph



AI News Generator Graph



## ✊ Contribute

We welcome contributions! Feel free to fork the repo, make changes, and submit a pull request.

## ⚠️ License

This project is licensed under the MIT License.

## 👤 Author

Created by Nivakaran S. — exploring multi-agent AI with real-world applications.
