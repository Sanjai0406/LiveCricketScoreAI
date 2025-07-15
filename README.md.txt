# Live Cricket Score AI Assistant

## About
This project fetches live cricket scores from an API, saves the results, and uses LangChain RAG with OpenAI LLM to answer user queries on the latest matches.

## Tech Stack
- Python
- LangChain
- OpenAI API
- FAISS Vector Database
- Public Cricket API

## How to Run
1. Install dependencies:

pip install requests langchain openai faiss-cpu 

2. Get your free API key from any cricket API provider (like cricapi.com)
3. Replace `your_api_key_here` with your key.
4. Run:

python cricket_score_ai.py

5. Ask your questions like:
- "What is the status of India match?"
- "Who is winning the match?"

## Author
Your Name
