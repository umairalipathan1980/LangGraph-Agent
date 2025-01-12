# LangGraph Smart Question Answering Agent with Intelligent Internet Search

This is a simple LangGraph agent application that answers user's queries by deciding whether the answer should be given by a large langugae model or by real-time internet serach.  

The application creates an AI agent using Groq’s free API and LangGraph, demonstrating how AI agents can combine decision-making workflows and real-time internet searches to enhance functionality.  

This application is based on my article [How to Develop a Free AI Agent with Automatic Internet Search](https://ai.gopubby.com/how-to-develop-a-free-ai-agent-with-automatic-internet-search-5ea24928d26b)

# How to use
Clone the repository:  
```
git clone https://github.com/umairalipathan1980/LangGraph-Smart-AI-Agent.git
```
Navigate to the repository folder:
```
cd LangGraph-Smart-AI-Agent
```
Install the required libraries:
```
pip install -r requirements.txt
```
Create a folder ".streamlit" in the root directory and create a "secrets.toml" file in it. Set your API keys there as follows:
   ```
   GROQ_API_KEY = "your_GROQ_api_key"
   TAVILY_API_KEY = "your_Tavily_api_key"
   ```
**Run the Streamlit app:**
   ```
   python -m streamlit run .\app.py  
   ```
