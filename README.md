# MCPLangchainExample 🚀

Example implementation showcasing **LangChain** integration with **Model Context Protocol (MCP)** servers via Python.

Built to demonstrate how to start MCP servers and connect them to LangChain clients for multi-agent workflows.

---

## 📁 Project Structure

MCPLangchainExample/
├── math_server.py # Example MCP server (stdio)
├── weather_server.py # Example MCP server (streamable-http)
├── client.py # LangChain client integrating both servers
├── requirements.txt # Python dependencies
└── README.md # This file

---

## ⚙️ Setup & Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/magnomilk100/MCPLangchainExample.git
   cd MCPLangchainExample
   ```

Install Dependencies
python3 -m venv venv
source venv/bin/activate # Windows: venv\Scripts\activate
pip install -r requirements.txt

Set environment variables
export OPENAI_API_KEY=your_openai_api_key

✅ Quick Start Summary
git clone ... && cd MCPLangchainExample
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
export OPENAI_API_KEY=...
python math_server.py & python weather_server.py &
python client.py
