---
{"dg-publish":true,"permalink":"/agentic-ai/","dg-note-properties":{"permalink":"AI study"}}
---

Parent: [[Artificial Intelligence\|Artificial Intelligence]]

**What is Agentic AI ?**

Agentic AI refers to autonomous artificial intelligence systems capable of proactively planning, executing, and iteratively refining multi-step actions to achieve a specific goal without requiring continuous human oversight. Unlike traditional generative AI, which merely responds to text prompts with text answers, Agentic AI acts as a proactive digital teammate that bridges the gap between text generation and real-world task execution.

**How Agentic AI Works ?**
Agentic AI systems function through a continuous cognitive feedback loop often referred to as the PRAL loop (Perceive, Reason, Act, Learn), powered by an underlying technology stack. 

**1. The Core Operations Loop**
- Perceive: The system gathers data from its environment via APIs, web searches, software databases, or user interactions to understand the context.
- Reason & Plan: An underlying Large Language Model (LLM) acts as the "brain," breaking down the main goal into smaller, logical sub-tasks. 
- Act: The system uses external tools to perform transactions, write data, or execute code instead of just giving instructions.
- Learn & Adapt: The agent evaluates the results of its actions, fixes its own errors (such as debugging broken code), and refines its strategy. 
```unset
       [ PERCEIVE ] ──> Gathers context from APIs & databases
            │
            ▼
       [ REASON ]   ──> Breaks down the goal using an LLM brain
            │
            ▼
        [ ACT ]     ──> Executes software tasks & updates systems
            │
            ▼
       [ LEARN ]    ──> Evaluates feedback & fixes errors automatically
```
 **2. The Four Pillars of an Agentic System**
- Every Agentic AI platform relies on four foundational components to operate:
- The Brain (LLM): Models like GPT-4 or Claude handle advanced reasoning, logic routing, and contextual decision-making.
- Memory Layer: Short-term memory tracks current conversation states, while long-term memory (using vector databases like Pinecone) recalls past outcomes and user preferences.
- Tools & APIs: Connectors that give the AI the hands to interact with the real world, including email clients, CRMs, calculators, and code execution environments.
- Orchestration Framework: Software layers like LangChain, Microsoft AutoGen, or CrewAI that manage the workflow, sequence steps, and coordinate handoffs.
---
**Traditional AI vs Agentic AI**

|Traditional AI|Agentic AI|
|---|---|
|Answers one prompt|Achieves a complete goal|
|Reactive|Proactive|
|Needs constant user instructions|Plans independently|
|Limited reasoning|Multi-step reasoning|
|Rarely uses external tools|Uses tools and APIs|
|Doesn't remember workflow|Tracks progress and adapts|

------
**Summary**
Agentic AI is an AI system that goes beyond answering questions—it acts like an intelligent assistant that can plan, reason, use tools, make decisions, and execute multiple steps to accomplish a goal with minimal human guidance. It is a key technology behind next-generation AI assistants capable of automating complex workflows.