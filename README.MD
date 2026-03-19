# 📘 Software Engineering Design with Agentic AI (New Outline)

## 1. Course Positioning

**Course Type:** Core (Year 2/3)
**Philosophy:**

> Move from *designing software systems* → to *designing human–AI collaborative systems*

---

## 2. Learning Objectives

By the end, students will:

### Classical SE (retain from 50002)

* Apply design patterns, refactoring, and TDD
* Evaluate maintainability, modularity, and cost of change ([帝国学院][1])

### Agentic AI Extensions

* Design **agent-based software architectures**
* Build **multi-step AI workflows with tools & memory**
* Reason about **autonomy, control, and safety**
* Evaluate **AI-driven systems (not just code quality)**
* Engineer **human–AI collaboration loops**

---

## 3. Course Structure (12 Weeks)

---

## 🧩 Part I — Foundations: From Software to Agentic Systems (Weeks 1–3)

### Week 1: Software Design Principles Revisited

* SOLID, modularity, abstraction
* Cost of change in AI-integrated systems
* Limits of traditional architectures

### Week 2: Introduction to Agentic AI

* What is agentic AI vs LLM APIs
* Autonomy spectrum (tool → agent → multi-agent) ([深度学习.ai][2])
* Case studies: AI coding agents, copilots

### Week 3: Agent Architecture Basics

* Core components:

  * Planner
  * Tool use
  * Memory
  * Environment
* Comparison with OOP / microservices

---

## ⚙️ Part II — Design Patterns for Agentic Software (Weeks 4–7)

### Week 4: Prompting as Programming

* Prompt engineering vs API design
* Context design & control flow
* Failure modes

### Week 5: Agent Design Patterns

* Reflection pattern
* ReAct (reason + act)
* Tool-use pattern ([深度学习.ai][2])
* Comparison with classical design patterns

### Week 6: Workflow Orchestration

* Pipelines vs agent workflows
* DAGs vs dynamic planning
* Frameworks (LangChain, etc.) ([Coursera][3])

### Week 7: Memory & State

* Stateless vs stateful agents
* Vector DB / RAG
* Long-term vs short-term memory

---

## 🏗️ Part III — System Design & Integration (Weeks 8–10)

### Week 8: AI-Native System Architecture

* AI-first architecture vs microservices
* Agent orchestration layer
* API/tool ecosystem design

### Week 9: Testing & Debugging Agentic Systems

* Why TDD breaks (non-determinism)
* Evaluation (evals, benchmarks)
* Simulation-based testing

### Week 10: Reliability, Safety & Governance

* Failure modes of autonomous agents
* Guardrails, monitoring
* Risk frameworks for agentic systems
* Human-in-the-loop design

---

## 🚀 Part IV — Advanced Topics & Project (Weeks 11–12)

### Week 11: Multi-Agent Systems

* Coordination & communication
* Task decomposition
* Distributed agents vs distributed systems

### Week 12: Future of Software Engineering

* AI as developer vs collaborator
* “Agentic software ecosystem” vision
* Research frontiers

---

## 4. Labs & Practical Work (Core Strength)

Following Imperial’s **“learning by doing” model** ([帝国学院][1]):

### Weekly Labs

* Refactor legacy code → AI-assisted system
* Build:

  * Tool-using agent
  * RAG system
  * Multi-agent workflow

### Capstone Project (Team-based)

Students design:

> A **production-grade agentic software system**

Examples:

* Autonomous debugging agent
* AI software architect assistant
* Security vulnerability analysis agent (fits your research well)

---

## 5. Assessment Design (Modernized)

| Component            | Weight | Description                                                 |
| -------------------- | ------ | ----------------------------------------------------------- |
| Weekly Labs          | 30%    | Hands-on agent/system building                              |
| Design Reviews       | 20%    | Architecture critique (like code review but for AI systems) |
| Capstone Project     | 30%    | End-to-end agentic system                                   |
| Final Practical Exam | 20%    | Build/debug an agent system                                 |

---

## 6. Key Innovations Over Traditional 50002

### 🔁 From Code-Centric → Workflow-Centric

* Not just classes → **agents + workflows**

### 🧠 From Deterministic → Probabilistic Design

* Testing & correctness redefined

### 🤖 From Developer → Human-AI Team

* Students learn to **orchestrate AI labor**

### 🏗️ From Patterns → Meta-Patterns

* Classical patterns + **agentic patterns**

---

## 7. Suggested Reading

### Core

* Gamma et al. (Design Patterns)
* Freeman & Pryce (TDD)

### New Additions

* Agentic AI design patterns (Andrew Ng course) ([深度学习.ai][2])
* LangChain / agent frameworks ([Coursera][3])
* Recent agentic systems research (architecture + governance)

---

## 8. Optional Differentiation (for Imperial context)

You could explicitly position this as:

> **“50002X: Software Engineering Design in the Age of AI Agents”**

And align with:

* ML course (50013)
* Systems (OS, compilers)
* Your research area: **AI + systems + security**
