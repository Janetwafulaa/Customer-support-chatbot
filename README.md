# Customer Support Chatbot (LangGraph + Groq)

This project is a **customer support chatbot** built with [LangGraph](https://python.langchain.com/docs/langgraph), [LangChain](https://www.langchain.com/), and [Groq](https://groq.com/) LLMs.  

The chatbot classifies incoming queries into **categories** (Technical, Billing, General), performs **sentiment analysis** (Positive, Neutral, Negative), and either provides an automated response or **escalates to a human agent** if the sentiment is negative.  

---

## Features
- Categorizes user queries into **Technical**, **Billing**, or **General**.  
- Detects query **sentiment** (Positive / Neutral / Negative).  
- Routes queries to the right support flow.  
- Escalates **negative sentiment** queries to a human agent.  

---

## Tech Stack
- **LangGraph** – workflow orchestration  
- **LangChain** – prompt templates & chains  
- **Groq LLM** – powered by `llama-3.3-70b-versatile`  
- **Python 3.9+**  
