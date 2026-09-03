Developed an AI Infrastructure Operations Platform using n8n, AI Agents, MCP, and gateway-based architecture.

The goal is to allow a user to give a request in natural language, such as:

“Investigate the failed deployment and create a GitHub issue with the findings.”

Instead of the user manually deciding which service or tool to use, the system interprets the request, routes it to the appropriate specialized agent, and executes the required operation through MCP.

The current implementation focuses mainly on Jira and GitHub operations.
