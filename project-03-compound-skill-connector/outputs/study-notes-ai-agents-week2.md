# Study Notes — AI Agents: The Next Frontier

## From Generative AI to Agentic AI
AI Agents mark a shift from Generative AI, which just responds passively, to Agentic AI, which actively pursues goals. An agent is an autonomous entity that perceives its environment through sensors, uses an LLM to process information, and takes actions through tools to reach specific objectives.

**Key terms:** Generative AI, Agentic AI, autonomous entity, perception, objectives

## Core Architecture: The Perceive-Reason-Act Cycle
Most modern agents run on a cognitive loop with three parts:
- **Planning** — breaking a complex task into smaller sub-goals, using techniques like Chain-of-Thought and Tree-of-Thoughts.
- **Memory** — short-term memory held in the context window, and long-term memory stored in vector databases or retrieved via RAG (Retrieval-Augmented Generation), keeping continuity across interactions.
- **Tool Use** — calling external APIs, executing code, or browsing the web to gather real-world data and complete tasks.

**Key terms:** Perceive-Reason-Act, planning, Chain-of-Thought, memory, RAG, tool use

## Multi-Agent Systems (MAS)
Agents become more powerful working in teams, where each agent takes on a specialized role:
- **Orchestrator** — manages the overall workflow and delegates tasks.
- **Worker** — executes specific technical tasks, such as coding or research.
- **Reviewer** — validates outputs and ensures quality control.

**Key terms:** multi-agent system, orchestrator, worker, reviewer, delegation

## Ethical & Safety Guardrails
As agents gain more autonomy, safety becomes critical. Human-in-the-loop (HITL) systems ensure that high-stakes decisions are always checked by a person before being acted on.

**Key terms:** autonomy, safety guardrails, human-in-the-loop, high-stakes decisions

## Review Questions
1. How does the Perceive-Reason-Act cycle let an agent break down and manage a complex task, and which component would fail first if memory were removed?
2. In a Multi-Agent System, why might separating the Orchestrator, Worker, and Reviewer roles produce more reliable outcomes than a single agent doing everything?
3. Why is a human-in-the-loop safeguard especially important for agents (as opposed to standard generative AI), given the shift toward autonomous action?
