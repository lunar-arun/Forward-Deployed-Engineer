# Forward Deployed Engineer (FDE) Roadmap

A curated public repository for learning, building, and mastering the skills required to become a **Forward Deployed Engineer (FDE)** at frontier AI companies.

**2026 FDE Roadmap** 

---

# What is a Forward Deployed Engineer?

A **Forward Deployed Engineer (FDE)** is a hybrid role combining:

* Software Engineering
* AI Systems Engineering
* Product Thinking
* Technical Consulting
* Customer Deployment

FDEs work directly with organizations to:

* Understand real business problems
* Design AI-powered solutions
* Deploy systems in production environments
* Build agentic workflows around LLMs
* Ensure observability, safety, and evaluation

This repo documents the complete learning journey toward becoming an industry-ready FDE.

---

# Repository Goals

This repository aims to become:

* A complete FDE learning reference
* A practical implementation hub
* A portfolio-building guide
* A deployment-pattern library
* A collection of production-grade AI engineering examples

---

# Core Learning Pillars

## 1. LLM-Native Foundations

Learn how modern AI systems are engineered around stochastic LLM behavior.

### Topics

* Workflows vs Agents
* Context Engineering
* Structured Outputs
* Tool Use
* Prompt Caching
* Reasoning Models
* Context Windows
* Streaming APIs

### Resources

* Anthropic Engineering Blogs
* OpenAI Agents Guides
* Chip Huyen — AI Engineering
* Simon Willison Blog
* Hamel Husain Articles

---

## 2. Major API Surfaces

Become fluent with frontier AI APIs.

### APIs to Learn

* OpenAI
* Anthropic Claude
* Google Gemini
* Meta Llama
* Open-weight models

### Key Concepts

* Chat/message loops
* Function calling
* Tool usage
* JSON mode
* Batch APIs
* Extended reasoning
* Cost optimization

---

## 3. Prompt & Context Engineering

Master production-grade prompting patterns.

### Topics

* Few-shot prompting
* Chain-of-thought
* ReAct
* Reflexion
* XML tagging
* Self-consistency
* Plan-and-execute
* Structured prompting

---

## 4. Agent Infrastructure & Protocols

The backbone of enterprise AI systems.

### Topics

* MCP (Model Context Protocol)
* Agent Skills
* Multi-agent systems
* Orchestrators
* Sub-agents
* Agent memory
* Tool routing

### Frameworks

* OpenAI Agents SDK
* LangGraph
* CrewAI
* AutoGen
* Mastra

---

## 5. Retrieval & RAG

Understand retrieval systems deeply.

### Topics

* Chunking strategies
* Hybrid search
* Dense retrieval
* BM25
* Reranking
* Recall@K
* MRR
* Graph-based retrieval

### Tools

* Pinecone
* LlamaIndex
* Vector Databases

---

## 6. Evaluation Frameworks

One of the most important production skills.

### Topics

* LLM-as-a-judge
* Golden datasets
* Regression testing
* Pairwise comparison
* Rubric-based grading
* Online evaluation systems

### Tools

* Promptfoo
* Braintrust
* Langfuse
* Inspect AI
* OpenAI Evals

---

## 7. Observability, Security & Safety

Production AI systems require reliability.

### Observability

* Tracing
* Token logging
* Cost monitoring
* Latency tracking
* Prompt tracking

### Security

* Prompt injection prevention
* OWASP LLM Top 10
* AI Risk Management
* Secure deployment patterns

### Tools

* Langfuse
* Helicone
* Arize Phoenix
* Braintrust

---

## 8. Vertical Specialization

Choose one industry and go deep.

### Suggested Verticals

* Finance
* Healthcare
* Legal
* Customer Experience (CX)

### Example Concepts

#### Finance

* KYC/AML
* Trade lifecycle
* SR 11-7

#### Healthcare

* HIPAA
* PHI
* FDA SaMD

#### Legal

* Contract review
* Document retention
* Legal privilege

#### CX

* Ticketing systems
* Agent assist
* Voice AI
* Deflection systems

---

## 9. The Consulting Motion

FDEs are not just engineers.

### Skills

* Discovery calls
* Stakeholder communication
* Executive presentations
* Requirement scoping
* Writing case studies
* Handling ambiguity

### Recommended Reading

* The Mom Test
* SPIN Selling
* The Pyramid Principle
* High Output Management
* An Elegant Puzzle

---

## 10. Evidence Portfolio

Your portfolio matters more than certificates.

### Recommended Projects

* MCP Server
* Agent Skill
* Multi-agent workflow
* Eval harness
* Deployment architecture writeups
* Enterprise AI demos
* AI workflow automation systems

---

# 8-Week FDE Learning Plan

## Week 1 — Rebuild on Frontier APIs

* Build an AI app using OpenAI/Claude/Gemini
* Add tool use
* Add prompt caching
* Implement structured outputs

---

## Week 2 — Ship an MCP Server

* Build an MCP server
* Support stdio + HTTP
* Open-source the project

---

## Week 3 — Agent Skills

* Study reference skills
* Build a custom reusable skill
* Integrate with MCP infrastructure

---

## Week 4 — Eval Harness

* Add evaluation framework
* Create golden datasets
* Measure baseline performance

---

## Week 5 — Multi-Agent Systems

* Create orchestrator agents
* Add sub-agents
* Compare against single-agent systems

---

## Week 6 — Deployment Surfaces

Deploy systems using:

* AWS Bedrock
* Google Vertex AI

Document:

* Security model
* Data flow
* Architecture diagrams

---

## Week 7 — Vertical Depth

Build a domain-specific solution.

Examples:

* AI Legal Assistant
* Healthcare Copilot
* Financial Analyst Agent
* Customer Support Agent

---

## Week 8 — Polish & Case Studies

* Improve documentation
* Record demos
* Write architecture explanations
* Practice project walkthroughs

---

# Suggested Repository Structure

```bash
fde-roadmap/
│
├── README.md
├── resources/
├── notes/
├── projects/
│   ├── mcp-server/
│   ├── agent-skills/
│   ├── eval-harness/
│   ├── multi-agent/
│   └── vertical-demos/
│
├── case-studies/
├── architectures/
├── deployment-patterns/
└── demos/
```

---

# What NOT to Over-Invest In

## Avoid Spending Too Much Time On:

### Building Vector DBs From Scratch

Focus on deploying AI systems effectively.

### Fine-Tuning Everything

Most production systems rely more on prompting and context engineering.

### Heavy Framework Dependency

Understand frameworks, but prioritize direct API understanding.

### Chasing Every New Model

Focus on capability classes instead of hype cycles.

---

# Recommended Learning Resources

## Core Resources

* Anthropic Engineering
* OpenAI Docs
* Gemini API Docs
* Simon Willison Blog
* Hamel Husain
* Eugene Yan
* Pinecone Learning Center
* Inspect AI

---

# Future Plans for This Repository

* [ ] MCP Server Implementations
* [ ] Agent Skill Library
* [ ] RAG Experiments
* [ ] Evaluation Benchmarks
* [ ] Multi-Agent Architectures
* [ ] Production Deployment Examples
* [ ] Security & Safety Guides
* [ ] Case Studies
* [ ] Architecture Diagrams
* [ ] Interview Preparation

---

# Contributing

Contributions, improvements, and discussions are welcome.

If you're also learning AI Engineering, Agent Systems, or the FDE pathway, feel free to contribute.

---

# Disclaimer

This repository is a community-driven educational resource inspired by the public FDE roadmap shared by multiple resources.

All credit for the roadmap concept belongs to its creator.

---

# License

MIT License
