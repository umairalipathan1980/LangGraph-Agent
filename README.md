# LangGraph-Agent
Developing a simple LangGraph agent to route user's queries to an LLM or to web search.  
# How to use
Create a folder ".streamlit" in the root directory and create a "secrets.toml" file in it. Set your API keys there as follows:
   ```
   GROQ_API_KEY = "your_GROQ_api_key"
   TAVILY_API_KEY = "your_Tavily_api_key"
   ```

**Run the Streamlit app:**
   ```
   python -m streamlit run .\app.py  
   ```
