# MCP Playground: Your Sandbox for Claude & Gemini with Model Context Protocol 🚀

**Unlock the full potential of Anthropic's Claude models and Google's Gemini models by seamlessly integrating them with external tools and data sources via the Model Context Protocol (MCP). MCP Playground provides an intuitive, web-based interface to experiment, debug, and innovate with dual AI provider support, advanced tool management, and comprehensive customization options.**

[![Try MCP Playground](https://img.shields.io/badge/Try%20Online-mcpsplayground.com-brightgreen?style=for-the-badge&logo=icloud)](https://mcpsplayground.com)

---

<p align="center">
  <em>The ultimate playground where you can instantly connect Claude or Gemini to any MCP-compliant server, customize their behavior with system prompts, selectively control tool access, and watch AI agents work with real-world capabilities in real-time.</em>
</p>

---

## 🔥 Key Features

MCP Playground is the most comprehensive platform for developers working with LLMs and MCP:

### 🤖 **Advanced AI Chat with Dual Provider Support**
*   **Claude Integration:** Full support for Anthropic's Claude models (claude-3-5-sonnet-20241022)
*   **Gemini Integration:** Complete support for Google's Gemini models (gemini-2.0-flash, gemini-1.5-pro, gemini-1.5-flash, etc.)
*   **Flexible API Configuration:** Securely manage your Anthropic and/or Gemini API keys independently
*   **Dynamic Model Selection:** Switch between different models from both providers instantly
*   **🆕 Custom System Prompts:** Define unique personalities and behaviors for both Claude and Gemini
    

### 🔌 **Professional MCP Server Integration**
*   **Universal Server Support:** Connect to any **SSE-based** MCP server with enterprise-grade reliability
*   **Quick Start Options:** Pre-configured examples (Cloudflare Docs, DeepWiki, GitHub) for instant testing
*   **Custom Server Integration:** Connect to your private or specialized MCP servers
*   **🆕 Production-Ready Authentication:**
    *   **Open Servers:** Public, no-authentication endpoints
    *   **Bearer Token Auth:** Secure API key/bearer token authentication
    *   **OAuth 2.0 Flow:** Full OAuth support for enterprise MCP servers (now officially supported)
*   **Capability Discovery:** Instant visibility into Tools, Prompts, and Resources per server

### 🛠️ **Intelligent Tool Management & Control**
*   **🆕 Advanced Tool Restriction:** Granular control over which tools AI can access
    *   **All Tools Mode:** AI can use any available tool
    *   **Selected Tools Mode:** Restrict AI to specific tools only
    *   **No Tools Mode:** Pure text-based AI responses
    *   **Real-time Tool Selection:** Dynamic tool restriction during conversations
*   **Cross-Provider Compatibility:** Same tools work seamlessly with both Claude and Gemini
*   **Dynamic Tool Discovery:** Automatically discover and categorize all available tools
*   **Detailed Tool Inspection:** View complete schemas, parameters, and descriptions
*   **Manual Tool Testing:** Execute any tool directly with custom parameters for debugging
*   **Rich Result Display:** Complete, untruncated JSON and text outputs with syntax highlighting

### ✨ **Developer Experience Excellence**
*   **Intuitive Multi-Panel Interface:** Organized workspace with chat, server management, tools, and configuration
*   **Provider Switching:** Seamless switching between Claude and Gemini mid-conversation
*   **Real-Time Notifications:** Toast notifications for all operations (connections, errors, successes)
*   **Responsive Design:** Works perfectly on desktop, tablet, and mobile devices

### 🔐 **Enterprise-Grade Security**
*   **Local Key Storage:** API keys stored securely in browser localStorage
*   **Direct API Communication:** Keys sent only to official provider APIs
*   **Independent Key Management:** Separate configuration for Claude and Gemini
*   **Secure Server Connections:** TLS/SSL enforcement for all MCP communications

---

## 🤔 Why Choose MCP Playground?

*   **🚀 Rapid AI Development:** Test Claude and Gemini tool interactions without writing any code
*   **🔄 Cross-Provider Comparison:** Compare how different AI models handle identical tasks and tools
*   **🐛 Advanced Debugging:** Isolate MCP server issues with direct tool testing and comprehensive logging
*   **📖 Learn by Doing:** Hands-on experience with Model Context Protocol across multiple AI providers
*   **🎯 Precision Control:** Fine-tune AI behavior with system prompts and selective tool access
*   **🎨 Showcase Capabilities:** Demonstrate your MCP-enabled services with professional-grade tooling
*   **⚡ Instant Experimentation:** Test server configurations, tool combinations, and AI providers in real-time

---

## 🚀 Get Started in Minutes!

### 1. **Access the Playground**
Visit [**mcpsplayground.com**](https://mcpsplayground.com/chat) - no login required!

### 2. **Configure Your AI Provider**
Navigate to the **"AI Model"** tab:
*   **For Claude:** 
    *   Enter your Anthropic API Key (get from [console.anthropic.com](https://console.anthropic.com))
    *   Select your preferred Claude model
    *   Optionally set a custom system prompt for Claude's personality
*   **For Gemini:** 
    *   Enter your Google AI Studio API Key (get from [aistudio.google.com](https://aistudio.google.com))
    *   Choose from available Gemini models
    *   Customize Gemini's behavior with system prompts

### 3. **Connect MCP Servers**
Go to the **"MCP Servers"** tab:
*   **Quick Add:** Use pre-configured examples (Cloudflare Docs, DeepWiki, etc.)
*   **Manual Add:** Connect your custom servers with SSE URLs and authentication
*   **OAuth Setup:** Complete OAuth flows for enterprise servers with guided setup

### 4. **Control Tool Access** ⭐ *New Feature*
In the **"Available Tools"** panel:
*   View all discovered tools from connected servers
*   **Restrict Tools:** Choose exactly which tools your AI can access
*   **Test Tools:** Execute tools manually with custom parameters
*   **Monitor Usage:** See which tools AI uses during conversations

### 5. **Start Advanced AI Conversations**
*   Chat with Claude or Gemini using connected MCP tools
*   Switch providers mid-conversation to compare responses
*   Watch as AI intelligently selects and uses only the tools you've authorized

---

## 🤖 Supported AI Providers

### 🔷 **Anthropic Claude**
*   **Models:** claude-3-5-sonnet-20241022 (flagship model)
*   **API Key:** Anthropic Console ([console.anthropic.com](https://console.anthropic.com))
*   **Strengths:** Advanced reasoning, thoughtful analysis, precise tool selection
*   **System Prompt Support:** ✅ Full customization available

### 🔶 **Google Gemini**  
*   **Models:** 
    *   `gemini-2.0-flash-001` (latest, fastest)
    *   `gemini-2.0-flash`
    *   `gemini-1.5-flash-001`
    *   `gemini-1.5-flash`
    *   `gemini-1.5-pro-001`
    *   `gemini-1.5-pro` (most capable)
*   **API Key:** Google AI Studio ([aistudio.google.com](https://aistudio.google.com))
*   **Strengths:** Fast inference, multimodal capabilities, efficient tool calling
*   **System Prompt Support:** ✅ Full customization available

---

## 💡 What is MCP?

The **Model Context Protocol (MCP)** is a standardized specification that enables Language Models like Claude and Gemini to securely interact with external tools, services, and data sources. MCP defines how AI agents:

*   🔍 **Discover capabilities** from connected servers
*   🛠️ **Execute tools** with proper parameter validation  
*   📦 **Receive structured results** for further processing
*   🔐 **Maintain security** through controlled access patterns

MCP Playground demonstrates these interactions using **Server-Sent Events (SSE)** transport for real-time communication, supporting both Anthropic's Claude and Google's Gemini with advanced tool management features.

---

## ✨ Experience the Future of AI Tool Integration

Ready to supercharge your AI development workflow with the most advanced MCP testing platform?

➡️ [**Launch MCP Playground**](https://mcpsplayground.com/chat)

Discover what's possible when you give Claude and Gemini access to real-world tools with precision control!

---

## 🏗️ Perfect For

*   **AI Developers** building LLM applications with external capabilities
*   **MCP Server Authors** testing and debugging their tool implementations  
*   **Enterprise Teams** evaluating AI providers for tool-based workflows
*   **Researchers** comparing Claude vs Gemini tool-using performance
*   **Product Managers** demonstrating AI capabilities to stakeholders
*   **Students & Educators** learning about AI agent architectures

---

*Built by developers who believe AI should be more capable, controllable, and accessible across all major providers.*
