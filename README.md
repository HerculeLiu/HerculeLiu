# Hercule Liu

AI Product Manager building local-first Agent products and interaction systems.

I focus on the place where **AI Agent architecture**, **product experience**, and **real workflows** meet: how an agent understands a task, uses tools, asks for permission, preserves context, recovers from interruption, and stays understandable to the user while it works.

## Current Focus

- **Local-first Agent apps**: desktop products where the agent can work with local files, tools, memory, and user-approved actions.
- **Agent interaction design**: Chat Stream, Work Pane, generated UI, permission interrupts, run resume, task timeline, and long-running workflows.
- **Data-driven experience automation**: using agents to connect user behavior data, experience issues, metric interpretation, insight summaries, and optimization suggestions.
- **Multimodal review agents**: using vision-language models and PDF rendering to support packaging compliance review.

## Featured Work

| Project | What it is | Focus |
| --- | --- | --- |
| [Nexus](https://github.com/HerculeLiu/Nexus) | A local-first macOS Agent app with a native desktop surface, local Agent Kernel, tool execution, memory, permission flow, ledger, and recovery. | Agent Kernel, macOS App, Tool Use, Memory, Run Lifecycle |
| [Ariadne](https://github.com/HerculeLiu/Ariadne) | An AI learning assistant for turning documents and web research into structured, interactive learning pages. | RAG, Knowledge Workflows, Interactive Learning |
| [Hippocampus](https://github.com/HerculeLiu/Hippocampus) | A long-term memory and retrieval exploration for agent systems. | Memory, Retrieval, Context |
| [voice-commander](https://github.com/HerculeLiu/voice-commander) | A voice input layer for agent workflows. | ASR, Agent Input, Local Tools |

## Nexus: The Agent App I Am Building

Nexus is my main current project. It explores what a usable personal Agent app should feel like when it can actually work on local tasks, local files, tools, memory, and user-approved actions.

The product is built around two core ideas:

1. **A local Agent Kernel**
   The agent runtime supports model calls, tool execution, context assembly, memory recall, permission governance, run records, recovery, and completion verification.

2. **An Agent-first desktop interaction model**
   The app treats chat as an operating surface, not a static log. Agent work is shown through Chat Stream, Composer, Work Pane, generated UI, permission interrupts, task timeline, artifacts, and recoverable run states.

Some interaction questions Nexus explores:

- How should users approve risky file writes or command execution?
- How can generated UI be safe without executing arbitrary model-generated code?
- How should an interrupted long-running task resume?
- What belongs in the chat stream, and what belongs in a side Work Pane?
- How should an agent expose its tool use, evidence, memory, and final answer without overwhelming the user?

## AI Agent Product Interests

- Agent Kernel and run lifecycle design
- Tool Use / Function Calling / MCP
- Context Engineering and Memory Recall
- Permission and governance UX
- Generated UI and Agent-UI protocols
- Local-first desktop Agent workflows
- Agent evaluation and benchmark design
- Data analysis automation
- User research automation
- UI/UX workflow automation

## Technical Stack

**AI / Agent**

`LLM` · `RAG` · `Tool Use` · `Function Calling` · `MCP` · `Context Engineering` · `Memory` · `Agent Evaluation` · `Vision-Language Models`

**Product / Interaction**

`Agent App UX` · `Generated UI` · `Permission Flow` · `Workflow Automation` · `Data-driven UX` · `Figma` · `PRD` · `User Research`

**Engineering**

`Python` · `SwiftUI` · `SQLite` · `Go` · `JavaScript` · `SQL` · `PyMuPDF` · `Git`

**AI Coding Tools**

`Codex` · `Claude Code` · `Cursor`

## Contact

- GitHub: [@HerculeLiu](https://github.com/HerculeLiu)
- Website: [herculeliu.com](https://herculeliu.com)
- X: [@HerculeLiu](https://x.com/HerculeLiu)

---

Building agents that are useful because they are visible, controllable, and grounded in real work.
