# Awesome Azure OpenAI & Copilot [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[<img src="logo.svg" align="right" width="70">](https://www.microsoft.com/en-us/ai)

A curated list of Microsoft Azure OpenAI & Copilot ecosystem resources — including services, frameworks, agent platforms, evaluation tooling, and reference architectures — for building secure, production-grade generative and agentic AI applications.

## Contents
- [Azure OpenAI Overview](#azure-openai-overview)
- [LLM Frameworks](#llm-frameworks)
- [Prompt Tooling](#prompt-tooling)
- [Agent Frameworks](#agent-frameworks)
- [Deep Learning](#deep-learning)
- [Risk & LLMOps](#risk--llmops)
- [Data Processing](#data-processing)
- [Developer Tooling](#developer-tooling)
- [Microsoft Copilot Products](#microsoft-copilot-products)
- [Agent Development](#agent-development)
- [Copilot Development](#copilot-development)
- [Azure AI Search](#azure-ai-search)
- [Azure AI Services](#azure-ai-services)
- [Microsoft Research](#microsoft-research)
- [Azure OpenAI Application](#azure-openai-application)
- [Azure OpenAI Accelerator & Samples](#azure-openai-accelerator--samples)
- [Use Case & Architecture References](#use-case--architecture-references)

---

## Azure OpenAI Overview

- [Abuse Monitoring](https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy) - ✍️Data handling and retention policy for abuse detection in Azure OpenAI.
- [OpenAI Models](https://platform.openai.com/docs/models) - ✍️Catalog of foundation and reasoning models available from OpenAI.
- [What is Azure OpenAI Service?](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/overview) - ✍️Overview of Azure-hosted OpenAI capabilities, security and integration features.

## LLM Frameworks

- 🏛️[Artificial Intelligence Controller Interface (AICI)](https://github.com/microsoft/aici) - ✨Secure sandboxed controllers for structured real-time LLM output control.
- [Azure ML Prompt Flow](https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/overview-what-is-prompt-flow) - ✍️Visual designer for prompt orchestration and evaluation supporting Jinja templates.
- 🏛️[Kernel Memory](https://github.com/microsoft/kernel-memory) - ✨Service and plugins for scalable ingestion, hybrid embedding, and memory pipelines.
- 🏛️[Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - ✨Unified SDK (Semantic Kernel & AutoGen), Graph-based Workflows, DevUI, Built-in connectors, MCP + A2A + OpenAPI
- 🏛️[Semantic Kernel](https://github.com/microsoft/semantic-kernel) - ✨SDK for orchestrating AI services, functions, memory, and planners across languages.

## Prompt Tooling

- 🏛️[GenAIScript](https://github.com/microsoft/genaiscript) - ✨JavaScript framework to orchestrate LLM calls, tools, and data in unified scripts.
- 🏛️[guidance](https://github.com/microsoft/guidance) - ✨DSL for structured prompting and controlled generation with chain-of-thought patterns.
- 🏛️[LLMLingua](https://github.com/microsoft/LLMLingua) - ✨Prompt and KV-cache compression achieving substantial token reduction with minimal quality loss.
- 🏛️[LMOps](https://github.com/microsoft/LMOps) - ✨Toolkit for optimizing and evaluating prompt quality across multimodal scenarios.
- 🏛️[Prompt Engine](https://github.com/microsoft/prompt-engine) - ✨Utilities for systematic prompt authoring and experimentation (Python variant available).
- 🏛️[PromptBench](https://github.com/microsoft/promptbench) - ✨Unified framework for large language model prompt evaluation.
- 🏛️[Prompty](https://github.com/microsoft/prompty) - ✨Template language for prompt definition, execution metadata, and evaluation integration.
- 🏛️[SAMMO](https://github.com/microsoft/sammo) - ✨Framework for automated prompt optimization through search and evaluation loops.
- 🏛️[TypeChat](https://github.com/microsoft/TypeChat) - ✨Schema-driven natural language interfaces using strongly typed APIs.

## Agent Frameworks

- [AIOpsLab](https://www.microsoft.com/en-us/research/blog/aiopslab-building-ai-agents-for-autonomous-clouds/) - ✍️Research-driven AI agents for cloud incident analysis and root cause automation.
- 🏛️[Autogen](https://github.com/microsoft/autogen) - ✨Customizable multi-agent conversation and tool orchestration framework (community AG2 and Microsoft variants).
- 🏛️[ExACT](https://github.com/microsoft/ExACT) - ✨Adaptive retrieval and planning using interaction memory and Monte Carlo Tree Search.
- 🏛️[JARVIS](https://github.com/microsoft/JARVIS) - ✨Bridge connecting LLMs with specialized AI models for composite task execution.
- [Magentic-One](https://www.microsoft.com/en-us/research/articles/magentic-one-a-generalist-multi-agent-system-for-solving-complex-tasks/) - ✍️Generalist multi-agent system for complex multi-step automation.
- 🏛️[OmniParser](https://github.com/microsoft/OmniParser) - ✨Vision-based GUI parsing for screen-grounded agent control.
- 🏛️[qlib](https://github.com/microsoft/qlib) - ✨Quantitative finance platform integrating supervised, temporal, and reinforcement modeling.
- 🏛️[RD-Agent](https://github.com/microsoft/RD-Agent) - ✨Open-source R&D automation for structured experimentation workflows.
- 🏛️[Semantic Workbench](https://github.com/microsoft/semanticworkbench) - ✨Development environment for intelligent multi-agent scenario design and debugging.
- 🏛️[TaskWeaver](https://github.com/microsoft/TaskWeaver) - ✨Code-first natural language to executable workflow translation with rich data planning.
- 🏛️[TinyTroupe](https://github.com/microsoft/TinyTroupe) - ✨Multi-agent persona simulation for scenario exploration and insight generation.
- 🏛️[UFO](https://github.com/microsoft/UFO) - ✨UI-centric Windows interaction agent for system-level task automation.
- 🏬[Vanilla AI Agents](https://github.com/Azure-Samples/vanilla-aiagents) - ✨Minimal agent patterns without heavy framework abstractions.
- 🏛️[Windows Agent Arena](https://github.com/microsoft/WindowsAgentArena) - ✨Benchmarking and evaluation platform for multimodal Windows desktop agents.

## Deep Learning

- 🏛️[BitNet](https://github.com/microsoft/BitNet) - ✨Inference framework for ultra-low precision (1-bit) large language models.
- 🏛️[DeepSpeed](https://github.com/microsoft/DeepSpeed) - ✨Distributed training and inference optimization library featuring ZeRO optimizations.
- 🏛️[FLAML](https://github.com/microsoft/FLAML) - ✨Lightweight automation for model selection, tuning, and economical experimentation.
- 🏛️[UniLM (Foundation Models)](https://github.com/microsoft/unilm) - ✨Collection of large-scale pretrained architectures for multimodal and language tasks.

## Risk & LLMOps

- 🏛️[AI Central](https://github.com/microsoft/AICentral) - ✨Control plane for authenticated, resilient access to multiple OpenAI endpoints.
- [Azure AI Evaluation SDK](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/develop/evaluate-sdk) - ✍️Evaluation tooling for generative AI quality and safety metrics.
- 🌐[PyRIT](https://github.com/Azure/PyRIT) - ✨Risk identification toolkit targeting robustness, safety, and adversarial prompt detection.

## Data Processing

- 🏛️[markitdown](https://github.com/microsoft/markitdown) - ✨Conversion utility for office and structured documents to Markdown.
- [Microsoft Fabric](https://learn.microsoft.com/en-us/fabric/) - ✍️Unified platform combining data integration, engineering, warehousing, and BI.
- 🏛️[NLWeb](https://github.com/microsoft/NLWeb) - ✨Conversational interfaces for web data with MCP, Schema.org, and RSS support.
- 🏛️[Presidio](https://github.com/microsoft/presidio) - ✨Context-aware, pluggable PII detection and de-identification for text and images.

## Developer Tooling

- 🏛️[AI Toolkit for VS Code](https://github.com/microsoft/vscode-ai-toolkit) - ✨VS Code extension integrating local and cloud AI workflows.
- [AIShell](https://github.com/PowerShell/AIShell) - ✨Interactive PowerShell shell integrating AI-assisted command workflows.
- 🏛️[Data Formulator](https://github.com/microsoft/data-formulator) - ✨Iterative AI-assisted creation and transformation of data visualizations.
- 🏛️[GitHub Copilot Chat for VS Code](https://github.com/microsoft/vscode-copilot-chat) - ✨In-editor contextual multi-turn AI assistance.
- [GitHub Copilot CLI](https://github.com/github/copilot-cli) - ✨AI-powered coding assistance in your terminal.

---

## Microsoft Copilot Products

- [Clarity Copilot](https://learn.microsoft.com/en-us/clarity/copilot/clarity-copilot) - ✍️Analytics insights assistant for session telemetry.
- [Copilot Pages](https://techcommunity.microsoft.com/en-us/microsoft-365-copilot/announcing-copilot-pages-for-multiplayer-collaboration/ba-p/4242701) - ✍️Persistent collaborative canvas in Copilot chat.
- [Copilot Pro](https://support.microsoft.com/en-us/copilot-pro) - ✍️Premium Copilot features, model priority, and M365 integration.
- [Copilot Scenario Library](https://adoption.microsoft.com/en-us/copilot-scenario-library/) - ✍️Examples of Copilot business use cases.
- [Copilot Vision](https://www.microsoft.com/en-us/microsoft-copilot/blog/2024/12/05/copilot-vision-now-in-preview-a-new-way-to-browse/) - ✍️Edge experience for browsing with on-page visual grounding.
- [Copilot in Azure Quantum](https://learn.microsoft.com/en-us/azure/quantum/get-started-azure-quantum) - ✍️Quantum workload guidance with Copilot integration.
- [Copilot in Windows](https://learn.microsoft.com/en-us/copilot/copilot) - ✍️System-level AI integration in Windows.
- [Copilot+ PC](https://blogs.microsoft.com/blog/2024/05/20/introducing-copilot-pcs/) - ✍️Windows PCs with integrated NPUs for AI workloads.
- [Dynamics 365 Copilot](https://learn.microsoft.com/en-us/microsoft-cloud/dev/copilot/copilot-for-dynamics365) - ✍️Embedded generative assistance across Dynamics workloads.
- [Fabric Copilot](https://learn.microsoft.com/en-us/fabric/get-started/copilot-fabric-overview) - ✍️Copilot features for Fabric.
- [GitHub Copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot) - ✍️AI pair programming for code completion and chat.
- [Microsoft 365 Copilot](https://learn.microsoft.com/en-us/microsoft-365-copilot/microsoft-365-copilot-overview) - ✍️Cross-suite productivity AI assistance.
- [Microsoft 365 Copilot Chat](https://www.microsoft.com/en-us/microsoft-365/blog/2025/01/15/copilot-for-all-introducing-microsoft-365-copilot-chat/) - ✍️Chat experience (free tier) and pay-as-you-go agents.
- [Microsoft Copilot](https://copilot.microsoft.com/) - ✍️Web-based AI assistant (formerly Bing Chat Enterprise).
- [Microsoft Copilot for Azure](https://learn.microsoft.com/en-us/azure/copilot) - ✍️AI-assisted cloud operations for management and optimization.
- [Nuance DAX Copilot](https://www.nuance.com/healthcare/dragon-ai-clinical-solutions/dax-copilot.html) - ✍️Clinical documentation automation.
- [Power Apps AI Copilot](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/ai-overview) - Copilot feature in ✍️Power Apps AI.
- [Power Automate Copilot](https://learn.microsoft.com/en-us/power-automate/get-started-with-copilot) - Copilot feature in ✍️Power Automate cloud flows.
- [PowerBI Copilot](https://learn.microsoft.com/en-us/power-bi/create-reports/copilot-introduction) - ✍️Copilot features in Power BI.
- [Process Mining ingestion](https://learn.microsoft.com/en-us/power-automate/process-mining-copilot-in-ingestion) - ✍️Copilot feature for process mining ingestion in Power Automate.
- [Security Copilot](https://learn.microsoft.com/en-us/security-copilot/microsoft-security-copilot) - ✍️Security operations copiloting for defenders.
- [Team Copilot](https://www.microsoft.com/en-us/microsoft-365/blog/2024/05/21/new-agent-capabilities-in-microsoft-copilot-unlock-business-value/) - ✍️Meeting, collaboration, and project facilitation.
- [Viva Copilot](https://www.microsoft.com/en-us/microsoft-365/blog/2023/04/20/introducing-copilot-in-microsoft-viva-a-new-way-to-boost-employee-engagement-and-performance/) - ✍️Employee experience and engagement assistance.
- [Windows AI Foundry](https://developer.microsoft.com/en-us/windows/ai/) - ✍️Platform for local and hybrid AI app development (evolved from Windows Copilot Runtime).
- [Windows Copilot Runtime](https://blogs.windows.com/windowsdeveloper/2024/05/21/unlock-a-new-era-of-innovation-with-windows-copilot-runtime-and-copilot-pcs/) - ✍️The set of APIs powered by the 40+ on-device models.

## Agent Development
- 🏛️[AI Agents for Beginners - A Course](https://github.com/microsoft/ai-agents-for-beginners) - ✨Ten-lesson introduction to building AI agents for Beginners.
- [Agent builder & Plan designer in Power Apps](https://www.microsoft.com/en-us/power-platform/blog/power-apps/build-user-focused-intelligent-solutions-in-power-apps-start-with-a-plan/) - ✍️Design and configure intelligent solutions in Power Apps.
- [Agents in Power Platform](https://www.microsoft.com/en-us/power-platform/blog/2024/11/19/redefine-development-ai-first-innovation-with-agents-and-microsoft-copilot-in-power-platform/) - ✍️AI first no-code development with Copilot agents in Power Platform.
- [Combine Copilot Agents with Office Add-ins](https://devblogs.microsoft.com/microsoft365dev/office-addins-at-build-2025/) - ✍️Enhance Copilot with Office add-in actions for natural language interaction with Office documents.
- [Introducing Copilot Actions, new agents, Copilot Control System](https://www.microsoft.com/en-us/microsoft-365/blog/2024/11/19/introducing-copilot-actions-new-agents-and-tools-to-empower-it-teams/) - ✍️New agent capabilities and management tools for IT teams.
- [Microsoft 365 Agents SDK](https://devblogs.microsoft.com/microsoft365dev/introducing-the-microsoft-365-agents-sdk/) - ✍️The evolution of the Bot Framework to build AI Agents.
- [Microsoft Discovery](https://azure.microsoft.com/en-us/blog/transforming-rd-with-agentic-ai-introducing-microsoft-discovery/) - ✍️Graph-based scientific co-reasoning. Specialized discovery agents for conducting research.
- [Microsoft Entra Agent ID](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/announcing-microsoft-entra-agent-id-secure-and-manage-your-ai-agents/3827392) - ✍️Central registration and governance for organizational AI agents.
- [SharePoint Agent](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/ignite-2024-agents-in-sharepoint-now-in-general-availability/4298746) - ✍️Turn SharePoint sites and documents into interactive agents.

## Copilot Development
- [Azure AI Agent Service](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/introducing-azure-ai-agent-service/4298357) - ✍️Managed agent service in Azure AI Foundry.
- [Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-studio/what-is-ai-studio) - ✍️Portal and SDK for building generative AI solutions.
- [Community contributed samples for the Microsoft 365 Copilot](https://github.com/pnp/copilot-pro-dev-samples) - ✨Samples for extending Microsoft 365 Copilot features.
- [Copilot Studio March 2025 Update](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/whats-new-in-copilot-studio-march-2025/) - ✍️Added autonomous agents, deep reasoning, and MCP integration.
- [Copilot Studio Monthly updates](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/cs-content-type/monthly-updates/) - Copilot Studio news and features for the last month.
- [Copilot System Overview (video)](https://www.youtube.com/watch?v=E5g20qmeKpg) - Copilot Architecture explanation video.
- [Copilot Tuning](https://techcommunity.microsoft.com/blog/microsoft365copilotblog/introducing-microsoft-365-copilot-tuning/4414762) - ✍️Low-code model tuning and grounded agent creation.
- [Microsoft Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/) - ✍️Customization and orchestration environment (formerly Power Virtual Agents).

---

## Azure AI Search

- [Agentic retrieval in Azure AI Search](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/introducing-agentic-retrieval-in-azure-ai-search/4414677) - ✍️An automated query engine that creates and runs its own retrieval plan for relevant results to complex questions.
- [Azure AI Search Blog](https://azure.microsoft.com/en-us/blog/product/azure-ai-search) - ✍️News, best practices, and updates for Azure AI Search.
- 🏬[Azure AI Search Demos using Jupyter Notebook](https://github.com/Azure-Samples/rag-with-azure-ai-search-notebooks) - ✨Jupyter notebooks that demonstrate vector search, hybrid search, image search, RAG, and evaluation.
- [Azure AI Search Documentation](https://learn.microsoft.com/en-us/azure/search/) - ✍️Official product documentation and tutorials for Azure AI Search.
- 🏬[Azure AI Search Multimodal Sample](https://github.com/Azure-Samples/azure-ai-search-multimodal-sample) - ✨Demonstrates multimodal ingestion and retrieval patterns.
- 🏬[Azure AI Search Power Skills](https://github.com/Azure-Samples/azure-search-power-skills) - ✨Custom skills for Azure AI Search.
- [Azure AI Search Python Playground](https://github.com/farzad528/azure-ai-search-python-playground) - ✨A collection of Jupyter notebooks designed to explore the various capabilities of Azure AI Search.
- [Azure AI Search Samples](https://github.com/Azure-Samples/azureai-samples) - ✨Official sample code for Azure AI Search.
- 🏬[Azure AI Search OpenAI Purview Data Security Demo](https://github.com/Azure-Samples/azure-search-openai-demo-purviewdatasecurity) - ✨Demo integrating Azure Search, OpenAI, and Purview data security.
- [Azure AI Search: Outperforming vector search with hybrid retrieval and reranking](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/azure-cognitive-search-outperforming-vector-search-with-hybrid/ba-p/3929167) - ✍️Vector search with hybrid retrieval and reranking.
- [Document-level access control](https://learn.microsoft.com/en-us/azure/search/search-document-level-access-overview) - ✍️Document-level access helps restrict content visibility to authorized users, based on predefined access rules.
- [Integrated vectorization](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/integrated-vectorization-with-azure-openai-for-azure-ai-search/ba-p/4206836) - ✍️Automatically splits documents into chunks, creates embeddings with Azure OpenAI, maps them to an Azure AI Search index, and automates query vectorization.
- [Python samples for Azure AI Search](https://github.com/Azure-Samples/azure-search-python-samples) - ✨Python samples for Azure AI Search.
- [RAG-Knowledge](https://github.com/microsoft/RAG-Knowledge) - ✨Sample code for Data Preprocessing, Chunking, Index Design, Query Optimization.
- [Relevance scoring in hybrid search using Reciprocal Rank Fusion (RRF)](https://learn.microsoft.com/en-us/azure/search/hybrid-search-ranking) - ✍️Reciprocal Rank Fusion (RRF).
- [REST examples for Azure AI Search](https://github.com/Azure-Samples/azure-search-rest-samples) - ✨REST sample requests for search features.
- 🌐[Vector Search Sample Code](https://github.com/Azure/azure-search-vector-samples) - Sample code demonstrating Azure AI Search vector capabilities.

## Azure AI Services

- [Artificial Intelligence Architecture Design](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/) - ✍️Overview of Azure AI services and solution patterns.
- [Assistants API](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/azure-openai-service-announces-assistants-api-new-models-for/ba-p/4049940) - ✍️Code Interpreter, Function calling, Knowledge retrieval tool, and Threads.
- [Azure AI Content Understanding](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/announcing-azure-ai-content-understanding-transforming-multimodal-data-into-insi/4297196) - ✍️Azure AI Content Understanding: Transforming Multimodal Data into Insights.
- [Azure AI Foundry](https://ai.azure.com/) - ✍️Azure AI Foundry portal (formerly Azure AI Studio).
- [Azure AI Foundry Agent Service](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/announcing-general-availability-of-azure-ai-foundry-agent-service/4414352) - ✍️Azure AI Foundry Agent Service to create enterprise-grade, multi-agent systems.
- [Azure AI Foundry Fine Tuning](https://techcommunity.microsoft.com/blog/aiplatformblog/what%E2%80%99s-new-in-azure-ai-foundry-fine-tuning/4413873) - ✍️Reinforcement Fine-Tuning (RFT) with o4-mini.
- [Azure AI Foundry SDK](https://aka.ms/aifoundrysdk/reference) - ✍️Unified SDK with pre-built app templates.
- [Introducing Deep Research in Azure AI Foundry Agent Service](https://azure.microsoft.com/en-us/blog/introducing-deep-research-in-azure-ai-foundry-agent-service) - ✍️Deep Research capabilities in Azure AI Foundry Agent Service.
- [Responses API](https://devblogs.microsoft.com/foundry/introducing-new-tools-and-features-in-the-responses-api-in-azure-ai-foundry/) - ✍️Chat Completions API with the advanced tool-calling capabilities.
- [Weights & Biases with Azure](https://aka.ms/WBFineTuningPartnership) - Fine-Tuning with ✍️Weights & Biases and Azure OpenAI.

## Microsoft Research

- [AutoGen Studio](https://alphaxiv.org/abs/2408.15247) - ✍️A No-Code Developer Tool for Building and Debugging Multi-Agent Systems.
- [Azure AI Foundry Labs](https://ai.azure.com/labs/) - ✍️Research driven tools and experimental projects.
- [Data Formulator](https://alphaxiv.org/abs/2309.10094) - ✍️AI-powered Concept-driven Visualization Authoring.
- [Data Formulator 2](https://alphaxiv.org/abs/2408.16119) - ✍️Iterative Creation of Data Visualizations, with AI Transforming Data Along the Way.
- [Data Science Toolkit](https://www.ds-toolkit.com/) - ✍️Open-source collection of proven ML and AI implementation accelerators.
- [GraphRAG (by Microsoft)](https://alphaxiv.org/abs/2404.16130) - ✍️RAG with a graph-based approach to efficiently answer both specific and broad questions over large text.
- [Knowledge-Augmented Large Language Models for Personalized Contextual Query Suggestion](https://alphaxiv.org/abs/2311.06318) - ✍️K-LaMP. Contextual memory layer for LLM application.
- [Magentic-One](https://microsoft.github.io/autogen/stable/user-guide/agentchat-user-guide/magentic-one.html) - ✍️A Generalist Multi-Agent System for Solving Complex Tasks.
- [Magentic-UI](https://www.microsoft.com/en-us/research/blog/magentic-ui-an-experimental-human-centered-web-agent/) - ✍️Magentic-UI, built on Magentic-One, can browse the web, run Python and shell code, and process files.
- 🏛️[MarS - A Financial Market Simulation Engine Powered by Generative Foundation Model](https://github.com/microsoft/MarS) - Financial market simulation using generative AI.
- [MatterGen](https://www.microsoft.com/en-us/research/blog/mattergen-a-new-paradigm-of-materials-design-with-generative-ai/) - ✍️Generative model for inorganic materials design.
- [Microsoft AI Diagnostic Orchestrator (MAI-DxO)](https://alphaxiv.org/abs/2506.22405) - ✍️Multi-Agent System. Accurately diagnoses up to 85% of NEJM case proceedings, which is over four times the rate achieved by a group of experienced physicians.
- [Microsoft Office Copilot: Natural Language Commanding via Program Synthesis](https://alphaxiv.org/abs/2306.03460) - ✍️Semantic Interpreter, a natural language-friendly AI system for productivity software such as Microsoft Office that leverages large language models (LLMs) to execute user intent across application features.
- [NL2KQL](https://alphaxiv.org/abs/2404.02933) - ✍️From Natural Language to Kusto Query.
- [Optimizing Model Selection for Compound AI Systems](https://alphaxiv.org/abs/2502.14815) - ✍️A framework that automatically optimizes model selection for compound AI systems.
- [PromptWizard](https://www.microsoft.com/en-us/research/blog/promptwizard-the-future-of-prompt-optimization-through-feedback-driven-self-evolving-prompts/) - ✍️The prompt optimization through feedback-driven self-evolving prompts.
- [R&D-Agent-Quant](https://alphaxiv.org/abs/2505.15155) - ✍️R&D-Agent for Quantitative Finance, in short RD-Agent(Q), the first data-centric multi-agent framework designed to automate the full-stack research and development of quantitative strategies via coordinated factor-model co-optimization.
- [SpreadsheetLLM](https://alphaxiv.org/abs/2407.09025) - ✍️Introduces an efficient method to encode Excel sheets, outperforming previous approaches with 25 times fewer tokens.
- [VibeVoice](https://alphaxiv.org/abs/2508.19205) - ✍️Open-Source Text-to-Speech.

## Azure OpenAI Application

- 🏛️[AI Dev Gallery](https://github.com/microsoft/ai-dev-gallery) - ✨Windows application featuring interactive samples powered by local AI models.
- [An open-source template gallery](https://azure.github.io/awesome-azd/?tags=aicollection) - ✍️An open-source template gallery to get started with Azure.
- 🏬[ARGUS](https://github.com/Azure-Samples/ARGUS) - ✨Hybrid approach with Azure Document Intelligence combined and GPT4-Vision to get better results without any pre-training.
- 🌐[Azure AI CLI](https://github.com/Azure/azure-ai-cli) - ✨Interactive command-line tool for AI.
- 🏬[Azure Cosmos DB + OpenAI ChatGPT](https://github.com/AzureCosmosDB/cosmosdb-nosql-copilot) - ✨Integration sample with Cosmos DB and chat interface.
- 🏬[Azure OpenAI Embeddings QnA](https://github.com/Azure-Samples/azure-open-ai-embeddings-qna) - ✨Embeddings-powered Q&A sample.
- [Azure Video Indexer demo](https://aka.ms/viopenaidemo) - ✍️Azure Video Indexer demo integrating OpenAI.
- 🏬[C# ChatGPT + Enterprise Data](https://github.com/Azure-Samples/azure-search-openai-demo-csharp) - ✨C# reference app using Azure AI Search and Azure OpenAI.
- 🏬[Chat with Your Data Accelerator](https://github.com/Azure-Samples/chat-with-your-data-solution-accelerator) - ✨Accelerator for grounding chat on custom data sources.
- 🏬[ChatGPT + Enterprise Data RAG (Retrieval-Augmented Generation)](https://github.com/Azure-Samples/azure-search-openai-demo) - ✨Enterprise RAG sample integrating Azure OpenAI and Azure AI Search.
- 🏬[ChatGPT Plugin Quickstart using Python and FastAPI](https://github.com/Azure-Samples/openai-plugin-fastapi) - ✨Sample plugin implementation using Python and FastAPI.
- [eShopSupport](https://github.com/dotnet/eshopsupport) - ✨A reference .NET application using AI for a customer support ticketing system.
- [GPT-Azure-Search-Engine](https://github.com/pablomarin/GPT-Azure-Search-Engine) - ✨Integration of Azure Bot Service with LangChain.
- [Miyagi](https://github.com/Azure-Samples/miyagi) - ✨Integration demo spanning multiple LangChain libraries.
- [Prompt Buddy](https://github.com/stuartridout/promptbuddy) - ✨Share and upvote favorite AI prompts.
- [Simple ChatGPT UI Application](https://github.com/Azure/openai-at-scale) - ✨Scalable web UI pattern for Azure OpenAI chat.
- [Smart Components](https://github.com/dotnet-smartcomponents/smartcomponents) - ✨Experimental, end-to-end AI features for .NET apps.
- 🏬[VoiceRAG](https://github.com/Azure-Samples/aisearch-openai-rag-audio) - ✨Voice-enabled RAG using Azure AI Search and GPT-4o Realtime.

## Azure OpenAI Accelerator & Samples

- [AI Samples for .NET](https://github.com/dotnet/ai-samples) - ✨Official .NET AI samples (evaluation, integration).
- 🌐[AI-in-a-Box](https://github.com/Azure/AI-in-a-Box) - ✨AI-in-a-Box aims to provide an "Azure AI/ML Easy Button" for common scenarios.
- 🏬[AI-in-a-Box - Generative AI Bot Quickstart](https://github.com/Azure-Samples/gen-ai-bot-in-a-box) - ✨A template deploys a Generative AI Virtual Assistant using Azure OpenAI and Bot Framework. 
- 🌐[Azure-llm-fine-tuning](https://github.com/Azure/azure-llm-fine-tuning) - ✨SLM/LLM Fine-tuning on Azure.
- 🌐[Azure Accelerator Repos](https://github.com/orgs/Azure/repositories?q=accelerator+sort%3Astars) - ✨Collection of official Azure accelerators.
- 🏬[Azure AI Foundry Baseline](https://github.com/Azure-Samples/azure-ai-foundry-baseline) - ✨Baseline setup for Azure AI Foundry projects
- 👥[Azure-Cognitive-Search-Azure-OpenAI-Accelerator](https://github.com/MSUSAzureAccelerators/Azure-Cognitive-Search-Azure-OpenAI-Accelerator) - ✨Proof of Concept (POC) for a Generative AI Multi-Agent Architecture using Azure Services.
- 🌐[Azure Functions OpenAI Extension](https://github.com/Azure/azure-functions-openai-extension) - ✨OpenAI bindings for Azure Functions (C#).
- 🌐[Azure Multimodal AI + LLM Processing Accelerator](https://github.com/Azure/multimodal-ai-llm-processing-accelerator) - ✨Build multimodal data processing pipelines with Azure AI Services + LLMs.
- 🏬[Azure OpenAI cookbook](https://github.com/Azure-Samples/openai) - ✨The repository for all Azure OpenAI Samples complementing the OpenAI cookbook.
- 🏛️[Azure OpenAI Design Patterns](https://github.com/microsoft/azure-openai-design-patterns) - ✨A set of design patterns using the Azure OpenAI service.
- [Azure OpenAI Network Latency Test Script](https://github.com/wloryo/networkchatgpt/blob/dc76f2264ff8c2a83392e6ae9ee2aaa55ca86f0e/openai_network_latencytest_nocsv_pub_v1.1.py) - ✨Azure OpenAI Network Latency Test Script.
- 🏬[Azure OpenAI RAFT](https://github.com/Azure-Samples/azure-openai-raft ) - ✨RAFT Fine-Tuning for RAG Using Azure OpenAI.
- 🏬[Azure OpenAI RAG workshop](https://github.com/Azure-Samples/azure-openai-rag-workshop) - ✨RAG using LangChain.js and OpenAI. Hosted on Azure Static Web Apps and Azure Container Apps, with Azure AI Search as the vector database.
- 🏛️[Azure OpenAI workshop](https://github.com/microsoft/OpenAIWorkshop) - ✨Workshop materials to build intelligent solutions on Open AI.
- 🏬[Azure OpenAI with AKS by Terraform (simple version)](https://github.com/Azure-Samples/azure-openai-terraform-deployment-sample) - ✨Azure OpenAI with AKS by Terraform (simple version).
- 🏬[Azure SQL DB + AOAI](https://github.com/Azure-Samples/SQL-AI-samples) - ✨AI applications built on data from an Azure SQL Database.
- 🏬[Azure-Samples](https://github.com/Azure-Samples) - ✨Azure-Samples GitHub organization site.
- 🏬[Azure-Samples Accelerators](https://github.com/orgs/Azure-samples/repositories?q=accelerator+sort%3Astars) - ✨Community driven sample accelerators.
- 🏬[Azure-samples: Accelerator Collection](https://github.com/orgs/Azure-samples/repositories?q=quick+sort%3Astars) - ✨Accelerator Collection sorted by stars count.
- 🏛️[Build Your Own Copilot Solution Accelerator](https://github.com/microsoft/Build-your-own-copilot-Solution-Accelerator) - ✨Solution Accelerator to show how to build your own copilot.
- 👥[Conversational-Azure-OpenAI-Accelerator](https://github.com/MSUSAzureAccelerators/Conversational-Azure-OpenAI-Accelerator) - ✨Conversational AI solution accelerator using Azure OpenAI.
- 🏬[Create an Azure OpenAI, LangChain, ChromaDB, and Chainlit ChatGPT-like application in Azure Container Apps using Terraform](https://github.com/Azure-Samples/container-apps-openai/) - ✨ChatGPT-like application in Azure Container Apps using Terraform.
- 🏬[Design and Evaluation of RAG Solutions](https://github.com/Azure-Samples/Design-and-evaluation-of-RAG-solutions) - ✨Resources for designing and evaluating RAG solutions.
- 🏛️[Document generation solution accelerator](https://github.com/microsoft/document-generation-solution-accelerator) - ✨AI assistant for document generation.
- 🏬[Document Processing with Azure AI Samples](https://github.com/Azure-Samples/azure-ai-document-processing-samples) - ✨Document Intelligence plus generative enrichment examples.
- 🏬[Enterprise Logging](https://github.com/Azure-Samples/openai-python-enterprise-logging) - ✨Comprehensive logging of Azure OpenAI model execution.
- 🌐[Enterprise RAG Avatar](https://github.com/Azure/gpt-rag-avatar) - ✨GPT-RAG Avatar integrates Generative AI responses, real-time streaming into a dynamic avatar interface.
- 🏬[Evaluating a RAG Chat App](https://github.com/Azure-Samples/ai-rag-chat-evaluator) - ✨Tools for evaluation of RAG Chat Apps using Azure AI Evaluate SDK.
- 🏛️[Fabric notebooks for analyzing chat history stored in CosmosDB](https://github.com/microsoft/fabric-cosmosdb-chat-analytics) - ✨Fabric notebooks for analyzing chat history.
- 🏛️[Generic accelerator for Build your own copilot](https://github.com/microsoft/Generic-Build-your-own-copilot-Solution-Accelerator) - ✨Build your own copilot solution accelerator.
- 🌐[GPT RAG Ingestion](https://github.com/Azure/gpt-rag-ingestion) - ✨GPT-based RAG ingestion utilities.
- 🌐[GPT-RAG](https://github.com/Azure/GPT-RAG) - ✨Enterprise RAG solution accelerator.
- 🏛️[Microsoft AI Tour](https://github.com/microsoft/aitour-repo-principal-list) - ✨A session and workshop how to best leverage AI.
- 🏛️[Microsoft Copilot Studio Samples](https://github.com/microsoft/CopilotStudioSamples) - ✨Samples and artifacts for Microsoft Copilot Studio.
- [Microsoft.Extensions.AI](https://devblogs.microsoft.com/dotnet/introducing-microsoft-extensions-ai-preview/) - ✍️Unified C# abstractions for models, embeddings, and middleware.
- 👥[MSUS Azure Accelerators](https://github.com/MSUSAzureAccelerators) - ✨Partner accelerator implementations.
- 🏛️[Model Context Protocol Curriculum for Beginners](https://github.com/microsoft/mcp-for-beginners) - ✨Introductory MCP course.
- 🏬[OpenAI Chat Application with Microsoft Entra Authentication](https://github.com/Azure-Samples/openai-chat-app-entra-auth-builtin) - ✨Authenticated chat starter with Microsoft Entra ID.
- 🏛️[RAG for Azure Data](https://github.com/microsoft/AzureDataRetrievalAugmentedGenerationSamples) - ✨Retrieval Augmented Generation (RAG) for Azure Data.
- 🏛️[Semantic Kernel Cookbook](https://github.com/microsoft/SemanticKernelCookBook) - ✨Semantic Kernel Cookbook for beginners.
- 🌐[Setting up Azure OpenAI with Azure API Management](https://github.com/Azure/enterprise-azureai) - ✨Azure AI to your application developers in a secure & manageable way with Azure API Management.
- 🏬[Smart Load Balancing for Azure OpenAI](https://github.com/Azure-Samples/openai-aca-lb) - ✨Intelligent routing across multiple Azure OpenAI deployments.
- 🏬[Vector similarity search with Azure SQL & Azure OpenAI](https://github.com/Azure-Samples/azure-sql-db-openai) - ✨Samples on how to use Azure SQL database with Azure OpenAI.

## Use Case & Architecture References
- [AI Agent-Driven Auto Insurance Claims RAG Pipeline](https://techcommunity.microsoft.com/t5/azure-architecture-blog/exploring-ai-agent-driven-auto-insurance-claims-rag-pipeline/ba-p/4233779) - ✍️Agent-driven claims processing reference.
- [AI decision tree](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/strategy) - ✍️Selecting the most suitable tools and platforms for your generative and nongenerative AI use cases.
- [AI Feed](https://techcommunity.microsoft.com/t5/artificial-intelligence-and/ct-p/AI) - ✍️Azure AI news, events, and discussions.
- [AI gateway capabilities in Azure API Management](https://techcommunity.microsoft.com/blog/integrationsonazureblog/ai-gateway-enhancements-llm-policies-real-time-api-support-content-safety-and-mo/4409828) - ✍️Semantic Caching. Azure AI Content Safety. LLM policies (llm-token-limit, llm-emit-metric, llm-content-safety).
- [Azure AI Foundry Blog](https://techcommunity.microsoft.com/t5/ai-ai-platform-blog/bg-p/AIPlatformBlog) - ✍️Azure AI Foundry Blog for Azure AI news, events.
- [An Introduction to LLMOps](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/an-introduction-to-llmops-operationalizing-and-managing-large/ba-p/3910996) - ✍️Operationalizing and Managing Large Language Models using Azure ML.
- [Authentication and Authorization in Generative AI applications with Entra ID and Azure AI Search](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/authentication-and-authorization-in-generative-ai-applications/ba-p/4022277) - ✍️Authentication and Authorization in Generative AI applications with Entra ID and Azure AI Search.
- [Azure AI Services Landing Zone](https://github.com/FreddyAyala/AzureAIServicesLandingZone) - ✨Azure AI Landing Zone with Terraform.
- [Azure Command Companion](https://techcommunity.microsoft.com/t5/analytics-on-azure-blog/azure-command-companion/ba-p/4005044) - ✍️Azure CLI Command Generation to translate natural language into the appropriate Azure CLI commands.
- [Azure OpenAI and Call Center Modernization](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-openai-and-call-center-modernization/ba-p/4107070) - ✍️Azure OpenAI and Call use case to improve its customer service and reduce the cost and time of handling customer calls.
- [Azure OpenAI Best Practices Insights from Customer Journeys](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/azure-openai-best-practices-insights-from-customer-journeys/ba-p/4166943) - ✍️Best Practices for Azure OpenAI Resources.
- [Azure OpenAI chat baseline architecture](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/architecture/basic-openai-e2e-chat) - ✍️Designing your production enterprise chat applications.
- [Azure OpenAI Landing Zone reference architecture](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-openai-landing-zone-reference-architecture/ba-p/3882102) - ✍️Azure AI Services OpenAI Landing Zone is a reference architecture that integrates a variety of services to create a seamless infrastructure for running OpenAI workloads.
- [Baseline Agentic AI Systems Architecture](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/baseline-agentic-ai-systems-architecture/ba-p/4207137) - ✍️Baseline Agentic AI Systems Architecture to build multiple conversable agents system.
- [Baseline OpenAI end-to-end chat reference architecture](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat) - ✍️Azure AI Foundry chat reference architecture.
- [Build language model pipelines with memory](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/openai/guide/language-model-pipelines) - ✍️Build language model pipelines with memory.
- [Chat with your Azure DevOps data](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/chat-with-your-azure-devops-data/ba-p/4017784) - ✍️The solution leverages Azure DevOps CLI to periodically export ADO Work Items as JSON and store them in Azure Blob storage.
- [Check Your Facts and Try Again: Improving Large Language Models with External Knowledge and Automated Feedback](https://www.microsoft.com/en-us/research/group/deep-learning-group/articles/check-your-facts-and-try-again-improving-large-language-models-with-external-knowledge-and-automated-feedback/) - ✍️Improving Large Language Models with External Knowledge and Automated Feedback.
- [Designing and developing a RAG solution](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/rag/rag-solution-design-and-evaluation-guide) - ✍️Designing and developing a RAG application flow, RAG data pipeline flow.
- [Grounding LLMs](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/grounding-llms/ba-p/3843857) - ✍️Use-cases for Grounding & Retrieval-Augmented Generation (RAG).
- [How real-world businesses are transforming with AI](https://blogs.microsoft.com/blog/2024/11/12/how-real-world-businesses-are-transforming-with-ai/) - ✍️Collected over 200 examples of how organizations are leveraging Microsoft AI capabilities.
- [How to develop AI Apps and Agents in Azure – A Visual Guide](https://devblogs.microsoft.com/all-things-azure/how-to-develop-ai-apps-and-agents-in-azure-a-visual-guide/) - ✍️A Visual map to help you decide which Azure AI service is best for your use case.
- [Integrate private access to your Azure Open AI Chatbot](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/integrate-private-access-to-your-azure-open-ai-chatbot/ba-p/3994613) - ✍️Integrate private access to your Azure Open AI Chatbot.
- [Microsoft AI / Responsible AI](https://aka.ms/RAIResources) - ✍️Responsible AI resources from Microsoft.
- [NL to SQL Architecture Alternative](https://techcommunity.microsoft.com/t5/azure-architecture-blog/nl-to-sql-architecture-alternatives/ba-p/4136387) - ✍️LLM to dynamically generate SQL queries, execute those SQL queries.
- [Optimize Azure OpenAI Applications with Semantic Caching](https://techcommunity.microsoft.com/t5/azure-architecture-blog/optimize-azure-openai-applications-with-semantic-caching/ba-p/4106867) - ✍️Semantic cache pattern for latency and cost reduction.
- [Partner Resources: AI & ML Academy](https://microsoft.github.io/PartnerResources/skilling/ai-ml-academy) - ✍️Comprehensive learning resources for partners and developers.
- [Responsible AI Transparency Report](https://www.microsoft.com/en-us/corporate-responsibility/responsible-ai-transparency-report) - ✍️Responsible AI Transparency Report.
- [Retrieval Augmented Fine Tuning](https://techcommunity.microsoft.com/t5/ai-ai-platform-blog/retrieval-augmented-fine-tuning-use-gpt-4o-to-fine-tune-gpt-4o/ba-p/4248861) - ✍️RAFT: Combining the best parts of RAG and fine-tuning (SFT).
- [Revolutionize your Enterprise Data with ChatGPT](https://techcommunity.microsoft.com/t5/ai-applied-ai-blog/revolutionize-your-enterprise-data-with-chatgpt-next-gen-apps-w/ba-p/3762087) - ✍️Revolutionize your Enterprise Data with ChatGPT.
- [Safeguard and trustworthy generative AI applications](https://azure.microsoft.com/en-us/blog/announcing-new-tools-in-azure-ai-to-help-you-build-more-secure-and-trustworthy-generative-ai-applications/) - ✍️Announcing new tools in Azure AI to help you build more secure and trustworthy generative AI applications.
- [Security Best Practices for GenAI Applications (OpenAI) in Azure](https://techcommunity.microsoft.com/t5/azure-architecture-blog/security-best-practices-for-genai-applications-openai-in-azure/ba-p/4027885) - ✍️The best practices of security for GenAI applications in Azure.
- [Using Keyless Authentication with Azure OpenAI](https://techcommunity.microsoft.com/t5/microsoft-developer-community/using-keyless-authentication-with-azure-openai/ba-p/4111521) - ✍️Entra ID token-based access to Azure OpenAI.

---

## Footnotes 

### Emoji meanings in the list
- GitHub organizations: 🌐 [Azure](https://github.com/Azure) | 🏬 [Azure-samples](https://github.com/Azure-samples) | 🏛️ [Microsoft](https://github.com/microsoft) | 👥 Azure Accelerators
- ✍️ Blog post / Documentation / Paper
- ✨ GitHub repository

<!--
> npx awesome-lint README.md
-->
