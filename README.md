# ✈️ Multi-Agent Travel Planner

A multi-agent travel planning application built using **LangGraph, LangChain, Groq, Tavily, PostgreSQL, and Streamlit**.

The application uses multiple AI agents to help users plan their trips by finding flight information, hotel information, and generating a travel itinerary.

## 🚀 Features

- 🤖 Multi-agent architecture using LangGraph
- ✈️ Flight search and recommendations
- 🏨 Hotel search and recommendations
- 🗺️ AI-generated travel itinerary
- 🔎 Web search using Tavily
- 🧠 LLM-powered agents using Groq
- 💾 PostgreSQL-based LangGraph memory/checkpointing
- 🖥️ Streamlit frontend
- 🔐 Environment variables for API keys and database credentials

## 🏗️ Project Structure

```text
multi-agent/
│
├── main.py
├── frontend.py
├── requirements.txt
├── .gitignore
├── tools/
│   ├── __init__.py
│   ├── flight_tool.py
│   ├── hotel_tool.py
│   └── ...
│
└── .env
