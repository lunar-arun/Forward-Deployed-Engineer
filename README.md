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

| Category                 | Week 1                                                                                                                     | Week 2                                                                     | Week 3                                                                                           | Week 4                                                                                 |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| **Focus Area**           | Rebuild on Frontier APIs                                                                                                   | Ship an MCP Server                                                         | Agent Skills                                                                                     | Eval Harness                                                                           |
| **Tasks / Deliverables** | Build an AI app using OpenAI / Claude / Gemini <br> Add tool use <br> Add prompt caching <br> Implement structured outputs | Build an MCP server <br> Support stdio + HTTP <br> Open-source the project | Study reference skills <br> Build a custom reusable skill <br> Integrate with MCP infrastructure | Add evaluation framework <br> Create golden datasets <br> Measure baseline performance |

---

| Category                 | Week 5                                                                                   | Week 6                                                                                                         | Week 7                                                                 | Week 8                                                                                                  |
| ------------------------ | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Focus Area**           | Multi-Agent Systems                                                                      | Deployment Surfaces                                                                                            | Vertical Depth                                                         | Polish & Case Studies                                                                                   |
| **Tasks / Deliverables** | Create orchestrator agents <br> Add sub-agents <br> Compare against single-agent systems | Deploy using AWS Bedrock & Google Vertex AI <br> Document security model, data flow, and architecture diagrams | Build a domain-specific solution (Legal, Healthcare, Finance, Support) | Improve documentation <br> Record demos <br> Write architecture explanations <br> Practice walkthroughs |

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
