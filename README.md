# Awesome Deep Research

[![Awesome](https://img.shields.io/badge/Awesome-DeepResearch-blueviolet?logo=awesome-lists&logoColor=white)](https://github.com/AaronAust1n/awesome-deep-research)
[![Stars](https://img.shields.io/github/stars/AaronAust1n/awesome-deep-research?style=social)](https://github.com/AaronAust1n/awesome-deep-research/stargazers)
[![License](https://img.shields.io/github/license/AaronAust1n/awesome-deep-research)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](#contributing-guidelines)
[![Status](https://img.shields.io/badge/status-active-brightgreen)](#)
[![Contributors](https://img.shields.io/github/contributors/AaronAust1n/awesome-deep-research)](https://github.com/AaronAust1n/awesome-deep-research/graphs/contributors)

[中文版本](README-zh.md) | English Version

## Table of Contents

- [Frameworks & Agents](#frameworks--agents)
- [Agent Skills](#agent-skills)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Search & Applications](#search--applications)
- [Project Details](#project-details)
- [Contributing Guidelines](#contributing-guidelines)
- [License](#license)

## Frameworks & Agents

| Project | Stars | Language | Category | Status | Tags | Features |
|---------|-------|----------|----------|--------|------|----------|
| [OpenResearcher](https://github.com/TIGER-AI-Lab/OpenResearcher) | 1.3k+ | Python | Data Synthesis, Training | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Open Pipeline, Trajectory Data | Fully open trajectory synthesis pipeline, 30B-A3B model, BrowseComp-Plus 54.8% |
| [ResearStudio](https://github.com/dornenkrone/ResearStudio) | 6+ | Python | Agent, Interactive | ![Inactive](https://img.shields.io/badge/status-inactive-yellow) | Human-in-loop, Real-time Control | Real-time intervention, plan editing, GAIA benchmark |
| [Tongyi DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | 20.0k+ | Python | Agent, Model | ![Active](https://img.shields.io/badge/status-active-brightgreen) | MoE, RL, Open Weights | 30B-A3B MoE, agentic training, MCP, SOTA on BrowseComp/GAIA/HLE |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) | 8.4k+ | Python | Model, Agent | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Open Weights, Prediction | Interactive scaling, 256K context, SOTA open-source search agent |
| [MiroFlow](https://github.com/MiroMindAI/MiroFlow) | 3.1k+ | Python | Agent, Fullstack | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Agent Framework, Fullstack | Multi-tool calling, GAIA high score, mobile support |
| [gemini-fullstack-langgraph-quickstart](https://github.com/google-gemini/gemini-fullstack-langgraph-quickstart) | 18.3k+ | TypeScript/Python | Fullstack, Agent | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Gemini, LangGraph, Fullstack | React frontend, LangGraph backend, dynamic search, web research, citations |
| [DeerFlow](https://github.com/bytedance/deer-flow) | 83.2k+ | Python | Multi-modal, Reasoning | ![Active](https://img.shields.io/badge/status-active-brightgreen) | LLM, Multi-source, Private Deploy | Multi-step reasoning, data integration, report generation, private deploy |
| [Deep Research Agent](https://github.com/SkyworkAI/DeepResearchAgent) | 3.5k+ | Python | Agent, Literature | ![Active](https://img.shields.io/badge/status-active-brightgreen) | LLM, Multi-agent, Browser | Cross-language retrieval, summary, suggestions, browser automation |
| [Deep Researcher](https://github.com/GAIR-NLP/DeepResearcher) | 800+ | Python | RL, Academic | ![Active](https://img.shields.io/badge/status-active-brightgreen) | RL, Trend, HuggingFace | RL-based, trend analysis, 7B model, cross-validation |
| [Deep Research](https://github.com/shibing624/deep-research) | 50+ | Python | Assistant, API | ![Inactive](https://img.shields.io/badge/status-inactive-yellow) | LLM, API, CLI, Gradio | Search+LLM, iterative, RESTful, Chinese support |
| [Deep Searcher](https://github.com/zilliztech/deep-searcher) | 8.3k+ | Python | Search, Reasoning | ![Active](https://img.shields.io/badge/status-active-brightgreen) | API, SDK, Local | Private data, API, SDK, local deploy |
| [dzhng/deep-research](https://github.com/dzhng/deep-research) | 19.7k+ | TypeScript | Agent, Web | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Firecrawl, Iterative | Configurable breadth/depth, markdown report with sources |
| [deep-research](https://github.com/u14app/deep-research) | 4.7k+ | JavaScript | Report, SaaS | ![Active](https://img.shields.io/badge/status-active-brightgreen) | LLM, SaaS, PWA | Multi-LLM, fast report, local KB, PWA |
| [open-deep-research](https://github.com/nickscamara/open-deep-research) | 6.3k+ | TypeScript | Web, Data Extraction | ![Inactive](https://img.shields.io/badge/status-inactive-yellow) | Firecrawl, Next.js, SSR | Real-time extraction, multi-model, SSR |
| [OpenDeepResearcher](https://github.com/mshumer/OpenDeepResearcher) | 2.8k+ | Jupyter Notebook | Agent, Web | ![Inactive](https://img.shields.io/badge/status-inactive-yellow) | SERPAPI, Jina, Gradio | Iterative search, async, dedup, Gradio |
| [local-deep-research](https://github.com/LearningCircuit/local-deep-research) | 9.1k+ | Python | Local, RAG | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Local, RAG, Docker | Local run, privacy, vector search, Docker |
| [deep-research-web-ui](https://github.com/AnotiaWang/deep-research-web-ui) | 2.2k+ | Vue/TypeScript | Web UI | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Web UI, Docker, Multi-AI | Real-time feedback, tree view, export |
| [open-deep-research](https://github.com/btahir/open-deep-research) | 2.1k+ | TypeScript | Web, Report | ![Archived](https://img.shields.io/badge/status-archived-red) | Gemini, Web, Vercel | AI report, modern UI, multi-model |
| [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) | 1.7k+ | Python | Assistant, Automation | ![Active](https://img.shields.io/badge/status-active-brightgreen) | LLM, Docker, File | Auto, multi-LLM, file upload, Docker |
| [agents-deep-research](https://github.com/qx-labs/agents-deep-research) | 790+ | Python | Multi-agent | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Multi-agent, Workflow | Autonomous, multi-source, workflow |
| [node-DeepResearch](https://github.com/jina-ai/node-DeepResearch) | 5.2k+ | TypeScript | Web, Q&A | ![Active](https://img.shields.io/badge/status-active-brightgreen) | LLM, API, Docker | Iterative Q&A, local LLM, API |
| [local-deep-researcher](https://github.com/langchain-ai/local-deep-researcher) | 9.4k+ | Python | Local, Web | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Local, Web, Markdown | Local research, privacy, markdown |
| [DeepGit](https://github.com/zamalali/DeepGit) | 917+ | Python | Code, GitHub | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Code, GitHub, ColBERT | Repo analysis, recommendation, workflow |
| [Open Deep Research](https://github.com/langchain-ai/open_deep_research) | 12.7k+ | Python | Framework | ![Archived](https://img.shields.io/badge/status-archived-red) | LangChain, Workflow | Multi-step, automation, local |
| [BettaFish](https://github.com/666ghj/BettaFish) | 42.3k+ | Python | Multi-agent, Public Opinion | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Multi-agent, Sentiment, Report | Opinion analysis, trend prediction, framework-free implementation |
| [storm](https://github.com/stanford-oval/storm) | 31.5k+ | Python | Knowledge Curation, Report | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Stanford, Citation | Wikipedia-like articles, perspective-guided questions, co-STORM |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher) | 29.8k+ | Python | Agent, Report | ![Active](https://img.shields.io/badge/status-active-brightgreen) | LLM, Citation, Streaming | Autonomous, multi-round, citation |

## Agent Skills

| Project | Stars | Language | Category | Status | Tags | Features |
|---------|-------|----------|----------|--------|------|----------|
| [hyperresearch](https://github.com/jordan-gibbs/hyperresearch) | 3.7k+ | Python | Skill, Deep Research | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Claude Code, Codex, Citation Verification | 16-step pipeline, citation verification, persistent source vault |
| [DeepPaperNote](https://github.com/917Dhj/DeepPaperNote) | 1.1k+ | Python | Skill, Paper Reading | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Obsidian, Multi-host | Paper deep-reading, Obsidian notes, multi-host support |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) | 1.2k+ | TypeScript | Skill, Social Media | ![Active](https://img.shields.io/badge/status-active-brightgreen) | X/Twitter, Briefings | X/Twitter search, thread following, sourced briefings |
| [last30days-skill](https://github.com/mvanhorn/last30days-skill) | 63.2k+ | Python | Skill, Research | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Reddit, X, Engagement Scoring | Social sources, engagement scoring, grounded briefs |
| [Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) | 2.3k+ | Python | Skill, Workflow | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Human-in-loop, Outline | Two-phase workflow, human-in-loop, outline generation |
| [claude-deep-research-skill](https://github.com/199-biotechnologies/claude-deep-research-skill) | 1.2k+ | Python | Skill, Report | ![Active](https://img.shields.io/badge/status-active-brightgreen) | 8-Phase Pipeline, Credibility | 8-phase pipeline, credibility scoring, multi-provider search |

## Benchmarks & Evaluation

| Project | Stars | Language | Category | Status | Tags | Features |
|---------|-------|----------|----------|--------|------|----------|
| [Vision-DeepResearch](https://github.com/Osilly/Vision-DeepResearch) | 685+ | Python | Benchmark, Multimodal | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Multimodal, Long-horizon | First long-horizon multimodal deep-research MLLM and benchmark |
| [Dr. Bench](https://github.com/EVIGBYEN/DrBench) | 8+ | Jupyter Notebook | Benchmark, Evaluation | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Long-form Reports, Retrieval | 214 expert-curated deep-research tasks with report-quality and retrieval-trustworthiness metrics |
| [BrowseComp-Plus](https://github.com/texttron/BrowseComp-Plus) | 365+ | Python | Benchmark, Retrieval | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Fixed Corpus, Reproducible | Fixed 100K-document corpus, decouples retriever and agent |
| [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) | 836+ | Python | Benchmark, Evaluation | ![Active](https://img.shields.io/badge/status-active-brightgreen) | RACE, FACT, Leaderboard | Report quality (RACE) and citation accuracy (FACT) evaluation |

## Search & Applications

| Project | Stars | Language | Category | Status | Tags | Features |
|---------|-------|----------|----------|--------|------|----------|
| [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) | 4.7k+ | Python | Data Science, Report | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Agentic LLM, Data Analysis | Autonomous data science, one-click professional reports |
| [SurveyX](https://github.com/IAAR-Shanghai/SurveyX) | 990+ | TeX | Academic, Report | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Survey, Paper | Academic survey paper generation, TeX output |
| [Vane (formerly Perplexica)](https://github.com/ItzCrazyKns/Vane) | 36.9k+ | TypeScript | Search Engine, Answer Engine | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Perplexity Alternative, Citations | AI answers, citations, self-hostable |
| [morphic](https://github.com/miurla/morphic) | 9.1k+ | TypeScript | Search Engine, UI | ![Active](https://img.shields.io/badge/status-active-brightgreen) | Generative UI, AI Search | Generative UI, multi-model, sourced answers |

## Project Details

### Frameworks & Agents

#### [OpenResearcher](https://github.com/TIGER-AI-Lab/OpenResearcher) - By TIGER-AI-Lab
- ⭐ 1.3k+ stars
- Language: Python
- Features:
  - Fully open pipeline for long-horizon deep research trajectory synthesis
  - Open-source 30B-A3B agentic LLM achieving 54.8% on BrowseComp-Plus
  - Surpasses GPT-4.1, Claude-Opus-4, Gemini-2.5-Pro, DeepSeek-R1 and Tongyi-DeepResearch on the benchmark
  - Fully open training and evaluation recipe: data, model, training methodology, and evaluation framework
  - Open-sourced dataset, model and evaluation logs on Hugging Face
  - Adopted by NVIDIA's Nemotron family and NeMo Data Designer for deep research trajectory generation
- Open Source Date: February 2026

#### [ResearStudio](https://github.com/dornenkrone/ResearStudio) - By dornenkrone
- ⭐ 6+ stars
- Language: Python
- Features:
  - Human-in-the-loop framework for building controllable deep research agents
  - Real-time human intervention and control during execution
  - Hierarchical planner-executor architecture with real-time "plan document" writing
  - Fast communication layer streaming every action, file change, and tool call
  - Users can pause, edit plans or code, run custom commands at any time
  - State-of-the-art results on GAIA benchmark, surpassing OpenAI DeepResearch
  - Collaborative workshop design with real-time human control
  - MIT License
- Open Source Date: October 2025

#### [Tongyi DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) - By Alibaba Tongyi Lab
- ⭐ 20.0k+ stars
- Language: Python
- Features:
  - Leading open-source deep research agent from Alibaba Tongyi Lab
  - 30B-A3B MoE model with only 3B parameters activated per token
  - Fully agentic training paradigm: agentic continued pre-training, SFT and RL
  - IterResearch test-time scaling for long-horizon research tasks
  - Native MCP tool calling and deep web information seeking
  - Open model weights on Hugging Face
  - State-of-the-art performance on BrowseComp, GAIA, HLE and other benchmarks
  - Apache 2.0 License
- Open Source Date: September 2025

#### [MiroThinker](https://github.com/MiroMindAI/MiroThinker) - By MiroMindAI
- ⭐ 8.4k+ stars
- Language: Python
- Features:
  - Deep research agent optimized for complex research and prediction tasks
  - Open-source model series from 8B to 235B parameters (v1.0, v1.5, 1.7)
  - Interactive scaling as a third dimension of performance improvement
  - Supports 256K context window and up to 600 tool calls per task
  - State-of-the-art open-source results on BrowseComp, BrowseComp-ZH, GAIA and HLE
  - Open training data (MiroVerse) and trace collection toolkit
  - Works with MiroFlow as part of the full-stack open deep research project (ODR)
- Open Source Date: August 2025

#### [MiroFlow](https://github.com/MiroMindAI/MiroFlow) - By MiroMindAI
- ⭐ 3.1k+ stars
- Language: Python
- Features:
  - Part of full-stack open-source deep research project (ODR)
  - Agent framework supporting multiple mainstream tool calls
  - Achieves 82.4 score on GAIA validation set, surpassing existing commercial model APIs
  - Includes MiroFlow (Agent framework), MiroThinker (core model), MiroVerse (dataset), MiroTrain/MiroRL (training infrastructure)
  - Supports mobile device deployment
  - Provides open, reusable research platform for developers
  - Promotes innovation and collaboration in AI field
- Open Source Date: August 2025

#### [gemini-fullstack-langgraph-quickstart](https://github.com/google-gemini/gemini-fullstack-langgraph-quickstart) - By Google Gemini
- ⭐ 18.3k+ stars
- Language: TypeScript/Python
- Features:
  - Fullstack application with React frontend and LangGraph backend
  - Powered by Gemini 2.5 and LangGraph for advanced research
  - Dynamic search query generation and web research
  - Reflective reasoning to identify knowledge gaps
  - Generates answers with citations from gathered sources
  - Hot-reloading for both frontend and backend development
  - Apache 2.0 License
- Open Source Date: May 2025

#### [DeerFlow](https://github.com/bytedance/deer-flow) - By ByteDance
- ⭐ 83.2k+ stars
- Language: Python
- Features:
  - Multi-step reasoning and complex problem decomposition
  - Multi-source heterogeneous data integration (text, PDF, images, etc.)
  - Automated structured research report generation
  - Private deployment and customization support
  - Web crawling and Python execution support
- Open Source Date: May 2025

#### [Deep Research Agent](https://github.com/SkyworkAI/DeepResearchAgent) - By SkyworkAI
- ⭐ 3.5k+ stars
- Language: Python
- Features:
  - LLM-based intelligent research assistant
  - Cross-language literature retrieval and analysis
  - Automatic research summary and key findings generation
  - Research suggestions and direction guidance
  - Hierarchical multi-agent system architecture
  - Browser automation support
  - Asynchronous task processing
  - Local deployment support
- Open Source Date: May 2025

#### [Deep Researcher](https://github.com/GAIR-NLP/DeepResearcher) - By GAIR-NLP
- ⭐ 800+ stars
- Language: Python
- Features:
  - Reinforcement learning based deep research system
  - Support for real-world research tasks
  - Research trend analysis and hot spot discovery
  - Deep understanding of academic literature
  - End-to-end training framework
  - 7B parameter pre-trained model
  - Multi-source information cross-validation
  - Self-reflection and honesty maintenance
  - Hugging Face model support
- Open Source Date: April 2025

#### [Deep Research](https://github.com/shibing624/deep-research) - Personal Project
- ⭐ 50+ stars
- Language: Python
- Features:
  - AI-powered research assistant
  - Combines search engines, web scraping, and LLMs
  - Iterative deep research support
  - RESTful API interface
  - Deep search and intelligent query generation
  - Multiple output formats (concise answers and detailed reports)
  - Full Chinese language support
  - Command-line interface and Gradio web UI
  - Streaming CoT output support
  - Apache 2.0 License
- Open Source Date: March 2025

#### [Deep Searcher](https://github.com/zilliztech/deep-searcher) - By Zilliz
- ⭐ 8.3k+ stars
- Language: Python
- Features:
  - Open source deep research alternative
  - Reasoning and search on private data
  - Python implementation
  - Rich API interfaces and SDKs
  - Comprehensive documentation
  - Local deployment support
  - Apache 2.0 License
- Open Source Date: February 2025

#### [dzhng/deep-research](https://github.com/dzhng/deep-research) - By dzhng
- ⭐ 19.7k+ stars
- Language: TypeScript
- Features:
  - Original open-source alternative to OpenAI Deep Research
  - Iterative deep research on any topic by combining search engines, web scraping, and LLMs
  - Configurable research breadth and depth
  - Firecrawl-powered search and content extraction
  - Generates a detailed markdown report with sources
  - Lightweight codebase, easy to embed in other applications
  - MIT License
- Open Source Date: February 2025

#### [deep-research](https://github.com/u14app/deep-research) - By u14app
- ⭐ 4.7k+ stars
- Language: JavaScript
- Features:
  - Supports multiple mainstream LLMs (Gemini, OpenAI, Anthropic, Deepseek, Mistral, etc.), freely switchable
  - Lightning-fast deep research report generation, typically within 2 minutes, suitable for efficient office and academic research
  - Supports uploading local knowledge base (text, Office, PDF, etc.) for personalized knowledge integration
  - Provides PWA, SaaS, API, and other usage modes, one-click deployment on Vercel, Cloudflare, etc.
  - Multi-language (including Chinese), multiple web search engines (Searxng, Tavily, Firecrawl, etc.)
  - Advanced features: history, content editing (WYSIWYM/Markdown), automatic knowledge graph generation
  - Supports SSE API and MCP service for easy integration into other AI services
  - MIT License
- Open Source Date: February 2025

#### [open-deep-research](https://github.com/nickscamara/open-deep-research) - By nickscamara
- ⭐ 6.3k+ stars
- Language: TypeScript
- Features:
  - Real-time data extraction and reasoning based on Firecrawl, simulating OpenAI Deep Research experiment
  - Supports multiple models (OpenAI, Anthropic, Cohere, etc.), flexible switching via AI SDK
  - Built with Next.js App Router, supports server-side rendering and high-performance routing
  - Data persistence (Vercel Postgres), file storage (Vercel Blob), user authentication (NextAuth.js)
  - One-click Vercel deployment, supports custom environment variables and API keys
  - Suitable for deep research scenarios requiring large-scale web data extraction and multi-step reasoning
- Open Source Date: February 2025

#### [OpenDeepResearcher](https://github.com/mshumer/OpenDeepResearcher) - By mshumer
- ⭐ 2.8k+ stars
- Language: Jupyter Notebook
- Features:
  - AI researcher, automatic iterative search, web scraping, reasoning, and report generation
  - Supports multiple services: SERPAPI (Google search), Jina (web content extraction), OpenRouter (LLM reasoning)
  - Asynchronous concurrent processing for improved search and extraction efficiency
  - Automatic deduplication and aggregation to ensure comprehensive, non-redundant results
  - Gradio interface for interactive use
  - Suitable for scientific, academic, and technical research
  - MIT License
- Open Source Date: February 2025

#### [local-deep-research](https://github.com/LearningCircuit/local-deep-research) - By LearningCircuit
- ⭐ 9.1k+ stars
- Language: Python
- Features:
  - Local AI deep research assistant, supports multiple LLMs and multi-source knowledge integration
  - Academic databases, scientific repositories, web, and private document retrieval
  - Local run, privacy protection, vector search (RAG)
  - Quickly generates summaries or detailed reports, all with citations, suitable for academic and enterprise scenarios
  - One-click Docker Compose deployment, easy to extend
  - MIT License
- Open Source Date: February 2025

#### [deep-research-web-ui](https://github.com/AnotiaWang/deep-research-web-ui) - By AnotiaWang
- ⭐ 2.2k+ stars
- Language: Vue/TypeScript
- Features:
  - Web UI for deep research with real-time feedback and search visualization
  - Safe & secure: all config and API requests stay in browser locally
  - Supports multiple AI providers (OpenAI, SiliconFlow, Infiniai, DeepSeek, etc.)
  - Multiple web search engines (Tavily, Firecrawl)
  - Tree structure visualization of research process
  - Export research reports as Markdown/PDF
  - Docker support for easy deployment
  - Multi-language support
  - MIT License
- Open Source Date: February 2025

#### [open-deep-research](https://github.com/btahir/open-deep-research) - By btahir
- ⭐ 2.1k+ stars
- Language: TypeScript
- Features:
  - Open source alternative to Gemini Deep Research
  - AI-powered report generation based on search results
  - Modern web interface with real-time updates
  - Supports multiple AI models and search providers
  - Easy deployment on Vercel
  - MIT License
  - Repository archived (no longer maintained)
- Open Source Date: February 2025

#### [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) - By HKUDS
- ⭐ 1.7k+ stars
- Language: Python
- Features:
  - Fully-automated and cost-effective personal AI assistant
  - Open-source alternative to OpenAI's Deep Research
  - Universal LLM support (OpenAI, Anthropic, Deepseek, vLLM, Grok, Huggingface)
  - Flexible interaction with both function-calling and non-function-calling LLMs
  - File upload support for enhanced data interaction
  - One-click launch with zero configuration
  - Docker support for easy deployment
  - Cost-efficient alternative to Deep Research's subscription
- Open Source Date: February 2025

#### [agents-deep-research](https://github.com/qx-labs/agents-deep-research) - By QX Labs
- ⭐ 790+ stars
- Language: Python
- Features:
  - Multi-agent system for deep research tasks
  - Autonomous research and analysis capabilities
  - Support for multiple data sources and formats
  - Advanced reasoning and knowledge integration
  - Customizable research workflows
  - Real-time collaboration features
  - Comprehensive documentation and examples
  - MIT License
- Open Source Date: February 2025

#### [node-DeepResearch](https://github.com/jina-ai/node-DeepResearch) - By Jina AI
- ⭐ 5.2k+ stars
- Language: TypeScript
- Features:
  - Automated web search, content extraction, and reasoning, iteratively performing "search-read-reason" until an answer is found or token budget is exceeded
  - Focused on precise, fast deep Q&A, suitable for complex problems requiring multi-step reasoning and information integration
  - Supports local LLMs (e.g., Ollama, LMStudio) and OpenAI-compatible APIs, flexible backend switching
  - Official UI (search.jina.ai) and API for easy production integration
  - One-click Docker deployment, easy for local and private deployment
  - Rich API interfaces, supports streaming output and structured results
  - Apache 2.0 License
- Open Source Date: January 2025

#### [local-deep-researcher](https://github.com/langchain-ai/local-deep-researcher) - By LangChain AI
- ⭐ 9.4k+ stars
- Language: Python
- Features:
  - Fully local web research and report generation assistant, all data and reasoning can be performed locally for privacy protection
  - Supports Ollama, LMStudio and other local LLMs, compatible with various models
  - Automatically generates search queries, fetches web pages, summarizes, reflects on knowledge gaps, and iteratively fills them
  - Outputs final markdown research report with citations, suitable for academic and professional scenarios
  - Customizable models, search tools, and iteration rounds for flexible adaptation
  - Detailed environment variable configuration and video tutorials for easy onboarding
  - MIT License
- Open Source Date: December 2024

#### [DeepGit](https://github.com/zamalali/DeepGit) - Personal Project
- ⭐ 917+ stars
- Language: Python
- Features:
  - Research agent for finding best GitHub repositories
  - Deep code repository analysis and understanding
  - Intelligent code recommendations and refactoring suggestions
  - Project dependency analysis and optimization
  - Langgraph-based intelligent workflow
  - Multi-dimensional ColBERT v2 embeddings
  - Smart hardware filtering
  - Lightweight version (DeepGit-lite)
  - Hybrid dense retrieval and cross-encoder re-ranking
  - Online demo (Vercel deployment)
- Open Source Date: December 2024

#### [Open Deep Research](https://github.com/langchain-ai/open_deep_research) - By LangChain AI
- ⭐ 12.7k+ stars
- Language: Python
- Features:
  - LangChain-based deep research framework
  - Multi-step reasoning and knowledge integration
  - Research process automation tools
  - Customizable research strategies
  - Two implementations: workflow and multi-agent architecture
  - Local deployment and customization support
  - Complete development environment configuration
  - Repository archived (no longer maintained)
- Open Source Date: November 2024

#### [BettaFish](https://github.com/666ghj/BettaFish) - By 666ghj
- ⭐ 42.3k+ stars
- Language: Python
- Features:
  - Multi-agent public opinion analysis assistant, accessible to everyone
  - Breaks information cocoons and restores the full picture of public opinion
  - Predicts future trends and supports decision-making
  - Built from scratch without relying on any agent framework
  - Deep analysis of Chinese social media and public opinion data
- Open Source Date: July 2024

#### [storm](https://github.com/stanford-oval/storm) - By Stanford OVAL
- ⭐ 31.5k+ stars
- Language: Python
- Features:
  - LLM-powered knowledge curation system
  - Researches a topic and generates a full-length Wikipedia-like article with citations
  - Perspective-guided question asking and simulated multi-perspective conversations
  - Internet search to gather and verify information
  - Co-STORM mode for human-AI collaborative knowledge curation
  - MIT License
- Open Source Date: April 2024

#### [gpt-researcher](https://github.com/assafelovic/gpt-researcher) - By assafelovic
- ⭐ 29.8k+ stars
- Language: Python
- Features:
  - LLM-based autonomous agent for local and web deep research
  - Multi-round search, extraction, and reasoning to generate long research reports with citations
  - Supports multiple models and APIs (OpenAI, Anthropic, etc.), customizable backend
  - Supports local knowledge base, streaming output, and structured results
  - Suitable for academic, market, technical, and other deep information integration scenarios
  - Apache 2.0 License
- Open Source Date: May 2023

### Agent Skills

#### [hyperresearch](https://github.com/jordan-gibbs/hyperresearch) - By jordan-gibbs
- ⭐ 3.7k+ stars
- Language: Python
- Features:
  - Deep research skill and harness for Claude Code and OpenAI Codex
  - Tier-adaptive 16-step pipeline producing adversarially-audited reports with full source provenance
  - Leads the DeepResearch-Bench RACE leaderboard (internal benchmark)
  - Every source read lands in a persistent, searchable vault so each session starts smarter
  - Targets 250+ sources per run with citation chasing and gap-fill fetching
  - Cite-checker verifies every citation before the report ships; independence audit clusters syndicated copies
  - MIT License
- Open Source Date: April 2026

#### [DeepPaperNote](https://github.com/917Dhj/DeepPaperNote) - By 917Dhj
- ⭐ 1.1k+ stars
- Language: Python
- Features:
  - Agent skill for deep-reading a single paper and generating high-quality Obsidian-style research notes
  - Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI and more
  - Turns papers into structured, linkable notes for long-term knowledge bases
  - MIT License
- Open Source Date: March 2026

#### [x-research-skill](https://github.com/rohunvora/x-research-skill) - By rohunvora
- ⭐ 1.2k+ stars
- Language: TypeScript
- Features:
  - X/Twitter research skill for Claude Code and OpenClaw
  - Agentic search, thread following and deep-dives on X
  - Produces sourced briefings instead of raw link dumps
- Open Source Date: February 2026

#### [last30days-skill](https://github.com/mvanhorn/last30days-skill) - By mvanhorn
- ⭐ 63.2k+ stars
- Language: Python
- Features:
  - AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, GitHub, arXiv and more
  - An agent-led search engine scored by upvotes, likes and real money instead of editors
  - Parallel multi-source search with engagement-based ranking and cross-source cluster merging
  - AI agent judge synthesizes one grounded brief with citations
  - Zero config for free sources; bring your own keys for X, TikTok, LinkedIn, etc.
  - Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, OpenClaw and 50+ Agent Skills hosts
  - MIT License
- Open Source Date: January 2026

#### [Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) - By Weizhena
- ⭐ 2.3k+ stars
- Language: Python
- Features:
  - Structured deep research workflow skill for Claude Code, OpenCode and Codex
  - Two-phase research: extensible outline generation and deep investigation
  - Human-in-the-loop design for precise control at every stage
  - Supports academic, technical, market and due-diligence research
  - English and Chinese skill versions
  - MIT License
- Open Source Date: December 2025

#### [claude-deep-research-skill](https://github.com/199-biotechnologies/claude-deep-research-skill) - By 199 Biotechnologies
- ⭐ 1.2k+ stars
- Language: Python
- Features:
  - Enterprise-grade deep research skill for Claude Code
  - 8-phase pipeline: scope, plan, retrieve, triangulate, outline refinement, synthesize, critique, refine and package
  - Citation-backed reports with source credibility scoring
  - Multi-provider search aggregation across Brave, Serper, Exa, Jina and Firecrawl
  - Four research modes: Quick, Standard, Deep and UltraDeep
  - Automated validation with critique loop-back
- Open Source Date: November 2025

### Benchmarks & Evaluation

#### [Vision-DeepResearch](https://github.com/Osilly/Vision-DeepResearch) - By Osilly
- ⭐ 685+ stars
- Language: Python
- Features:
  - Multimodal deep-research MLLM and benchmark (ICML 2026 & EMNLP 2026)
  - First long-horizon multimodal deep-research MLLM
  - Extends reasoning turns to dozens and search-engine interactions to hundreds
  - Includes a multimodal deep-research benchmark
  - MIT License
- Open Source Date: January 2026

#### [Dr. Bench](https://github.com/EVIGBYEN/DrBench) - By EVIGBYEN
- ⭐ 8+ stars
- Language: Jupyter Notebook
- Features:
  - Multidimensional evaluation framework for deep research agents, from answers to reports
  - 214 expert-curated challenging tasks across 10 broad domains
  - Each task accompanied by manually constructed reference bundles
  - Composite metrics for semantic quality, topical focus, and retrieval trustworthiness
  - Comprehensive evaluation of long-form reports generated by deep research agents
  - arXiv preprint 2025 (arXiv:2510.02190), by Shanghai AI Laboratory and partner universities
- Open Source Date: October 2025

#### [BrowseComp-Plus](https://github.com/texttron/BrowseComp-Plus) - By texttron
- ⭐ 365+ stars
- Language: Python
- Features:
  - Benchmark to evaluate deep research systems against a fixed, curated corpus of ~100K human-verified documents
  - Isolates the effect of the retriever and the LLM agent for fair, transparent and reproducible comparisons
  - Reasoning-intensive queries sourced from OpenAI's BrowseComp
  - Official dataset and leaderboard on Hugging Face
  - MIT License
- Open Source Date: August 2025

#### [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) - By Ayanami0730
- ⭐ 836+ stars
- Language: Python
- Features:
  - Comprehensive benchmark for deep research agents
  - Evaluates report generation with the RACE (report quality) and FACT (citation accuracy) frameworks
  - Official dataset and leaderboard on Hugging Face
  - arXiv:2506.11763
- Open Source Date: June 2025

### Search & Applications

#### [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) - By RUC DataLab
- ⭐ 4.7k+ stars
- Language: Python
- Features:
  - First agentic LLM for autonomous data science
  - Your AI data analyst: automatically analyzes large-scale data
  - One-click generation of professional analysis reports
  - End-to-end data understanding, analysis and report writing
- Open Source Date: October 2025

#### [SurveyX](https://github.com/IAAR-Shanghai/SurveyX) - By IAAR-Shanghai
- ⭐ 990+ stars
- Language: TeX
- Features:
  - Academic survey paper generation system
  - Automates literature organization and survey writing from a topic
  - TeX-based paper output
- Open Source Date: February 2025

#### [Vane (formerly Perplexica)](https://github.com/ItzCrazyKns/Vane) - By ItzCrazyKns
- ⭐ 36.9k+ stars
- Language: TypeScript
- Features:
  - AI-powered answering engine, formerly known as Perplexica
  - Open-source alternative to Perplexity AI
  - Combines LLMs with SearxNG-based web search and multiple providers
  - Answers with citations and focused research modes
  - Self-hostable and privacy-friendly, supports local LLMs
  - MIT License
- Open Source Date: April 2024

#### [morphic](https://github.com/miurla/morphic) - By miurla
- ⭐ 9.1k+ stars
- Language: TypeScript
- Features:
  - AI-powered search engine with a generative UI
  - Streams answers with sources instead of a list of links
  - Supports multiple AI models and search providers
  - Apache 2.0 License
- Open Source Date: April 2024

## Contributing Guidelines

Pull requests are welcome! Please ensure:

1. The project is open source
2. Provide basic project information (name, link, description, features, etc.)
3. Put the project in the right category, arranged in chronological order within that category
4. Provide descriptions in both English and Chinese

## License

This project is licensed under the [MIT License](LICENSE).