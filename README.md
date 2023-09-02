# awesome-semantickernel
 Awesome list of tools and projects with the awesome semantic kernel framework

 > Curated list of tools and projects using semantic kernel.

Semantic kernel is an amazing framework to get LLM projects done in a matter of no time and the ecosystem is growing fast. Here is an attempt to keep track of the initiatives around semantic kernel.

Contributions welcome. Add links through pull requests or create an issue to start a discussion. Please read the [contribution guidelines](contribution.md) before contributing.

## Table of Contents

- [Awesome semantickernel ](#-awesome-semantickernel--)
  - [Table of Contents](#table-of-contents)
  - [Semantickernel Framework](#semantickernel-framework)
  - [Plugins](#plugins)
  - [Open Source Projects](#open-source-projects)
  - [Learn](#learn)
    - [Notebooks](#notebooks)
    - [Videos](#videos)
    - [Articles](#articles)
  - [Alternatives](#alternatives)
  - [Complement to this list](#complement-to-this-list)

## Semantickernel Framework
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): the original  ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social) 
- [Concepts](https://learn.microsoft.com/en-us/semantic-kernel/overview/): Semantic Kernel concepts doc 
- [Discord discussion](https://aka.ms/SKDiscord)
- [Semantic Kernel Blog](https://devblogs.microsoft.com/semantic-kernel/): The Official Semantic Kernel blog 
- [Semantic Kernel starter](https://github.com/microsoft/semantic-kernel-starters): Starter Projects for Semantic Kernel
- [VisualStudio Code Tool](https://marketplace.visualstudio.com/items?itemName=ms-semantic-kernel.semantic-kernel): Visual Code Studio Semantic Kernel Extension
- [OSSInsight.io](https://ossinsight.io/analyze/microsoft/semantic-kernel?vs=langchain-ai%2Flangchain#overview)
- [gosk](https://github.com/mfmayer/gosk) Go Semantic Kernel (gosk) adapts Microsoft's Semantic Kernel (C#, Python) to provide OpenAI API integration for Golang developers
- [Semantic Kernel vs LangChain](https://github.com/formulahendry/semantic-kernel-vs-langchain) Compare Semantic Kernel and LangChai
- [Explore the Power of AI with SKPlayground](https://skplayground.dev/)

## Plugins
Plugins are at the heart of unlocking more potential with your [Semantic Kernel](https://github.com/microsoft/semantic-kernel) applications. They allow you to connect to external data sources and give large language models tools to be able to interact with native functions and API services.

If you want to try out your plugins and you do not have a ChatGPT plus subscription or are off the waitlist, you can test this directly **for free** using the Semantic Kernel!

See [this tutorial doc](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/chatgpt-plugins) or watch the [video](https://youtu.be/W_xF8PcdT78) for how to get set up.

**Why:** Microsoft is standardizing around the [plugin architecture](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/plugins?tabs=Csharp) for all of its internal AI copilots
and encourage developers to use them for their own applications. This hackathon serves to jumpstart a larger plugin ecosystem that is valuable to the broader community.

**How:** Follow the getting started guides for creating a plugin
- **C#** - [(Video)](https://youtu.be/T7XLn11rpYI) | [(Repo) Semantic Kernel ChatGPT plugin starter](https://github.com/microsoft/semantic-kernel-starters/tree/main/sk-csharp-chatgpt-plugin)
- **Python** - [(Video)](https://youtu.be/_4HZCdd3OxI) | [(Repo) Semantic Kernel Python Flask (and plugin) Starter](https://github.com/microsoft/semantic-kernel-starters/tree/main/sk-python-flask)

- [NL2EF](https://github.com/anthonypuppo/sk-nl2ef-plugin) A Semantic Kernel plugin designed to be a drop-in service that can expose an existing database to be queried via natural language
- [Packages, Examples and Demo code for Semantic Kernel](https://github.com/thinktecture/SemanticKernel)
- [sk-ethereumtx-plugin](https://github.com/sustia-llc/sk-ethereumtx-plugin) Semantic Kernel ChatGPT plugin for Ethereum Txs
- [Webscraper AIplugin](https://github.com/craigomatic/webscraper-aiplugin): AI Plugin that can be used to scrape useful information from a given URL
- [teams-bot-semantic-kernel](https://github.com/formulahendry/teams-bot-semantic-kernel) A Teams Bot app integrated with Semantic Kernel and its Microsoft Graph Plugin
- [EmbedElite marketplace](https://github.com/embedelite/sk-hackathon)This project is creating a plugin for the EmbedElite marketplace for the SK Hackathon. The Sementic Kernel plugin facilitates fetching ready-made premium context based on embeddings via an API


## Open Source Projects
- [Copilot Chat Sample Application](https://github.com/microsoft/chat-copilot):This is an enriched intelligence app, with multiple dynamic components including command messages, user intent, and memories
- [Index and query any data using LLM and natural language](https://github.com/microsoft/semantic-memory):Semantic Memory is an open-source library and service specializing in the efficient indexing of datasets through custom continuous data pipelines
- [Conversational Speaker](https://github.com/microsoft/conversational-speaker): uses a Raspberry Pi (or desktop) to enable spoken conversation with OpenAI large language models. This implementation listens to speech, processes the conversation through the OpenAI service, and responds back.
- [SolidWorks-Copilot](https://github.com/weianweigan/SolidWorks-Copilot) : Your SolidWorks Copoilt based on LLM(ChatGPT) and semantical kernel
- [Email-Copilot](https://github.com/jogendrasinghgurjar/email-copilot): Email-copilot for Outlook aims to revolutionize email management by leveraging natural language processing to streamline drafting, responding, and organizing emails
- [SS.SemanticKernel.Extensions](https://github.com/chenrensong/SS.SemanticKernel.Extensions):  This extension enables you to generate text embeddings with a semantic-based kernel function.
- [A port of the Python example that answers questions about 2022 Winter Olympics](https://github.com/afederici75/SKWinterOlympics)
- [Fantasy Copilot](https://github.com/Richasy/FantasyCopilot): Fantasy Copilot integrates Open AI and Azure's AI services, dedicated to building a personal assistant tool with a large language model as the core and high scalability 
- [sk-ingest](https://github.com/craigomatic/sk-ingest): Small library to make it easier to BYO data for use with Semantic Kernel and LLMs 
- [sk-classifier](https://github.com/craigomatic/sk-classifier): This small sample project shows how to perform basic classification on a series on prompts, against a pre-defined series of classifications using Semantic Kernel
- [Using Semantic Kernel to Summarize Youtube Videos](https://github.com/RogerBarreto/sk-youtube-summarizer)
- [semantic-kernel-LLamaSharp](https://github.com/xbotter/semantic-kernel-LLamaSharp) use LLamaSharp to implement the Completion and Embedding interfaces of the semantic kernel
- [semantic-kernel-ERNIE-Bot](https://github.com/custouch/semantic-kernel-ERNIE-Bot): Semantic Kernel 集成文心千帆
- [Elsa.SemanticKernel](https://github.com/rysweet/Elsa.SemanticKernel): SemanticKernel Activity Provider for Elsa Workflows
- [Write a blog using Semantic Kernel](https://github.com/devedium/WriteABlog)
- [Chat with your Enterprise Data: powered by Azure OpenAI/ChatGPT, Cognitive Search, and Bot Service](https://github.com/ronikurnia1/gpt-azure-botservice)
- [Semantic Kernel Sidecar](https://github.com/raykao/semantic-kernel-sidecar) About A prototype for an abstracted Sidecar Process that runs/abstracts Semantic Kernel via HTTP/gRPC
- [LangChain](https://github.com/tryAGI/LangChain): C# implementation of LangChain
- [sk-researcher](https://github.com/craigomatic/sk-researcher): Using Semantic Kernel to power a research agent that will work on your behalf to research a topic
- [semantic-kernel-ecom](https://github.com/alexcalabrese/semantic-kernel-ecom) AI-Powered eShopOnWeb E-commerce using Semantic Kernel
- [A Teams Bot app integrated with Semantic Kernel and its Microsoft Graph Plugin](https://github.com/formulahendry/teams-bot-semantic-kernel)
- [azure-openai-dev-skills-orchestrator](https://github.com/microsoft/azure-openai-dev-skills-orchestrator) Build a Virtual AI Dev Team using Semantic Kernel Skills
- [Semantic Kernel From Config](https://github.com/matthewbolanos/semantic-kernel-from-config) Provides an example of how you could extend Semantic Kernel to support config files for agents and plugins
- [GPTMeetingAgent](https://github.com/NetCoreApps/GPTMeetingAgent) A pattern for GPT Agent integration with ServiceStack services
- [SemanticKernel.PowerFx](https://github.com/jorisdg/SemanticKernel.PowerFx) Add low-code skills to Semantic Kernel using Power Fx
- [SemanticNativeFunctions](https://github.com/RobertEichenseer/OpenAI.SemanticNativeFunctions) Chaining native & semantic functions using MS Semantic Kernel


## Learn

### Notebooks
- [A collection of C# notebooks to get you started with Semantic Kernel quickly](https://github.com/johnmaeda/SK-Recipes)
- [Intelligent app workshop](https://github.com/Azure/intelligent-app-workshop): This is an envisioning workshop, based on Microsoft's Copilot stack, to rethink user experience, architecture, and app development by leveraging the intelligence of foundation models
- [Project Miyagi - Financial coach](https://github.com/Azure-Samples/miyagi): showcasing AI-first application architectures and generative AI capabilities with nascent design patterns to embed intelligence. A Hyper-personalized agent powered by SoTA foundation models and event-driven architecture
- [Tutorial: ChatGPT + Enterprise data with Semantic Kernel, OpenAI and Azure Cognitive Search](https://github.com/Azure-Samples/azure-search-openai-demo-csharp/)
- [Learn Azure OpenAI Service with .NET](https://github.com/kinfey/dotNETOAIBooks): This is a Azure OpenAI book for .NET Developer
- [MSFabricCopilotWorkshop](https://github.com/kinfey/MSFabricCopilotWorkshop) : Building Microsoft Fabric Copilot App Workshop
- [Semantic Kernel OpenAPI Skill Sample Project](https://github.com/mbenachour/semantic-kernel-course) This is a sample project to demonstrate the Semantic Kernel OpenAPI skill. It consists of a clothing API, which is a Swagger API, and a Copilot chat app.
- [openai-sk-demos](https://github.com/msalemor/openai-sk-demos) Semantic Kernel Demos
- [SemanticKernelLearningLab](https://github.com/walidamro-msft/SemanticKernelLearningLab) This is a lab to learn Semantic Kernel and Azure Open AI Services
- [Semantic-Kernel-Workshop](https://github.com/jogendrasinghgurjar/Semantic-Kernel-Workshop)

### Videos
- [A Lightweight SDK for Integrating AI Models and Plugins](https://thedataexchange.media/semantic-kernel/amp/)

### Articles
- [Empowering AI with Semantic Kernel Planners for Seamless Orchestration](https://medium.com/@akshaykokane09/empowering-ai-with-semantic-kernel-planners-for-seamless-orchestration-1c7ad35f2337)
- [Unleashing the Power of Semantic Kernel and Azure Cognitive Search: A Step-by-Step Guide to Building Your Own ChatGPT-like App with Internal Data! — Part 1](https://medium.com/@akshaykokane09/how-to-build-custom-chatgpt-with-semantic-kernel-and-azure-cognitive-search-ef899afba0b9)
- [Unleashing the Power of Semantic Kernel and Azure Cognitive Search: A Step-by-Step Guide to Building Your Own ChatGPT-like App with Internal Data!— Part 2](https://medium.com/@akshaykokane09/how-to-build-chatgpt-like-app-with-semantic-kernel-and-azure-cognitive-search-on-internal-data-814e4694decb)
- [Semantic Kernel Planner 101](https://blog.baeke.info/2023/06/01/semantic-kernel-planner-101/)
- [Running Large Language Models locally – Your own ChatGPT-like AI in C#](https://blog.maartenballiauw.be/post/2023/06/15/running-large-language-models-locally-your-own-chatgpt-like-ai-in-csharp.html)
- [GUEST POST: Getting Started with Semantic Kernel for LangChain users](https://devblogs.microsoft.com/semantic-kernel/getting-started-with-semantic-kernel-for-langchain-users/)
- [Create Semantic Kernel code & skills to build AI-powered apps with .NET](https://labs.thinktecture.com/create-semantic-kernel-code-skills-to-build-ai-powered-apps-with-net/)
- [Using (Azure) Open AI Models with Semantic Kernel behind a reverse proxy](https://labs.thinktecture.com/using-azure-open-ai-models-with-semantic-kernel-behind-a-proxy/)

## Complement to this list

- [Open LLMs](https://github.com/eugeneyan/open-llms): A list of open LLMs available for commercial use ![GitHub Repo stars](https://img.shields.io/github/stars/eugeneyan/open-llms?style=social)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM): Awesome-LLM: a curated list of Large Language Model resources. ![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/Awesome-LLM?style=social)
- [LLaMA Cult and More](https://github.com/shm007g/LLaMA-Cult-and-More): Keeping Track of Affordable LLMs, 🦙 Cult and More ![GitHub Repo stars](https://img.shields.io/github/stars/shm007g/LLaMA-Cult-and-More?style=social)

## Known Users


## Stargazers over time

[![Stargazers over time](https://starchart.cc/microsoft/semantic-kernel.svg)](https://starchart.cc/microsoft/semantic-kernel)


