# Simple MCP with Node.js & TypeScript

This project is a minimal, educational implementation of a **Model Context Protocol (MCP)**–style system using **Node.js** and **TypeScript**. It demonstrates how a client and server can communicate over standard input/output (stdio) using structured messages, simulating how modern AI tools interact with external context providers.

The project was built using **VS Code** with **GitHub Copilot**, exploring how AI-assisted development integrates with protocol-based system design.

---

## 🚀 What This Project Demonstrates

- A lightweight MCP-style **client–server architecture**
- Communication over **stdio** instead of HTTP
- Structured request/response handling
- Type-safe development with TypeScript
- Local JSON-based data access
- Practical experimentation with AI tooling workflows

This repository focuses on **clarity over complexity**, making it ideal for learning, experimentation, and extension.

---

## 🧠 Architecture Overview
      Client (client.ts)
      |
      | stdio messages
      v
      Server (server.ts)
      |
      | Reads local data
      v
      users.json
  
- **Client** sends structured requests
- **Server** processes requests and responds via stdio
- **users.json** acts as a mock data source
- **mcp.json** defines how the MCP server is launched and integrated

---

## 📁 Project Structure

      ├── client.ts # MCP client implementation
      ├── server.ts # MCP server implementation
      ├── users.json # Sample data source
      ├── mcp.json # MCP server configuration
      ├── package.json
      ├── package-lock.json
      └── README.md


---

## ⚙️ How It Works

1. The MCP server is launched using Node.js (configured in `mcp.json`)
2. The client communicates with the server via stdio
3. Requests are parsed and handled in a structured manner
4. The server reads from `users.json` and returns results
5. Responses are sent back to the client in a predictable format

This mirrors how AI tools query external systems for context without relying on traditional REST APIs.

---

## ▶️ Running the Project

### Install dependencies
```bash
npm install
npm run build
node build/server.js
(Client execution depends on your MCP setup or test harness.)
```
---

🧪 Why This Matters

Modern AI systems increasingly rely on protocol-driven context sharing rather than monolithic APIs. This project provides a hands-on foundation for understanding:

- AI tool integrations
- Context-aware systems
- Protocol-oriented backend design
- Developer tooling workflows

---

📌 Notes

- This is a learning and exploration project
- Designed to be easily extended (databases, auth, tools, schemas)
- Emphasizes readability and correctness over feature depth

