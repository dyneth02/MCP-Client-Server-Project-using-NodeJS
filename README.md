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


