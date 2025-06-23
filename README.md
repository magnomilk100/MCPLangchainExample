# MCPLangchainExample 🚀

Example implementation showcasing **LangChain** integration with **Model Context Protocol (MCP)** servers via Python.

Built to demonstrate how to start MCP servers and connect them to LangChain clients for multi-agent workflows.

---

## 📁 Project

**Structure**

```bash
MCPLangchainExample/
├── math_server.py # Example MCP server (stdio)
├── weather_server.py # Example MCP server (streamable-http)
├── client.py # LangChain client integrating both servers
├── requirements.txt # Python dependencies
└── README.md # This file
```

---

## ⚙️ Setup & Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/magnomilk100/MCPLangchainExample.git
   cd MCPLangchainExample
   ```

2. **Install Dependencies**

   ```bash
   python3 -m venv venv && source venv/bin/activate
   source venv/bin/activate # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Set environment variables**
   ```bash
   Create an .env file in the root of the project
   Add to it
       GROQ_API_KEY="<<Here the Groq api key, refer to groq api web site to get it>>"
   ```

## ✅ Start Server and Client

```bash
     python math_server.py & python weather_server.py &
     python client.py
```
