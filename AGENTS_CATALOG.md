# Agent Catalog — 1003 Specialists

> **⚠️ Every agent listed below was authored by someone else.** This catalog is an index over an aggregation of 10 open-source projects. **Full credit goes to the original authors** named in the Source column of every row. See [ATTRIBUTION.md](ATTRIBUTION.md) for upstream links and licenses.

A plain-English reference for every agent in this collection. Each entry shows:
- **Agent name** (use this exact value as `subagent_type` when invoking via the Task tool)
- **What it does** (one-line summary)
- **Source** (which curated collection it came from — see attribution at end)

Agents are grouped by category for fast scanning. To invoke one, use Claude Code's Task tool with the agent's name.

## Table of Contents

- [AI / ML / LLM](#ai-ml-llm) — 51 agents
- [Architecture & Design](#architecture-and-design) — 91 agents
- [Backend Development](#backend-development) — 34 agents
- [Cloud & Infra](#cloud-and-infra) — 13 agents
- [Code Review & Quality](#code-review-and-quality) — 48 agents
- [Crypto / Blockchain / FinTech](#crypto-blockchain-fintech) — 2 agents
- [Data Analysis & Science](#data-analysis-and-science) — 9 agents
- [Data Engineering](#data-engineering) — 1 agents
- [Database](#database) — 23 agents
- [Design & UX](#design-and-ux) — 15 agents
- [Desktop / CLI](#desktop-cli) — 6 agents
- [DevOps & SRE](#devops-and-sre) — 33 agents
- [Documentation](#documentation) — 14 agents
- [Frontend Development](#frontend-development) — 25 agents
- [Game / Graphics / Embedded](#game-graphics-embedded) — 4 agents
- [Language Specialists](#language-specialists) — 7 agents
- [Marketing & Content](#marketing-and-content) — 25 agents
- [Mobile Development](#mobile-development) — 19 agents
- [Observability & Monitoring](#observability-and-monitoring) — 14 agents
- [Performance & Optimization](#performance-and-optimization) — 27 agents
- [Plugins & Tooling](#plugins-and-tooling) — 2 agents
- [Product & Business](#product-and-business) — 46 agents
- [Refactoring & Modernization](#refactoring-and-modernization) — 26 agents
- [Research & Analysis](#research-and-analysis) — 14 agents
- [Security & Compliance](#security-and-compliance) — 139 agents
- [Testing & QA](#testing-and-qa) — 51 agents
- [Workflow & Orchestration](#workflow-and-orchestration) — 22 agents
- [Other / Uncategorized](#other-uncategorized) — 242 agents

---

## AI / ML / LLM

_51 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `activecampaign-automation` | Automate ActiveCampaign tasks via Rube MCP (Composio): manage contacts, tags, list subscriptions, automation enrollment, and tasks. | davepoon |
| `agent-analytics` | Analytics your AI agent can actually use. | davepoon |
| `agent-expert` | Create and optimize specialized Claude Code agents. | davepoon |
| `agent-orchestration-context-manager` | Elite AI context engineering specialist mastering dynamic context management, vector databases, knowledge graphs, and intelligent memory systems. | wshobson |
| `arbitrage-bot` | Identify and execute cryptocurrency arbitrage opportunities across exchanges and DeFi protocols. | davepoon |
| `box-automation` | Automate Box cloud storage operations including file upload/download, search, folder management, sharing, collaborations, and metadata queries via Rube MCP (Composio). | davepoon |
| `brand-guidelines` | Applies Anthropic's official brand colors and typography to any sort of artifact that may benefit from having Anthropic's look-and-feel. | davepoon |
| `bullmq-expert` | Expert in BullMQ task queue library for Node.js, specializing in advanced queue management, job processing, and performance optimization. | 0xfurai |
| `customer-support` | Elite AI-powered customer support specialist mastering conversational AI, automated ticketing, sentiment analysis, and omnichannel support experiences. | wshobson |
| `distill` | > Synthesize wiki pages from related memories. | davepoon |
| `explain-equity-terms` | Activate for ANY equity, legal, or term sheet question related to startup investing or fundraising. | davepoon |
| `gallery-researcher` | >- Gallery search and inspiration agent. | wshobson |
| `gingiris-growth-playbooks` | Open-source growth playbooks for AI products, B2B SaaS, and developer tools. | davepoon |
| `gsd-ai-researcher` | Researches a chosen AI framework's official docs to produce implementation-ready guidance — best practices, syntax, core patterns, and pitfalls distilled for the specific use case. | davepoon |
| `gsd-domain-researcher` | Researches the business domain and real-world application context of the AI system being built. | davepoon |
| `gsd-framework-selector` | Presents an interactive decision matrix to surface the right AI/LLM framework for the user's specific use case. | davepoon |
| `gsd-roadmapper` | Creates project roadmaps with phase breakdown, requirement mapping, success criteria derivation, and coverage validation. | davepoon |
| `gsd:ai-integration-phase` | Generate AI design contract (AI-SPEC.md) for phases that involve building AI systems — framework selection, implementation guidance from official docs, and evaluation strategy argument-hint: "[phase n... | davepoon |
| `gsd:review` | Request cross-AI peer review of phase plans from external AI CLIs argument-hint: "--phase N [--gemini] [--claude] [--codex] [--opencode] [--qwen] [--cursor] [--all]" allowed-tools: - Read - Write - Ba... | davepoon |
| `hackathon-ai-strategist` | Expert guidance on hackathon strategy, AI solution ideation, and project evaluation. | davepoon |
| `hard-predict-future` | > Activate this agent for any future-oriented question that requires deep quantitative analysis, historical precedents, and structured scenario planning. | davepoon |
| `langchain-expert` | Expert in LangChain with focus on document processing, pipeline construction, and optimization. | 0xfurai |
| `llms-maintainer` | Generates and maintains llms.txt roadmap files for AI crawler navigation. | davepoon |
| `lobsterdomains` | Register ICANN domains with crypto payments (USDC/USDT/ETH/BTC) via API — built for AI agents | davepoon |
| `mcp-developer` | Use this agent when you need to build, debug, or optimize Model Context Protocol (MCP) servers and clients that connect AI systems to external tools and data sources. | VoltAgent |
| `meeting` | Convene a meeting of AI personas (3 to 10 participants) who debate a subject and reach a synthesis. | davepoon |
| `ml-data-expert` | Expert en Machine Learning et Data Science avec Python. | vijaythecoder |
| `ml-engineer` | Use this agent when building production ML systems requiring model training pipelines, model serving infrastructure, performance optimization, and automated retraining. | VoltAgent |
| `morning-ai` | AI news tracking skill that monitors 80+ entities across 6 free sources (Reddit, HN, GitHub, HuggingFace, arXiv, X/Twitter). | davepoon |
| `ocaml-expert` | Expert in OCaml programming, covering functional programming, type systems, and performance optimization | 0xfurai |
| `ops-ecom` | Shopify store command center. | davepoon |
| `ops-gtm` | Go-to-market strategy planner. | davepoon |
| `pressreleasesonline` | Draft and publish AI-powered press releases — submit a URL + notes, get a live release page instantly. | davepoon |
| `prompt-crafter` | >- Batch prompt writing agent. | wshobson |
| `python-pro` | Use this agent when you need to build type-safe, production-ready Python code for web APIs, system utilities, or complex applications requiring modern async patterns and extensive type coverage. | VoltAgent |
| `pytorch-expert` | Expert in PyTorch for building and optimizing deep learning models. | 0xfurai |
| `redis-expert` | Expert in Redis for in-memory data storage, caching, and real-time analytics. | 0xfurai |
| `resemble-detect` | Deepfake detection and media safety — detect AI-generated audio, images, video, and text, trace synthesis sources, apply watermarks, verify speaker identity, and analyze media intelligence using Resem... | davepoon |
| `scikit-learn-expert` | Master scikit-learn for machine learning, focusing on model selection, feature engineering, and hyperparameter tuning. | 0xfurai |
| `skyvern` | AI-powered browser automation — navigate sites, fill forms, extract structured data, log in with stored credentials, and build reusable multi-step workflows using natural language. | davepoon |
| `socialclaw` | Social media scheduling and publishing for AI agents. | davepoon |
| `sosa-governance` | Real-time SOSA governance enforcement — apply supervision policies, trust gradients, and capability boundaries to AI agent actions as they execute. | davepoon |
| `supabase-automation` | Automate Supabase database queries, table management, project administration, storage, edge functions, and SQL execution via Rube MCP (Composio). | davepoon |
| `team-configurator` | MUST BE USED to set up—or refresh—the AI development team for the current project. | vijaythecoder |
| `tensorflow-expert` | Expert in TensorFlow, specializing in developing, optimizing, and deploying machine learning models using TensorFlow framework. | 0xfurai |
| `terragrunt-expert` | Expert Terragrunt specialist mastering infrastructure orchestration, DRY configurations, and multi-environment deployments. | VoltAgent |
| `twitter-ai-influencer-manager` | Interact with Twitter around AI thought leaders and influencers. | davepoon |
| `ui-ux-master` | Expert UI/UX design agent with 10+ years of experience creating award-winning user experiences. | zhsama |
| `vector-database-engineer` | Expert in vector databases, embedding strategies, and semantic search implementation. | wshobson |
| `vector-db-expert` | Expert in Vector Databases, handling indexing, querying, and optimization of vector data. | 0xfurai |
| `visual-asset-generator` | Use this agent when you need to generate production-ready visual assets for a project — app icons, favicons, OG images, logos, wordmarks, or social media images. | VoltAgent |

## Architecture & Design

_91 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `ag2-architect` | AG2 architecture advisor that recommends agent patterns and orchestration strategies. | davepoon |
| `agent-architect` | Creates and manages project-specific agents | charles-adedotun |
| `ai-engineer` | Use this agent when architecting, implementing, or optimizing end-to-end AI systems—from model selection and training pipelines to production deployment and monitoring. | VoltAgent |
| `android-expert` | Expert in Android development, specializing in modern Android practices, optimizing performance, and ensuring robust application architecture. | 0xfurai |
| `angular-architect` | Use when architecting enterprise Angular 15+ applications with complex state management, optimizing RxJS patterns, designing micro-frontend systems, or solving performance and scalability challenges in large codebases. | VoltAgent |
| `angular-expert` | Write idiomatic Angular code with best practices, performance optimizations, and modern Angular features. | 0xfurai |
| `architect` | Architect agent. Reads orchestrator-output.md, AGENTS.md, and project-doc.md to produce a numbered step-by-step implementation plan. | wshobson |
| `architecture` | Architecture design skill with ADR records, system design checklists, scalability assessment, and architecture patterns | davepoon |
| `architecture-critic` | Reviews proposed target architectures and transformed code against modern best practice. | Anthropic Official |
| `astro-expert` | Expert in Astro with deep understanding of component architecture, content collections, and static site optimization. | 0xfurai |
| `azure-infra-engineer` | Use when designing, deploying, or managing Azure infrastructure with focus on network architecture, Entra ID integration, PowerShell automation, and Bicep IaC. | VoltAgent |
| `backend-architect` | Design RESTful APIs, microservice boundaries, and database schemas. | davepoon |
| `backend-developer` | Use this agent when building server-side APIs, microservices, and backend systems that require robust architecture, scalability planning, and production-ready implementation. | VoltAgent |
| `c4-component` | Expert C4 Component-level documentation specialist. | wshobson |
| `c4-container` | Expert C4 Container-level documentation specialist. | wshobson |
| `c4-context` | Expert C4 Context-level documentation specialist. | wshobson |
| `code-architect` | Designs feature architectures by analyzing existing codebase patterns and conventions, then providing comprehensive implementation blueprints with specific files to create/modify, component designs, d... | Anthropic Official |
| `code-explorer` | Deeply analyzes existing codebase features by tracing execution paths, mapping architecture layers, understanding patterns and abstractions, and documenting dependencies to inform new development | Anthropic Official |
| `csharp-developer` | Use this agent when building ASP.NET Core web APIs, cloud-native .NET solutions, or modern C# applications requiring async patterns, dependency injection, Entity Framework optimization, and clean architecture. | VoltAgent |
| `database-administrator` | Use this agent when optimizing database performance, implementing high-availability architectures, setting up disaster recovery, or managing database infrastructure for production systems. | VoltAgent |
| `database-design-database-architect` | Expert database architect specializing in data layer design from scratch, technology selection, schema modeling, and scalable database architectures. | wshobson |
| `database-optimization` | Database performance specialist focusing on query optimization, indexing strategies, schema design, connection pooling, and database monitoring. | davepoon |
| `design-system-architect` | Expert design system architect specializing in design tokens, component libraries, theming infrastructure, and scalable design operations. | wshobson |
| `dev-boss` | The Boss of the dev team. | davepoon |
| `directus-developer` | Build and customize Directus applications with extensions, hooks, and API integrations. | davepoon |
| `django-orm-expert` | Expert in Django ORM optimization, complex queries, and database performance. | vijaythecoder |
| `documentation-engineer` | Use this agent when you need to create, architect, or overhaul comprehensive documentation systems including API docs, tutorials, guides, and developer-friendly content that keeps pace with code changes. | VoltAgent |
| `documentation-generation-docs-architect` | Creates comprehensive technical documentation from existing codebases. | wshobson |
| `documentation-specialist` | MUST BE USED to craft or update project documentation. | vijaythecoder |
| `dotnet-architect` | Expert .NET backend architect specializing in C#, ASP.NET Core, Entity Framework, Dapper, and enterprise application patterns. | wshobson |
| `dotnet-core-expert` | Use when building .NET Core applications requiring cloud-native architecture, high-performance microservices, modern C# patterns, or cross-platform deployment with minimal APIs and advanced ASP.NET Core features. | VoltAgent |
| `drupal-developer` | Build and customize Drupal applications with custom modules, themes, and integrations. | davepoon |
| `elixir-expert` | Use this agent when you need to build fault-tolerant, concurrent systems leveraging OTP patterns, GenServer architectures, and Phoenix framework for real-time applications. | VoltAgent |
| `forja-dev` | Developer and Software Architect agent for architecture decisions, full-stack implementation, code writing, testing, infrastructure, CI/CD, and technical documentation. | davepoon |
| `frontend-designer` | Use this agent when you need to convert design mockups, wireframes, or visual concepts into detailed technical specifications and implementation guides for frontend development. | iannuttall |
| `frontend-mobile-development-mobile-developer` | Develop React Native, Flutter, or native mobile apps with modern architecture patterns. | wshobson |
| `golang-pro` | Use when building Go applications requiring concurrent programming, high-performance systems, microservices, or cloud-native architectures where idiomatic patterns, error handling excellence, and efficiency are critical. | VoltAgent |
| `graphql-architect` | Use this agent when designing or evolving GraphQL schemas across microservices, implementing federation architectures, or optimizing query performance in distributed graphs. | VoltAgent |
| `graphql-expert` | Expert in GraphQL API design, query optimization, and implementation. | 0xfurai |
| `haskell-pro` | Expert Haskell engineer specializing in advanced type systems, pure functional design, and high-reliability software. | wshobson |
| `hyperledger-fabric-developer` | Develop enterprise blockchain solutions with Hyperledger Fabric v2.5 LTS and v3.x. | davepoon |
| `implement` | Developer agent. Implements the architect plan step-by-step, guided by AGENTS.md guardrails. | wshobson |
| `implement-feature` | Implements a feature from its specification. | davepoon |
| `java-architect` | Use this agent when designing enterprise Java architectures, migrating Spring Boot applications, or establishing microservices patterns for scalable cloud-native systems. | VoltAgent |
| `java-pro` | Master Java 21+ with modern features like virtual threads, pattern matching, and Spring Boot 3.x. | wshobson |
| `kafka-expert` | Write highly efficient, scalable, and fault-tolerant Kafka architectures. | 0xfurai |
| `laravel-backend-expert` | Laravel backend specialist for any Laravel architecture. | vijaythecoder |
| `laravel-specialist` | Use when building Laravel 10+ applications, architecting Eloquent models with complex relationships, implementing queue systems for async processing, or optimizing API performance. | VoltAgent |
| `laravel-vue-developer` | Build full-stack Laravel applications with Vue3 frontend. | davepoon |
| `llm-architect` | Use when designing LLM systems for production, implementing fine-tuning or RAG architectures, optimizing inference serving infrastructure, or managing multi-model deployments. | VoltAgent |
| `mermaid-expert` | Create Mermaid diagrams for flowcharts, sequences, ERDs, and architectures. | wshobson |
| `microservices-architect` | Use when designing distributed system architecture, decomposing monolithic applications into independent microservices, or establishing communication patterns between services at scale. | VoltAgent |
| `minecraft-bukkit-pro` | Master Minecraft server plugin development with Bukkit, Spigot, and Paper APIs. | wshobson |
| `mobile-developer` | Use this agent when building cross-platform mobile applications requiring native performance optimization, platform-specific features, and offline-first architecture. | VoltAgent |
| `monorepo-architect` | Expert in monorepo architecture, build systems, and dependency management at scale. | wshobson |
| `multi-platform-apps-backend-architect` | Expert backend architect specializing in scalable API design, microservices architecture, and distributed systems. | wshobson |
| `multi-platform-apps-frontend-developer` | Build React components, implement responsive layouts, and handle client-side state management. | wshobson |
| `nextjs-developer` | Use this agent when building production Next.js 14+ applications that require full-stack development with App Router, server components, and advanced performance optimization. | VoltAgent |
| `nextjs-expert` | Expert in Next.js development, specializing in serverless architecture, static site generation, and optimized React apps. | 0xfurai |
| `node-specialist` | Use this agent when you need to build, optimize, or debug Node.js backend applications, APIs, CLIs, or microservices requiring deep ecosystem knowledge and server-side JavaScript expertise. | VoltAgent |
| `observability-monitoring-database-optimizer` | Expert database optimizer specializing in modern performance tuning, query optimization, and scalable architectures. | wshobson |
| `oiloil-ui-ux-guide` | Modern, clean UI/UX guidance + review skill. | davepoon |
| `php-developer` | Write idiomatic PHP code with design patterns, SOLID principles, and modern best practices. | davepoon |
| `platform-engineer` | Use when building or improving internal developer platforms (IDPs), designing self-service infrastructure, or optimizing developer workflows to reduce friction and accelerate delivery. | VoltAgent |
| `powershell-module-architect` | Use this agent when architecting and refactoring PowerShell modules, designing profile systems, or creating cross-version compatible automation libraries. | VoltAgent |
| `powershell-ui-architect` | Use when designing or building desktop graphical interfaces (WinForms, WPF, Metro-style dashboards) or terminal user interfaces (TUIs) for PowerShell automation tools that need clean separation between UI and business logic. | VoltAgent |
| `project-analyst` | MUST BE USED to analyse any new or unfamiliar codebase. | vijaythecoder |
| `python-development-django-pro` | Master Django 5.x with async views, DRF, Celery, and Django Channels. | wshobson |
| `python-development-fastapi-pro` | Build high-performance async APIs with FastAPI, SQLAlchemy 2.0, and Pydantic V2. | wshobson |
| `rails-backend-expert` | Comprehensive Rails backend developer with expertise in all aspects of Ruby on Rails development. | vijaythecoder |
| `react-component-architect` | Expert React architect specializing in modern patterns and component design. | vijaythecoder |
| `react-expert` | React development expert with deep understanding of component architecture, hooks, state management, and performance optimization. | 0xfurai |
| `react-nextjs-expert` | Expert in Next.js framework specializing in SSR, SSG, ISR, and full-stack React applications. | vijaythecoder |
| `react-specialist` | Use when optimizing existing React applications for performance, implementing advanced React 18+ features, or solving complex state management and architectural challenges within React codebases. | VoltAgent |
| `sales-engineer` | Use this agent when you need to conduct technical pre-sales activities including solution architecture, proof-of-concept development, and technical demonstrations for complex sales deals. | VoltAgent |
| `scala-pro` | Master enterprise-grade Scala development with functional programming, distributed systems, and big data processing. | wshobson |
| `senior-backend-architect` | Senior backend engineer and system architect with 10+ years at Google, leading multiple products with 10M+ users. | zhsama |
| `senior-frontend-architect` | Senior frontend engineer and architect with 10+ years at Meta, leading multiple products with 10M+ users. | zhsama |
| `seo-structure-architect` | Analyzes and optimizes content structure including header hierarchy, suggests schema markup, and internal linking opportunities. | wshobson |
| `server-components` | This skill should be used when the user asks about "Server Components", "Client Components", "'use client' directive", "when to use server vs client", "RSC patterns", "component composition", "data fe... | davepoon |
| `spec-developer` | Expert developer that implements features based on specifications. | zhsama |
| `spec-planner` | Implementation planning specialist that breaks down architectural designs into actionable tasks. | zhsama |
| `spring-boot-engineer` | Use this agent when building enterprise Spring Boot 3+ applications requiring microservices architecture, cloud-native deployment, or reactive programming patterns. | VoltAgent |
| `swift-expert` | Use this agent when building native iOS, macOS, or server-side Swift applications requiring advanced concurrency patterns, protocol-oriented architecture, and Swift-specific optimizations. | VoltAgent |
| `symfony-specialist` | Use when building Symfony 6+/7+/8+ applications, architecting Doctrine ORM entities with complex relationships, implementing Messenger component for async processing, or optimizing API Platform performance. | VoltAgent |
| `tech-lead-orchestrator` | Senior technical lead who analyzes complex software projects and provides strategic recommendations. | vijaythecoder |
| `temporal-python-pro` | Master Temporal workflow orchestration with Python SDK. | wshobson |
| `terraform-engineer` | Use when building, refactoring, or scaling infrastructure as code using Terraform with focus on multi-cloud deployments, module architecture, and enterprise-grade state management. | VoltAgent |
| `vue-component-architect` | Vue 3 expert specializing in Composition API, scalable component architecture, and modern Vue tooling. | vijaythecoder |
| `vue-nuxt-expert` | Expert in Nuxt.js framework specializing in SSR, SSG, and full-stack Vue applications. | vijaythecoder |
| `yolo-cto` | Technical health agent. | davepoon |

## Backend Development

_34 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `actix-expert` | Expert in Actix for building high-performance web applications with Rust | 0xfurai |
| `api-developer` | Backend API development specialist for creating robust, scalable REST and GraphQL APIs with best practices | webdevtodayjason |
| `api-documenter` | Use this agent when creating or improving API documentation, writing OpenAPI specifications, building interactive documentation portals, or generating code examples for APIs. | VoltAgent |
| `backend-development-performance-engineer` | Profile and optimize application performance including response times, memory usage, query efficiency, and scalability. | wshobson |
| `django-api-developer` | Expert Django API developer specializing in Django REST Framework and GraphQL. | vijaythecoder |
| `django-backend-expert` | Expert Django backend developer specializing in models, views, services, and Django-specific implementations. | vijaythecoder |
| `django-developer` | Use when building Django 4+ web applications, REST APIs, or modernizing existing Django projects with async views and enterprise patterns. | VoltAgent |
| `django-expert` | Write expert Django code with optimized models, views, and templates. | 0xfurai |
| `documentation-generation-api-documenter` | Master API documentation with OpenAPI 3.1, AI-powered tools, and modern developer experience practices. | wshobson |
| `express-expert` | Specializes in building performant and scalable web applications using Express.js. | 0xfurai |
| `fastapi-developer` | Use when building modern async Python APIs with FastAPI, implementing Pydantic v2 validation, dependency injection patterns, or deploying high-performance ASGI applications. | VoltAgent |
| `fastapi-expert` | FastAPI development with an emphasis on best practices, optimization, and robust design patterns. | 0xfurai |
| `flask-expert` | Expert in developing and optimizing web applications using the Flask framework. | 0xfurai |
| `gin-expert` | Create a Claude Code Agent that is an expert in the Gin web framework for Go, focusing on efficient web server implementation and optimization. | 0xfurai |
| `grpc-expert` | Specialist in gRPC protocol, mastering streaming, services, and transport optimization for scalable, high-performance systems. | 0xfurai |
| `gsd-eval-planner` | Designs a structured evaluation strategy for an AI phase. | davepoon |
| `java-developer` | Master modern Java with streams, concurrency, and JVM optimization. | davepoon |
| `m365-admin` | Use when automating Microsoft 365 administrative tasks including Exchange Online mailbox provisioning, Teams collaboration management, SharePoint site configuration, license lifecycle management, and Graph API-driven identity automation. | VoltAgent |
| `monitor-agent` | Lightweight APM and metrics probe agent. | davepoon |
| `nestjs-expert` | Expert in building scalable and efficient applications using the NestJS framework. | 0xfurai |
| `openai-api-expert` | Trained to expertly handle OpenAI API features, usage patterns, and best practices. | 0xfurai |
| `openapi-expert` | Expert in designing, documenting, and optimizing APIs using OpenAPI specifications. | 0xfurai |
| `ops-monitor` | Unified APM and monitoring surface. | davepoon |
| `orchestrate` | Product Orchestrator agent. | wshobson |
| `perl-expert` | Master Perl scripting with regular expressions, data manipulation, CPAN modules, and advanced text processing. | 0xfurai |
| `php-pro` | Use this agent when working with PHP 8.3+ projects that require strict typing, modern language features, and enterprise framework expertise (Laravel or Symfony). | VoltAgent |
| `plugin-validator` | \| Use this agent when the user asks to "validate my plugin", "check plugin structure", "verify plugin is correct", "validate plugin.json", "check plugin files", or mentions plugin validation. | Anthropic Official |
| `public-plugin-builder` | > Activate when the user wants to build a Claude plugin, create a Claude skill, make a Claude agent, structure a Claude Code plugin, says "build a plugin", "create a skill", "new claude skill", "new a... | davepoon |
| `rails-activerecord-expert` | Expert in Rails ActiveRecord optimization, complex queries, and database performance. | vijaythecoder |
| `rails-api-developer` | Expert Rails API developer specializing in RESTful APIs and GraphQL. | vijaythecoder |
| `rails-expert` | Use when building or modernizing Rails applications requiring API development, Hotwire reactivity, real-time features, background job processing, deployment automation, or Rails-idiomatic patterns for maximum productivity. | VoltAgent |
| `rest-expert` | Master in designing and implementing RESTful APIs with focus on best practices, HTTP methods, status codes, and resource modeling. | 0xfurai |
| `spring-boot-expert` | Expert in developing, optimizing, and maintaining Spring Boot applications with best practices and modern techniques for enterprise-grade applications. | 0xfurai |
| `trpc-expert` | Expert in building reliable, efficient, and type-safe backend services using tRPC. | 0xfurai |

## Cloud & Infra

_13 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `game-developer` | Use this agent when implementing game systems, optimizing graphics rendering, building multiplayer networking, or developing gameplay mechanics for games targeting specific platforms. | VoltAgent |
| `gsd:ultraplan-phase` | [BETA] Offload plan phase to Claude Code's ultraplan cloud — drafts remotely while terminal stays free, review in browser with inline comments, import back via /gsd:import. | davepoon |
| `moc-agent` | Identifies and generates missing Maps of Content (MOCs) and organizes orphaned assets. | davepoon |
| `observability-monitoring-observability-engineer` | Build production-ready monitoring, logging, and tracing systems. | wshobson |
| `ops-package` | Ship parcels via any configured carrier — MyParcel, Sendcloud, DHL Parcel NL, PostNL, DPD, UPS, FedEx. | davepoon |
| `ops-revenue` | Revenue and costs tracker. | davepoon |
| `ops-speedup` | Cross-platform, hardware-adaptive system optimizer. | davepoon |
| `ops-whatsapp-biz` | WhatsApp Business Cloud API — send approved template messages at scale, manage templates with approval tracking, and integrate product catalogs. | davepoon |
| `performance-monitor` | Use when establishing observability infrastructure to track system metrics, detect performance anomalies, and optimize resource usage across multi-agent environments. | VoltAgent |
| `performance-optimizer` | MUST BE USED whenever users report slowness, high cloud costs, or scaling concerns. | vijaythecoder |
| `pulumi-expert` | Expert in Pulumi infrastructure as code for cloud resources | 0xfurai |
| `x-twitter-scraper` | X (Twitter) data extraction and monitoring via Xquik: tweet search, user lookup, follower extraction, giveaway draws, trending topics, account monitoring with webhooks, reply/retweet/quote extraction, community and Space data, follow checks. | davepoon |
| `yolo-cfo` | Financial analysis agent. | davepoon |

## Code Review & Quality

_48 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `Python Testing Expert` | Specialized agent for Python testing, test automation, quality assurance, and comprehensive testing strategies | vijaythecoder |
| `agent-creator` | \| Use this agent when the user asks to "create an agent", "generate an agent", "build a new agent", "make me an agent that...", or describes agent functionality they need. | Anthropic Official |
| `architect-review` | Reviews code changes for architectural consistency and patterns. | davepoon |
| `architect-reviewer` | Use this agent when you need to evaluate system design decisions, architectural patterns, and technology choices at the macro level. | VoltAgent |
| `audio-quality-controller` | Analyzes, enhances, and standardizes audio quality for professional-grade content. | davepoon |
| `code-health` | Scans the codebase for dead code, tech debt, outdated dependencies, and code quality issues. | davepoon |
| `code-reviewer` | Use this agent when you need to review code for adherence to project guidelines, style guides, and best practices. | Anthropic Official |
| `comment-analyzer` | Use this agent when you need to analyze code comments for accuracy, completeness, and long-term maintainability. | Anthropic Official |
| `content-quality-editor` | Use this agent before publishing any AI-generated content — blog posts, READMEs, release notes, commit messages, PR descriptions, documentation, or social posts. | VoltAgent |
| `content-research-writer` | Assists in writing high-quality content by conducting research, adding citations, improving hooks, iterating on outlines, and providing real-time feedback on each section. | davepoon |
| `cpp-expert` | Expert in writing high-quality, efficient, and modern C++ code. | 0xfurai |
| `csharp-expert` | Expert in C# programming focusing on best practices, performance optimization, and code quality. | 0xfurai |
| `data-engineer` | Use this agent when you need to design, build, or optimize data pipelines, ETL/ELT processes, and data infrastructure. | VoltAgent |
| `data-researcher` | Use this agent when you need to discover, collect, and validate data from multiple sources to fuel analysis and decision-making. | VoltAgent |
| `eval-judge` | LLM judge for plugin quality assessment. | wshobson |
| `eval-orchestrator` | Orchestrates plugin quality evaluation. | wshobson |
| `framework-migration-architect-review` | Master software architect specializing in modern architecture patterns, clean architecture, microservices, event-driven systems, and DDD. | wshobson |
| `gsd-code-fixer` | Applies fixes to code review findings from REVIEW.md. | davepoon |
| `gsd-codebase-mapper` | Explores codebase and writes structured analysis documents. | davepoon |
| `gsd-plan-checker` | Verifies plans will achieve phase goal before execution. | davepoon |
| `gsd-ui-checker` | Validates UI-SPEC.md design contracts against 6 quality dimensions. | davepoon |
| `gsd:code-review-fix` | Auto-fix issues found by code review in REVIEW.md. | davepoon |
| `gsd:set-profile` | Switch model profile for GSD agents (quality/balanced/budget/inherit) argument-hint: <profile (quality\|balanced\|budget\|inherit)> | davepoon |
| `haiku-reviewer` | Tier 1 (surface) Ralph Review. | davepoon |
| `image-enhancer` | Improves the quality of images, especially screenshots, by enhancing resolution, sharpness, and clarity. | davepoon |
| `ios-expert` | Write high-quality iOS applications using Swift and SwiftUI, ensuring optimal performance, user-friendly interfaces, and adherence to Apple's guidelines. | 0xfurai |
| `jasmine-expert` | Master unit testing with the Jasmine framework, focusing on best practices for writing and organizing tests to ensure software quality. | 0xfurai |
| `javascript-expert` | Expert in modern JavaScript specializing in language features, optimization, and best practices. | 0xfurai |
| `lead-research-assistant` | Identifies high-quality leads for your product or service by analyzing your business, searching for target companies, and providing actionable contact strategies. | davepoon |
| `lint-on-save` | Automatically run linting tools after file modifications | davepoon |
| `mcp-builder` | Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. | davepoon |
| `ocr-quality-assurance` | You are an OCR Quality Assurance specialist performing final review and validation of OCR-corrected text against original image sources. | davepoon |
| `pr-test-analyzer` | Use this agent when you need to review a pull request for test coverage quality and completeness. | Anthropic Official |
| `python-expert` | Master advanced Python features, optimize performance, and ensure code quality. | 0xfurai |
| `qa-expert` | Use this agent when you need comprehensive quality assurance strategy, test planning across the entire development cycle, or quality metrics analysis to improve overall software quality. | VoltAgent |
| `research-orchestrator` | You are the Research Orchestrator, an elite coordinator responsible for managing comprehensive research projects using the Open Deep Research methodology. | davepoon |
| `review-agent` | You are a specialized quality assurance agent for knowledge management systems. | davepoon |
| `scientific-literature-researcher` | Use when you need to search scientific literature and retrieve structured experimental data from published studies. | VoltAgent |
| `skill-reviewer` | \| Use this agent when the user has created or modified a skill and needs quality review, asks to "review my skill", "check skill quality", "improve skill description", or wants to ensure skill follows best practices. | Anthropic Official |
| `sonnet-reviewer` | Tier 2 (logic) Ralph Review. | davepoon |
| `spec-orchestrator` | Workflow coordination specialist focused on project organization, quality gate management, and progress tracking. | zhsama |
| `tdd-specialist` | Test-Driven Development specialist for creating comprehensive test suites, implementing TDD workflows, and ensuring code quality | webdevtodayjason |
| `technical-researcher` | Analyze code repositories, technical documentation, and implementation details. | davepoon |
| `type-design-analyzer` | Use this agent when you need expert analysis of type design in your codebase. | Anthropic Official |
| `unit-testing-test-automator` | Master AI-powered test automation with modern frameworks, self-healing tests, and comprehensive quality engineering. | wshobson |
| `verifier` | Agent that verifies build, lint, test, and checklist after TASK completion within a WORK. | davepoon |
| `vitest-expert` | Create organized, comprehensive, and efficient unit tests with Vitest, ensuring high code quality and stability. | 0xfurai |
| `youtube-downloader` | Download YouTube videos with customizable quality and format options. | davepoon |

## Crypto / Blockchain / FinTech

_2 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `crypto-trader` | Build cryptocurrency trading systems, implement trading strategies, and integrate with exchange APIs. | davepoon |
| `episode-orchestrator` | Manages episode-based workflows by coordinating multiple specialized agents in sequence. | davepoon |

## Data Analysis & Science

_9 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `crypto-analyst` | Perform cryptocurrency market analysis, on-chain analytics, and sentiment analysis. | davepoon |
| `data-analyst` | Use when you need to extract insights from business data, create dashboards and reports, or perform statistical analysis to support decision-making. | VoltAgent |
| `google-analytics-automation` | Automate Google Analytics tasks via Rube MCP (Composio): run reports, list accounts/properties, funnels, pivots, key events. | davepoon |
| `mailchimp-automation` | Automate Mailchimp email marketing including campaigns, audiences, subscribers, segments, and analytics via Rube MCP (Composio). | davepoon |
| `numpy-expert` | Expert in NumPy for scientific computing, data analysis, and numerical operations. | 0xfurai |
| `ops-marketing` | Marketing command center. | davepoon |
| `pandas-expert` | Expert in data manipulation and analysis using pandas library in Python. | 0xfurai |
| `sendgrid-automation` | Automate SendGrid email operations including sending emails, managing contacts/lists, sender identities, templates, and analytics via Rube MCP (Composio). | davepoon |
| `youtube-automation` | Automate YouTube tasks via Rube MCP (Composio): upload videos, manage playlists, search content, get analytics, and handle comments. | davepoon |

## Data Engineering

_1 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `sql-pro` | Use this agent when you need to optimize complex SQL queries, design efficient database schemas, or solve performance issues across PostgreSQL, MySQL, SQL Server, and Oracle requiring advanced query o... | VoltAgent |

## Database

_23 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `cassandra-expert` | Master in Cassandra database design, optimization, and management. | 0xfurai |
| `cockroachdb-expert` | Specializes in CockroachDB setup, optimization, and best practices. | 0xfurai |
| `database-optimizer` | Use this agent when you need to analyze slow queries, optimize database performance across multiple systems, or implement indexing strategies to improve query execution. | VoltAgent |
| `dynamodb-expert` | Expert in DynamoDB optimization, best practices, and data modeling. | 0xfurai |
| `elasticsearch-expert` | Master Elasticsearch operations, query optimizations, and cluster management. | 0xfurai |
| `elk-expert` | Expert in ELK stack management, optimization, and deployment. | 0xfurai |
| `infra-monitor` | Multi-service infrastructure health checker. | davepoon |
| `mariadb-expert` | Expert in MariaDB database management, optimization, and best practices. | 0xfurai |
| `mongodb-expert` | Master MongoDB operations, schema design, performance optimization, and data modeling. | 0xfurai |
| `mongoose-expert` | Mongoose ODM specialist for MongoDB, proficient in schema design, query optimization, and data validation. | 0xfurai |
| `mssql-expert` | Expert in Microsoft SQL Server handling query optimization, database design, and advanced T-SQL features. | 0xfurai |
| `mysql-expert` | Expert in MySQL database management, query optimization, and schema design. | 0xfurai |
| `neo4j-expert` | Expert in Neo4j graph database specializing in Cypher queries, graph modeling, and optimization. | 0xfurai |
| `notion-automation` | Automate Notion tasks via Rube MCP (Composio): pages, databases, blocks, comments, users. | davepoon |
| `notion-memory` | Long-term memory for Claude via Notion databases — persist project context, decisions, contact profiles, and interaction logs across sessions with collaborative access. | davepoon |
| `obsidian-bases` | Create and edit Obsidian Bases (.base files) with views, filters, formulas, and summaries. | davepoon |
| `performance-engineer` | Use this agent when you need to identify and eliminate performance bottlenecks in applications, databases, or infrastructure systems, and when baseline performance metrics need improvement. | VoltAgent |
| `postgres-expert` | Expert in PostgreSQL database management and optimization, handling complex SQL queries, indexing strategies, and ensuring high-performance database systems. | 0xfurai |
| `postgres-pro` | Use when you need to optimize PostgreSQL performance, design high-availability replication, or troubleshoot database issues at scale. | VoltAgent |
| `sql-bulk-delete-warn` | Warn when a destructive SQL command (DELETE/UPDATE/TRUNCATE) runs via psql, mysql, sqlite3, or sqlcmd without a row-count safeguard | davepoon |
| `sql-expert` | Master complex SQL queries, optimize execution plans, and ensure database integrity. | 0xfurai |
| `sqlite-expert` | SQLite database optimization, query writing, indexing, and best practices specialist. | 0xfurai |
| `typeorm-expert` | Expertise in TypeORM for defining and managing data models with efficient database interactions in Node.js applications | 0xfurai |

## Design & UX

_15 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `canvas-design` | Create beautiful visual art in .png and .pdf documents using design philosophy. | davepoon |
| `command-expert` | Create CLI commands for automation and tooling. | davepoon |
| `defi-strategist` | Design and implement DeFi yield strategies, liquidity provision, and protocol interactions. | davepoon |
| `design-boss` | The Boss of the design team. | davepoon |
| `design-cynic` | The Cynic of the design team. | davepoon |
| `design-pusher` | The Pusher of the design team. | davepoon |
| `design-rookie` | The Rookie of the design team. | davepoon |
| `design-watcher` | The Watcher of the design team. | davepoon |
| `git-workflow-manager` | Use this agent when you need to design, establish, or optimize Git workflows, branching strategies, and merge management for a project or team. | VoltAgent |
| `gsd:sketch-wrap-up` | Package sketch design findings into a persistent project skill for future build conversations allowed-tools: - Read - Write - Edit - Bash - Grep - Glob - AskUserQuestion | davepoon |
| `macos-design` | Design and build native-feeling macOS application UIs. | davepoon |
| `mcp-expert` | Create Model Context Protocol integrations and server configurations. | davepoon |
| `shadcn-ui-builder` | UI/UX specialist for designing and implementing interfaces using the ShadCN UI component library. | webdevtodayjason |
| `ui-designer` | Use this agent when designing visual interfaces, creating design systems, building component libraries, or refining user-facing aesthetics requiring expert visual design, interaction patterns, and accessibility considerations. | VoltAgent |
| `ui-ux-designer` | Create interface designs, wireframes, and design systems. | wshobson |

## Desktop / CLI

_6 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `cli-developer` | Use this agent when building command-line tools and terminal applications that require intuitive command design, cross-platform compatibility, and optimized developer experience. | VoltAgent |
| `it-ops-orchestrator` | Use for orchestrating complex IT operations tasks that span multiple domains (PowerShell automation, .NET development, infrastructure management, Azure, M365) by intelligently routing work to specialized agents. | VoltAgent |
| `ops-go` | Token-efficient morning briefing. | davepoon |
| `posix-shell-pro` | Expert in strict POSIX sh scripting for maximum portability across Unix-like systems. | wshobson |
| `powershell-7-expert` | Use when building cross-platform cloud automation scripts, Azure infrastructure orchestration, or CI/CD pipelines requiring PowerShell 7+ with modern .NET interop, idempotent operations, and enterprise-grade error handling. | VoltAgent |
| `tauri-expert` | Expert in Tauri for building cross-platform desktop applications leveraging web technologies. | 0xfurai |

## DevOps & SRE

_33 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `Python DevOps/CI-CD Expert` | Specialized agent for Python DevOps, CI/CD, deployment automation, containerization, and infrastructure as code | vijaythecoder |
| `ansible-expert` | Master Ansible automation for configuration management, application deployment, and task orchestration. | 0xfurai |
| `bot-deploy-verifier` | Adversarial post-deploy verifier. | davepoon |
| `celery-expert` | Expert in Celery for distributed task queue management, optimizing task execution, and ensuring robust Celery deployments. | 0xfurai |
| `cf-proxy` | Deploy a free VLESS proxy/VPN node on Cloudflare Pages using edgetunnel. | davepoon |
| `circleci-expert` | Expert in CircleCI configuration, optimization, and troubleshooting for seamless continuous integration and delivery. | 0xfurai |
| `deployment-engineer` | Use this agent when designing, building, or optimizing CI/CD pipelines and deployment automation strategies. | VoltAgent |
| `devops-incident-responder` | Use when actively responding to production incidents, diagnosing critical service failures, or conducting incident postmortems to implement permanent fixes and preventative measures. | VoltAgent |
| `devops-troubleshooter` | Debug production issues, analyze logs, and fix deployment failures. | davepoon |
| `docker-expert` | Use this agent when you need to build, optimize, or secure Docker container images and orchestration for production environments. | VoltAgent |
| `force-push-guard` | Block dangerous --force flags in git push, npm install, and docker prune | davepoon |
| `github-actions-expert` | Expert in GitHub Actions for automating workflows and CI/CD processes. | 0xfurai |
| `github-automation` | Automate GitHub repositories, issues, pull requests, branches, CI/CD, and permissions via Rube MCP (Composio). | davepoon |
| `gitlab-ci-expert` | Expert in configuring, optimizing, and maintaining GitLab CI/CD pipelines for efficient software delivery. | 0xfurai |
| `google-drive-upload` | > Upload files directly to Google Drive via a deployed Google Apps Script web app. | davepoon |
| `incident-response-devops-troubleshooter` | Expert DevOps troubleshooter specializing in rapid incident response, advanced debugging, and modern observability. | wshobson |
| `jenkins-expert` | Jenkins expert specializing in continuous integration, delivery, and deployment automation. | 0xfurai |
| `kubernetes-expert` | Master Kubernetes for container orchestration, pod management, and cluster optimization. | 0xfurai |
| `kubernetes-specialist` | Use this agent when you need to design, deploy, configure, or troubleshoot Kubernetes clusters and workloads in production environments. | VoltAgent |
| `mac-cleanup` | Reclaim disk space on macOS — clean Xcode derived data, Homebrew caches, system logs, Docker images, and find large forgotten files. | davepoon |
| `machine-learning-engineer` | Use this agent when you need to deploy, optimize, or serve machine learning models at scale in production environments. | VoltAgent |
| `mlops-engineer` | Use this agent when you need to design and implement ML infrastructure, set up CI/CD for machine learning models, establish model versioning systems, or optimize ML platforms for reliability and automation. | VoltAgent |
| `ops` | Business operations command center. | davepoon |
| `ops-deploy` | Deploy status across all projects. | davepoon |
| `ops-yolo` | YOLO mode. Spawns 4 parallel C-suite agents (CEO, CTO, CFO, COO). | davepoon |
| `project-task-planner` | Use this agent when you need to create a comprehensive development task list from a Product Requirements Document (PRD). | iannuttall |
| `reinforcement-learning-engineer` | Use when designing RL environments, training agents with reward optimization, implementing policy gradient methods, or deploying decision-making systems for robotics, gaming, and autonomous operations. | VoltAgent |
| `render-automation` | Automate Render tasks via Rube MCP (Composio): services, deployments, projects. | davepoon |
| `sre-engineer` | Use this agent when you need to establish or improve system reliability through SLO definition, error budget management, and automation. | VoltAgent |
| `terraform-expert` | Expert in infrastructure-as-code using Terraform, specializing in efficient and reliable infrastructure provisioning and management. | 0xfurai |
| `terraform-specialist` | Write Terraform modules and manage infrastructure as code. | davepoon |
| `unity-developer` | Build Unity games with optimized C# scripts, efficient rendering, and proper asset management. | wshobson |
| `vercel-automation` | Automate Vercel tasks via Rube MCP (Composio): manage deployments, domains, DNS, env vars, projects, and teams. | davepoon |

## Documentation

_14 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `coda-automation` | Automate Coda tasks via Rube MCP (Composio): manage docs, pages, tables, rows, formulas, permissions, and publishing. | davepoon |
| `doc-writer` | Documentation specialist for creating comprehensive technical documentation, API references, and README files. | webdevtodayjason |
| `docusaurus-expert` | Configure and troubleshoot Docusaurus documentation sites. | davepoon |
| `gsd-doc-classifier` | Classifies a single planning document as ADR, PRD, SPEC, DOC, or UNKNOWN. | davepoon |
| `gsd-doc-synthesizer` | Synthesizes classified planning docs into a single consolidated context. | davepoon |
| `gsd-doc-verifier` | Verifies factual claims in generated docs against the live codebase. | davepoon |
| `gsd:discuss-phase` | Gather phase context through adaptive questioning before planning. | davepoon |
| `gsd:docs-update` | Generate or update project documentation verified against the codebase argument-hint: "[--force] [--verify-only]" allowed-tools: - Read - Write - Edit - Bash - Glob - Grep - Task - AskUserQuestion | davepoon |
| `gsd:ingest-docs` | Scan a repo for mixed ADRs, PRDs, SPECs, and DOCs and bootstrap or merge the full .planning/ setup from them. | davepoon |
| `gsd:spike` | Spike an idea through experiential exploration, or propose what to spike next (frontier mode) argument-hint: "[idea to validate] [--quick] [--text] or [frontier]" allowed-tools: - Read - Write - Edit ... | davepoon |
| `planner` | Agent that analyzes projects to create WORK (unit of work) and decompose sub-TASKs. | davepoon |
| `readme-generator` | Use this agent when you need a maintainer-ready README built from exact repository reality, with deep codebase scanning, zero hallucination, and optional git commit/push only when explicitly requested. | VoltAgent |
| `reference-builder` | Creates exhaustive technical references and API documentation. | wshobson |
| `technical-writer` | Use this agent when you need to create, improve, or maintain technical documentation including API references, user guides, SDK documentation, and getting-started guides. | VoltAgent |

## Frontend Development

_25 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `analyze-pitch-deck` | Activate for ANY pitch deck analysis, feedback, or review request. | davepoon |
| `angularjs-expert` | Expert in AngularJS development, focusing on optimizing code structure, improving performance, and ensuring best practices. | 0xfurai |
| `artifacts-builder` | Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui). | davepoon |
| `discord-automation` | Automate Discord tasks via Rube MCP (Composio): messages, channels, roles, webhooks, reactions. | davepoon |
| `expo-expert` | Expert in developing, optimizing, and maintaining applications using the Expo framework for React Native. | 0xfurai |
| `expo-react-native-expert` | Use when building mobile applications with Expo and React Native that require native module integration, navigation setup, performant animations, push notifications, OTA updates, or App Store/Play Store deployment. | VoltAgent |
| `frontend-developer` | Use when building complete frontend applications across React, Vue, and Angular frameworks requiring multi-framework expertise and full-stack integration. | VoltAgent |
| `fullstack-developer` | Use this agent when you need to build complete features spanning database, API, and frontend layers together as a cohesive unit. | VoltAgent |
| `gsd-ui-researcher` | Produces UI-SPEC.md design contract for frontend phases. | davepoon |
| `gsd:sketch` | Sketch UI/design ideas with throwaway HTML mockups, or propose what to sketch next (frontier mode) argument-hint: "[design idea to explore] [--quick] [--text] or [frontier]" allowed-tools: - Read - Wr... | davepoon |
| `gsd:ui-phase` | Generate UI design contract (UI-SPEC.md) for frontend phases argument-hint: "[phase]" allowed-tools: - Read - Write - Bash - Glob - Grep - Task - WebFetch - AskUserQuestion - mcp__context7__* | davepoon |
| `html-expert` | Expert in HTML structure, semantics, and best practices for building clean, accessible, and optimized web pages. | 0xfurai |
| `javascript-developer` | JavaScript expert for modern ES6+, async patterns, and Node.js. | davepoon |
| `jquery-expert` | jQuery specialist focusing on efficient DOM manipulation, event handling, and AJAX interactions. | 0xfurai |
| `nextjs-app-router-developer` | Build modern Next.js applications using App Router with Server Components, Server Actions, PPR, and advanced caching strategies. | davepoon |
| `react-native-expert` | Expert in React Native development focusing on cross-platform mobile applications with optimal performance and native integrations. | 0xfurai |
| `react-performance-optimization` | You are a React Performance Optimization specialist focusing on identifying, analyzing, and resolving performance bottlenecks in React applications. | davepoon |
| `remix-expert` | Expert in building performant, scalable web applications using the Remix framework, with deep understanding of loaders, actions, and dynamic routing. | 0xfurai |
| `slack-automation` | Automate Slack messaging, channel management, search, reactions, and threads via Rube MCP (Composio). | davepoon |
| `slack-message-formatter` | \| Format messages for Slack with pixel-perfect accuracy. | davepoon |
| `solidjs-expert` | SolidJS expert specializing in creating efficient and reactive UI components using SolidJS. | 0xfurai |
| `svelte-expert` | Master Svelte.js development with a focus on building performant, maintainable, and idiomatic Svelte applications. | 0xfurai |
| `tailwind-expert` | Expert in Tailwind CSS for efficient and responsive styling of web projects, utilizing utility-first approaches and responsive design principles. | 0xfurai |
| `theme-factory` | Toolkit for styling artifacts with a theme. | davepoon |
| `vue-expert` | Use this agent when building Vue 3 applications that require Composition API mastery, reactivity optimization, or Nuxt 3 development with enterprise-scale performance concerns. | VoltAgent |

## Game / Graphics / Embedded

_4 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `arm-cortex-expert` | > Senior embedded software engineer specializing in firmware and driver development for ARM Cortex-M microcontrollers (Teensy, STM32, nRF52, SAMD). | wshobson |
| `c-developer` | C programming expert for systems programming and embedded development. | davepoon |
| `embedded-systems` | Use when developing firmware for resource-constrained microcontrollers, implementing RTOS-based applications, or optimizing real-time systems where hardware constraints, latency guarantees, and reliability are critical. | VoltAgent |
| `gsd:join-discord` | Join the GSD Discord community allowed-tools: [] | davepoon |

## Language Specialists

_7 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `about-atlantic-home-mortgage` | Background information about Lendtrain powered by Atlantic Home Mortgage — company history, credentials, founder bio, and contact information for borrower trust-building. | davepoon |
| `erlang-expert` | Expert in writing efficient, concurrent, and robust Erlang applications. | 0xfurai |
| `format-javascript-files` | Automatically format JavaScript/TypeScript files after any Edit operation using prettier | davepoon |
| `gsd-integration-checker` | Verifies cross-phase integration and E2E flows. | davepoon |
| `java-expert` | Master Java developer specializing in writing efficient, clean, and maintainable Java code across various domains. | 0xfurai |
| `pagerduty-automation` | Automate PagerDuty tasks via Rube MCP (Composio): manage incidents, services, schedules, escalation policies, and on-call rotations. | davepoon |
| `typescript-pro` | Use when implementing TypeScript code requiring advanced type system patterns, complex generics, type-level programming, or end-to-end type safety across full-stack applications. | VoltAgent |

## Marketing & Content

_25 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `capture` | > Save a memory to Origin in flow. | davepoon |
| `confluence-automation` | Automate Confluence page creation, content search, space management, labels, and hierarchy navigation via Rube MCP (Composio). | davepoon |
| `connection-agent` | Analyzes and suggests meaningful links between related content in knowledge management systems. | davepoon |
| `documentation-generation-tutorial-engineer` | Creates step-by-step tutorials and educational content from code. | wshobson |
| `docx` | Comprehensive document creation, editing, and analysis with support for tracked changes, comments, formatting preservation, and text extraction. | davepoon |
| `internal-comms` | A set of resources to help me write all kinds of internal communications, using the formats that my company likes to use. | davepoon |
| `no-vibes` | Block positive Stop closeouts ("done"/"ready"/"shipped") that lack same-turn verification evidence — empirically F1 0.815 against MAST mode 3.3 | davepoon |
| `podcast-content-analyzer` | Analyze podcast transcripts to identify engaging segments and viral moments. | davepoon |
| `podcast-metadata-specialist` | You are a Podcast Metadata Specialist generating comprehensive metadata, show notes, chapter markers, and platform-specific descriptions for podcast episodes. | davepoon |
| `podcast-trend-scout` | You are a Podcast Trend Scout identifying emerging tech topics and news for podcast episodes. | davepoon |
| `pptx` | Presentation creation, editing, and analysis. | davepoon |
| `qwen-vision` | > Use when the user asks to "analyze video", "watch this video", "what happens in this video", "describe this clip", "review this footage", "classify these videos", "compare videos", "analyze this ima... | davepoon |
| `reddit-automation` | Automate Reddit tasks via Rube MCP (Composio): search subreddits, create posts, manage comments, and browse top content. | davepoon |
| `search-specialist` | Use when you need to find specific information across multiple sources using advanced search strategies, query optimization, and targeted information retrieval. | VoltAgent |
| `seo-cannibalization-detector` | Analyzes multiple provided pages to identify keyword overlap and potential cannibalization issues. | wshobson |
| `seo-content-planner` | Creates comprehensive content outlines and topic clusters for SEO. | wshobson |
| `seo-content-refresher` | Identifies outdated elements in provided content and suggests updates to maintain freshness. | wshobson |
| `seo-content-writer` | Writes SEO-optimized content based on provided keywords and topic briefs. | wshobson |
| `seo-keyword-strategist` | Analyzes keyword usage in provided content, calculates density, suggests semantic variations and LSI keywords based on the topic. | wshobson |
| `seo-snippet-hunter` | Formats content to be eligible for featured snippets and SERP features. | wshobson |
| `social-media-copywriter` | You are an expert social media copywriter specializing in podcast promotion. | davepoon |
| `tiktok-automation` | Automate TikTok tasks via Rube MCP (Composio): upload/publish videos, post photos, manage content, and view user profiles/stats. | davepoon |
| `url-context-validator` | Validate URLs for both technical functionality and contextual appropriateness. | davepoon |
| `visual-analysis-ocr` | Extract and analyze text content from PNG images while preserving original formatting and structure. | davepoon |
| `x-intelligence` | Scrape X/Twitter for content insights — analyze trends, extract engagement data, identify top-performing content patterns, and generate data-driven content calendars. | davepoon |

## Mobile Development

_19 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `ag2-prompt-engineer` | Crafts and reviews system prompts for AG2 agents. | davepoon |
| `canva-automation` | Automate Canva tasks via Rube MCP (Composio): designs, exports, folders, brand templates, autofill. | davepoon |
| `cap-table-waterfall` | Model cap table dilution, SAFE conversion, and exit waterfall across scenarios. | davepoon |
| `conversation-analyzer` | Use this agent when analyzing conversation transcripts to find behaviors worth preventing with hooks. | Anthropic Official |
| `dart-expert` | Write idiomatic Dart code, optimize for Dart VM, and ensure cross-platform compatibility for Flutter applications. | 0xfurai |
| `figma-automation` | Automate Figma tasks via Rube MCP (Composio): files, components, design tokens, comments, exports. | davepoon |
| `flutter-expert` | Use when building cross-platform mobile applications with Flutter 3+ that require custom UI implementation, complex state management, native platform integrations, or performance optimization across iOS/Android/Web. | VoltAgent |
| `ios-developer` | Develop native iOS applications with Swift/SwiftUI. | wshobson |
| `ios-hig-design-guide` | Build, update, and apply iOS design specifications using Apple Human Interface Guidelines (HIG) source data. | davepoon |
| `iot-engineer` | Use when designing and deploying IoT solutions requiring expertise in device management, edge computing, cloud integration, and handling challenges like massive device scale, complex connectivity scenarios, or real-time data pipelines. | VoltAgent |
| `kotlin-expert` | Expert in Kotlin programming language, focusing on idiomatic Kotlin code, coroutines, extension functions, and memory management. | 0xfurai |
| `kotlin-specialist` | Use when building Kotlin applications requiring advanced coroutine patterns, multiplatform code sharing, or Android/server-side development with functional programming principles. | VoltAgent |
| `mobile-app-developer` | Use this agent when developing iOS and Android mobile applications with focus on native or cross-platform implementation, performance optimization, and platform-specific user experience. | VoltAgent |
| `revenue-tracker` | Revenue, billing, and credits analysis agent. | davepoon |
| `social-media-clip-creator` | Creates optimized video clips for social media platforms from longer content. | davepoon |
| `swiftui-expert` | Expert in SwiftUI development, focusing on building dynamic, responsive, and maintainable applications for Apple platforms. | 0xfurai |
| `trend-analyst` | Use when analyzing emerging patterns, predicting industry shifts, or developing future scenarios to inform strategic planning and competitive positioning. | VoltAgent |
| `tweetclaw` | Use TweetClaw as an OpenClaw plugin for X/Twitter automation: search tweets, search tweet replies, post tweets/replies, export followers, look up users, handle media, monitor tweets, deliver webhooks,... | davepoon |
| `uninstall` | Completely remove claude-ops plugin, all stored credentials, cached files, shell exports, and MCP registrations. | davepoon |

## Observability & Monitoring

_14 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `brevo-automation` | Automate Brevo (Sendinblue) tasks via Rube MCP (Composio): manage email campaigns, create/edit templates, track senders, and monitor campaign performance. | davepoon |
| `context-monitor` | Monitor context window remaining capacity with graduated warnings (CAUTION → WARNING → CRITICAL → EMERGENCY) | davepoon |
| `crypto-risk-manager` | Implement risk management systems for cryptocurrency trading and DeFi positions. | davepoon |
| `datadog-automation` | Automate Datadog tasks via Rube MCP (Composio): query metrics, search logs, manage monitors/dashboards, create events and downtimes. | davepoon |
| `deal-sourcing-signals` | Scan a company or sector for deal-sourcing signals across 6 dimensions. | davepoon |
| `grafana-expert` | Expert in Grafana dashboard creation, visualization best practices, and alerting systems. | 0xfurai |
| `klaviyo-automation` | Automate Klaviyo tasks via Rube MCP (Composio): manage email/SMS campaigns, inspect campaign messages, track tags, and monitor send jobs. | davepoon |
| `loki-expert` | Master in building, managing, and optimizing Loki for efficient log aggregation and querying. | 0xfurai |
| `opentelemetry-expert` | Master in OpenTelemetry for observability, tracing, metrics, and logs. | 0xfurai |
| `ops-fires` | Production incidents dashboard. | davepoon |
| `ops-merge` | Autonomous PR merge pipeline. | davepoon |
| `postmark-automation` | Automate Postmark email delivery tasks via Rube MCP (Composio): send templated emails, manage templates, monitor delivery stats and bounces. | davepoon |
| `prometheus-expert` | Expert in Prometheus for monitoring, alerting, and performance optimization. | 0xfurai |
| `sentry-automation` | Automate Sentry tasks via Rube MCP (Composio): manage issues/events, configure alerts, track releases, monitor projects and teams. | davepoon |

## Performance & Optimization

_27 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `Python Performance Expert` | Specialized agent for Python performance optimization, profiling, concurrent programming, and system efficiency | vijaythecoder |
| `build-engineer` | Use this agent when you need to optimize build performance, reduce compilation times, or scale build systems across growing teams. | VoltAgent |
| `bun-expert` | Expertise in Bun, focusing on high-performance JavaScript runtime, efficient module execution, and optimized bundling. | 0xfurai |
| `c-pro` | Write efficient C code with proper memory management, pointer arithmetic, and system calls. | wshobson |
| `cpp-pro` | Use this agent when building high-performance C++ systems requiring modern C++20/23 features, template metaprogramming, or zero-overhead abstractions for systems programming, embedded systems, or performance-critical applications. | VoltAgent |
| `debugging-toolkit-dx-optimizer` | Developer Experience specialist. | wshobson |
| `fastify-expert` | Expert in building high-performance Node.js applications using Fastify framework. | 0xfurai |
| `fund-operations` | Compute fund KPIs (TVPI, DPI, IRR, MOIC), model carried interest and management fees, and generate LP quarterly update narratives. | davepoon |
| `go-expert` | Go specialist focusing on idiomatic Go, concurrency, and performance optimization. | 0xfurai |
| `gsd-user-profiler` | Analyzes extracted session messages across 8 behavioral dimensions to produce a scored developer profile with confidence levels and evidence. | davepoon |
| `hr-pro` | Professional, ethical HR partner for hiring, onboarding/offboarding, PTO and leave, performance, compliant policies, and employee relations. | wshobson |
| `julia-pro` | Master Julia 1.10+ with modern features, performance optimization, multiple dispatch, and production-ready practices. | wshobson |
| `life-cynic` | The Cynic of the life team. | davepoon |
| `lua-expert` | Write efficient and idiomatic Lua code, mastering the language features, patterns, and performance optimization. | 0xfurai |
| `marketing-optimizer` | Cross-platform ad budget optimization — reads Meta + Google Ads data, computes blended ROAS, and recommends specific budget shifts. | davepoon |
| `nodejs-expert` | Specializes in Node.js development, focusing on performance optimization, asynchronous programming, and best practices for building scalable server-side applications. | 0xfurai |
| `opensearch-expert` | Expert in OpenSearch cluster management, query optimization, indexing strategies, and performance tuning. | 0xfurai |
| `phoenix-expert` | Expert in Phoenix framework, optimizing web applications, and ensuring best practices. | 0xfurai |
| `rollup-expert` | Expert in Rollup.js for bundling JavaScript projects with optimal performance and configuration. | 0xfurai |
| `ruby-expert` | Expert in Ruby programming language, focusing on idiomatic Ruby, performance optimization, and best practices. | 0xfurai |
| `rust-engineer` | Use when building Rust systems where memory safety, ownership patterns, zero-cost abstractions, and performance optimization are critical for systems programming, embedded development, async applications, or high-performance services. | VoltAgent |
| `rust-expert` | Expert in writing idiomatic Rust code with focus on safety, concurrency, and performance. | 0xfurai |
| `scala-expert` | Scala expert specializing in functional programming, type safety, and performance optimization. | 0xfurai |
| `seo-meta-optimizer` | Creates optimized meta titles, descriptions, and URL suggestions based on character limits and best practices. | wshobson |
| `seo-podcast-optimizer` | You are an SEO consultant specializing in tech podcasts. | davepoon |
| `szamlazz-invoicing` | Issue, cancel, and fetch Hungarian invoices via the szamlazz.hu Agent API. | davepoon |
| `twitter-algorithm-optimizer` | Analyze and optimize tweets for maximum reach using Twitter's open-source algorithm insights. | davepoon |

## Plugins & Tooling

_2 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `gsd:undo` | Safe git revert. Roll back phase or plan commits using the phase manifest with dependency checks." argument-hint: "--last N \| --phase NN \| --plan NN-MM" allowed-tools: - Read - Bash - Glob - Grep - As... | davepoon |
| `tooling-engineer` | Use this agent when you need to build or enhance developer tools including CLIs, code generators, build tools, and IDE extensions. | VoltAgent |

## Product & Business

_46 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `assumption-mapping` | Use when the user needs to identify and prioritize risky assumptions in a product idea, feature, or strategy. | VoltAgent |
| `backlog-grooming` | Use when the user needs to groom, refine, or clean up a product backlog. | VoltAgent |
| `business-analyst` | Use when analyzing business processes, gathering requirements from stakeholders, or identifying process improvement opportunities to drive operational efficiency and measurable business value. | VoltAgent |
| `business-boss` | The Boss of the business team. | davepoon |
| `business-cynic` | The Cynic of the business team. | davepoon |
| `business-pusher` | The Pusher of the business team. | davepoon |
| `business-rookie` | The Rookie of the business team. | davepoon |
| `closing-costs` | Calculates itemized state-specific closing costs for mortgage refinance transactions across 10 licensed states, with product-specific fees for Conventional, FHA, FHA Streamline, VA IRRRL, and VA Cash-Out. | davepoon |
| `coinpaprika-api` | Access cryptocurrency market data from CoinPaprika: prices, tickers, OHLCV, exchanges, contract lookups for 12,000+ coins and 350+ exchanges. | davepoon |
| `competitive-ads-extractor` | Extracts and analyzes competitors' ads from ad libraries (Facebook, LinkedIn, etc.) to understand what messaging, problems, and creative approaches are working. | davepoon |
| `competitive-analyst` | Use when you need to analyze direct and indirect competitors, benchmark against market leaders, or develop strategies to strengthen competitive positioning and market advantage. | VoltAgent |
| `content-marketer` | Use this agent when you need to develop comprehensive content strategies, create SEO-optimized marketing content, or execute multi-channel content campaigns to drive engagement and conversions. | VoltAgent |
| `content-writer` | Use this agent when you need to create compelling, informative content that explains complex topics in simple terms. | iannuttall |
| `customer-success-manager` | Use this agent when you need to assess customer health, develop retention strategies, identify upsell opportunities, or maximize customer lifetime value. | VoltAgent |
| `design-bridge` | Use this agent when you need to translate a DESIGN.md from the VoltAgent/awesome-design-md repository into polished Claude Code instructions for building user interfaces that faithfully match the chosen brand. | VoltAgent |
| `dexpaprika-api` | Access DeFi data from DexPaprika: token prices, liquidity pools, OHLCV, transactions across 34+ blockchains and 30M+ pools. | davepoon |
| `error-debugging-error-detective` | Search logs and codebases for error patterns, stack traces, and anomalies. | wshobson |
| `feature-spec` | Creates a complete product feature specification with acceptance criteria, scope, dependencies, and risks. | davepoon |
| `growth-loops` | Use when the user wants to design a growth loop, understand PLG mechanics, or build sustainable acquisition. | VoltAgent |
| `market-research-analyst` | Conducts comprehensive market research and competitive analysis for business strategy and investment decisions. | davepoon |
| `market-researcher` | Use this agent when you need to analyze markets, understand consumer behavior, assess competitive landscapes, and size opportunities to inform business strategy and market entry decisions. | VoltAgent |
| `market-size` | Run TAM/SAM/SOM market sizing with top-down and bottom-up methods, competitive landscape, and tech stack analysis. | davepoon |
| `marketing-writer` | Marketing content specialist for product descriptions, landing pages, blog posts, and technical marketing materials | webdevtodayjason |
| `nlp-engineer` | Use when building production NLP systems, implementing text processing pipelines, developing language models, or solving domain-specific NLP tasks like named entity recognition, sentiment analysis, or machine translation. | VoltAgent |
| `ocr-grammar-fixer` | You are an OCR Grammar Fixer specializing in cleaning up text processed through OCR that contains recognition errors, spacing issues, or grammatical problems. | davepoon |
| `ops-dash` | Interactive pixel-art command center dashboard. | davepoon |
| `ops-next` | Business-level "what should I do next". | davepoon |
| `product-boss` | The Boss of the product team. | davepoon |
| `product-cynic` | The Cynic of the product team. | davepoon |
| `product-manager` | Use this agent when you need to make product strategy decisions, prioritize features, or define roadmap plans based on user needs and business goals. | VoltAgent |
| `product-pusher` | The Pusher of the product team. | davepoon |
| `product-watcher` | The Watcher of the product team. | davepoon |
| `prometeo-pm` | Product Manager agent for product strategy, feature specifications, user stories, business logic, prioritization, and roadmap management. | davepoon |
| `sales-automator` | Draft cold emails, follow-ups, and proposal templates. | wshobson |
| `salesforce-automation` | Automate Salesforce tasks via Rube MCP (Composio): leads, contacts, accounts, opportunities, SOQL queries. | davepoon |
| `shopify-automation` | Automate Shopify tasks via Rube MCP (Composio): products, orders, customers, inventory, collections. | davepoon |
| `soft-predict-future` | > Activate this skill for ANY future-oriented question. | davepoon |
| `startup-analyst` | Expert startup business analyst specializing in market sizing, financial modeling, competitive analysis, and strategic planning for early-stage companies. | wshobson |
| `stripe-automation` | Automate Stripe tasks via Rube MCP (Composio): customers, charges, subscriptions, invoices, products, refunds. | davepoon |
| `toggl-tracking` | Track time with Toggl from Claude — start and stop timers, log hours to projects and clients, generate weekly reports, and manage time entries for billing and productivity. | davepoon |
| `tycana` | Persistent task management and productivity intelligence via MCP. | davepoon |
| `whatsapp-automation` | Automate WhatsApp Business tasks via Rube MCP (Composio): send messages, manage templates, upload media, and handle contacts. | davepoon |
| `whatsapp-messaging` | Send and receive WhatsApp messages through Claude — search contacts, read conversations, send text, images, audio, and files via WhatsApp Business API MCP integration. | davepoon |
| `wordpress-management` | Manage WordPress sites from Claude — create and edit posts, manage users, handle WooCommerce products, configure plugins and settings via the WordPress REST API. | davepoon |
| `workflow-orchestrator` | Use this agent when you need to design, implement, or optimize complex business process workflows with multiple states, error handling, and transaction management. | VoltAgent |
| `yolo-ceo` | Strategic priority agent. | davepoon |

## Refactoring & Modernization

_26 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `clojure-expert` | Master Clojure development with a focus on functional programming, immutability, concurrency, and Lisp macros. | 0xfurai |
| `code-refactoring-legacy-modernizer` | Refactor legacy codebases, migrate outdated frameworks, and implement gradual modernization. | wshobson |
| `codebase-orchestrator` | Use this agent when you need repository-wide refactor governance with explicit approval loops, weighted risk prioritization, diff previews, and deterministic fallback strategies. | VoltAgent |
| `cpp-engineer` | Write idiomatic C++ code with modern features, RAII, smart pointers, and STL algorithms. | davepoon |
| `css-expert` | Master CSS stylist with expertise in layouts, responsive design, animations, and accessibility. | 0xfurai |
| `dotnet-framework-4.8-expert` | Use this agent when working on legacy .NET Framework 4.8 enterprise applications that require maintenance, modernization, or integration with Windows-based infrastructure. | VoltAgent |
| `elixir-pro` | Write idiomatic Elixir code with OTP patterns, supervision trees, and Phoenix LiveView. | wshobson |
| `flyway-expert` | Master Flyway for database migrations, versioning, and schema management. | 0xfurai |
| `golang-expert` | Write idiomatic Go code with goroutines, channels, and interfaces. | davepoon |
| `haskell-expert` | Write idiomatic Haskell code with advanced type system features, monads, and functional programming techniques. | 0xfurai |
| `implementer` | Delegates autonomous implementation work to a Codex agent running in an isolated git worktree. | davepoon |
| `javascript-pro` | Use this agent when you need to build, optimize, or refactor modern JavaScript code for browser, Node.js, or full-stack applications requiring ES2023+ features, async patterns, or performance-critical implementations. | VoltAgent |
| `knex-expert` | Expertise in Knex.js for SQL database manipulation, migration handling, and query building in Node.js environments. | 0xfurai |
| `kotlin-intelligence` | Kotlin code intelligence via Language Server Protocol — completions, diagnostics, go-to-definition, and refactoring for Android and JVM projects. | davepoon |
| `laravel-eloquent-expert` | Specialized in Laravel’s Eloquent ORM—designing schemas & migrations, modeling complex relationships, writing efficient queries, and tuning database performance. | vijaythecoder |
| `legacy-analyst` | Deep-reads legacy codebases (COBOL, Java, .NET, Node, anything) to build structural and behavioral understanding. | Anthropic Official |
| `legacy-modernizer` | Use this agent when modernizing legacy systems that need incremental migration strategies, technical debt reduction, and risk mitigation while maintaining business continuity. | VoltAgent |
| `liquibase-expert` | Expert in Liquibase for database schema management, migrations, and version control. | 0xfurai |
| `powershell-5.1-expert` | Use when automating Windows infrastructure tasks requiring PowerShell 5.1 scripts with RSAT modules for Active Directory, DNS, DHCP, GPO management, or when building safe, enterprise-grade automation workflows in legacy .NET Framework environments. | VoltAgent |
| `prisma-expert` | Write efficient, type-safe, and maintainable database queries using Prisma. | 0xfurai |
| `refactor` | Code refactoring specialist. | webdevtodayjason |
| `refactoring-specialist` | Use when you need to transform poorly structured, complex, or duplicated code into clean, maintainable systems while preserving all existing behavior. | VoltAgent |
| `sequelize-expert` | Expert in Sequelize ORM, proficient in database modeling, querying, associations, and migrations. | 0xfurai |
| `swift-intelligence` | Swift code intelligence via Language Server Protocol — completions, diagnostics, go-to-definition, and refactoring for iOS and macOS projects. | davepoon |
| `tailwind-frontend-expert` | MUST BE USED for any Tailwind‑CSS styling, utility‑first refactors, or responsive component work. | vijaythecoder |
| `typescript-expert` | Expert in TypeScript specializing in type safety, async patterns, and modern ES features. | 0xfurai |

## Research & Analysis

_14 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `academic-research-synthesizer` | Synthesize academic research from multiple sources with citations. | davepoon |
| `academic-researcher` | Find and analyze scholarly sources, research papers, and academic literature. | davepoon |
| `cohort-analysis` | Use when the user wants to analyze retention, cohort behavior, engagement trends, or understand how different user groups perform over time. | VoltAgent |
| `gsd-advisor-researcher` | Researches a single gray area decision and returns a structured comparison table with rationale. | davepoon |
| `gsd-debugger` | Investigates bugs using scientific method, manages debug sessions, handles checkpoints. | davepoon |
| `gsd-phase-researcher` | Researches how to implement a phase before planning. | davepoon |
| `gsd-project-researcher` | Researches domain ecosystem before roadmap creation. | davepoon |
| `gsd-research-synthesizer` | Synthesizes research outputs from parallel researcher agents into SUMMARY.md. | davepoon |
| `gsd:research-phase` | Research how to implement a phase (standalone - usually use /gsd:plan-phase instead) argument-hint: "[phase]" allowed-tools: - Read - Bash - Task | davepoon |
| `report-generator` | You are the Report Generator, a specialized expert in transforming synthesized research findings into comprehensive, well-structured final reports. | davepoon |
| `research-analyst` | Use this agent when you need comprehensive research across multiple sources with synthesis of findings into actionable insights, trend identification, and detailed reporting. | VoltAgent |
| `research-brief-generator` | Transforms user research queries into structured, actionable research briefs with specific questions, keywords, source preferences, and success criteria. | davepoon |
| `research-coordinator` | Strategically plan and coordinate complex research tasks across multiple specialists. | davepoon |
| `research-synthesizer` | Consolidate and synthesize findings from multiple research sources into unified analysis. | davepoon |

## Security & Compliance

_139 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `Python Security Expert` | Specialized agent for Python security, cryptography, secure coding practices, vulnerability assessment, and compliance | vijaythecoder |
| `accessibility-expert` | Expert accessibility specialist ensuring WCAG compliance, inclusive design, and assistive technology compatibility. | wshobson |
| `accessibility-specialist` | Ensure web applications meet WCAG 2.1 AA/AAA standards. | davepoon |
| `accessibility-tester` | Use this agent when you need comprehensive accessibility testing, WCAG compliance verification, or assessment of assistive technology support. | VoltAgent |
| `ad-security-reviewer` | Use this agent when you need to audit Active Directory security posture, evaluate privilege escalation risks, review identity delegation patterns, or assess authentication protocol hardening. | VoltAgent |
| `ag2-reviewer` | Reviews AG2 agent code for tool contract violations, prompt quality, security issues, and best practices. | davepoon |
| `ai-writing-auditor` | Use this agent when you need to audit content for AI writing patterns and rewrite text to remove them. | VoltAgent |
| `api-architect` | Universal API designer specializing in RESTful design, GraphQL schemas, and modern contract standards. | vijaythecoder |
| `api-designer` | Use this agent when designing new APIs, creating API specifications, or refactoring existing API architecture for scalability and developer experience. | VoltAgent |
| `api-security-audit` | Conduct security audits for REST APIs and identify vulnerabilities. | davepoon |
| `aurakit` | Sonnet Amplified fullstack engine. | davepoon |
| `auth-patterns` | This skill should be used when the user asks about "authentication in Next.js", "NextAuth", "Auth.js", "middleware auth", "protected routes", "session management", "JWT", "login flow", or needs guidan... | davepoon |
| `auth0-expert` | Expert in Auth0 implementation, configuration, and best practices | 0xfurai |
| `backend-development-graphql-architect` | Master modern GraphQL with federation, performance optimization, and enterprise security. | wshobson |
| `blockchain-developer` | Use this agent when building smart contracts, DApps, and blockchain protocols that require expertise in Solidity, gas optimization, security auditing, and Web3 integration. | VoltAgent |
| `business-watcher` | The Watcher of the business team. | davepoon |
| `centinela-qa` | QA Engineer and Security Auditor agent for code review, security auditing, testing verification, compliance checking, dead code detection, and quality gates. | davepoon |
| `claim-auditor` | Quantitative report auditor. | davepoon |
| `cloud-architect` | Use this agent when you need to design, evaluate, or optimize cloud infrastructure architecture at scale. | VoltAgent |
| `cloud-infrastructure-cloud-architect` | Expert cloud architect specializing in AWS/Azure/GCP/OCI multi-cloud infrastructure design, advanced IaC (Terraform/OpenTofu/CDK), FinOps cost optimization, and modern architectural patterns. | wshobson |
| `cloud-infrastructure-deployment-engineer` | Expert deployment engineer specializing in modern CI/CD pipelines, GitOps workflows, and advanced deployment automation. | wshobson |
| `cloud-infrastructure-network-engineer` | Expert network engineer specializing in modern cloud networking, security architectures, and performance optimization. | wshobson |
| `code-archaeologist` | MUST BE USED to explore and document unfamiliar, legacy, or complex codebases. | vijaythecoder |
| `code-refactorer` | Use this agent when you need to improve existing code structure, readability, or maintainability without changing functionality. | iannuttall |
| `code-refactorer-agent` | Use this agent when you need to improve existing code structure, readability, or maintainability without changing functionality. | zhsama |
| `code-refactoring-code-reviewer` | Elite code review expert specializing in modern AI-powered code analysis, security vulnerabilities, performance optimization, and production reliability. | wshobson |
| `code-simplifier` | \| Use this agent when code has been written or modified and needs to be simplified for clarity, consistency, and maintainability while preserving all functionality. | Anthropic Official |
| `compliance-auditor` | Use this agent when you need to achieve regulatory compliance, implement compliance controls, or prepare for audits across frameworks like GDPR, HIPAA, PCI DSS, SOC 2, and ISO standards. | VoltAgent |
| `comprehensive-researcher` | Conduct in-depth research with multiple sources, cross-verification, and structured reports. | davepoon |
| `dashboard` | View all tracked vulnerabilities and their current status user-invocable: true allowed-tools: Read, Glob, Grep | davepoon |
| `data-validation-suite-backend-security-coder` | Expert in secure backend coding practices specializing in input validation, authentication, and API security. | wshobson |
| `database-admin` | Expert database administrator specializing in modern cloud databases, automation, and reliability engineering. | wshobson |
| `deno-expert` | Expert in Deno for modern JavaScript and TypeScript runtime, security, performance, and tooling. | 0xfurai |
| `dependency-checker` | Monitor and audit dependencies for security vulnerabilities and updates | davepoon |
| `dependency-manager` | Use this agent when you need to audit dependencies for vulnerabilities, resolve version conflicts, optimize bundle sizes, or implement automated dependency updates. | VoltAgent |
| `deployment-strategies-terraform-specialist` | Expert Terraform/OpenTofu specialist mastering advanced IaC automation, state management, and enterprise infrastructure patterns. | wshobson |
| `dev-watcher` | The Watcher of the dev team. | davepoon |
| `devops-engineer` | Use this agent when building or optimizing infrastructure automation, CI/CD pipelines, containerization strategies, and deployment workflows to accelerate software delivery while maintaining reliability and security. | VoltAgent |
| `digital-presence` | Monitor and audit your digital presence — track brand mentions, social profiles, website SEO, domain health, and online reputation across platforms. | davepoon |
| `electron-expert` | Specializes in building cross-platform desktop applications using Electron. | 0xfurai |
| `electron-pro` | Use this agent when building Electron desktop applications that require native OS integration, cross-platform distribution, security hardening, and performance optimization. | VoltAgent |
| `event-sourcing-architect` | Expert in event sourcing, CQRS, and event-driven architecture patterns. | wshobson |
| `exploits` | Analyze exploit intelligence for a vulnerability against the current repository argument-hint: <vuln-id> user-invocable: true allowed-tools: Bash, Read, Glob, Grep, Edit, Write, WebFetch | davepoon |
| `exploits-search` | Search for exploits across all vulnerabilities with filtering by ecosystem, severity, source, and EPSS argument-hint: [search query] user-invocable: true allowed-tools: Bash, Read, Glob, Grep, Edit, W... | davepoon |
| `feedoracle-compliance` | MiCA compliance evidence and stablecoin risk scoring. | davepoon |
| `fintech-engineer` | Use when building payment systems, financial integrations, or compliance-heavy financial applications that require secure transaction processing, regulatory adherence, and high transaction accuracy. | VoltAgent |
| `firmware-analyst` | Expert firmware analyst specializing in embedded systems, IoT security, and hardware reverse engineering. | wshobson |
| `fix` | Get fix intelligence for a vulnerability and propose concrete remediation for the current repository argument-hint: <vuln-id> user-invocable: true allowed-tools: Bash, Read, Glob, Grep, Edit, Write, W... | davepoon |
| `frontend-security-coder` | Expert in secure frontend coding practices specializing in XSS prevention, output sanitization, and client-side security patterns. | wshobson |
| `gcloud-check` | Run a comprehensive Google Cloud CLI health check — verify installation, authentication, active project, enabled APIs, billing status, and Cloud Run service health. | davepoon |
| `gdpr-ccpa-compliance` | Use when the user needs to understand GDPR or CCPA compliance, review data practices, or assess privacy requirements. | VoltAgent |
| `git_hub_cleanse` | Pre-push security cleanser for any repo destined for GitHub. | Personal |
| `git_hub_testi` | Post-cleanse verification agent. | Personal |
| `github-check` | Run a GitHub CLI health check — verify gh authentication, list accessible repos, check API rate limits, and test push/pull connectivity. | davepoon |
| `gsd-code-reviewer` | Reviews source files for bugs, security issues, and code quality problems. | davepoon |
| `gsd-eval-auditor` | Retroactive audit of an implemented AI phase's evaluation coverage. | davepoon |
| `gsd-nyquist-auditor` | Fills Nyquist validation gaps by generating tests and verifying coverage for phase requirements | davepoon |
| `gsd-security-auditor` | Verifies threat mitigations from PLAN.md threat model exist in implemented code. | davepoon |
| `gsd-ui-auditor` | Retroactive 6-pillar visual audit of implemented frontend code. | davepoon |
| `gsd:audit-fix` | Autonomous audit-to-fix pipeline — find issues, classify, fix, test, commit argument-hint: "--source <audit-uat> [--severity <medium\|high\|all>] [--max N] [--dry-run]" allowed-tools: - Read - Write - E... | davepoon |
| `gsd:audit-milestone` | Audit milestone completion against original intent before archiving argument-hint: "[version]" allowed-tools: - Read - Glob - Grep - Bash - Task - Write | davepoon |
| `gsd:audit-uat` | Cross-phase audit of all outstanding UAT and verification items allowed-tools: - Read - Glob - Grep - Bash | davepoon |
| `gsd:code-review` | Review source files changed during a phase for bugs, security issues, and code quality problems argument-hint: "<phase-number> [--depth=quick\|standard\|deep] [--files file1,file2,...]" allowed-tools: -... | davepoon |
| `gsd:eval-review` | Retroactively audit an executed AI phase's evaluation coverage — scores each eval dimension as COVERED/PARTIAL/MISSING and produces an actionable EVAL-REVIEW.md with remediation plan argument-hint: "[... | davepoon |
| `gsd:map-codebase` | Analyze codebase with parallel mapper agents to produce .planning/codebase/ documents argument-hint: "[optional: specific area to map, e.g., 'api' or 'auth']" allowed-tools: - Read - Bash - Glob - Gre... | davepoon |
| `gsd:plan-milestone-gaps` | Create phases to close all gaps identified by milestone audit allowed-tools: - Read - Write - Bash - Glob - Grep - AskUserQuestion | davepoon |
| `gsd:progress` | Check project progress, show context, and route to next action (execute or plan). | davepoon |
| `gsd:ui-review` | Retroactive 6-pillar visual audit of implemented frontend code argument-hint: "[phase]" allowed-tools: - Read - Write - Bash - Glob - Grep - Task - AskUserQuestion | davepoon |
| `gsd:validate-phase` | Retroactively audit and fill Nyquist validation gaps for a completed phase argument-hint: "[phase number]" allowed-tools: - Read - Write - Edit - Bash - Glob - Grep - Task - AskUserQuestion | davepoon |
| `hard-screening-startup` | Deterministic Python-scored startup screening with full audit trail. | davepoon |
| `healthcare-admin` | Use when working on healthcare administration tasks including revenue cycle management, HIPAA/compliance auditing, medical coding (ICD-10, CPT, DRGs), CMS cost reports, payer contract analysis, qualit... | VoltAgent |
| `hipaa-compliance` | Use when the user is building a healthcare product and needs to understand HIPAA compliance. | VoltAgent |
| `hybrid-cloud-architect` | Expert hybrid cloud architect specializing in complex multi-cloud solutions across AWS/Azure/GCP/OCI and private clouds (OpenStack/VMware). | wshobson |
| `immich-photo-manager` | Manage your self-hosted Immich photo library through conversation — natural language search, geographic album curation, duplicate detection, library health audits, and interactive HTML galleries. | davepoon |
| `incident-responder` | Use this agent when an active security breach, service outage, or operational incident requires immediate response, evidence preservation, and coordinated recovery. | VoltAgent |
| `jwt-expert` | Specializes in JSON Web Tokens (JWT) implementation, security, and optimization. | 0xfurai |
| `kubernetes-operations-kubernetes-architect` | Expert Kubernetes architect specializing in cloud-native infrastructure, advanced GitOps workflows (ArgoCD/Flux), and enterprise container orchestration. | wshobson |
| `legal-advisor` | Use this agent when you need to draft contracts, review compliance requirements, develop IP protection strategies, or assess legal risks for technology businesses. | VoltAgent |
| `license-engineer` | Use this agent when architecting, implementing, or optimizing end-to-end legal licensing systems—from OSI standard selection and dependency compliance pipelines to proprietary deployment and risk monitoring. | VoltAgent |
| `malware-analyst` | Expert malware analyst specializing in defensive malware research, threat intelligence, and incident response. | wshobson |
| `mcp-deployment-orchestrator` | Deploys MCP servers to production with containerization, Kubernetes deployments, autoscaling, monitoring, and high-availability operations. | davepoon |
| `mcp-security-auditor` | You are an MCP Security Auditor specializing in reviewing MCP server implementations for vulnerabilities, designing authentication systems, and ensuring compliance. | davepoon |
| `mcp-server-architect` | Designs and implements MCP servers with transport layers, tool/resource/prompt definitions, completion support, session management, and protocol compliance. | davepoon |
| `mcp-testing-engineer` | Tests, debugs, and ensures quality for MCP servers including JSON schema validation, protocol compliance, security vulnerability assessment, load testing, and comprehensive debugging. | davepoon |
| `memstack` | 127 production skills across 10 categories (Security, Deployment, Dev, Business, Content, SEO, Marketing, Product, Automation, Core). | davepoon |
| `mobile-security-coder` | Expert in secure mobile coding practices specializing in input validation, WebView security, and mobile-specific security patterns. | wshobson |
| `mortgage-compliance` | Enforces mortgage regulatory compliance — TRID, RESPA, TILA, ECOA/Fair Lending, state licensing, required disclosures, and data privacy rules for all borrower interactions. | davepoon |
| `mqtt-expert` | Master of MQTT protocol, focusing on message brokering, QoS levels, and efficient IoT communication. | 0xfurai |
| `nats-expert` | Specialized in NATS, handling messaging patterns, scalability, and security features accurately within NATS deployments. | 0xfurai |
| `network-engineer` | Use this agent when designing, optimizing, or troubleshooting cloud and hybrid network infrastructures, or when addressing network security, performance, or reliability challenges. | VoltAgent |
| `notify-before-bash` | Show notification before any Bash command execution for security awareness | davepoon |
| `oauth-oidc-expert` | Expert in OAuth 2.0 and OpenID Connect (OIDC) for secure authentication and authorization. | 0xfurai |
| `ops-inbox` | Full inbox management across all channels — WhatsApp (wacli), Email (Gmail MCP), Slack (MCP), Telegram (user-auth MCP), Discord (webhook + REST read), Notion (MCP — comments, mentions, assigned tasks). | davepoon |
| `ops-integrate` | Add any SaaS API as a first-class integration. | davepoon |
| `ops-orchestrate` | Autonomous multi-project orchestration engine. | davepoon |
| `opus-reviewer` | Tier 3 (deep) Ralph Review. | davepoon |
| `owasp-top10-expert` | OWASP Top 10 expert specializing in identifying and mitigating the most critical web application security risks. | 0xfurai |
| `package-search` | Search for packages and assess security risk before adding as dependencies argument-hint: <package-name> user-invocable: true allowed-tools: Bash, Read, Glob, Grep, Edit, Write | davepoon |
| `payment-integration` | Use this agent when implementing payment systems, integrating payment gateways, or handling financial transactions that require PCI compliance, fraud prevention, and secure transaction processing. | VoltAgent |
| `penetration-tester` | Use this agent when you need to conduct authorized security penetration tests to identify real vulnerabilities through active exploitation and validation. | VoltAgent |
| `policy-enforcer` | Cedar policy author and reviewer for Claude Code tool calls. | wshobson |
| `powershell-security-hardening` | Use this agent when you need to harden PowerShell automation, secure remoting configuration, enforce least-privilege design, or align scripts with enterprise security baselines and compliance frameworks. | VoltAgent |
| `prd-writer` | Use this agent when you need to create a comprehensive Product Requirements Document (PRD) for a software project or feature. | iannuttall |
| `prompt_perfect_Agent` | Use this agent whenever the user wants to write, rewrite, refine, debug, or audit a prompt for any LLM (Claude, GPT, Gemini, etc.). | Personal |
| `receipt-verifier` | Expert in Ed25519 signed receipts, JCS canonicalization, hash chains, and offline verification. | wshobson |
| `release-check` | Pre-release verification checklist. | davepoon |
| `remediation` | Get a context-aware remediation plan for a vulnerability with fix verification steps argument-hint: <vuln-id> user-invocable: true allowed-tools: Bash, Read, Glob, Grep, Edit, Write | davepoon |
| `reverse-engineer` | Expert reverse engineer specializing in binary analysis, disassembly, decompilation, and software analysis. | wshobson |
| `review` | PR Reviewer agent. Reviews implemented code using a 3-tier taxonomy (🔴 Critical / 🟡 Should Fix / 💡 Consider). | wshobson |
| `review-policy-author` | Cedar policy author specialized in gating AI agent review actions (PR comments, reviews, merges, CI edits) behind human approval. | wshobson |
| `reviewer` | Runs a Codex-powered read-only code review using a SOTA GPT model. | davepoon |
| `risk-manager` | Use this agent when you need to identify, quantify, and mitigate enterprise-level risks across financial, operational, regulatory, and strategic domains. | VoltAgent |
| `security-audit` | Deep security audit covering OWASP Top 10, authentication, authorization, data protection, dependency vulnerabilities, and secrets scanning. | davepoon |
| `security-auditor` | Adversarial security reviewer — OWASP Top 10, CWE, dependency CVEs, secrets, injection. | Anthropic Official |
| `security-engineer` | Use this agent when implementing comprehensive security solutions across infrastructure, building automated security controls into CI/CD pipelines, or establishing compliance and vulnerability management programs. | VoltAgent |
| `security-guardrails` | Adversarial defense layer for the mortgage plugin — protects against prompt injection, system prompt extraction, PII leakage, workflow bypass, and social engineering attacks. | davepoon |
| `security-scanner` | Scan code for security vulnerabilities and secrets after modifications | davepoon |
| `security-scanning-security-auditor` | Expert security auditor specializing in DevSecOps, comprehensive cybersecurity, and compliance frameworks. | wshobson |
| `seo-authority-builder` | Analyzes content for E-E-A-T signals and suggests improvements to build authority and trust. | wshobson |
| `seo-content-auditor` | Analyzes provided content for quality, E-E-A-T signals, and SEO best practices. | wshobson |
| `seo-specialist` | Use this agent when you need comprehensive SEO optimization encompassing technical audits, keyword strategy, content optimization, and search rankings improvement. | VoltAgent |
| `service-mesh-expert` | Expert service mesh architect specializing in Istio, Linkerd, and cloud-native networking patterns. | wshobson |
| `silent-failure-hunter` | Use this agent when reviewing code changes in a pull request to identify silent failures, inadequate error handling, and inappropriate fallback behavior. | Anthropic Official |
| `slack-expert` | Use this agent when developing Slack applications, implementing Slack API integrations, or reviewing Slack bot code for security and best practices. | VoltAgent |
| `soft-screening-startup` | Activate for ANY startup evaluation, investment screening, or company assessment. | davepoon |
| `sosa-audit` | Audit plugins and skills against the SOSA governance framework — check Supervised, Orchestrated, Secured, Agents compliance and generate remediation reports. | davepoon |
| `spec-architect` | System architect specializing in technical design and architecture. | zhsama |
| `spec-reviewer` | Senior code reviewer specializing in code quality, best practices, and security. | zhsama |
| `spec-tester` | Comprehensive testing specialist that creates and executes test suites. | zhsama |
| `spec-validator` | Final quality validation specialist that ensures requirements compliance and production readiness. | zhsama |
| `tdd-workflows-code-reviewer` | Elite code review expert specializing in modern AI-powered code analysis, security vulnerabilities, performance optimization, and production reliability. | wshobson |
| `team-reviewer` | Multi-dimensional code reviewer that operates on one assigned review dimension (security, performance, architecture, testing, or accessibility) with structured finding format. | wshobson |
| `threat-modeling-expert` | Expert in threat modeling methodologies, security architecture review, and risk assessment. | wshobson |
| `token-audit` | Audit Claude plugins and skills for token waste — check description bloat, skill body length, unused MCP connectors, duplicate data, and context overhead. | davepoon |
| `ui-visual-validator` | Rigorous visual validation expert specializing in UI testing, design system compliance, and accessibility verification. | wshobson |
| `vuln` | Look up a vulnerability by ID or list all vulnerabilities for a package argument-hint: <vuln-id or package-name> user-invocable: true allowed-tools: Bash, Read, Glob, Grep, Edit, Write | davepoon |
| `windows-infra-admin` | Use when managing Windows Server infrastructure, Active Directory, DNS, DHCP, and Group Policy configurations, especially for enterprise-scale deployments requiring safe automation and compliance validation. | VoltAgent |
| `wordpress-developer` | Build professional WordPress solutions with custom themes, plugins, and advanced functionality. | davepoon |
| `wordpress-master` | Use this agent when you need to architect, optimize, or troubleshoot WordPress implementations ranging from custom theme/plugin development to enterprise-scale multisite platforms. | VoltAgent |

## Testing & QA

_51 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `ab-test-analysis` | Use when the user wants to analyze A/B test results, interpret p-values, determine statistical significance, or make a ship/no-ship decision. | VoltAgent |
| `agent-sdk-verifier-py` | Use this agent to verify that a Python Agent SDK application is properly configured, follows SDK best practices and documentation recommendations, and is ready for deployment or testing. | Anthropic Official |
| `agent-sdk-verifier-ts` | Use this agent to verify that a TypeScript Agent SDK application is properly configured, follows SDK best practices and documentation recommendations, and is ready for deployment or testing. | Anthropic Official |
| `ava-expert` | Expert in Ava for running tests and managing test suites efficiently. | 0xfurai |
| `bash-expert` | Master of defensive Bash scripting for production automation, CI/CD pipelines, and system utilities. | 0xfurai |
| `bash-pro` | Master of defensive Bash scripting for production automation, CI/CD pipelines, and system utilities. | wshobson |
| `build` | Autonomous app-building skill — transforms plain-English descriptions into fully built, tested, and deployed applications via a 9-phase pipeline | davepoon |
| `business-rules-extractor` | Mines domain logic, calculations, validations, and policies from legacy code into testable Given/When/Then specifications. | Anthropic Official |
| `chaos-engineer` | Use this agent when you need to design and execute controlled failure experiments, validate system resilience before incidents occur, or conduct game day exercises to test your team's incident response capabilities. | VoltAgent |
| `circleci-automation` | Automate CircleCI tasks via Rube MCP (Composio): trigger pipelines, monitor workflows/jobs, retrieve artifacts and test metadata. | davepoon |
| `csharp-pro` | Write modern C# code with advanced features like records, pattern matching, and async/await. | wshobson |
| `cypress-expert` | Expert in Cypress testing framework for end-to-end testing and automation. | 0xfurai |
| `data-scientist` | Use this agent when you need to analyze data patterns, build predictive models, or extract statistical insights from datasets. | VoltAgent |
| `debugging-toolkit-debugger` | Debugging specialist for errors, test failures, and unexpected behavior. | wshobson |
| `dev-rookie` | The Rookie of the dev team. | davepoon |
| `dx-optimizer` | Use this agent when optimizing the complete developer workflow including build times, feedback loops, testing efficiency, and developer satisfaction metrics across the entire development environment. | VoltAgent |
| `gsd:add-tests` | Generate tests for a completed phase based on UAT criteria and implementation argument-hint: "<phase> [additional instructions]" allowed-tools: - Read - Write - Edit - Bash - Glob - Grep - Task - AskU... | davepoon |
| `gsd:execute-phase` | Execute all plans in a phase with wave-based parallelization argument-hint: "<phase-number> [--wave N] [--gaps-only] [--interactive] [--tdd]" allowed-tools: - Read - Write - Edit - Glob - Grep - Bash ... | davepoon |
| `gsd:plan-phase` | Create detailed phase plan (PLAN.md) with verification loop argument-hint: "[phase] [--auto] [--research] [--skip-research] [--gaps] [--skip-verify] [--prd <file>] [--reviews] [--text] [--tdd] | davepoon |
| `gsd:update` | Update GSD to latest version with changelog display allowed-tools: - Bash - AskUserQuestion | davepoon |
| `jest-expert` | Expert in testing JavaScript applications using Jest, ensuring comprehensive test coverage and efficient test practices. | 0xfurai |
| `laravel-expert` | Expert in Laravel framework, mastering modern Laravel features, Eloquent ORM, and comprehensive testing strategies. | 0xfurai |
| `life-rookie` | The Rookie of the life team. | davepoon |
| `mocha-expert` | Expertise in Mocha, the JavaScript test framework running on Node.js, focusing on writing, organizing, and executing tests efficiently. | 0xfurai |
| `ops-settings` | Post-setup credential manager. | davepoon |
| `playwright` | Playwright testing agent. | wshobson |
| `playwright-expert` | Expert in Playwright testing for modern web applications. | 0xfurai |
| `product-rookie` | The Rookie of the product team. | davepoon |
| `project-idea-validator` | Use this agent when you need an idea pressure-tested with brutal honesty, competitor teardown, market validation, and clear go/no-go guidance before building. | VoltAgent |
| `prompt-engineer` | Use this agent when you need to design, optimize, test, or evaluate prompts for large language models in production systems. | VoltAgent |
| `puppeteer-expert` | Expert in automating browser interactions using Puppeteer. | 0xfurai |
| `qa` | QA Agent. Tests all acceptance criteria and edge cases from orchestrator-output.md. | wshobson |
| `quant-analyst` | Use this agent when you need to develop quantitative trading strategies, build financial models with rigorous mathematical foundations, or conduct advanced risk analytics for derivatives and portfolios. | VoltAgent |
| `raffle-winner-picker` | Picks random winners from lists, spreadsheets, or Google Sheets for giveaways, raffles, and contests. | davepoon |
| `review-findings` | Addresses and fixes findings from a QA code review. | davepoon |
| `ruby-pro` | Write idiomatic Ruby code with metaprogramming, Rails patterns, and performance optimization. | wshobson |
| `run-tests-after-changes` | Automatically run quick tests after code modifications to ensure nothing breaks | davepoon |
| `rust-pro` | Master Rust 1.75+ with modern async patterns, advanced type system features, and production-ready systems programming. | wshobson |
| `selenium-expert` | Expert in automated browser testing using Selenium. | 0xfurai |
| `shipwright` | Use this agent to autonomously build, test, and deploy complete applications from plain-English descriptions. | davepoon |
| `slopmop` | >- Trigger when you would normally reach for pytest, gh, mypy, black, or other raw repo tooling. | davepoon |
| `tdd-workflows-tdd-orchestrator` | Master TDD orchestrator specializing in red-green-refactor discipline, multi-agent workflow coordination, and comprehensive test-driven development practices. | wshobson |
| `test-automator` | Use this agent when you need to build, implement, or enhance automated test frameworks, create test scripts, or integrate testing into CI/CD pipelines. | VoltAgent |
| `test-engineer` | Writes characterization, contract, and equivalence tests that pin down legacy behavior so transformation can be proven correct. | Anthropic Official |
| `test-runner` | Automatically run relevant tests after code changes | davepoon |
| `testcafe-expert` | Expert in writing and optimizing TestCafe tests for reliable and maintainable UI testing. | 0xfurai |
| `testing` | Testing strategies and methodologies including TDD, E2E testing, and multi-framework support | davepoon |
| `ui-ux-tester` | Use this agent when you need exhaustive UI and UX functionality testing driven by documented user flows, with browser or desktop interaction tooling and structured defect reporting. | VoltAgent |
| `ux-researcher` | Use this agent when you need to conduct user research, analyze user behavior, or generate actionable insights to validate design decisions and uncover user needs. | VoltAgent |
| `webapp-testing` | Toolkit for interacting with and testing local web applications using Playwright. | davepoon |
| `zoho-health` | Zoho Mail health check — verify mail accounts are operational, test connectivity, check SPF/DKIM/DMARC records, and monitor account deliverability. | davepoon |

## Workflow & Orchestration

_22 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `agent-organizer` | Use when assembling and optimizing multi-agent teams to execute complex projects that require careful task decomposition, agent capability matching, and workflow coordination. | VoltAgent |
| `builder` | Agent that receives a specific TASK within a WORK and implements the actual code. | davepoon |
| `committer` | Agent that first generates the result report for a verified TASK and then performs git commit. | davepoon |
| `context-manager` | Use for managing shared state, information retrieval, and data synchronization when multiple agents need coordinated access to context and metadata. | VoltAgent |
| `git-add-changes` | Automatically stage changes in git after file modifications for easier commit workflow | davepoon |
| `gsd-executor` | Executes GSD plans with atomic commits, deviation handling, checkpoint protocols, and state management. | davepoon |
| `gsd-pattern-mapper` | Analyzes codebase for existing patterns and produces PATTERNS.md mapping new files to closest analogs. | davepoon |
| `gsd-planner` | Creates executable phase plans with task breakdown, dependency analysis, and goal-backward verification. | davepoon |
| `gsd:forensics` | Post-mortem investigation for failed GSD workflows — analyzes git history, artifacts, and state to diagnose what went wrong argument-hint: "[problem description]" allowed-tools: - Read - Write - Bash ... | davepoon |
| `gsd:next` | Automatically advance to the next logical step in the GSD workflow allowed-tools: - Read - Bash - Grep - Glob - SlashCommand | davepoon |
| `gsd:settings` | Configure GSD workflow toggles and model profile allowed-tools: - Read - Write - Bash - AskUserQuestion | davepoon |
| `knowledge-synthesizer` | Use when you need to extract actionable patterns from agent interactions, synthesize insights across multiple workflows, and enable organizational learning from collective experience. | VoltAgent |
| `multi-agent-coordinator` | Use when coordinating multiple concurrent agents that need to communicate, share state, synchronize work, and handle distributed failures across a system. | VoltAgent |
| `project-planner` | Strategic planning specialist for breaking down complex projects into actionable tasks and managing development workflows | webdevtodayjason |
| `project-supervisor-orchestrator` | You are a Project Supervisor Orchestrator managing complex multi-step workflows that coordinate multiple specialized agents in sequence. | davepoon |
| `query-clarifier` | Analyze research queries for clarity and determine if clarification is needed. | davepoon |
| `scheduler` | Agent that manages the TASK dependency DAG for a specific WORK and executes the pipeline. | davepoon |
| `skill-creator` | Guide for creating effective skills. | davepoon |
| `sosa-orchestration` | Multi-skill workflow orchestration — coordinate Plan-Act-Verify patterns, structured handoffs between agents, dependency tracking, and token-efficient execution. | davepoon |
| `task-decomposition-expert` | Break down complex user goals into actionable tasks and identify optimal combinations of tools, agents, and workflows for system integration. | davepoon |
| `team-lead` | Team orchestrator that decomposes work into parallel tasks with file ownership boundaries, manages team lifecycle, and synthesizes results. | wshobson |
| `trello-automation` | Automate Trello boards, cards, and workflows via Rube MCP (Composio). | davepoon |

## Other / Uncategorized

_242 agents in this category._

| Agent | What it does | Source |
|---|---|---|
| `Python Web Scraping Expert` | Specialized agent for Python web scraping, data extraction, automation, and web crawling with modern async techniques | vijaythecoder |
| `agent-installer` | Use this agent when the user wants to discover, browse, or install Claude Code agents from the awesome-claude-code-subagents repository. | VoltAgent |
| `agents` | Quick reference for Claude agents | charles-adedotun |
| `airtable-automation` | Automate Airtable tasks via Rube MCP (Composio): records, bases, tables, fields, views. | davepoon |
| `amplitude-automation` | Automate Amplitude tasks via Rube MCP (Composio): events, user activity, cohorts, user identification. | davepoon |
| `apify-scraping` | Web scraping with Apify — run pre-built Actors for any website, manage datasets and key-value stores, create schedules for recurring scrapes, and set up webhooks for automation. | davepoon |
| `apollo-prospecting` | Prospect leads and enrich contacts with Apollo.io — search companies by industry/size/location, find decision-makers by title, bulk enrich profiles with emails, and manage outreach campaigns. | davepoon |
| `app-router` | This skill should be used when the user asks to "create a Next.js route", "add a page", "set up layouts", "implement loading states", "add error boundaries", "organize routes", "create dynamic routes"... | davepoon |
| `asana-automation` | Automate Asana tasks via Rube MCP (Composio): tasks, projects, sections, teams, workspaces. | davepoon |
| `aspnet-core-expert` | Expert in ASP.NET Core web application development, optimization, and best practices. | 0xfurai |
| `auto-git-add` | Automatically stage modified files with git add after editing | davepoon |
| `bamboohr-automation` | Automate BambooHR tasks via Rube MCP (Composio): employees, time-off, benefits, dependents, employee updates. | davepoon |
| `basecamp-automation` | Automate Basecamp project management, to-dos, messages, people, and to-do list organization via Rube MCP (Composio). | davepoon |
| `bitbucket-automation` | Automate Bitbucket repositories, pull requests, branches, issues, and workspace management via Rube MCP (Composio). | davepoon |
| `braintree-expert` | Braintree specialist focusing on payment gateways, integrations, and optimization. | 0xfurai |
| `branch-guard` | Prevent accidental git push to main/master branches without explicit approval | davepoon |
| `brief` | > Session-start briefing from Origin. | davepoon |
| `build-on-change` | Automatically trigger build processes when source files change | davepoon |
| `c-expert` | C language expert specializing in efficient, reliable systems-level programming. | 0xfurai |
| `c4-code` | Expert C4 Code-level documentation specialist. | wshobson |
| `cal-com-automation` | Automate Cal.com tasks via Rube MCP (Composio): manage bookings, check availability, configure webhooks, and handle teams. | davepoon |
| `calendly-automation` | Automate Calendly scheduling, event management, invitee tracking, availability checks, and organization administration via Rube MCP (Composio). | davepoon |
| `change-tracker` | Track file changes in a simple log | davepoon |
| `changelog-generator` | Automatically creates user-facing changelogs from git commits by analyzing commit history, categorizing changes, and transforming technical commits into clear, customer-friendly release notes. | davepoon |
| `chrome-fix` | Diagnose and repair broken Chrome MCP connections — fix extension not responding errors, reconnect after account switches, verify connection health, clean up stale tabs. | davepoon |
| `clawring` | Phone calling skill for OpenClaw: agent makes real outbound phone calls to users for alerts, briefings, reminders, and urgent notifications. | davepoon |
| `clickup-automation` | Automate ClickUp project management including tasks, spaces, folders, lists, comments, and team operations via Rube MCP (Composio). | davepoon |
| `close-automation` | Automate Close CRM tasks via Rube MCP (Composio): create leads, manage calls/SMS, handle tasks, and track notes. | davepoon |
| `comms-scanner` | Scans all communication channels for FULL inbox state (not just unread). | davepoon |
| `conductor-validator` | Validates Conductor project artifacts for completeness, consistency, and correctness. | wshobson |
| `continue-implementation` | Continue with the next task in a context-forge implementation plan | webdevtodayjason |
| `convertkit-automation` | Automate ConvertKit (Kit) tasks via Rube MCP (Composio): manage subscribers, tags, broadcasts, and broadcast stats. | davepoon |
| `cowork-memory` | Persistent memory across Cowork sessions — automatically recall decisions, file changes, insights, and errors from previous sessions. | davepoon |
| `credential-leak-guard` | Block credential hunting and exfiltration attempts via environment scanning, file access, and HTTP upload | davepoon |
| `daemon-agent` | Manages the ops background daemon — start, stop, restart services, check health | davepoon |
| `debrief` | > Alias for `/origin:handoff` — symmetric brief/debrief naming. | davepoon |
| `debugger` | Use this agent when you need to diagnose and fix bugs, identify root causes of failures, or analyze error logs and stack traces to resolve issues. | VoltAgent |
| `dev-cynic` | The Cynic of the dev team. | davepoon |
| `dev-pusher` | The Pusher of the dev team. | davepoon |
| `developer-growth-analysis` | Analyzes your recent Claude Code chat history to identify coding patterns, development gaps, and areas for improvement, curates relevant learning resources from HackerNews, and automatically sends a personalized growth report to your Slack DMs. | davepoon |
| `discord-detailed-notifications` | Send detailed Discord notifications with session information and rich embeds | davepoon |
| `discord-error-notifications` | Send Discord notifications for long-running operations and important events | davepoon |
| `discord-notifications` | Send Discord notifications when Claude Code finishes working | davepoon |
| `doctor-agent` | Diagnoses and auto-fixes ops plugin configuration errors, manifest issues, broken permissions, invalid JSON, and stale cache copies. | davepoon |
| `docusign-automation` | Automate DocuSign tasks via Rube MCP (Composio): templates, envelopes, signatures, document management. | davepoon |
| `domain-name-brainstormer` | Generates creative domain name ideas for your project and checks availability across multiple TLDs (.com, .io, .dev, .ai, etc.). | davepoon |
| `drive-upload` | Upload files from Claude directly to Google Drive — select destination folder, automatic MIME type detection, supports any file type and size. | davepoon |
| `dropbox-automation` | Automate Dropbox file management, sharing, search, uploads, downloads, and folder operations via Rube MCP (Composio). | davepoon |
| `error-coordinator` | Use this agent when distributed system errors occur and need coordinated handling across multiple components, or when you need to implement comprehensive error recovery strategies with automated failure detection and cascade prevention. | VoltAgent |
| `error-detective` | Use this agent when you need to diagnose why errors are occurring in your system, correlate errors across services, identify root causes, and prevent future failures. | VoltAgent |
| `fiber-expert` | Master in fiber technology specializing in manufacturing, properties, applications, and innovations in fiber industry. | 0xfurai |
| `file-backup` | Automatically backup files before editing | davepoon |
| `file-organizer` | Intelligently organizes your files and folders across your computer by understanding context, finding duplicates, suggesting better structures, and automating cleanup tasks. | davepoon |
| `file-protection` | Protect critical files from accidental modification | davepoon |
| `file-protection-hook` | Protect critical files from accidental modification | davepoon |
| `financial-model` | Run deterministic financial models for startup valuation and SaaS health analysis. | davepoon |
| `first-principles-thinking` | Use when the user wants to challenge assumptions, break down a complex problem from scratch, or approach something with first principles reasoning. | VoltAgent |
| `fix-stuck-session` | Fix stuck Cowork sessions — resolve 'RPC error: process already running', orphaned processes, connection aborted errors, and frozen sessions with automated diagnosis and recovery. | davepoon |
| `forget` | > Delete a memory from Origin by ID. | davepoon |
| `format-python-files` | Automatically format Python files after any Edit operation using black formatter | davepoon |
| `freshdesk-automation` | Automate Freshdesk helpdesk operations including tickets, contacts, companies, notes, and replies via Rube MCP (Composio). | davepoon |
| `freshservice-automation` | Automate Freshservice ITSM tasks via Rube MCP (Composio): create/update tickets, bulk operations, service requests, and outbound emails. | davepoon |
| `gitlab-automation` | Automate GitLab project management, issues, merge requests, pipelines, branches, and user operations via Rube MCP (Composio). | davepoon |
| `gmail-automation` | Automate Gmail tasks via Rube MCP (Composio): send/reply, search, labels, drafts, attachments. | davepoon |
| `google-calendar-automation` | Automate Google Calendar events, scheduling, availability checks, and attendee management via Rube MCP (Composio). | davepoon |
| `google-drive-automation` | Automate Google Drive file operations (upload, download, search, share, organize) via Rube MCP (Composio). | davepoon |
| `googlesheets-automation` | Automate Google Sheets operations (read, write, format, filter, manage spreadsheets) via Rube MCP (Composio). | davepoon |
| `gsd-assumptions-analyzer` | Deeply analyzes codebase for a phase and returns structured assumptions with evidence. | davepoon |
| `gsd-debug-session-manager` | Manages multi-cycle /gsd:debug checkpoint and continuation loop in isolated context. | davepoon |
| `gsd-doc-writer` | Writes and updates project documentation. | davepoon |
| `gsd-intel-updater` | Analyzes codebase and writes structured intel files to .planning/intel/. | davepoon |
| `gsd-verifier` | Verifies phase goal achievement through goal-backward analysis. | davepoon |
| `gsd:add-backlog` | Add an idea to the backlog parking lot (999.x numbering) argument-hint: <description> allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:add-phase` | Add phase to end of current milestone in roadmap argument-hint: <description> allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:add-todo` | Capture idea or task as todo from current conversation context argument-hint: [optional description] allowed-tools: - Read - Write - Bash - AskUserQuestion | davepoon |
| `gsd:analyze-dependencies` | Analyze phase dependencies and suggest Depends on entries for ROADMAP.md allowed-tools: - Read - Write - Bash - Glob - Grep - AskUserQuestion | davepoon |
| `gsd:autonomous` | Run all remaining phases autonomously — discuss→plan→execute per phase argument-hint: "[--from N] [--to N] [--only N] [--interactive]" allowed-tools: - Read - Write - Bash - Glob - Grep - AskUserQuest... | davepoon |
| `gsd:check-todos` | List pending todos and select one to work on argument-hint: [area filter] allowed-tools: - Read - Write - Bash - AskUserQuestion | davepoon |
| `gsd:cleanup` | Archive accumulated phase directories from completed milestones allowed-tools: - Read - Write - Bash - AskUserQuestion | davepoon |
| `gsd:complete-milestone` | Archive completed milestone and prepare for next version argument-hint: <version> allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:debug` | Systematic debugging with persistent state across context resets argument-hint: [list \| status <slug> \| continue <slug> \| --diagnose] [issue description] allowed-tools: - Read - Bash - Task - AskUserQ... | davepoon |
| `gsd:do` | Route freeform text to the right GSD command automatically argument-hint: "<description of what you want to do>" allowed-tools: - Read - Bash - AskUserQuestion | davepoon |
| `gsd:explore` | Socratic ideation and idea routing — think through ideas before committing to plans allowed-tools: - Read - Write - Bash - Grep - Glob - Task - AskUserQuestion | davepoon |
| `gsd:extract-learnings` | Extract decisions, lessons, patterns, and surprises from completed phase artifacts argument-hint: <phase-number> allowed-tools: - Read - Write - Bash - Grep - Glob - Agent | davepoon |
| `gsd:fast` | Execute a trivial task inline — no subagents, no planning overhead argument-hint: "[task description]" allowed-tools: - Read - Write - Edit - Bash - Grep - Glob | davepoon |
| `gsd:from-gsd2` | Import a GSD-2 (.gsd/) project back to GSD v1 (.planning/) format argument-hint: "[--path <dir>] [--force]" allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:graphify` | Build, query, and inspect the project knowledge graph in .planning/graphs/" argument-hint: "[build\|query <term>\|status\|diff]" allowed-tools: - Read - Bash - Task | davepoon |
| `gsd:health` | Diagnose planning directory health and optionally repair issues argument-hint: [--repair] allowed-tools: - Read - Bash - Write - AskUserQuestion | davepoon |
| `gsd:help` | Show available GSD commands and usage guide allowed-tools: - Read | davepoon |
| `gsd:import` | Ingest external plans with conflict detection against project decisions before writing anything. | davepoon |
| `gsd:inbox` | Triage and review all open GitHub issues and PRs against project templates and contribution guidelines argument-hint: "[--issues] [--prs] [--label] [--close-incomplete] [--repo owner/repo]" allowed-to... | davepoon |
| `gsd:insert-phase` | Insert urgent work as decimal phase (e.g., 72.1) between existing phases argument-hint: <after> <description> allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:intel` | Query, inspect, or refresh codebase intelligence files in .planning/intel/" argument-hint: "[query <term>\|status\|diff\|refresh]" allowed-tools: - Read - Bash - Task | davepoon |
| `gsd:list-phase-assumptions` | Surface Claude's assumptions about a phase approach before planning argument-hint: "[phase]" allowed-tools: - Read - Bash - Grep - Glob | davepoon |
| `gsd:list-workspaces` | List active GSD workspaces and their status allowed-tools: - Bash - Read | davepoon |
| `gsd:manager` | Interactive command center for managing multiple phases from one terminal allowed-tools: - Read - Write - Bash - Glob - Grep - AskUserQuestion - Skill - Task | davepoon |
| `gsd:milestone-summary` | Generate a comprehensive project summary from milestone artifacts for team onboarding and review argument-hint: "[version]" allowed-tools: - Read - Write - Bash - Grep - Glob | davepoon |
| `gsd:mvp-phase` | Plan an MVP-mode phase — captures an "As a / I want to / So that" user story, runs SPIDR splitting, then delegates to plan-phase argument-hint: "<phase> [--force] [--text] | davepoon |
| `gsd:new-milestone` | Start a new milestone cycle — update PROJECT.md and route to requirements argument-hint: "[milestone name, e.g., 'v1.1 Notifications']" allowed-tools: - Read - Write - Bash - Task - AskUserQuestion | davepoon |
| `gsd:new-project` | Initialize a new project with deep context gathering and PROJECT.md argument-hint: "[--auto]" allowed-tools: - Read - Bash - Write - Task - AskUserQuestion | davepoon |
| `gsd:new-workspace` | Create an isolated workspace with repo copies and independent .planning/ argument-hint: "--name <name> [--repos repo1,repo2] [--path /target] [--strategy worktree\|clone] [--branch name] [--auto]" allo... | davepoon |
| `gsd:note` | Zero-friction idea capture. | davepoon |
| `gsd:pause-work` | Create context handoff when pausing work mid-phase allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:plant-seed` | Capture a forward-looking idea with trigger conditions — surfaces automatically at the right milestone argument-hint: "[idea summary]" allowed-tools: - Read - Write - Edit - Bash - AskUserQuestion | davepoon |
| `gsd:pr-branch` | Create a clean PR branch by filtering out .planning/ commits — ready for code review argument-hint: "[target branch, default: main]" allowed-tools: - Bash - Read - AskUserQuestion | davepoon |
| `gsd:profile-user` | Generate developer behavioral profile and create Claude-discoverable artifacts argument-hint: "[--questionnaire] [--refresh]" allowed-tools: - Read - Write - Bash - Glob - Grep - AskUserQuestion - Tas... | davepoon |
| `gsd:quick` | Execute a quick task with GSD guarantees (atomic commits, state tracking) but skip optional agents argument-hint: "[list \| status <slug> \| resume <slug> \| --full] [--validate] [--discuss] [--research]... | davepoon |
| `gsd:reapply-patches` | Reapply local modifications after a GSD update allowed-tools: Read, Write, Edit, Bash, Glob, Grep, AskUserQuestion | davepoon |
| `gsd:remove-phase` | Remove a future phase from roadmap and renumber subsequent phases argument-hint: <phase-number> allowed-tools: - Read - Write - Bash - Glob | davepoon |
| `gsd:remove-workspace` | Remove a GSD workspace and clean up worktrees argument-hint: "<workspace-name>" allowed-tools: - Bash - Read - AskUserQuestion | davepoon |
| `gsd:resume-at` | Schedule a future resume of work - e.g. | davepoon |
| `gsd:resume-work` | Resume work from previous session with full context restoration allowed-tools: - Read - Bash - Write - AskUserQuestion - SlashCommand | davepoon |
| `gsd:review-backlog` | Review and promote backlog items to active milestone allowed-tools: - Read - Write - Bash - AskUserQuestion | davepoon |
| `gsd:scan` | Rapid codebase assessment — lightweight alternative to /gsd:map-codebase allowed-tools: - Read - Write - Bash - Grep - Glob - Agent - AskUserQuestion | davepoon |
| `gsd:secure-phase` | Retroactively verify threat mitigations for a completed phase argument-hint: "[phase number]" allowed-tools: - Read - Write - Edit - Bash - Glob - Grep - Task - AskUserQuestion | davepoon |
| `gsd:session-report` | Generate a session report with token usage estimates, work summary, and outcomes allowed-tools: - Read - Bash - Write | davepoon |
| `gsd:ship` | Create PR, run review, and prepare for merge after verification passes argument-hint: "[phase number or milestone, e.g., '4' or 'v1.0']" allowed-tools: - Read - Bash - Grep - Glob - Write - AskUserQue... | davepoon |
| `gsd:spec-phase` | Socratic spec refinement — clarify WHAT a phase delivers with ambiguity scoring before discuss-phase. | davepoon |
| `gsd:spike-wrap-up` | Package spike findings into a persistent project skill for future build conversations allowed-tools: - Read - Write - Edit - Bash - Grep - Glob - AskUserQuestion | davepoon |
| `gsd:stats` | Display project statistics — phases, plans, requirements, git metrics, and timeline allowed-tools: - Read - Bash | davepoon |
| `gsd:thread` | Manage persistent context threads for cross-session work argument-hint: "[list [--open \| --resolved] \| close <slug> \| status <slug> \| name \| description]" allowed-tools: - Read - Write - Bash | davepoon |
| `gsd:verify-work` | Validate built features through conversational UAT argument-hint: "[phase number, e.g., '4']" allowed-tools: - Read - Bash - Glob - Grep - Edit - Write - Task | davepoon |
| `gsd:workstreams` | Manage parallel workstreams — list, create, switch, status, progress, complete, and resume allowed-tools: - Read - Bash | davepoon |
| `handoff` | > End-of-session ritual. | davepoon |
| `help` | > One-screen quick reference for the Origin plugin. | davepoon |
| `helpdesk-automation` | Automate HelpDesk tasks via Rube MCP (Composio): list tickets, manage views, use canned responses, and configure custom fields. | davepoon |
| `hubspot-automation` | Automate HubSpot CRM operations (contacts, companies, deals, tickets, properties) via Rube MCP using Composio integration. | davepoon |
| `image-generator` | >- Image generation executor agent. | wshobson |
| `implementation-status` | Show current implementation progress and next steps for context-forge projects | webdevtodayjason |
| `init` | > Frictionless setup. | davepoon |
| `instagram-automation` | Automate Instagram tasks via Rube MCP (Composio): create posts, carousels, manage media, get insights, and publishing limits. | davepoon |
| `intercom-automation` | Automate Intercom tasks via Rube MCP (Composio): conversations, contacts, companies, segments, admins. | davepoon |
| `invoice-organizer` | Automatically organizes invoices and receipts for tax preparation by reading messy files, extracting key information, renaming them consistently, and sorting them into logical folders. | davepoon |
| `jira-automation` | Automate Jira tasks via Rube MCP (Composio): issues, projects, sprints, boards, comments, users. | davepoon |
| `json-canvas` | Create and edit JSON Canvas files (.canvas) with nodes, edges, groups, and connections. | davepoon |
| `keycloak-expert` | Keycloak specialist for identity and access management, realm configuration, and user federation. | 0xfurai |
| `large-file-guard` | Warn when files larger than 100KB are written to prevent repo bloat | davepoon |
| `life-boss` | The Boss of the life team. | davepoon |
| `life-pusher` | The Pusher of the life team. | davepoon |
| `life-watcher` | The Watcher of the life team. | davepoon |
| `linear-automation` | Automate Linear tasks via Rube MCP (Composio): issues, projects, cycles, teams, labels. | davepoon |
| `linkedin-automation` | Automate LinkedIn tasks via Rube MCP (Composio): create posts, manage profile, company info, comments, and image uploads. | davepoon |
| `linkedin-research` | Scrape LinkedIn profiles and company pages for research — extract work history, skills, education, company details, and recent posts. | davepoon |
| `make-automation` | Automate Make (Integromat) tasks via Rube MCP (Composio): operations, enums, language and timezone lookups. | davepoon |
| `markdown-syntax-formatter` | Converts text with visual formatting into proper markdown syntax, fixes markdown formatting issues, and ensures consistent document structure. | davepoon |
| `mcp-registry-navigator` | You are an MCP Registry Navigator specializing in discovering, evaluating, and integrating MCP servers from various registries. | davepoon |
| `meeting-insights-analyzer` | Analyzes meeting transcripts and recordings to uncover behavioral patterns, communication insights, and actionable feedback. | davepoon |
| `memory-extractor` | Background agent that extracts user profiles, contact cards, and behavioral patterns from chat history. | davepoon |
| `metadata-agent` | Handles frontmatter standardization and metadata addition across vault files. | davepoon |
| `microsoft-teams-automation` | Automate Microsoft Teams tasks via Rube MCP (Composio): send messages, manage channels, create meetings, handle chats, and search messages. | davepoon |
| `miro-automation` | Automate Miro tasks via Rube MCP (Composio): boards, items, sticky notes, frames, sharing, connectors. | davepoon |
| `mixpanel-automation` | Automate Mixpanel tasks via Rube MCP (Composio): events, segmentation, funnels, cohorts, user profiles, JQL queries. | davepoon |
| `monday-automation` | Automate Monday.com work management including boards, items, columns, groups, subitems, and updates via Rube MCP (Composio). | davepoon |
| `mortgage-loan-officer` | Guides borrowers through mortgage refinance evaluation — collects loan data, extracts mortgage statement fields, evaluates qualification, and delivers recommendations with consumer-friendly communication. | davepoon |
| `no-ask-human` | Detect when Claude Code asks questions and remind it to decide autonomously instead | davepoon |
| `obsidian-markdown` | Create and edit Obsidian Flavored Markdown with wikilinks, embeds, callouts, properties, and other Obsidian-specific syntax. | davepoon |
| `one-drive-automation` | Automate OneDrive file management, search, uploads, downloads, sharing, permissions, and folder operations via Rube MCP (Composio). | davepoon |
| `ops-comms` | Send and read messages across all channels. | davepoon |
| `ops-daemon` | Check claude-ops background daemon end-to-end and auto-fix common issues. | davepoon |
| `ops-doctor` | Health check and auto-repair for the ops plugin. | davepoon |
| `ops-linear` | Linear command center. | davepoon |
| `ops-projects` | Portfolio dashboard for all GSD-tracked projects. | davepoon |
| `ops-status` | Lightweight green/red status panel for every configured integration. | davepoon |
| `ops-triage` | Cross-platform issue triage. | davepoon |
| `ops-voice` | Voice operations — make phone calls (Bland AI), text-to-speech (ElevenLabs), transcribe audio (Whisper/Groq). | davepoon |
| `outlook-automation` | Automate Outlook tasks via Rube MCP (Composio): emails, calendar, contacts, folders, attachments. | davepoon |
| `outlook-calendar-automation` | Automate Outlook Calendar tasks via Rube MCP (Composio): create events, manage attendees, find meeting times, and handle invitations. | davepoon |
| `pdf` | Comprehensive PDF manipulation toolkit for extracting text and tables, creating new PDFs, merging/splitting documents, and handling forms. | davepoon |
| `php-expert` | Specialized in developing efficient, secure, and modern PHP applications adhering to best practices. | 0xfurai |
| `pipedrive-automation` | Automate Pipedrive CRM operations including deals, contacts, organizations, activities, notes, and pipeline management via Rube MCP (Composio). | davepoon |
| `podcast-transcriber` | You are a Podcast Transcriber specializing in extracting accurate transcripts from audio/video files with timestamp precision. | davepoon |
| `posthog-automation` | Automate PostHog tasks via Rube MCP (Composio): events, feature flags, projects, user profiles, annotations. | davepoon |
| `prime-context` | Load project context and detect context-forge structure | webdevtodayjason |
| `project-boundary` | Block destructive commands and file operations outside the project directory | davepoon |
| `project-manager` | Use this agent when you need to establish project plans, track execution progress, manage risks, control budget/schedule, and coordinate stakeholders across complex initiatives. | VoltAgent |
| `project-scanner` | Git, PR, and CI status scanner across all registered repos. | davepoon |
| `prp-execute` | Execute a PRP with context-forge awareness and validation gates | webdevtodayjason |
| `rabbitmq-expert` | Expert in RabbitMQ messaging, configuration, and optimization. | 0xfurai |
| `ralph-review-trio` | Run a sequential three-tier code review on a finished implementation branch — Haiku (surface) → Sonnet (logic) → Opus (deep). | davepoon |
| `read` | > Preview a distilled wiki page from inside Claude Code. | davepoon |
| `recall` | > Search Origin's local memory by query. | davepoon |
| `recap` | Triggered by "monthly recap", "how did I do this month", "spending summary", "financial review", "weekly recap", "quarterly review", "year in review | davepoon |
| `remote-agent-dispatcher` | Mechanical scp-and-spawn for autonomous Claude Code agents on a remote host. | davepoon |
| `rm-safety-net` | Block dangerous rm commands on critical paths while allowing cleanup of safe directories | davepoon |
| `root-directory-guard` | Block write operations targeting system directories like /etc, /usr, /bin, and /boot | davepoon |
| `route-handlers` | This skill should be used when the user asks to "create an API route", "add an endpoint", "build a REST API", "handle POST requests", "create route handlers", "stream responses", or needs guidance on Next.js API development in the App Router. | davepoon |
| `rtl-text-formatting` | Fix bidirectional text rendering in Claude responses — proper RTL formatting for Hebrew, Arabic, Persian, and Urdu, especially when mixing with English or other LTR text. | davepoon |
| `scrum-master` | Use when teams need facilitation, process optimization, velocity improvement, or agile ceremony management—especially for sprint planning, retrospectives, impediment removal, and scaling agile practices across multiple teams. | VoltAgent |
| `segment-automation` | Automate Segment tasks via Rube MCP (Composio): track events, identify users, manage groups, page views, aliases, batch operations. | davepoon |
| `server-actions` | This skill should be used when the user asks about "Server Actions", "form handling in Next.js", "mutations", "useFormState", "useFormStatus", "revalidatePath", "revalidateTag", or needs guidance on d... | davepoon |
| `session-backup` | Automatic daily backups of Claude sessions, skills, and configuration files to Google Drive — versioned, organized, and recoverable. | davepoon |
| `setup` | Interactive setup wizard for the claude-ops plugin. | davepoon |
| `sidekiq-expert` | Specialist in optimizing and managing Sidekiq for efficient job processing and background task management. | 0xfurai |
| `simple-notifications` | Send simple desktop notifications when Claude Code operations complete | davepoon |
| `skill-share` | A skill that creates new Claude skills and automatically shares them on Slack using Rube for seamless team collaboration and skill discovery. | davepoon |
| `slack-detailed-notifications` | Send detailed Slack notifications with session information and rich blocks | davepoon |
| `slack-error-notifications` | Send Slack notifications when Claude Code encounters long-running operations or when tools take significant time | davepoon |
| `slack-gif-creator` | Toolkit for creating animated GIFs optimized for Slack, with validators for size constraints and composable animation primitives. | davepoon |
| `slack-notifications` | Send Slack notifications when Claude Code finishes working | davepoon |
| `smart-commit` | Intelligent git commit creation with automatic message generation and validation | davepoon |
| `smart-formatting` | Smart code formatting based on file type | davepoon |
| `sns-expert` | Master of Amazon Simple Notification Service (SNS) for message management and notification solutions. | 0xfurai |
| `spec-analyst` | Requirements analyst and project scoping expert. | zhsama |
| `specifier` | Agent that analyzes user requests to create requirement specifications and WORK units. | davepoon |
| `spend` | Show current Claude Code spend by project and branch via BudgetClaw user-invocable: true allowed-tools: Bash(budgetclaw *) | davepoon |
| `square-automation` | Automate Square tasks via Rube MCP (Composio): payments, orders, invoices, locations. | davepoon |
| `stripe-expert` | This agent specializes in managing and optimizing Stripe integrations, handling payments, managing subscriptions, and utilizing Stripe APIs. | 0xfurai |
| `tag-agent` | Normalizes and hierarchically organizes tag taxonomy for knowledge management systems. | davepoon |
| `tailored-resume-generator` | Analyzes job descriptions and generates tailored resumes that highlight relevant experience, skills, and achievements to maximize interview chances | davepoon |
| `task-distributor` | Use when distributing tasks across multiple agents or workers, managing queues, and balancing workloads to maximize throughput while respecting priorities and deadlines. | VoltAgent |
| `team-debugger` | Hypothesis-driven debugging investigator that investigates one assigned hypothesis, gathering evidence to confirm or falsify it with file:line citations and confidence levels. | wshobson |
| `team-implementer` | Parallel feature builder that implements components within strict file ownership boundaries, coordinating at integration points via messaging. | wshobson |
| `telegram-automation` | Automate Telegram tasks via Rube MCP (Composio): send messages, manage chats, share photos/documents, and handle bot commands. | davepoon |
| `telegram-detailed-notifications` | Send detailed Telegram notifications with session information and metrics | davepoon |
| `telegram-error-notifications` | Send Telegram notifications for long-running operations and important events | davepoon |
| `telegram-notifications` | Send Telegram notifications when Claude Code finishes working | davepoon |
| `text-comparison-validator` | Compare extracted text from images with existing markdown files to ensure accuracy and consistency. | davepoon |
| `tidy` | Triggered by "tidy up", "clean up transactions", "categorize uncategorized", "organize my transactions | davepoon |
| `timestamp-precision-specialist` | Extract frame-accurate timestamps from audio/video files for podcast editing. | davepoon |
| `todoist-automation` | Automate Todoist task management, projects, sections, filtering, and bulk operations via Rube MCP (Composio). | davepoon |
| `triage-agent` | Investigates a specific issue from Sentry, Linear, or GitHub. | davepoon |
| `tubeify` | > Remove pauses, filler words (um, uh), and dead air from raw YouTube recordings via the Tubeify API. | davepoon |
| `twitter-automation` | Automate Twitter/X tasks via Rube MCP (Composio): posts, search, users, bookmarks, lists, media. | davepoon |
| `uctm-init` | Initialize uc-taskmanager for the current project. | davepoon |
| `url-link-extractor` | Find, extract, and catalog all URLs and links within website codebases. | davepoon |
| `vibe-coding-coach` | Use this agent when users want to build applications through conversation, focusing on the vision and feel of their app rather than technical implementation details. | iannuttall |
| `vm-cleanup` | Clean up disk space in Cowork VMs and Claude Code sandboxes — remove caches, temp files, old logs, and package manager artifacts. | davepoon |
| `webflow-automation` | Automate Webflow CMS collections, site publishing, page management, asset uploads, and ecommerce orders via Rube MCP (Composio). | davepoon |
| `webpack-expert` | Expert in Webpack configuration, optimization, and troubleshooting for efficient bundling and module loading. | 0xfurai |
| `websocket-engineer` | Use this agent when implementing real-time bidirectional communication features using WebSockets, Socket.IO, or similar technologies at scale. | VoltAgent |
| `websocket-expert` | Specializes in WebSocket protocol, implementation, and application. | 0xfurai |
| `windows-python-stub-detector` | SessionStart probe that surfaces the Microsoft Store python3 stub on Windows Git Bash before Python-based hooks silently no-op | davepoon |
| `work-pipeline` | Triggers the WORK-PIPELINE when a user request starts with a [] tag (e.g., [new-feature], [bugfix], [WORK start]). | davepoon |
| `work-status` | Shows WORK progress and TASK status. | davepoon |
| `wrike-automation` | Automate Wrike project management via Rube MCP (Composio): create tasks/folders, manage projects, assign work, and track progress. | davepoon |
| `xlsx` | Comprehensive spreadsheet creation, editing, and analysis with support for formulas, formatting, data analysis, and visualization. | davepoon |
| `yolo-coo` | Operations execution agent. | davepoon |
| `youtube-transcription` | Transcribe YouTube videos and playlists — extract clean formatted text from any video, any language, no API key required. | davepoon |
| `zendesk-automation` | Automate Zendesk tasks via Rube MCP (Composio): tickets, users, organizations, replies. | davepoon |
| `zoho-crm-automation` | Automate Zoho CRM tasks via Rube MCP (Composio): create/update records, search contacts, manage leads, and convert leads. | davepoon |
| `zoom-automation` | Automate Zoom meeting creation, management, recordings, webinars, and participant tracking via Rube MCP (Composio). | davepoon |
| `{{AGENT_NAME}}` | {{DESCRIPTION}} | charles-adedotun |

---

## Attribution

This collection aggregates agents from the following open-source projects (full credit to the original authors):

- **Anthropic Official** — https://github.com/anthropics/claude-plugins-official
- **VoltAgent** — https://github.com/VoltAgent/awesome-claude-code-subagents
- **wshobson** — https://github.com/wshobson/agents
- **davepoon** — https://github.com/davepoon/claude-code-subagents-collection
- **0xfurai** — https://github.com/0xfurai/claude-code-subagents
- **vijaythecoder** — https://github.com/vijaythecoder/awesome-claude-agents
- **iannuttall** — https://github.com/iannuttall/claude-agents
- **charles-adedotun** — https://github.com/charles-adedotun/claude-code-sub-agents
- **zhsama** — https://github.com/zhsama/claude-sub-agent
- **webdevtodayjason** — https://github.com/webdevtodayjason/sub-agents
- **hesreallyhim** (curated directory) — https://github.com/hesreallyhim/awesome-claude-code
- **rahulvrane** (curated directory) — https://github.com/rahulvrane/awesome-claude-agents

Each agent retains the license of its source project.