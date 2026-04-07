# AI Agents

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/ResourceChest/ai-agents)](https://github.com/ResourceChest/ai-agents/stargazers)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/ResourceChest/.github/blob/main/CONTRIBUTING.md)
[![Link Check](https://github.com/ResourceChest/ai-agents/actions/workflows/link-check.yml/badge.svg)](https://github.com/ResourceChest/ai-agents/actions/workflows/link-check.yml)

A curated list of practical AI agents, agentic frameworks, and tools for developers and power users. This list focuses on tools you can actually use today to build, automate, and ship — not research papers or vaporware.

## Contents

- [Agent Frameworks](#agent-frameworks)
- [Coding Agents](#coding-agents)
- [General Purpose Agents](#general-purpose-agents)
- [Research & Data Agents](#research--data-agents)
- [Automation & Workflow Agents](#automation--workflow-agents)
- [Open Source & Self-Hosted Agents](#open-source--self-hosted-agents)
- [Guides & Patterns](#guides--patterns)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

## Agent Frameworks

- [**LangChain**](https://github.com/langchain-ai/langchain) — Python and JS framework for building applications powered by LLMs, with composable chains and tool integrations.
- [**LangGraph**](https://github.com/langchain-ai/langgraph) — Stateful agent orchestration framework built on LangChain for building reliable, controllable multi-step agents.
- [**CrewAI**](https://github.com/crewAIInc/crewAI) — Multi-agent orchestration framework that lets you define roles, goals, and backstories for cooperating AI agents.
- [**AutoGen**](https://github.com/microsoft/autogen) — Microsoft's framework for building multi-agent conversational systems with customizable and composable agents.
- [**Semantic Kernel**](https://github.com/microsoft/semantic-kernel) — Microsoft's open-source SDK for integrating LLMs into apps with plugins, planners, and memory across C#, Python, and Java.
- [**Haystack**](https://github.com/deepset-ai/haystack) — End-to-end LLM framework by deepset for building retrieval-augmented generation pipelines and custom NLP applications.
- [**Claude Agent SDK**](https://github.com/anthropics/anthropic-sdk-python) — Anthropic's SDK for building AI agents with tool use, multi-turn conversations, and structured workflows.

## Coding Agents

- [**Claude Code**](https://docs.anthropic.com/en/docs/claude-code) — Anthropic's agentic CLI tool for coding tasks, capable of editing files, running commands, and managing entire projects.
- [**GitHub Copilot**](https://github.com/features/copilot) — AI pair programmer that suggests code completions, generates functions, and answers questions inline in your editor.
- [**Cursor**](https://www.cursor.com/) — AI-native code editor built on VS Code with inline editing, codebase-aware chat, and multi-file generation.
- [**Windsurf**](https://codeium.com/windsurf) — AI code editor by Codeium with deep codebase understanding and collaborative coding flows.
- [**Aider**](https://github.com/Aider-AI/aider) — CLI-based AI coding assistant that pairs with your local git repo to make coordinated edits across multiple files.
- [**OpenHands**](https://github.com/All-Hands-AI/OpenHands) — Open-source AI software engineer (formerly OpenDevin) that can write code, run tests, and browse the web autonomously.
- [**SWE-agent**](https://github.com/princeton-nlp/SWE-agent) — Princeton's autonomous agent for resolving real-world GitHub issues, built on top of language models.
- [**Codex CLI**](https://github.com/openai/codex) — OpenAI's open-source CLI coding agent that runs locally and can write, refactor, and explain code.

## General Purpose Agents

- [**ChatGPT**](https://chat.openai.com/) — OpenAI's conversational AI with tool use, code execution, web browsing, and image generation.
- [**Claude**](https://claude.ai/) — Anthropic's AI assistant with large context windows, strong reasoning, and careful instruction following.
- [**Gemini**](https://gemini.google.com/) — Google's multimodal AI with deep Google ecosystem integration and long context support.
- [**Perplexity**](https://www.perplexity.ai/) — AI-powered answer engine that combines search with synthesis for sourced, up-to-date responses.
- [**Manus**](https://manus.im/) — General-purpose AI agent that can browse the web, write code, and complete multi-step tasks autonomously.

## Research & Data Agents

- [**Elicit**](https://elicit.com/) — AI research assistant that finds relevant papers, extracts key claims, and helps synthesize findings across studies.
- [**Consensus**](https://consensus.app/) — AI-powered academic search engine that surfaces evidence-based answers from peer-reviewed research.
- [**Grok**](https://grok.x.ai/) — xAI's conversational AI with real-time access to X (Twitter) data and current events.
- [**NotebookLM**](https://notebooklm.google.com/) — Google's AI-powered notebook that grounds responses in your uploaded documents for focused research.

## Automation & Workflow Agents

- [**n8n**](https://github.com/n8n-io/n8n) — Open-source workflow automation platform with AI agent nodes, LLM integrations, and a visual builder.
- [**Zapier AI**](https://zapier.com/ai) — AI-powered automation that connects thousands of apps with natural language workflow creation.
- [**Make**](https://www.make.com/) — Visual automation platform with AI modules for building complex, branching workflows across services.
- [**Activepieces**](https://github.com/activepieces/activepieces) — Open-source business automation tool with a growing library of AI-powered pieces and integrations.
- [**Relevance AI**](https://relevanceai.com/) — Platform for building AI agents and workforce tools that handle business tasks like sales, support, and research.

## Open Source & Self-Hosted Agents

- [**Ollama**](https://github.com/ollama/ollama) — Run large language models locally with a simple CLI, supporting a wide range of open-weight models.
- [**Jan**](https://github.com/janhq/jan) — Open-source ChatGPT alternative that runs entirely on your machine with a clean desktop interface.
- [**Open WebUI**](https://github.com/open-webui/open-webui) — Self-hosted web interface for LLMs with support for Ollama, OpenAI-compatible APIs, and multi-user setups.
- [**LocalAI**](https://github.com/mudler/LocalAI) — Drop-in replacement for the OpenAI API that runs models locally on consumer hardware without a GPU.
- [**GPT4All**](https://github.com/nomic-ai/gpt4all) — Desktop application by Nomic AI for running local LLMs privately with no data leaving your device.

## Guides & Patterns

- [**LLM Wiki Pattern**](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) — Andrej Karpathy's design pattern for building persistent LLM-powered knowledge bases instead of traditional RAG. Describes a three-layer architecture (raw sources, wiki, schema) for incremental knowledge synthesis.
- [**Building Effective Agents**](https://www.anthropic.com/engineering/building-effective-agents) — Anthropic's practical guide to agent architectures, covering workflows, tool use, and when to use autonomous agents vs. simpler patterns.
- [**A Practical Guide to Building Agents**](https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf) — OpenAI's guide covering agent design, orchestration patterns, and guardrails for production deployments.

---

## More from ResourceChest

Explore our other curated collections:

| Repository | Description |
|---|---|
| [Chrome Privacy Extensions](https://github.com/ResourceChest/chrome-privacy-extensions) | Curated list of Chrome extensions for privacy and security |
| [Custom GPTs](https://github.com/ResourceChest/custom-gpts) | Community-curated catalog of useful Custom GPTs |

> Follow [ResourceChest](https://github.com/ResourceChest) for more curated resource collections.

---

## Contributing

Want to add or suggest a new AI agent or tool? Check out our [CONTRIBUTING.md](https://github.com/ResourceChest/.github/blob/main/CONTRIBUTING.md) for guidelines. Pull requests are welcome.

## Disclaimer

All tools and frameworks listed here are based on personal research and community feedback. We are not affiliated with any of the projects or their developers. Please conduct your own evaluation before adopting any tool in production.
