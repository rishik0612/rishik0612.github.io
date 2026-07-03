---
layout: post
title: "Microsoft Build 2026: Shift from Model to Context"
date: 2026-07-03
categories: AI Microsoft
---

# Microsoft Build 2026: Shift from Model to Context

This post is about the latest advancements in the AI ecosystem, focusing on the new foundations being established by Microsoft Fabric IQ, the emergence of powerful new models, and the shift towards al[...]

## 🚀 The New Semantic Foundation: Fabric IQ & Foundry IQ

The focus is shifting from raw model capability to shared organizational context, unified by a new semantic layer. This unification is being built through several interconnected layers:

### 1. Fabric IQ: Unifying Enterprise Intelligence
Fabric IQ ties together various enterprise knowledge sources into a shared context layer, allowing agents to reason consistently over unified data, semantic models, and operational ontologies.

*   **Core Components:** Work IQ, Fabric IQ, Foundry IQ, and Web IQ all contribute to this unified context.
*   **Key Takeaway:** Agents can now reason reliably over a single multi-source knowledge base combining enterprise signals, structured data, file uploads, and external web context.

### 2. Foundry IQ: Enabling Agent Workloads
Foundry IQ focuses on making agent workloads frictionless through "scale to zero" pricing for context retrieval.

*   **Serverless Context Retrieval:** Enables instant, frictionless access to organizational signals (Work IQ), structured data (Fabric IQ), file uploads, and MCP servers without managing clusters or [...]
*   **Enhanced Retrieval:** Achieves improved retrieval quality (up to 20% benchmark gains, 54% recall gains) and enhanced security features like federated identity credentials.

### 3. Web IQ: Real-World Grounding
Web IQ provides agents with low-latency access to external web data while respecting publisher preferences and compliance policies.

*   **Unified Context Layer:** Integrates seamlessly with Work IQ, Fabric IQ, and Foundry IQ to combine enterprise knowledge with real-world context for more accurate reasoning.
*   **Performance Focus:** Designed for agentic workflows, delivering sub-second retrievals.

## 🧠 The Next Generation of Models: MAI Family

Microsoft AI Superintelligence Team has released a family of new in-house models, designed for efficiency, performance, and specialized capabilities:

| Model Name | Primary Focus | Key Feature | Availability |
| :--- | :--- | :--- | :--- |
| **MAI-Thinking-1** | Reasoning & Code Generation | First reasoning model; excellent for complex multi-step instructions and code generation. | Foundry (Private Preview) |
| **MAI-Image-2.5 / Flash** | Multimodal Creativity | First models to serve both text-to-image and image-to-image workloads. | PowerPoint, OneDrive, Foundry |
| **MAI Transcribe 1.5** | Multilingual Speech | State-of-the-art accuracy across 43 languages with streaming support. | N/A |
| **MAI-Voice-2 / Flash** | Voice Generation | Available in more than 15 additional languages with new voice options. | N/A |
| **MAI-Code-1** | Coding Efficiency | Inference-efficient model specifically tuned for GitHub tasks. | Copilot, VS Code |

*   **Performance Note:** Independent raters prefer **MAI-Thinking-1** over Sonnet 4.6 [1], and it matches Opus 4.6 on coding abilities on SWE Bench Pro [2].

## 🤖 The Agentic Shift: Introducing Microsoft Scout

The focus is moving from model capability to **shared organizational context**. This shift enables the development of always-on autonomous agents.

**Microsoft Scout** is a new personal agent designed for work that embodies this shift:

*   **Core Philosophy:** Built on OpenClaw and WorkIQ, it understands *how you work*.
*   **Proactive Capabilities:** It proactively handles routine tasks like meeting prep, scheduling conflicts, and routine follow-ups **without asking**.
*   **Interaction:** It can operate applications on a Windows Cloud PC by interacting with the user interface through natural mouse and keyboard inputs, mirroring human behavior.

## 🛠️ The Infrastructure Layer: Rayfin SDK & Azure Database Enhancements

To support these agentic systems at scale, foundational infrastructure is being introduced:

*   **Rayfin SDK & CLI:** An open-source toolkit that allows developers to move applications from prompt to production with enterprise-grade backends integrated directly into Microsoft Fabric.
*   **Azure HorizonDB:** A new PostgreSQL-compatible database optimized for AI workloads, featuring massive scalability, vector search, and integrated AI model management.
*   **Cosmos DB Enhancements:** Includes semantic reranking, an agent memory toolkit, and a Linux emulator to simplify building reliable multi-agent applications.

---

### 💡 Summary of Key Shifts

1.  **From Model Focus to Context Focus:** The primary goal is no longer just raw model capability but coordinating agents over shared enterprise knowledge (Fabric IQ).
2.  **Agentic Automation:** Introduction of proactive, always-on agents like Microsoft Scout that handle workflow management autonomously.
3.  **Unified Data & Web Access:** The integration of **Web IQ** ensures agents can ground their decisions in both internal enterprise data and live, reliable web information.
4.  **Efficiency & Quality:** New models (like MAI-Thinking-1) prioritize reasoning efficiency, while infrastructure (Rayfin, HorizonDB) prioritizes scalable, low-latency AI application deployment.

This convergence of semantic foundations, advanced models, and agentic tooling creates a unified platform for building truly autonomous and context-aware AI systems.
