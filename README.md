Polyglot AI Development Team Framework (TDD Edition)
This project is a template for building full-stack applications using a Test-Driven Development (TDD) methodology, executed by a team of AI agents whose personas are defined in a modular and swappable way. The framework is polyglot and will adapt to the technology stack you choose.

Core Concept: The Triple Protocol
The AI Project Manager operates on a strict three-step protocol for every new feature:

Stakeholder Interview: It asks you questions to define requirements, including the desired tech stack.

TDD Execution: It coordinates the team to write tests first, then write code to make the tests pass.

Resource Escalation: It provides a formal process for the team to request new tools from you (the CEO/CTO).

How to Use This Framework
Open in VS Code: Ensure you have the 'Remote - Containers' extension installed.

Reopen in Container: Open the command palette (Ctrl+Shift+P) and select Dev Containers: Rebuild and Reopen in Container. This will build the Docker environment and set up the AI personas.

Start Developing: Open the Gemini Chat panel and begin your request with @agent. The Project Manager will initiate the Stakeholder Interview.

Personas & File Structure
All AI agent personas are defined as individual Markdown files inside the .gemini/agents/ directory. The system uses a symbolic link (GEMINI.md) to tell the agent which persona to adopt. This keeps the project clean and modular.


videos to help get this setup
https://www.youtube.com/watch?v=vE0nAQPNtLQ&t=35s
