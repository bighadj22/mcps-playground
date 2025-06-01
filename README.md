# MCP Playground: Your Sandbox for Claude & Gemini with Model Context Protocol 🚀

**Unlock the full potential of Anthropic's Claude models and Google's Gemini models by seamlessly integrating them with external tools and data sources via the Model Context Protocol (MCP). MCP Playground provides an intuitive, web-based interface to experiment, debug, and innovate with dual AI provider support, primarily with SSE-based MCP servers.**

[![Try MCP Playground](https://img.shields.io/badge/Try%20Online-mcpsplayground.com-brightgreen?style=for-the-badge&logo=icloud)](https://mcpsplayground.com)

---

<!-- Optional: Add a GIF or screenshot here -->
<!-- ![MCP Playground Demo](link_to_your_gif_or_screenshot.gif) -->
<p align="center">
  <em>Imagine a place where you can instantly connect Claude or Gemini to any MCP-compliant server, test their tool-using capabilities, and see the magic unfold in real-time. That's MCP Playground.</em>
</p>

---

## 🔥 Key Features

MCP Playground is packed with features designed for developers working with LLMs and MCP:

*   **🤖 Interactive AI Chat with Dual Provider Support:**
    *   **Claude Support:** Chat with Anthropic's Claude models (claude-3-5-sonnet).
    *   **Gemini Support:** Chat with Google's Gemini models (gemini-2.0-flash, gemini-1.5-pro, etc.).
    *   **Flexible API Configuration:** Securely configure your Anthropic API key and/or Gemini API key.
    *   **Model Selection:** Choose between different models from both providers.
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
    *   **Cross-Provider Tool Compatibility:** Both Claude and Gemini can access the same MCP tools seamlessly.
    *   **Inspect Tool Schemas:** View detailed information for each tool, including its name, description, and input parameters (schema).
    *   **Manual Tool Execution:** Directly trigger any tool with custom arguments from the UI – perfect for testing and debugging.
    *   **View Rich Tool Results:** See the complete, un-truncated JSON or text output from tool calls.
*   **📚 Resource Exploration:**
    *   Discover and list resources (e.g., files, documents) made available by connected MCP servers.
    *   View resource metadata including URI and MIME type.
*   **✨ Developer-Friendly Interface:**
    *   **Intuitive Layout:** Separate panels for chat, server management, tools, and model configuration.
    *   **AI Provider Selection:** Easy switching between Claude and Gemini providers.
    *   **Real-time Feedback:** Toast notifications for connections, errors, and successful operations.
*   **🔐 Secure API Key Management:**
    *   Your Anthropic and Gemini API keys are stored locally in your browser and only sent directly to the agent backend when needed.
    *   Easy to update or clear your API keys independently.
---

## 🤔 Why Use MCP Playground?

*   **Rapid Prototyping:** Quickly test how Claude or Gemini interact with new or existing MCP tools without writing extensive boilerplate code.
*   **Cross-Provider Testing:** Compare how different AI models (Claude vs Gemini) handle the same tools and tasks.
*   **Debug MCP Servers:** Isolate issues by directly calling tools on your MCP server and inspecting the raw responses.
*   **Learn MCP:** A hands-on way to understand the Model Context Protocol and how different LLMs can leverage external capabilities.
*   **Showcase Tool Capabilities:** Demonstrate the power of your MCP-enabled services to your team or clients across multiple AI providers.
*   **Experiment Freely:** A dedicated environment to explore different, server configurations, tool combinations, and AI providers.

---

## 🚀 Get Started in Minutes!

1.  **Visit the Playground:** Go to [**mcpsplayground.com**](https://mcpsplayground.com).
2.  **Configure Your AI Provider:**
    *   Navigate to the "AI Model" (or "API") tab.
    *   **For Claude:** Enter your Anthropic API Key (starts with `sk-ant-...`).
    *   **For Gemini:** Enter your Google AI Studio API Key (starts with `AIza...`).
    *   **Provider Selection:** Choose your preferred AI provider (Claude or Gemini).
    *   **Model Selection:** Pick from available models (e.g., claude-3-5-sonnet, gemini-2.0-flash).
    *   Optionally, set a custom system prompt.
3.  **Add MCP Servers:**
    *   Go to the "MCP Servers" tab.
    *   Use "Quick Add" for example servers or "Add MCP Server Manually" for your own.
    *   Provide a name, the server's **SSE URL**, and a bearer token if required.
4.  **Chat & Use Tools:**
    *   Head back to the "Chat" panel. Your chosen AI model can now use tools from your connected servers!
    *   Switch between Claude and Gemini to compare their tool-using capabilities.
    *   Explore the "Available Tools" panel to see what's discovered and even execute them manually.

---

## 🤖 Supported AI Providers

### Anthropic Claude
*   **Models:** claude-3-5-sonnet-20241022
*   **API Key:** Anthropic API Key (get from console.anthropic.com)
*   **Features:** Advanced reasoning, tool calling, function execution

### Google Gemini  
*   **Models:** 
    *   gemini-2.0-flash-001 (latest)
    *   gemini-2.0-flash
    *   gemini-1.5-flash-001
    *   gemini-1.5-flash
    *   gemini-1.5-pro-001
    *   gemini-1.5-pro
*   **API Key:** Google AI Studio API Key (get from aistudio.google.com)
*   **Features:** Fast inference, multimodal capabilities, function calling

---

## 💡 What is MCP?

The Model Context Protocol (MCP) is a specification that allows Language Models (like Claude and Gemini) to securely and reliably interact with external tools, services, and data sources. It standardizes how an LLM agent discovers capabilities, calls tools, and receives results. MCP Playground primarily focuses on demonstrating these interactions with servers using the **Server-Sent Events (SSE)** transport for real-time updates, supporting both Anthropic's Claude and Google's Gemini models.

---

## ✨ Try MCP Playground Now!

Ready to supercharge your Claude and Gemini development workflow?

➡️ [**Launch MCP Playground**](https://mcpsplayground.com)

Experience the power of dual AI provider support with seamless MCP integration!

---

*Built for developers, by developers who love making AI more capable across multiple providers.*
