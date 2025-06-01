# MCP Playground: Your Sandbox for Claude & Model Context Protocol 🚀

**Unlock the full potential of Anthropic's Claude models by seamlessly integrating them with external tools and data sources via the Model Context Protocol (MCP). MCP Playground provides an intuitive, web-based interface to experiment, debug, and innovate, primarily with SSE-based MCP servers.**

[![Try MCP Playground](https://img.shields.io/badge/Try%20Online-mcpsplayground.com-brightgreen?style=for-the-badge&logo=icloud)](https://mcpsplayground.com)

---

<!-- Optional: Add a GIF or screenshot here -->
<!-- ![MCP Playground Demo](link_to_your_gif_or_screenshot.gif) -->
<p align="center">
  <em>Imagine a place where you can instantly connect Claude to any MCP-compliant server, test its tool-using capabilities, and see the magic unfold in real-time. That's MCP Playground.</em>
</p>

---

## 🔥 Key Features

MCP Playground is packed with features designed for developers working with LLMs and MCP:

*   **🤖 Interactive Claude Chat:**
    *   Directly chat with Anthropic's Claude models.
    *   Securely configure your Anthropic API key.
    *   Customize system prompts to guide Claude's behavior.
*   **🔌 Seamless MCP Server Integration (SSE Focus):**
    *   **Add & Manage Servers:** Easily connect to any **SSE-based** MCP server.
        *   **Quick Add:** Pre-configured examples (like Cloudflare Docs, DeepWiki) to get started instantly.
        *   **Manual Add:** Connect to your custom or private MCP servers.
    *   **Authentication Support:**
        *   **Open Servers:** Connect to public, no-auth MCP endpoints.
        *   **Bearer Token Auth:** Securely connect to servers requiring API key/bearer token authentication.
        *   **OAuth 2.0 Flow (Experimental):** Basic support for MCP servers requiring OAuth is in progress. Functionality may vary.
    *   **Live Server Status:** Real-time feedback on connection state (connecting, ready, authenticating, error).
    *   **View Server Capabilities:** Instantly see if a server provides Tools, Prompts, or Resources.
*   **🛠️ Dynamic Tool Discovery & Execution:**
    *   **Browse Available Tools:** Automatically discover and list all tools exposed by your connected MCP servers.
    *   **Inspect Tool Schemas:** View detailed information for each tool, including its name, description, and input parameters (schema).
    *   **Manual Tool Execution:** Directly trigger any tool with custom arguments from the UI – perfect for testing and debugging.
    *   **View Rich Tool Results:** See the complete, un-truncated JSON or text output from tool calls.
*   **📚 Resource Exploration:**
    *   Discover and list resources (e.g., files, documents) made available by connected MCP servers.
    *   View resource metadata including URI and MIME type.
*   **✨ Developer-Friendly Interface:**
    *   **Intuitive Layout:** Separate panels for chat, server management, tools, and model configuration.
    *   **Real-time Feedback:** Toast notifications for connections, errors, and successful operations.
    *   **Loading & Empty States:** Clear visual cues for asynchronous operations and when no data is available.
    *   **Responsive Design:** Use it on your desktop for focused development.
*   **🔐 Secure API Key Management:**
    *   Your Anthropic API key is stored locally in your browser and only sent directly to the agent backend when needed.
    *   Easy to update or clear your API key.

---

## 🤔 Why Use MCP Playground?

*   **Rapid Prototyping:** Quickly test how Claude interacts with new or existing MCP tools without writing extensive boilerplate code.
*   **Debug MCP Servers:** Isolate issues by directly calling tools on your MCP server and inspecting the raw responses.
*   **Learn MCP:** A hands-on way to understand the Model Context Protocol and how LLMs can leverage external capabilities.
*   **Showcase Tool Capabilities:** Demonstrate the power of your MCP-enabled services to your team or clients.
*   **Experiment Freely:** A dedicated environment to explore different system prompts, server configurations, and tool combinations.

---

## 🚀 Get Started in Minutes!

1.  **Visit the Playground:** Go to [**mcpsplayground.com**](https://mcpsplayground.com).
2.  **Configure Claude:**
    *   Navigate to the "AI Model" (or "API") tab.
    *   Enter your Anthropic API Key (starts with `sk-ant-...`).
    *   Optionally, set a custom system prompt.
3.  **Add MCP Servers:**
    *   Go to the "MCP Servers" tab.
    *   Use "Quick Add" for example servers or "Add MCP Server Manually" for your own.
    *   Provide a name, the server's **SSE URL**, and a bearer token if required.
4.  **Chat & Use Tools:**
    *   Head back to the "Chat" panel. Claude can now use tools from your connected servers!
    *   Explore the "Available Tools" panel to see what's discovered and even execute them manually.

---

## 💡 What is MCP?

The Model Context Protocol (MCP) is a specification that allows Language Models (like Claude) to securely and reliably interact with external tools, services, and data sources. It standardizes how an LLM agent discovers capabilities, calls tools, and receives results. MCP Playground primarily focuses on demonstrating these interactions with servers using the **Server-Sent Events (SSE)** transport for real-time updates.

---

## ✨ Try MCP Playground Now!

Ready to supercharge your Claude development workflow?

➡️ [**Launch MCP Playground**](https://mcpsplayground.com)


---

*Built for developers, by developers who love making AI more capable.*
