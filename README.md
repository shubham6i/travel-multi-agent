# ✈️ Multi-Agent Travel Planner

A multi-agent AI travel planning application built using **Python, LangGraph, LangChain, Groq, Tavily, PostgreSQL, and Streamlit**.

## 🚀 Features

* ✈️ Flight search
* 🏨 Hotel search
* 🗺️ Travel itinerary generation
* 🤖 AI agents using LangGraph and Groq
* 🔎 Web search using Tavily
* 💾 PostgreSQL memory
* 🖥️ Streamlit interface

## 🏗️ Project Structure

```text
multi-agent/
│
├── main.py
├── frontend.py
├── requirements.txt
├── .gitignore
├── .env
│
└── tools/
    ├── __init__.py
    ├── flight_tool.py
    ├── hotel_tool.py
    └── ...
```

## 🔐 Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key
AVIATIONSTACK_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key
DATABASE_URL=your_database_url
```

**Do not upload `.env` to GitHub.**

## 🌐 Live Demo

[View Project](https://multiagenttraveltrip.streamlit.app/)
