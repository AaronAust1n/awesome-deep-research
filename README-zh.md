# Awesome Deep Research

[![Awesome](https://img.shields.io/badge/Awesome-DeepResearch-blueviolet?logo=awesome-lists&logoColor=white)](https://github.com/AaronAust1n/awesome-deep-research)
[![Star数](https://img.shields.io/github/stars/AaronAust1n/awesome-deep-research?style=social)](https://github.com/AaronAust1n/awesome-deep-research/stargazers)
[![许可证](https://img.shields.io/github/license/AaronAust1n/awesome-deep-research)](LICENSE)
[![欢迎PR](https://img.shields.io/badge/欢迎PR-brightgreen.svg?style=flat-square)](#贡献指南)
[![项目状态](https://img.shields.io/badge/项目状态-活跃-green)](#)
[![贡献者](https://img.shields.io/github/contributors/AaronAust1n/awesome-deep-research)](https://github.com/AaronAust1n/awesome-deep-research/graphs/contributors)

中文版本 | [English Version](README.md)

## 目录

- [框架与智能体](#框架与智能体)
- [智能体技能](#智能体技能)
- [基准与评估](#基准与评估)
- [搜索与应用](#搜索与应用)
- [项目详情](#项目详情)
- [贡献指南](#贡献指南)
- [许可证](#许可证)

## 框架与智能体

| 项目 | Star数 | 语言 | 分类 | 状态 | 标签 | 主要特点 |
|------|--------|------|------|------|------|----------|
| [OpenResearcher](https://github.com/TIGER-AI-Lab/OpenResearcher) | 1.3k+ | Python | 数据合成, 训练 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 开放流水线, 轨迹数据 | 全开放轨迹合成流水线, 30B-A3B模型, BrowseComp-Plus 54.8% |
| [ResearStudio](https://github.com/dornenkrone/ResearStudio) | 6+ | Python | 智能体, 交互 | ![不活跃](https://img.shields.io/badge/项目状态-不活跃-yellow) | 人机交互, 实时控制 | 实时干预, 计划编辑, GAIA基准 |
| [Tongyi DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | 20.0k+ | Python | 智能体, 模型 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | MoE, RL, 开放权重 | 30B-A3B MoE, 智能体训练, MCP, BrowseComp/GAIA/HLE领先 |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) | 8.4k+ | Python | 模型, 智能体 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 开放权重, 预测 | 交互式扩展, 256K上下文, 开源搜索智能体SOTA |
| [MiroFlow](https://github.com/MiroMindAI/MiroFlow) | 3.1k+ | Python | 智能体, 全栈 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Agent框架, 全栈 | 多工具调用, GAIA高分, 移动端支持 |
| [gemini-fullstack-langgraph-quickstart](https://github.com/google-gemini/gemini-fullstack-langgraph-quickstart) | 18.3k+ | TypeScript/Python | 全栈, 智能体 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Gemini, LangGraph, 全栈 | React前端, LangGraph后端, 动态搜索, 网页研究, 引用 |
| [DeerFlow](https://github.com/bytedance/deer-flow) | 83.2k+ | Python | 多模态, 推理 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | LLM, 多源, 私有化 | 多步推理, 数据整合, 报告生成, 私有部署 |
| [Deep Research Agent](https://github.com/SkyworkAI/DeepResearchAgent) | 3.5k+ | Python | 智能体, 文献 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | LLM, 多智能体, 浏览器 | 跨语言检索, 摘要, 建议, 浏览器自动化 |
| [Deep Researcher](https://github.com/GAIR-NLP/DeepResearcher) | 800+ | Python | 强化学习, 学术 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | RL, 趋势, HuggingFace | 强化学习, 趋势分析, 7B模型, 交叉验证 |
| [Deep Research](https://github.com/shibing624/deep-research) | 50+ | Python | 助手, API | ![不活跃](https://img.shields.io/badge/项目状态-不活跃-yellow) | LLM, API, CLI, Gradio | 搜索+LLM, 迭代, RESTful, 中文支持 |
| [Deep Searcher](https://github.com/zilliztech/deep-searcher) | 8.3k+ | Python | 搜索, 推理 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | API, SDK, 本地 | 私有数据, API, SDK, 本地部署 |
| [dzhng/deep-research](https://github.com/dzhng/deep-research) | 19.7k+ | TypeScript | 智能体, Web | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Firecrawl, 迭代 | 广度/深度可配置, 带来源的Markdown报告 |
| [deep-research](https://github.com/u14app/deep-research) | 4.7k+ | JavaScript | 报告, SaaS | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | LLM, SaaS, PWA | 多模型, 极速报告, 本地知识库, PWA |
| [open-deep-research](https://github.com/nickscamara/open-deep-research) | 6.3k+ | TypeScript | Web, 数据抓取 | ![不活跃](https://img.shields.io/badge/项目状态-不活跃-yellow) | Firecrawl, Next.js, SSR | 实时抓取, 多模型, SSR |
| [OpenDeepResearcher](https://github.com/mshumer/OpenDeepResearcher) | 2.8k+ | Jupyter Notebook | 智能体, Web | ![不活跃](https://img.shields.io/badge/项目状态-不活跃-yellow) | SERPAPI, Jina, Gradio | 迭代搜索, 异步, 去重, Gradio |
| [local-deep-research](https://github.com/LearningCircuit/local-deep-research) | 9.1k+ | Python | 本地, RAG | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 本地, RAG, Docker | 本地运行, 隐私, 向量检索, Docker |
| [deep-research-web-ui](https://github.com/AnotiaWang/deep-research-web-ui) | 2.2k+ | Vue/TypeScript | Web UI | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Web UI, Docker, 多AI | 实时反馈, 树形可视, 导出 |
| [open-deep-research](https://github.com/btahir/open-deep-research) | 2.1k+ | TypeScript | Web, 报告 | ![已归档](https://img.shields.io/badge/项目状态-已归档-red) | Gemini, Web, Vercel | AI报告, 现代UI, 多模型 |
| [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) | 1.7k+ | Python | 助手, 自动化 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | LLM, Docker, 文件 | 全自动, 多模型, 文件上传, Docker |
| [agents-deep-research](https://github.com/qx-labs/agents-deep-research) | 790+ | Python | 多智能体 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 多智能体, 工作流 | 自主, 多源, 工作流 |
| [node-DeepResearch](https://github.com/jina-ai/node-DeepResearch) | 5.2k+ | TypeScript | Web, 问答 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | LLM, API, Docker | 迭代问答, 本地LLM, API |
| [local-deep-researcher](https://github.com/langchain-ai/local-deep-researcher) | 9.4k+ | Python | 本地, Web | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 本地, Web, Markdown | 本地研究, 隐私, markdown |
| [DeepGit](https://github.com/zamalali/DeepGit) | 917+ | Python | 代码, GitHub | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 代码, GitHub, ColBERT | 仓库分析, 推荐, 工作流 |
| [Open Deep Research](https://github.com/langchain-ai/open_deep_research) | 12.7k+ | Python | 框架 | ![已归档](https://img.shields.io/badge/项目状态-已归档-red) | LangChain, 工作流 | 多步, 自动化, 本地 |
| [BettaFish](https://github.com/666ghj/BettaFish) | 42.3k+ | Python | 多智能体, 舆情分析 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 多智能体, 情感分析, 报告 | 舆情分析, 趋势预测, 零框架依赖实现 |
| [storm](https://github.com/stanford-oval/storm) | 31.5k+ | Python | 知识整理, 报告 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Stanford, 引用 | 类维基长文, 多视角提问, co-STORM |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher) | 29.8k+ | Python | 智能体, 报告 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | LLM, 引用, 流式 | 自主, 多轮, 引用 |

## 智能体技能

| 项目 | Star数 | 语言 | 分类 | 状态 | 标签 | 主要特点 |
|------|--------|------|------|------|------|----------|
| [hyperresearch](https://github.com/jordan-gibbs/hyperresearch) | 3.7k+ | Python | 技能, 深度研究 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Claude Code, Codex, 引用核验 | 16步流水线, 引用核验, 持久来源库 |
| [DeepPaperNote](https://github.com/917Dhj/DeepPaperNote) | 1.1k+ | Python | 技能, 论文阅读 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Obsidian, 多宿主 | 论文精读, Obsidian笔记, 多宿主支持 |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) | 1.2k+ | TypeScript | 技能, 社交媒体 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | X/Twitter, 简报 | X/Twitter检索, 线程追踪, 带来源简报 |
| [last30days-skill](https://github.com/mvanhorn/last30days-skill) | 63.2k+ | Python | 技能, 研究 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Reddit, X, 互动评分 | 社媒来源, 互动评分, 有据简报 |
| [Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) | 2.3k+ | Python | 技能, 工作流 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 人机交互, 大纲 | 两阶段工作流, 人工控制, 大纲生成 |
| [claude-deep-research-skill](https://github.com/199-biotechnologies/claude-deep-research-skill) | 1.2k+ | Python | 技能, 报告 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 8阶段流水线, 可信度 | 8阶段流水线, 来源可信度评分, 多搜索源 |

## 基准与评估

| 项目 | Star数 | 语言 | 分类 | 状态 | 标签 | 主要特点 |
|------|--------|------|------|------|------|----------|
| [Vision-DeepResearch](https://github.com/Osilly/Vision-DeepResearch) | 685+ | Python | 基准, 多模态 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 多模态, 长程 | 首个长程多模态深度研究MLLM与基准 |
| [Dr. Bench](https://github.com/EVIGBYEN/DrBench) | 8+ | Jupyter Notebook | 基准, 评估 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 长报告, 检索 | 214个专家精选深度研究任务, 报告质量与检索可信度指标 |
| [BrowseComp-Plus](https://github.com/texttron/BrowseComp-Plus) | 365+ | Python | 基准, 检索 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 固定语料, 可复现 | 10万文档固定语料, 解耦检索器与智能体 |
| [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) | 836+ | Python | 基准, 评估 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | RACE, FACT, 排行榜 | 报告质量（RACE）与引用准确性（FACT）评估 |

## 搜索与应用

| 项目 | Star数 | 语言 | 分类 | 状态 | 标签 | 主要特点 |
|------|--------|------|------|------|------|----------|
| [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) | 4.7k+ | Python | 数据科学, 报告 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 智能体LLM, 数据分析 | 自主数据科学, 一键专业报告 |
| [SurveyX](https://github.com/IAAR-Shanghai/SurveyX) | 990+ | TeX | 学术, 报告 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 综述, 论文 | 学术综述论文生成, TeX输出 |
| [Vane (原Perplexica)](https://github.com/ItzCrazyKns/Vane) | 36.9k+ | TypeScript | 搜索引擎, 问答 | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | Perplexity替代, 引用 | AI问答, 引用, 可自托管 |
| [morphic](https://github.com/miurla/morphic) | 9.1k+ | TypeScript | 搜索引擎, UI | ![活跃](https://img.shields.io/badge/项目状态-活跃-green) | 生成式UI, AI搜索 | 生成式UI, 多模型, 带来源答案 |

## 项目详情

### 框架与智能体

#### [OpenResearcher](https://github.com/TIGER-AI-Lab/OpenResearcher) - TIGER-AI-Lab
- ⭐ 1.3k+ stars
- 开发语言：Python
- 特点：
  - 全开放的长程深度研究轨迹合成流水线
  - 开源30B-A3B智能体模型，在BrowseComp-Plus上达到54.8%
  - 在该基准上超越GPT-4.1、Claude-Opus-4、Gemini-2.5-Pro、DeepSeek-R1和Tongyi-DeepResearch
  - 完全公开训练与评估方案：数据、模型、训练方法和评估框架
  - 在Hugging Face开源数据集、模型和评估日志
  - 已被NVIDIA Nemotron系列模型和NeMo Data Designer采用，用于深度研究轨迹生成
- 开源时间：2026年2月

#### [ResearStudio](https://github.com/dornenkrone/ResearStudio) - dornenkrone
- ⭐ 6+ stars
- 开发语言：Python
- 特点：
  - 以实时人机交互为核心的可控深度研究框架
  - 支持在执行过程中进行人类干预和控制
  - 层次化的计划-执行器架构，实时写入"计划文档"
  - 快速通信层，流式传输每个动作、文件更改和工具调用
  - 用户可以随时暂停、编辑计划或代码、运行自定义命令
  - 在GAIA基准测试中实现最先进的结果，超越OpenAI DeepResearch
  - 协作式工作坊设计，支持实时人类控制
  - MIT许可证
- 开源时间：2025年10月

#### [Tongyi DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) - 阿里巴巴通义实验室
- ⭐ 20.0k+ stars
- 开发语言：Python
- 特点：
  - 阿里巴巴通义实验室开源的领先深度研究智能体
  - 30B-A3B MoE模型，每个token仅激活3B参数
  - 全流程智能体化训练：智能体持续预训练、SFT和强化学习
  - IterResearch测试时扩展，支撑长程研究任务
  - 原生支持MCP工具调用和深度网络信息检索
  - 在Hugging Face开放模型权重
  - 在BrowseComp、GAIA、HLE等基准上达到最先进水平
  - Apache 2.0 许可证
- 开源时间：2025年9月

#### [MiroThinker](https://github.com/MiroMindAI/MiroThinker) - MiroMindAI
- ⭐ 8.4k+ stars
- 开发语言：Python
- 特点：
  - 面向复杂研究与预测任务优化的深度研究智能体
  - 开源8B至235B参数模型系列（v1.0、v1.5、1.7）
  - 交互式扩展（Interactive Scaling）作为性能提升的第三维度
  - 支持256K上下文窗口，单任务最多600次工具调用
  - 在BrowseComp、BrowseComp-ZH、GAIA和HLE上达到开源最先进水平
  - 开放训练数据（MiroVerse）和轨迹收集工具
  - 与MiroFlow配合，构成全栈开源深度研究项目（ODR）
- 开源时间：2025年8月

#### [MiroFlow](https://github.com/MiroMindAI/MiroFlow) - MiroMindAI
- ⭐ 3.1k+ stars
- 开发语言：Python
- 特点：
  - 全栈开源深度研究项目的一部分（ODR）
  - Agent框架，支持多种主流工具调用
  - 在GAIA验证集上实现82.4的高分，超越现有商用模型API
  - 包含MiroFlow（Agent框架）、MiroThinker（核心模型）、MiroVerse（数据集）、MiroTrain/MiroRL（训练基础设施）
  - 支持移动端运行
  - 为开发者提供开放、可复用的研究平台
  - 推动人工智能领域的创新与协作
- 开源时间：2025年8月

#### [gemini-fullstack-langgraph-quickstart](https://github.com/google-gemini/gemini-fullstack-langgraph-quickstart) - Google Gemini
- ⭐ 18.3k+ stars
- 开发语言：TypeScript/Python
- 特点：
  - 基于React前端和LangGraph后端的全栈应用
  - 采用Gemini 2.5和LangGraph进行高级研究
  - 支持动态搜索查询生成和网页研究
  - 具备反思推理能力，可识别知识缺口
  - 生成带引用的答案，来源可靠
  - 支持前端和后端开发的热重载
  - Apache 2.0 许可证
- 开源时间：2025年5月

#### [DeerFlow](https://github.com/bytedance/deer-flow) - 字节跳动
- ⭐ 83.2k+ stars
- 开发语言：Python
- 特点：
  - 支持多步骤推理和复杂问题拆解
  - 多源异构数据整合（文本、PDF、图像等）
  - 结构化研究报告自动生成
  - 支持私有化部署和定制化开发
  - 支持网络爬虫和Python执行
- 开源时间：2025年5月

#### [Deep Research Agent](https://github.com/SkyworkAI/DeepResearchAgent) - SkyworkAI
- ⭐ 3.5k+ stars
- 开发语言：Python
- 特点：
  - 基于大语言模型的智能研究助手
  - 支持跨语言文献检索和分析
  - 自动生成研究摘要和关键发现
  - 提供研究建议和方向指导
  - 分层多智能体系统架构
  - 支持浏览器自动化操作
  - 异步任务处理能力
  - 支持本地化部署
- 开源时间：2025年5月

#### [Deep Researcher](https://github.com/GAIR-NLP/DeepResearcher) - GAIR-NLP
- ⭐ 800+ stars
- 开发语言：Python
- 特点：
  - 基于强化学习的深度研究系统
  - 支持真实环境下的研究任务
  - 提供研究趋势分析和热点发现
  - 支持学术文献的深度理解
  - 端到端训练框架
  - 提供7B参数量的预训练模型
  - 支持多源信息交叉验证
  - 具备自我反思和诚实性保持能力
  - 提供Hugging Face模型支持
- 开源时间：2025年4月

#### [Deep Research](https://github.com/shibing624/deep-research) - 个人项目
- ⭐ 50+ stars
- 开发语言：Python
- 特点：
  - AI驱动的研究助手
  - 结合搜索引擎、网络爬虫和大语言模型
  - 支持迭代式深度研究
  - 提供RESTful API接口
  - 支持深度搜索和智能查询生成
  - 提供多种输出格式（简洁回答和详细报告）
  - 完全支持中文输入和输出
  - 提供命令行界面和Gradio网页界面
  - 支持流式输出CoT
  - 基于Apache 2.0许可证
- 开源时间：2025年3月

#### [Deep Searcher](https://github.com/zilliztech/deep-searcher) - Zilliz
- ⭐ 8.3k+ stars
- 开发语言：Python
- 特点：
  - 开源深度研究替代方案
  - 支持私有数据的推理和搜索
  - 基于Python实现
  - 提供丰富的API接口和SDK
  - 完整的文档支持
  - 支持本地化部署
  - 基于Apache 2.0许可证
- 开源时间：2025年2月

#### [dzhng/deep-research](https://github.com/dzhng/deep-research) - dzhng
- ⭐ 19.7k+ stars
- 开发语言：TypeScript
- 特点：
  - 最早的OpenAI Deep Research开源替代方案
  - 结合搜索引擎、网页抓取与大语言模型，对任意主题进行迭代式深度研究
  - 研究广度和深度可配置
  - 基于Firecrawl的搜索与内容提取
  - 生成带来源引用的详细Markdown报告
  - 代码库轻量，易于嵌入其他应用
  - MIT许可证
- 开源时间：2025年2月

#### [deep-research](https://github.com/u14app/deep-research) - u14app
- ⭐ 4.7k+ stars
- 开发语言：JavaScript
- 特点：
  - 支持多种主流大模型（Gemini、OpenAI、Anthropic、Deepseek、Mistral等），可自由切换
  - 极速生成深度研究报告，平均2分钟内完成，适合高效办公和学术调研
  - 支持本地知识库上传（文本、Office、PDF等），实现个性化知识整合
  - 提供PWA、SaaS、API等多种使用方式，支持Vercel、Cloudflare等平台一键部署
  - 支持多语言（含中文）、多种Web搜索引擎（Searxng、Tavily、Firecrawl等）
  - 具备历史记录、内容编辑（所见即所得/Markdown）、知识图谱自动生成等高级功能
  - 支持SSE API和MCP服务，便于集成到其他AI服务
  - MIT许可证
- 开源时间：2025年2月

#### [open-deep-research](https://github.com/nickscamara/open-deep-research) - nickscamara
- ⭐ 6.3k+ stars
- 开发语言：TypeScript
- 特点：
  - 基于Firecrawl的实时数据抓取与推理，模拟OpenAI Deep Research实验
  - 支持多模型（OpenAI、Anthropic、Cohere等），可通过AI SDK灵活切换
  - 采用Next.js App Router，支持服务端渲染和高性能路由
  - 支持数据持久化（Vercel Postgres）、文件存储（Vercel Blob）、用户认证（NextAuth.js）
  - 可一键Vercel部署，支持自定义环境变量和API密钥
  - 适合需要大规模网页数据抽取和多步推理的深度研究场景
- 开源时间：2025年2月

#### [OpenDeepResearcher](https://github.com/mshumer/OpenDeepResearcher) - mshumer
- ⭐ 2.8k+ stars
- 开发语言：Jupyter Notebook
- 特点：
  - AI研究员，自动迭代搜索、网页抓取、推理与报告生成
  - 支持SERPAPI（Google搜索）、Jina（网页内容抓取）、OpenRouter（LLM推理）等多服务
  - 采用异步并发处理，提升搜索和抓取效率
  - 自动去重、聚合信息，确保结果全面且无重复
  - 支持Gradio界面，便于交互式使用
  - 适合科研、学术、技术调研等场景
  - MIT许可证
- 开源时间：2025年2月

#### [local-deep-research](https://github.com/LearningCircuit/local-deep-research) - LearningCircuit
- ⭐ 9.1k+ stars
- 开发语言：Python
- 特点：
  - 本地AI深度研究助手，支持多LLM和多源知识整合
  - 支持学术数据库、科学库、网页、私有文档等多源检索
  - 支持本地运行，保护隐私，支持向量检索（RAG）
  - 可快速生成摘要或详细报告，均带引用，适合学术和企业场景
  - 支持Docker Compose一键部署，易于扩展
  - MIT许可证
- 开源时间：2025年2月

#### [deep-research-web-ui](https://github.com/AnotiaWang/deep-research-web-ui) - AnotiaWang
- ⭐ 2.2k+ stars
- 开发语言：Vue/TypeScript
- 特点：
  - 深度研究的Web界面，支持实时反馈和搜索可视化
  - 安全可靠：所有配置和API请求都在浏览器本地完成
  - 支持多种AI提供商（OpenAI、SiliconFlow、Infiniai、DeepSeek等）
  - 多种网络搜索引擎（Tavily、Firecrawl）
  - 研究过程的树形结构可视化
  - 支持将研究报告导出为Markdown/PDF格式
  - 支持Docker一键部署
  - 多语言支持
  - MIT许可证
- 开源时间：2025年2月

#### [open-deep-research](https://github.com/btahir/open-deep-research) - btahir
- ⭐ 2.1k+ stars
- 开发语言：TypeScript
- 特点：
  - Gemini Deep Research的开源替代方案
  - 基于搜索结果的AI驱动报告生成
  - 现代化的Web界面，支持实时更新
  - 支持多种AI模型和搜索提供商
  - 支持Vercel一键部署
  - MIT许可证
  - 仓库已归档（不再维护）
- 开源时间：2025年2月

#### [Auto-Deep-Research](https://github.com/HKUDS/Auto-Deep-Research) - HKUDS
- ⭐ 1.7k+ stars
- 开发语言：Python
- 特点：
  - 全自动且经济高效的个人AI助手
  - OpenAI Deep Research的开源替代方案
  - 通用LLM支持（OpenAI、Anthropic、Deepseek、vLLM、Grok、Huggingface）
  - 支持函数调用和非函数调用的灵活交互
  - 文件上传支持，增强数据交互
  - 零配置一键启动
  - 支持Docker部署
  - Deep Research订阅的经济替代方案
- 开源时间：2025年2月

#### [agents-deep-research](https://github.com/qx-labs/agents-deep-research) - QX Labs
- ⭐ 790+ stars
- 开发语言：Python
- 特点：
  - 用于深度研究任务的多智能体系统
  - 自主研究和分析能力
  - 支持多种数据源和格式
  - 高级推理和知识整合
  - 可定制的研究工作流
  - 实时协作功能
  - 全面的文档和示例
  - MIT许可证
- 开源时间：2025年2月

#### [node-DeepResearch](https://github.com/jina-ai/node-DeepResearch) - Jina AI
- ⭐ 5.2k+ stars
- 开发语言：TypeScript
- 特点：
  - 自动化网页搜索、内容抓取与推理，循环执行"搜索-阅读-推理"直到找到答案或超出token预算
  - 专注于精准、快速的深度问答，适合需要多步推理和信息整合的复杂问题
  - 支持本地LLM（如Ollama、LMStudio）和OpenAI兼容API，灵活切换推理后端
  - 提供官方UI（search.jina.ai）和API，便于集成到生产环境
  - 支持Docker一键部署，易于本地化和私有化部署
  - 丰富的API接口，支持流式输出和结构化结果
  - Apache 2.0 许可证
- 开源时间：2025年1月

#### [local-deep-researcher](https://github.com/langchain-ai/local-deep-researcher) - LangChain AI
- ⭐ 9.4k+ stars
- 开发语言：Python
- 特点：
  - 全本地化Web研究与报告生成助手，所有数据和推理均可在本地完成，保护隐私
  - 支持Ollama、LMStudio等本地LLM，兼容多种模型
  - 自动生成搜索查询、抓取网页、摘要整合、反思知识缺口，并多轮迭代补全
  - 最终输出带引用的Markdown格式研究报告，适合学术和专业场景
  - 支持自定义模型、搜索工具和迭代轮数，灵活适配不同需求
  - 提供详细的环境变量配置和视频教程，易于上手
  - MIT许可证
- 开源时间：2024年12月

#### [DeepGit](https://github.com/zamalali/DeepGit) - 个人项目
- ⭐ 917+ stars
- 开发语言：Python
- 特点：
  - 帮助发现最佳GitHub仓库的研究助手
  - 代码仓库深度分析和理解
  - 智能代码推荐和重构建议
  - 项目依赖分析和优化建议
  - 基于Langgraph的智能工作流
  - 支持多维度ColBERT v2嵌入
  - 智能硬件过滤功能
  - 提供轻量级版本（DeepGit-lite）
  - 支持混合密集检索和交叉编码器重排序
  - 提供在线演示（Vercel部署）
- 开源时间：2024年12月

#### [Open Deep Research](https://github.com/langchain-ai/open_deep_research) - LangChain AI
- ⭐ 12.7k+ stars
- 开发语言：Python
- 特点：
  - 基于LangChain的深度研究框架
  - 支持多步骤推理和知识整合
  - 提供研究流程自动化工具
  - 支持自定义研究策略
  - 提供工作流和多智能体两种实现方式
  - 支持本地化部署和定制化开发
  - 完整的开发环境配置支持
  - 仓库已归档（不再维护）
- 开源时间：2024年11月

#### [BettaFish](https://github.com/666ghj/BettaFish) - 666ghj
- ⭐ 42.3k+ stars
- 开发语言：Python
- 特点：
  - 人人可用的多Agent舆情分析助手
  - 打破信息茧房，还原舆情原貌
  - 预测未来走向，辅助决策
  - 从0实现，不依赖任何框架
  - 面向中文社交媒体与舆情数据的深度分析
- 开源时间：2024年7月

#### [storm](https://github.com/stanford-oval/storm) - Stanford OVAL
- ⭐ 31.5k+ stars
- 开发语言：Python
- 特点：
  - 基于LLM的知识整理系统
  - 研究主题并生成带引用的类维基百科长文
  - 多视角引导提问与模拟多视角对话
  - 联网搜索以收集和验证信息
  - Co-STORM模式支持人机协作知识整理
  - MIT许可证
- 开源时间：2024年4月

#### [gpt-researcher](https://github.com/assafelovic/gpt-researcher) - assafelovic
- ⭐ 29.8k+ stars
- 开发语言：Python
- 特点：
  - 基于LLM的自主智能体，自动进行本地和Web深度研究
  - 通过多轮搜索、抓取、推理，生成带引用的长篇研究报告
  - 支持多种模型和API（OpenAI、Anthropic等），可自定义推理后端
  - 支持本地知识库、流式输出、结构化结果
  - 适合学术、市场、技术等多场景的深度信息整合
  - Apache 2.0 许可证
- 开源时间：2023年5月

### 智能体技能

#### [hyperresearch](https://github.com/jordan-gibbs/hyperresearch) - jordan-gibbs
- ⭐ 3.7k+ stars
- 开发语言：Python
- 特点：
  - 面向Claude Code和OpenAI Codex的深度研究技能与运行框架
  - 分层自适应的16步流水线，产出带完整来源溯源的对抗式审计报告
  - 在DeepResearch-Bench RACE排行榜上领先（内部基准）
  - 每篇读过的来源都会沉淀到可检索的持久资料库，越用越聪明
  - 单次研究目标250+来源，支持引文追踪和缺口补全抓取
  - 发布前逐条核验引用，独立审计合并转载来源
  - MIT许可证
- 开源时间：2026年4月

#### [DeepPaperNote](https://github.com/917Dhj/DeepPaperNote) - 917Dhj
- ⭐ 1.1k+ stars
- 开发语言：Python
- 特点：
  - 精读单篇论文并生成高质量Obsidian风格研究笔记的智能体技能
  - 支持Claude Code、Codex、Cursor、Copilot、Gemini CLI等
  - 将论文转化为结构化、可链接的长期知识库笔记
  - MIT许可证
- 开源时间：2026年3月

#### [x-research-skill](https://github.com/rohunvora/x-research-skill) - rohunvora
- ⭐ 1.2k+ stars
- 开发语言：TypeScript
- 特点：
  - 面向Claude Code和OpenClaw的X/Twitter研究技能
  - 在X上进行智能体搜索、线程追踪和深度挖掘
  - 输出带来源的简报，而非原始链接堆砌
- 开源时间：2026年2月

#### [last30days-skill](https://github.com/mvanhorn/last30days-skill) - mvanhorn
- ⭐ 63.2k+ stars
- 开发语言：Python
- 特点：
  - AI智能体技能，跨Reddit、X、YouTube、HN、Polymarket、GitHub、arXiv等平台研究任意话题
  - 由点赞、转发和真金白银投票（而非编辑）排序的智能体搜索引擎
  - 多源并行搜索，按互动量排序并合并跨源同一事件
  - AI智能体评审综合成一份有依据、带引用的简报
  - 免费源零配置，X、TikTok、LinkedIn等自带密钥
  - 支持Claude Code、Codex、Cursor、Copilot、Gemini CLI、OpenClaw等50+技能宿主
  - MIT许可证
- 开源时间：2026年1月

#### [Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills) - Weizhena
- ⭐ 2.3k+ stars
- 开发语言：Python
- 特点：
  - 面向Claude Code、OpenCode和Codex的结构化深度研究工作流技能
  - 两阶段研究：可扩展大纲生成与深度调查
  - 人在回路设计，每个阶段都可精确控制
  - 支持学术、技术、市场和尽职调查研究
  - 提供中英文技能版本
  - MIT许可证
- 开源时间：2025年12月

#### [claude-deep-research-skill](https://github.com/199-biotechnologies/claude-deep-research-skill) - 199 Biotechnologies
- ⭐ 1.2k+ stars
- 开发语言：Python
- 特点：
  - 面向Claude Code的企业级深度研究技能
  - 8阶段流水线：范围界定、规划、检索、三角验证、大纲细化、综合、批判、精炼与打包
  - 带引用的报告与来源可信度评分
  - 聚合Brave、Serper、Exa、Jina、Firecrawl等多搜索源
  - 四种研究模式：Quick、Standard、Deep和UltraDeep
  - 自动化验证与批判回路
- 开源时间：2025年11月

### 基准与评估

#### [Vision-DeepResearch](https://github.com/Osilly/Vision-DeepResearch) - Osilly
- ⭐ 685+ stars
- 开发语言：Python
- 特点：
  - 多模态深度研究MLLM与基准（ICML 2026 & EMNLP 2026）
  - 首个长程多模态深度研究MLLM
  - 将推理轮数扩展到数十轮、搜索引擎交互扩展到数百次
  - 附带多模态深度研究基准
  - MIT许可证
- 开源时间：2026年1月

#### [Dr. Bench](https://github.com/EVIGBYEN/DrBench) - EVIGBYEN
- ⭐ 8+ stars
- 开发语言：Jupyter Notebook
- 特点：
  - 面向深度研究智能体的多维度评估框架，覆盖从答案到报告
  - 包含10大领域、214个专家精选的高难度任务
  - 每个任务均配有手工构建的参考材料包
  - 综合语义质量、主题聚焦度和检索可信度等指标
  - 对深度研究智能体生成的长篇报告进行全面评估
  - 2025年arXiv预印本（arXiv:2510.02190），由上海人工智能实验室及合作高校发布
- 开源时间：2025年10月

#### [BrowseComp-Plus](https://github.com/texttron/BrowseComp-Plus) - texttron
- ⭐ 365+ stars
- 开发语言：Python
- 特点：
  - 面向深度研究系统评测的基准，基于约10万篇人工校验文档的固定语料库
  - 隔离检索器与LLM智能体的影响，实现公平、透明、可复现的对比
  - 查询源自OpenAI BrowseComp的推理密集型问题
  - 在Hugging Face提供官方数据集和排行榜
  - MIT许可证
- 开源时间：2025年8月

#### [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) - Ayanami0730
- ⭐ 836+ stars
- 开发语言：Python
- 特点：
  - 面向深度研究智能体的综合基准
  - 通过RACE（报告质量）和FACT（引用准确性）框架评估报告生成
  - 在Hugging Face提供官方数据集和排行榜
  - arXiv:2506.11763
- 开源时间：2025年6月

### 搜索与应用

#### [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) - 中国人民大学DataLab
- ⭐ 4.7k+ stars
- 开发语言：Python
- 特点：
  - 首个面向自主数据科学的智能体LLM
  - 你的AI数据分析师：自动分析大规模数据
  - 一键生成专业分析报告
  - 端到端完成数据理解、分析与报告撰写
- 开源时间：2025年10月

#### [SurveyX](https://github.com/IAAR-Shanghai/SurveyX) - IAAR-Shanghai
- ⭐ 990+ stars
- 开发语言：TeX
- 特点：
  - 学术综述论文生成系统
  - 从主题出发自动完成文献整理与综述写作
  - 基于TeX的论文输出
- 开源时间：2025年2月

#### [Vane (原Perplexica)](https://github.com/ItzCrazyKns/Vane) - ItzCrazyKns
- ⭐ 36.9k+ stars
- 开发语言：TypeScript
- 特点：
  - AI驱动的问答引擎，原名Perplexica
  - Perplexity AI的开源替代方案
  - 结合LLM与基于SearxNG的网页搜索，支持多家服务商
  - 带引用的回答和聚焦研究模式
  - 可自托管、注重隐私，支持本地LLM
  - MIT许可证
- 开源时间：2024年4月

#### [morphic](https://github.com/miurla/morphic) - miurla
- ⭐ 9.1k+ stars
- 开发语言：TypeScript
- 特点：
  - 带生成式UI的AI搜索引擎
  - 以流式方式输出带来源的答案，而非链接列表
  - 支持多种AI模型和搜索提供商
  - Apache 2.0 许可证
- 开源时间：2024年4月

## 贡献指南

欢迎提交 Pull Request 来添加新的项目。请确保：

1. 项目是开源的
2. 提供项目的基本信息（名称、链接、简介、特点等）
3. 将项目放入对应分类，并按时间顺序排列
4. 同时提供中英文描述

## 许可证

本项目采用 [MIT 许可证](LICENSE)。