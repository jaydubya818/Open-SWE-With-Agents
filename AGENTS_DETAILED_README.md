# 🚀 Open-SWE AI Agents Collection - Comprehensive Guide

A sophisticated collection of **134+ specialized AI agents** designed for collaborative software development, featuring advanced communication protocols, multi-agent orchestration, and comprehensive project management capabilities.

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [🏗️ Agent Architecture](#️-agent-architecture)
- [📊 Agent Categories](#-agent-categories)
- [🤖 Detailed Agent Catalog](#-detailed-agent-catalog)
- [🔄 Communication Protocols](#-communication-protocols)
- [🚀 Usage Examples](#-usage-examples)
- [🔧 Setup & Configuration](#-setup--configuration)

## 🎯 Overview

The Open-SWE AI Agents Collection represents a paradigm shift from single AI assistant to **coordinated AI development teams**. Each agent is a domain specialist with standardized communication protocols, enabling seamless collaboration across complex software development workflows.

### Key Features

- ✅ **Specialized Expertise**: Domain-specific agents with deep knowledge
- ✅ **Multi-Agent Orchestration**: Intelligent agent selection and coordination
- ✅ **Standardized Communication**: JSON-based inter-agent protocols
- ✅ **Context Awareness**: Mandatory context acquisition prevents duplicate work
- ✅ **Quality Assurance**: Built-in review and validation processes
- ✅ **Parallel Execution**: Concurrent agent operations for efficiency
- ✅ **External Integrations**: MCP (Model Context Protocol) integrations

## 🏗️ Agent Architecture

### Agent Structure

Each agent follows a standardized markdown format with frontmatter configuration:

```yaml
---
name: agent-identifier           # Unique identifier for invocation (@agent-name)
description: Agent role and capabilities description
tools: Available computational tools and integrations
model: Language model specification (sonnet, haiku, etc.)
---
```

### Communication Protocol

All agents follow a **mandatory three-phase communication protocol**:

1. **Context Acquisition**: Query `context-manager` for project state
2. **Solution Implementation**: Execute specialized tasks
3. **Activity Reporting**: Report completion back to context-manager

### MCP Integrations

Agents leverage external tools and services through MCP (Model Context Protocol):

- **context7**: Library documentation and research capabilities
- **magic**: Component generation and design system integration
- **sequential-thinking**: Complex analysis and decision-making
- **playwright**: Browser automation and testing

## 📊 Agent Categories

| Category | Count | Purpose | Examples |
|----------|-------|---------|-----------|
| 🎯 [Orchestration & Management](#-orchestration--management) | 5 | Project coordination and multi-agent management | agent-organizer, context-manager |
| 🏗️ [Development & Architecture](#️-development--architecture) | 24 | Software development, frameworks, and system design | react-pro, backend-architect, python-pro |
| 🎨 [Design & User Experience](#-design--user-experience) | 7 | UI/UX design, visual systems, and user research | ui-designer, ux-designer, brand-guardian |
| 🔧 [Quality Assurance & Testing](#-quality-assurance--testing) | 15 | Code review, testing, performance optimization | code-reviewer, test-automator, qa-expert |
| 🔒 [Security & Compliance](#-security--compliance) | 4 | Security auditing, compliance, incident response | security-auditor, incident-responder |
| 📊 [Data & AI Engineering](#-data--ai-engineering) | 4 | Data pipelines, machine learning, AI systems | data-engineer, ml-engineer, prompt-engineer |
| ☁️ [DevOps & Infrastructure](#️-devops--infrastructure) | 13 | Cloud architecture, deployment, infrastructure | cloud-architect, deployment-engineer |
| 📝 [Documentation & Communication](#-documentation--communication) | 6 | Technical writing, API docs, content creation | api-documenter, documentation-expert |
| 🎯 [Product & Business](#-product--business) | 9 | Product management, sprint coordination, analytics | ai-scrum-master, product-manager |
| 📈 [Marketing & Growth](#-marketing--growth) | 7 | Growth hacking, social media, content strategy | growth-hacker, marketing-writer |
| 🏢 [Operations](#-operations) | 5 | Analytics, finance, legal compliance, support | analytics-reporter, finance-tracker |
| 🎭 [Specialized & Utility](#-specialized--utility) | 9 | Specialized tools, workflow optimization | workflow-optimizer, tool-evaluator |

## 🤖 Detailed Agent Catalog

### 🎯 Orchestration & Management

**Strategic coordination and multi-agent workflow management**

#### `agent-organizer`
- **Role**: Master orchestrator for complex, multi-agent tasks
- **Capabilities**: Project analysis, expert agent selection, delegation strategy, team composition
- **Use Cases**: Complex feature development, system architecture decisions, multi-domain projects
- **Tools**: Read, Write, Edit, Grep, Glob, Bash, TodoWrite
- **Model**: haiku (optimized for fast analysis)

#### `context-manager`
- **Role**: Central nervous system for agent coordination
- **Capabilities**: Project state awareness, purpose inference, multi-agent context sharing
- **Use Cases**: Context distribution, knowledge management, agent coordination
- **Tools**: Read, Write, Edit, Grep, Glob, LS, WebSearch
- **Model**: sonnet

#### `project-analyst`
- **Role**: Deep project analysis and strategic planning
- **Capabilities**: Requirement analysis, risk assessment, project planning, stakeholder alignment
- **Use Cases**: Project initialization, scope analysis, strategic decision-making
- **Tools**: Read, Write, Edit, Grep, Glob, Bash, WebSearch
- **Model**: sonnet

#### `team-configurator`
- **Role**: Team structure optimization and workflow configuration
- **Capabilities**: Team composition analysis, workflow design, resource allocation
- **Use Cases**: Team setup, process optimization, resource planning
- **Tools**: Read, Write, Edit, TodoWrite
- **Model**: haiku

#### `tech-lead-orchestrator`
- **Role**: Technical leadership and development coordination
- **Capabilities**: Technical decision-making, code architecture oversight, team mentoring
- **Use Cases**: Technical leadership, architectural decisions, development guidance
- **Tools**: Read, Write, Edit, Grep, Glob, Bash
- **Model**: sonnet

### 🏗️ Development & Architecture

**Comprehensive software development across frameworks and languages**

#### Frontend Specialists

#### `react-pro`
- **Role**: Expert React developer for modern web applications
- **Capabilities**: Component architecture, performance optimization, state management, testing
- **Specialties**: Hooks, Context API, Suspense, React Query, memoization
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS, WebFetch, WebSearch, Task
- **MCP**: context7 (React patterns), magic (component generation)
- **Model**: sonnet

#### `nextjs-pro`
- **Role**: Next.js specialist for full-stack React applications
- **Capabilities**: SSR/SSG optimization, API routes, performance tuning, SEO
- **Specialties**: App Router, Server Components, Image optimization, Edge functions
- **Tools**: Full development toolkit with Next.js focus
- **Model**: sonnet

#### `vue-component-architect`
- **Role**: Vue.js component system architect
- **Capabilities**: Component design, Composition API, Vue 3 patterns, state management
- **Specialties**: Reactive systems, component composition, Pinia integration
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob
- **Model**: sonnet

#### `vue-nuxt-expert`
- **Role**: Nuxt.js full-stack Vue development
- **Capabilities**: Universal applications, auto-imports, module ecosystem
- **Specialties**: SSR/SPA modes, Nuxt modules, performance optimization
- **Tools**: Full development toolkit
- **Model**: sonnet

#### `frontend-developer`
- **Role**: General frontend development across frameworks
- **Capabilities**: Responsive design, cross-browser compatibility, modern CSS
- **Specialties**: Web standards, accessibility, performance optimization
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### Backend Specialists

#### `backend-architect`
- **Role**: Backend system architect and API designer
- **Capabilities**: System design, API architecture, database design, scalability
- **Specialties**: Microservices, RESTful APIs, database optimization, caching
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS, WebSearch
- **MCP**: context7 (architecture patterns)
- **Model**: sonnet

#### `api-architect`
- **Role**: API design and integration specialist
- **Capabilities**: RESTful design, GraphQL schemas, API versioning, documentation
- **Specialties**: OpenAPI specifications, rate limiting, authentication
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `graphql-architect`
- **Role**: GraphQL schema design and implementation
- **Capabilities**: Schema design, resolver optimization, federation patterns
- **Specialties**: Type safety, query optimization, real-time subscriptions
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### Language Specialists

#### `python-pro`
- **Role**: Expert Python developer for backend and data applications
- **Capabilities**: Django/FastAPI, async programming, data processing, testing
- **Specialties**: Clean architecture, type hints, performance optimization
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS, WebSearch
- **MCP**: context7 (Python libraries)
- **Model**: sonnet

#### `golang-pro`
- **Role**: Go language specialist for high-performance systems
- **Capabilities**: Concurrent systems, microservices, CLI tools, performance optimization
- **Specialties**: Goroutines, channels, memory management, system programming
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `typescript-pro`
- **Role**: TypeScript expert for type-safe applications
- **Capabilities**: Advanced TypeScript features, type system design, tooling
- **Specialties**: Generic programming, utility types, compiler optimization
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### Mobile & Desktop

#### `mobile-developer`
- **Role**: Cross-platform mobile application developer
- **Capabilities**: React Native, Flutter, native integrations, mobile UX
- **Specialties**: Platform-specific optimizations, native modules, app store deployment
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `mobile-app-builder`
- **Role**: Rapid mobile app development and prototyping
- **Capabilities**: Quick prototyping, MVP development, app store optimization
- **Specialties**: No-code/low-code integration, rapid iteration
- **Tools**: Read, Write, Edit, MultiEdit, Bash
- **Model**: sonnet

#### `electron-pro`
- **Role**: Desktop application development with Electron
- **Capabilities**: Cross-platform desktop apps, native system integration
- **Specialties**: Main/renderer process optimization, native APIs, packaging
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### Full-Stack & Integration

#### `full-stack-developer`
- **Role**: End-to-end web application development
- **Capabilities**: Frontend/backend integration, database design, deployment
- **Specialties**: Modern tech stacks, API integration, user experience
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS
- **Model**: sonnet

#### `refactor`
- **Role**: Code refactoring and modernization specialist
- **Capabilities**: Legacy code improvement, architectural refactoring, tech debt reduction
- **Specialties**: Gradual refactoring, dependency management, testing integration
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `legacy-modernizer`
- **Role**: Legacy system modernization expert
- **Capabilities**: Gradual migration strategies, framework upgrades, architecture evolution
- **Specialties**: Risk-managed transitions, backward compatibility, phased rollouts
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `code-archaeologist`
- **Role**: Legacy codebase analysis and documentation
- **Capabilities**: Code archaeology, system understanding, documentation generation
- **Specialties**: Reverse engineering, system mapping, knowledge extraction
- **Tools**: Read, Grep, Glob, Bash, LS
- **Model**: sonnet

#### Component & UI Libraries

#### `react-component-architect`
- **Role**: React component system design
- **Capabilities**: Design system architecture, component libraries, reusable patterns
- **Specialties**: Component composition, prop design, accessibility
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob
- **Model**: sonnet

#### `shadcn-ui-builder`
- **Role**: Shadcn/ui component implementation
- **Capabilities**: Modern UI components, design system integration, accessibility
- **Specialties**: Radix UI primitives, Tailwind styling, component variants
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob
- **Model**: sonnet

#### `vue-state-manager`
- **Role**: Vue.js state management specialist
- **Capabilities**: Vuex/Pinia implementation, reactive state design, performance optimization
- **Specialties**: State architecture, reactive patterns, computed properties
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob
- **Model**: sonnet

### 🎨 Design & User Experience

**Visual design, user experience, and design systems**

#### `ui-designer`
- **Role**: User interface design specialist
- **Capabilities**: Component design, design systems, visual aesthetics, rapid prototyping
- **Specialties**: Mobile-first responsive design, Tailwind CSS, modern UI patterns
- **Tools**: Write, Read, MultiEdit, WebSearch, WebFetch
- **Focus**: 6-day sprint compatibility, social media optimization
- **Model**: sonnet

#### `ux-designer`
- **Role**: User experience specialist
- **Capabilities**: User research, interaction design, usability testing, accessibility
- **Specialties**: User-centered design, information architecture, journey mapping
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

#### `ux-researcher`
- **Role**: User research and behavioral analysis
- **Capabilities**: User interviews, usability testing, data analysis, insights generation
- **Specialties**: Research methodology, user personas, behavioral patterns
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

#### `brand-guardian`
- **Role**: Brand consistency and visual identity
- **Capabilities**: Brand guidelines, visual consistency, style systems
- **Specialties**: Brand application, design standards, visual communication
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `dx-optimizer`
- **Role**: Developer experience optimization
- **Capabilities**: Tooling improvement, workflow optimization, setup automation
- **Specialties**: Build tools, development environments, productivity enhancement
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `visual-storyteller`
- **Role**: Visual communication and storytelling
- **Capabilities**: Narrative design, visual communication, presentation design
- **Specialties**: Information visualization, storytelling techniques
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `whimsy-injector`
- **Role**: Delightful user interactions and micro-animations
- **Capabilities**: Micro-interactions, animation design, delightful moments
- **Specialties**: Framer Motion, CSS animations, user delight
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

### 🔧 Quality Assurance & Testing

**Comprehensive quality assurance, testing, and performance optimization**

#### Code Review & Quality

#### `code-reviewer`
- **Role**: Expert code review specialist
- **Capabilities**: Quality assessment, security review, maintainability analysis
- **Review Areas**: Code quality, security vulnerabilities, performance, testing, documentation
- **Tools**: Read, Grep, Glob, Bash
- **Output**: Prioritized issue reports with specific recommendations
- **Model**: sonnet

#### `architect-review`
- **Role**: Architectural consistency specialist
- **Capabilities**: Design pattern review, architectural compliance, system coherence
- **Focus Areas**: Architecture patterns, system design, scalability review
- **Tools**: Read, Grep, Glob, Bash
- **Model**: sonnet

#### `best-practices`
- **Role**: Coding standards and best practices enforcement
- **Capabilities**: Standards compliance, pattern recognition, improvement recommendations
- **Specialties**: Language-specific practices, framework conventions
- **Tools**: Read, Grep, Glob
- **Model**: sonnet

#### Testing Specialists

#### `test-automator`
- **Role**: Comprehensive test automation specialist
- **Capabilities**: Test suite creation, automation frameworks, CI/CD integration
- **Test Types**: Unit, integration, E2E, performance, security testing
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `qa-expert`
- **Role**: Quality assurance strategy and process design
- **Capabilities**: QA process design, testing strategies, quality metrics
- **Specialties**: Test planning, quality gates, defect management
- **Tools**: Read, Write, Edit, Grep, Glob, Bash
- **Model**: sonnet

#### `test-writer-fixer`
- **Role**: Test creation and maintenance specialist
- **Capabilities**: Test case development, test maintenance, coverage improvement
- **Specialties**: TDD/BDD practices, test case design, mock strategies
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob
- **Model**: sonnet

#### `test-runner`
- **Role**: Test execution and CI/CD integration
- **Capabilities**: Test automation, CI/CD pipelines, test orchestration
- **Specialties**: Test parallelization, flaky test management, reporting
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

#### `test-results-analyzer`
- **Role**: Test result analysis and reporting
- **Capabilities**: Test metrics analysis, failure pattern recognition, reporting
- **Specialties**: Test analytics, quality metrics, trend analysis
- **Tools**: Read, Write, Edit, Grep, Glob
- **Model**: sonnet

#### `tdd-specialist`
- **Role**: Test-driven development expert
- **Capabilities**: TDD methodology, red-green-refactor cycles, design through testing
- **Specialties**: Test design patterns, SOLID principles through TDD
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob
- **Model**: sonnet

#### Performance & Optimization

#### `performance-engineer`
- **Role**: Application performance optimization specialist
- **Capabilities**: Performance analysis, bottleneck identification, optimization strategies
- **Focus Areas**: Frontend/backend performance, database optimization, caching
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `performance-optimizer`
- **Role**: Performance tuning and optimization
- **Capabilities**: Code optimization, resource management, scalability improvements
- **Specialties**: Algorithm optimization, memory management, concurrency
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `performance-benchmarker`
- **Role**: Performance measurement and benchmarking
- **Capabilities**: Benchmark design, performance testing, metrics collection
- **Specialties**: Load testing, stress testing, performance monitoring
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

#### Database & API Testing

#### `database-optimizer`
- **Role**: Database performance and optimization specialist
- **Capabilities**: Query optimization, indexing strategies, schema design
- **Specialties**: SQL tuning, database monitoring, migration planning
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `postgres-pro`
- **Role**: PostgreSQL specialist and optimizer
- **Capabilities**: PostgreSQL-specific optimization, advanced features, performance tuning
- **Specialties**: PostgreSQL extensions, JSON/JSONB, query optimization
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `api-tester`
- **Role**: API testing and validation specialist
- **Capabilities**: API test automation, contract testing, performance testing
- **Specialties**: REST/GraphQL testing, schema validation, load testing
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

#### Debugging & Analysis

#### `debugger`
- **Role**: Debugging and error analysis specialist
- **Capabilities**: Error investigation, root cause analysis, debugging strategies
- **Specialties**: Log analysis, stack trace interpretation, reproduction strategies
- **Tools**: Read, Grep, Glob, Bash
- **Model**: sonnet

### 🔒 Security & Compliance

**Comprehensive security auditing and compliance management**

#### `security-auditor`
- **Role**: Senior application security auditor and ethical hacker
- **Capabilities**: Vulnerability assessment, penetration testing, security architecture review
- **Specialties**: OWASP compliance, authentication analysis, secure code review
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS, WebSearch, WebFetch, Task
- **MCP**: context7 (security standards), sequential-thinking (threat analysis), playwright (security testing)
- **Model**: sonnet

#### `incident-responder`
- **Role**: Critical security incident response specialist
- **Capabilities**: Crisis management, incident analysis, escalation procedures
- **Specialties**: Rapid response, damage assessment, recovery procedures
- **Tools**: Read, Write, Edit, Grep, Glob, Bash
- **Model**: sonnet

#### `devops-incident-responder`
- **Role**: Production infrastructure incident response
- **Capabilities**: System debugging, log analysis, deployment troubleshooting
- **Specialties**: Infrastructure issues, deployment failures, system recovery
- **Tools**: Read, Write, Edit, Grep, Glob, Bash
- **Model**: sonnet

#### `security-scanner`
- **Role**: Automated security scanning and vulnerability detection
- **Capabilities**: Dependency scanning, code analysis, configuration auditing
- **Specialties**: Automated security tools, vulnerability databases, compliance checking
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

### 📊 Data & AI Engineering

**Data infrastructure, machine learning, and AI system development**

#### `data-engineer`
- **Role**: Scalable data infrastructure and pipeline specialist
- **Capabilities**: ETL/ELT design, data warehousing, real-time streaming, data governance
- **Technologies**: Apache Spark, Airflow, Kafka, Snowflake, BigQuery
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS, WebSearch, WebFetch, Task
- **MCP**: context7 (data engineering patterns), sequential-thinking (pipeline design)
- **Model**: sonnet

#### `data-scientist`
- **Role**: Advanced analytics and business intelligence specialist
- **Capabilities**: Statistical analysis, data insights, BigQuery optimization, reporting
- **Specialties**: SQL expertise, data visualization, predictive analytics
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `ml-engineer`
- **Role**: Machine learning system implementation specialist
- **Capabilities**: ML pipeline development, model serving, feature engineering
- **Specialties**: Production ML systems, model monitoring, MLOps
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `prompt-engineer`
- **Role**: LLM optimization and prompt engineering specialist
- **Capabilities**: Prompt optimization, AI system design, LLM integration
- **Specialties**: Prompt patterns, model fine-tuning, AI application development
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

### ☁️ DevOps & Infrastructure

**Cloud architecture, deployment automation, and infrastructure management**

#### Cloud & Architecture

#### `cloud-architect`
- **Role**: Senior cloud solutions architect
- **Capabilities**: Multi-cloud architecture, cost optimization, security design, scalability
- **Platforms**: AWS, Azure, GCP
- **Specialties**: Terraform IaC, FinOps practices, serverless computing, disaster recovery
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash, LS, WebSearch, WebFetch, Task
- **MCP**: context7 (cloud documentation), sequential-thinking (architecture analysis)
- **Model**: sonnet

#### `deployment-engineer`
- **Role**: CI/CD pipeline and deployment automation specialist
- **Capabilities**: Pipeline design, containerization, Kubernetes orchestration, automation
- **Technologies**: Docker, Kubernetes, Jenkins, GitLab CI, GitHub Actions
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `devops-automator`
- **Role**: Infrastructure automation and tooling specialist
- **Capabilities**: Automation workflows, infrastructure provisioning, monitoring setup
- **Specialties**: Infrastructure as Code, monitoring, alerting, cost optimization
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `devops-engineer`
- **Role**: General DevOps practices and infrastructure management
- **Capabilities**: Infrastructure management, monitoring, security, compliance
- **Specialties**: Site reliability, incident response, performance monitoring
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `infrastructure-maintainer`
- **Role**: Infrastructure maintenance and optimization
- **Capabilities**: System maintenance, performance tuning, capacity planning
- **Specialties**: System administration, resource optimization, maintenance scheduling
- **Tools**: Read, Write, Edit, Grep, Glob, Bash
- **Model**: sonnet

#### Framework-Specific DevOps

#### Django Specialists

#### `django-api-developer`
- **Role**: Django REST API development specialist
- **Capabilities**: Django REST framework, API design, serialization, authentication
- **Specialties**: DRF optimization, API versioning, permission systems
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `django-backend-expert`
- **Role**: Django backend architecture and optimization
- **Capabilities**: Django architecture, performance optimization, best practices
- **Specialties**: Django patterns, middleware, caching, security
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `django-orm-expert`
- **Role**: Django ORM optimization and database design
- **Capabilities**: ORM optimization, query analysis, database design
- **Specialties**: Complex queries, performance tuning, migration strategies
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### Laravel Specialists

#### `laravel-backend-expert`
- **Role**: Laravel framework specialist
- **Capabilities**: Laravel architecture, feature development, optimization
- **Specialties**: Laravel patterns, service containers, middleware
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `laravel-eloquent-expert`
- **Role**: Laravel Eloquent ORM specialist
- **Capabilities**: Eloquent optimization, relationship design, query optimization
- **Specialties**: Complex relationships, query performance, data modeling
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### Ruby on Rails Specialists

#### `rails-api-developer`
- **Role**: Ruby on Rails API development
- **Capabilities**: Rails API design, JSON serialization, authentication
- **Specialties**: Rails API patterns, performance optimization, testing
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `rails-backend-expert`
- **Role**: Ruby on Rails backend architecture
- **Capabilities**: Rails architecture, best practices, performance optimization
- **Specialties**: Rails conventions, gem selection, background jobs
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `rails-activerecord-expert`
- **Role**: Rails ActiveRecord ORM specialist
- **Capabilities**: ActiveRecord optimization, complex queries, database design
- **Specialties**: Query optimization, migrations, data integrity
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

### 📝 Documentation & Communication

**Technical writing, API documentation, and knowledge management**

#### `api-documenter`
- **Role**: API documentation and integration guide specialist
- **Capabilities**: OpenAPI/Swagger specifications, developer documentation, SDK guides
- **Specialties**: API reference materials, code examples, integration tutorials
- **Tools**: Read, Write, Edit, MultiEdit, Grep, Glob, Bash
- **Model**: sonnet

#### `documentation-expert`
- **Role**: Technical writing and documentation systems specialist
- **Capabilities**: User manuals, system documentation, knowledge bases
- **Specialties**: Documentation strategy, information architecture, content management
- **Tools**: Read, Write, Edit, MultiEdit, WebSearch
- **Model**: sonnet

#### `documentation-specialist`
- **Role**: Specialized documentation creation and maintenance
- **Capabilities**: Technical documentation, process documentation, training materials
- **Specialties**: Documentation workflows, content organization, version control
- **Tools**: Read, Write, Edit, MultiEdit
- **Model**: sonnet

#### `doc-writer`
- **Role**: General documentation writing and content creation
- **Capabilities**: Content creation, editing, documentation standards
- **Specialties**: Clear communication, technical writing, content strategy
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `content-creator`
- **Role**: Content strategy and creation specialist
- **Capabilities**: Content planning, creation, optimization, distribution strategy
- **Specialties**: Content marketing, SEO optimization, audience engagement
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

#### `debugger`
- **Role**: Error analysis and troubleshooting documentation
- **Capabilities**: Error investigation, debugging guides, troubleshooting documentation
- **Specialties**: Problem diagnosis, solution documentation, knowledge capture
- **Tools**: Read, Grep, Glob, Bash
- **Model**: sonnet

### 🎯 Product & Business

**Product management, sprint coordination, and business analytics**

#### `ai-scrum-master`
- **Role**: Automated Scrum Master with continuous sprint management
- **Capabilities**: 3-hour standup cycles, sub-agent coordination, blocker detection, velocity tracking
- **Sub-Agents**: Sprint planning, daily standup, retrospective, backlog refinement, risk management, analytics
- **Specialties**: Automated sprint facilitation, blocker escalation, performance analytics
- **Tools**: Specialized agile management toolkit
- **Model**: sonnet

#### `product-manager`
- **Role**: Strategic product management and roadmap development
- **Capabilities**: Product strategy, market analysis, roadmap planning, stakeholder alignment
- **Specialties**: Product-market fit, feature prioritization, user research integration
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

#### `project-planner`
- **Role**: Project planning and resource coordination
- **Capabilities**: Project planning, timeline management, resource allocation
- **Specialties**: Project methodology, risk management, dependency tracking
- **Tools**: Read, Write, Edit, TodoWrite
- **Model**: sonnet

#### `project-shipper`
- **Role**: Project delivery and launch coordination
- **Capabilities**: Launch planning, delivery coordination, quality gates
- **Specialties**: Go-to-market execution, deployment coordination, post-launch monitoring
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

#### `sprint-prioritizer`
- **Role**: Sprint backlog prioritization and planning
- **Capabilities**: Backlog management, story prioritization, capacity planning
- **Specialties**: Agile prioritization frameworks, story estimation, team capacity
- **Tools**: Read, Write, Edit, TodoWrite
- **Model**: sonnet

#### `experiment-tracker`
- **Role**: A/B testing and experiment management
- **Capabilities**: Experiment design, data collection, results analysis
- **Specialties**: Statistical analysis, hypothesis testing, experiment framework
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `feedback-synthesizer`
- **Role**: User feedback analysis and insight generation
- **Capabilities**: Feedback collection, sentiment analysis, insight extraction
- **Specialties**: User research, feedback categorization, actionable recommendations
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `trend-researcher`
- **Role**: Market trend analysis and competitive intelligence
- **Capabilities**: Market research, trend identification, competitive analysis
- **Specialties**: Industry analysis, technology trends, market opportunities
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

#### `studio-producer`
- **Role**: Creative project coordination and production management
- **Capabilities**: Creative project management, resource coordination, timeline management
- **Specialties**: Creative workflows, production pipelines, creative team coordination
- **Tools**: Read, Write, Edit, TodoWrite
- **Model**: sonnet

### 📈 Marketing & Growth

**Growth hacking, social media strategy, and marketing automation**

#### `growth-hacker`
- **Role**: Rapid user acquisition and viral growth specialist
- **Capabilities**: Viral loop creation, growth experiments, channel optimization, data-driven growth
- **Frameworks**: AARRR metrics, ICE prioritization, viral loops, growth experimentation
- **Specialties**: User acquisition, retention optimization, referral systems
- **Tools**: Growth analytics and experimentation tools
- **Model**: sonnet

#### `marketing-writer`
- **Role**: Marketing content creation and copywriting
- **Capabilities**: Marketing copy, content strategy, brand voice, conversion optimization
- **Specialties**: Persuasive writing, content marketing, email campaigns
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### Social Media Specialists

#### `instagram-curator`
- **Role**: Instagram content strategy and curation
- **Capabilities**: Visual content strategy, Instagram growth, engagement optimization
- **Specialties**: Visual storytelling, hashtag strategy, influencer coordination
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `tiktok-strategist`
- **Role**: TikTok content strategy and viral marketing
- **Capabilities**: Short-form video strategy, trend identification, viral content creation
- **Specialties**: TikTok algorithm optimization, trend analysis, creator collaboration
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `twitter-engager`
- **Role**: Twitter engagement and community building
- **Capabilities**: Twitter strategy, community engagement, thought leadership
- **Specialties**: Twitter threads, engagement tactics, brand building
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `reddit-community-builder`
- **Role**: Reddit community engagement and growth
- **Capabilities**: Reddit strategy, community building, organic engagement
- **Specialties**: Subreddit engagement, authentic community participation
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `app-store-optimizer`
- **Role**: App store optimization and mobile marketing
- **Capabilities**: ASO strategy, app store ranking, mobile app marketing
- **Specialties**: App store algorithms, keyword optimization, conversion rate optimization
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

### 🏢 Operations

**Business operations, analytics, and compliance management**

#### `analytics-reporter`
- **Role**: Business analytics and reporting specialist
- **Capabilities**: Data analysis, report generation, KPI tracking, dashboard creation
- **Specialties**: Business intelligence, performance metrics, data visualization
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `finance-tracker`
- **Role**: Financial analysis and budget management
- **Capabilities**: Financial modeling, budget tracking, cost analysis, ROI calculation
- **Specialties**: Financial planning, cost optimization, investment analysis
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `legal-compliance-checker`
- **Role**: Legal compliance and regulatory analysis
- **Capabilities**: Compliance assessment, legal risk analysis, policy development
- **Specialties**: Privacy law, data protection, regulatory compliance
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `support-responder`
- **Role**: Customer support and issue resolution
- **Capabilities**: Support ticket analysis, issue resolution, customer communication
- **Specialties**: Customer service optimization, support automation, escalation management
- **Tools**: Read, Write, Edit, WebSearch
- **Model**: sonnet

#### `infrastructure-maintainer-studio`
- **Role**: Studio infrastructure maintenance and optimization
- **Capabilities**: Infrastructure monitoring, maintenance scheduling, performance optimization
- **Specialties**: Studio-specific infrastructure, creative tool optimization
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

### 🎭 Specialized & Utility

**Specialized tools, workflow optimization, and unique capabilities**

#### `workflow-optimizer`
- **Role**: Process optimization and workflow improvement
- **Capabilities**: Workflow analysis, process improvement, automation opportunities
- **Specialties**: Efficiency optimization, bottleneck identification, automation strategy
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

#### `tool-evaluator`
- **Role**: Technology evaluation and tool selection
- **Capabilities**: Tool comparison, technology assessment, recommendation generation
- **Specialties**: Technology decision-making, cost-benefit analysis, tool integration
- **Tools**: Read, Write, Edit, WebSearch, WebFetch
- **Model**: sonnet

#### `tailwind-css-expert`
- **Role**: Tailwind CSS specialist and utility-first design
- **Capabilities**: Tailwind optimization, utility-first methodology, design system creation
- **Specialties**: Tailwind configuration, custom utilities, responsive design
- **Tools**: Read, Write, Edit, MultiEdit
- **Model**: sonnet

#### `studio-coach`
- **Role**: Development team coaching and mentoring
- **Capabilities**: Team development, skill building, coaching methodologies
- **Specialties**: Technical mentoring, team dynamics, skills development
- **Tools**: Read, Write, Edit
- **Model**: sonnet

#### `creating-agents`
- **Role**: New AI agent creation and specification
- **Capabilities**: Agent design, capability definition, integration planning
- **Specialties**: Agent architecture, communication protocols, specialization design
- **Tools**: Read, Write, Edit
- **Model**: sonnet

#### `dependencies`
- **Role**: Dependency management and package optimization
- **Capabilities**: Dependency analysis, version management, security assessment
- **Specialties**: Package management, security scanning, dependency optimization
- **Tools**: Read, Write, Edit, Bash
- **Model**: sonnet

#### `joker` & `joker-bonus`
- **Role**: Creative problem-solving and unconventional approaches
- **Capabilities**: Creative solutions, humor injection, unconventional thinking
- **Specialties**: Out-of-the-box solutions, creative brainstorming, problem reframing
- **Tools**: Read, Write, Edit
- **Model**: sonnet

## 🔄 Communication Protocols

### Mandatory Context Acquisition

Every agent **must** begin by querying the `context-manager` to understand:

1. **Project State**: Current codebase structure and recent changes
2. **Related Activities**: Other agent work and dependencies
3. **Technical Context**: Technology stack and architectural decisions

### Standard Communication Flow

```json
{
  "requesting_agent": "agent-name",
  "request_type": "get_task_briefing",
  "payload": {
    "query": "Domain-specific context request"
  }
}
```

### Activity Reporting

After completion, agents report back to maintain project awareness:

```json
{
  "reporting_agent": "agent-name",
  "status": "success|error",
  "summary": "Work completed description",
  "files_modified": ["list", "of", "modified", "files"]
}
```

## 🚀 Usage Examples

### Single Agent Invocation
```bash
@react-pro Create a responsive dashboard component with real-time data
@security-auditor Audit authentication system for vulnerabilities
@cloud-architect Design scalable AWS infrastructure for microservices
```

### Multi-Agent Orchestration
```bash
@agent-organizer Build a complete e-commerce platform with payment integration
# Automatically selects and coordinates: backend-architect, react-pro, security-auditor, api-documenter
```

### Continuous Sprint Management
```bash
@ai-scrum-master Set up automated sprint management for development team
# Establishes 3-hour standup cycles with sub-agent coordination
```

### Complex Feature Development
```bash
@agent-organizer Implement user authentication with social login
# Delegates to: backend-architect, security-auditor, frontend-developer, api-documenter
```

## 🔧 Setup & Configuration

### Installation

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-org/open-swe-agents
   cd open-swe-agents
   ```

2. **Run Setup Script**
   ```bash
   ./setup_claude_agents.sh
   ```

3. **Optimize Agents**
   ```bash
   ./optimize_agents.sh
   ```

4. **Validate Setup**
   ```bash
   ./.claude/validate_agents.sh
   ```

### Configuration

Agent configuration is managed through:

- **Individual Agent Files**: `/category/agent-name.md`
- **Central Configuration**: `.claude/config.json`
- **Environment Variables**: Model settings, API keys, tool configurations

### External Integrations

The agents support various external tool integrations:

- **MCP Servers**: context7, magic, sequential-thinking, playwright
- **Development Tools**: Git, Docker, various testing frameworks
- **Cloud Platforms**: AWS, Azure, GCP
- **Communication**: Slack, Teams, Discord
- **Project Management**: Jira, Linear, Trello

## 🎯 Best Practices

### Agent Selection Guidelines

1. **Use `agent-organizer`** for complex, multi-domain tasks requiring coordination
2. **Use specialized agents** for focused, domain-specific work
3. **Use `ai-scrum-master`** for ongoing project management and sprint coordination
4. **Check `context-manager`** for project state before starting new work

### Communication Best Practices

1. **Always acquire context first** - prevents duplicate work and ensures informed decisions
2. **Report activities back** - maintains project awareness for other agents
3. **Use specific, actionable requests** - helps agents understand exact requirements
4. **Leverage agent expertise** - match tasks to specialized capabilities

### Quality Assurance

1. **Use `code-reviewer`** after significant code changes
2. **Engage `security-auditor`** for security-sensitive features
3. **Involve `performance-engineer`** for scalability-critical components
4. **Coordinate with `test-automator`** for comprehensive testing coverage

---

**The Open-SWE AI Agents Collection transforms software development from individual coding to coordinated AI team collaboration, delivering higher quality results through specialized expertise and intelligent coordination.** 🚀
