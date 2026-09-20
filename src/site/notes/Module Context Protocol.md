---
{"dg-publish":true,"permalink":"/module-context-protocol/","noteIcon":"","dg-note-properties":{}}
---

[[Agentic AI\|Agentic AI]]
 
**What is MCP?**
MCP (Model Context Protocol) is an open standard that allows AI models to connect with external tools, applications, databases, and data sources in a standardized way.

**How It Works**
Basic Architecture:
- MCP Client (Claude in this case) initiates a connection
- MCP Server (like Gmail, Asana, Canva, Salesforce, etc.) provides the interface to external services
- Secure Communication happens through a standardized protocol.

**The flow looks like this:**

User → Claude → MCP Server → External Service (Gmail, Asana, etc.)
                     ↓
              Returns data/results
                     ↓
            Claude processes & responds

**Key Capabilities**
What MCP enables:
- Read data: Check your emails, calendar events, project tasks, design files
- Write data: Create tasks, send messages, update documents
- Real-time access: Get current information that's beyond Claude's training data
- Automation: Combine multiple actions in one conversation

**Example use cases:**
"Create a task in Asana for reviewing the Q3 report"
"What's on my calendar tomorrow?"
"Search my Gmail for emails about the budget meeting"
"Check this Canva design against our brand kit"