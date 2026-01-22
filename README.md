🦜 LangChain: Chat with SQL Database

An interactive Streamlit web application that allows users to chat with SQL databases (SQLite or MySQL) using natural language, powered by LangChain agents and Groq LLMs (LLaMA-3).

Users can ask questions like:

“How many students are in each department?”
“Show top 5 students by marks”

…and the AI will automatically generate SQL queries, execute them, and return results in plain English.

🚀 Features

🔍 Natural Language → SQL Queries

🗄️ Supports Multiple Databases

SQLite (student.db)

MySQL (remote/local)

🤖 LLM-powered SQL Agent (LangChain)

⚡ Groq LLaMA-3 (Fast & Free-tier friendly)

💬 Chat-style UI using Streamlit

🔄 Streaming responses

🧠 Session-based chat history

🔐 Secure API key input

🛠️ Tech Stack
 Component	Technology
 Frontend	Streamlit
 LLM	Groq (LLaMA-3-8B-8192)
 Agent	LangChain SQL Agent
 Database	SQLite / MySQL
 ORM	SQLAlchemy



📂 Project Structure
.
├── app.py                 # Main Streamlit application 

├── student.db             # SQLite database (example)

├── requirements.txt       # Python dependencies

└── README.md              # Project documentation
