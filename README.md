multi-agent ai-agents agentic-ai langchain llm tool-calling research-assistant web-scraping streamlit python

# Multi-Agent Research System

A multi-agent AI pipeline that researches a topic end to end. Give it a question and
it finds sources on the web, reads one in depth, writes a structured report, and then
has a critic review and score that report.

Search Agent → Reader Agent → Writer Chain → Critic Chain

- **Search Agent:** uses a web-search tool to find relevant sources
- **Reader Agent:** uses a scraping tool to read a page in full
- **Writer Chain:** turns the findings into a report
- **Critic Chain:** reviews the report and gives feedback and a score
- **Streamlit UI:** run it and watch each stage in the browser

Built with Python, LangChain and Streamlit.
