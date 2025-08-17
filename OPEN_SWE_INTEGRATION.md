# Open-SWE Integration: LangGraph-Based Asynchronous Coding Agent

## Overview

The repository includes a sophisticated integration with **Open-SWE**, an open-source cloud-based asynchronous coding agent built with LangGraph. This integration provides a complementary system to the Claude Code sub-agents, offering end-to-end autonomous coding capabilities that work from initial planning through pull request creation.

## 🏗️ Open-SWE Architecture

### Location & Structure

The Open-SWE system is integrated at `/home/daytona/Open-SWE/external_repos/open-swe/` and provides a complete **LangGraph-based workflow orchestration system**.

```
external_repos/open-swe/
├── apps/
│   ├── open-swe/           # Core LangGraph agent application
│   ├── web/                # Next.js 15 + React 19 web interface
│   ├── docs/               # Comprehensive documentation
│   └── cli/                # Command-line interface
├── packages/
│   └── shared/             # Common utilities and types (@open-swe/shared)
├── langgraph.json          # LangGraph configuration
├── package.json            # Yarn workspace configuration
├── turbo.json              # Turbo build orchestration
└── yarn.lock               # Dependency lockfile
```

### Core Technology Stack

#### **LangGraph Orchestration**
- **Three Primary Graphs**: Programmer, Planner, and Manager
- **Node.js 20**: Modern runtime environment
- **TypeScript**: Strict type safety across all packages
- **Asynchronous Processing**: Non-blocking workflow execution

```json
{
  "graphs": {
    "programmer": "./apps/open-swe/src/graphs/programmer/index.ts:graph",
    "planner": "./apps/open-swe/src/graphs/planner/index.ts:graph", 
    "manager": "./apps/open-swe/src/graphs/manager/index.ts:graph"
  }
}
```

#### **Modern Web Stack**
- **Next.js 15**: Latest React framework with app router
- **React 19**: Concurrent features and improved performance
- **Shadcn UI**: Component library built on Radix UI
- **Tailwind CSS**: Utility-first styling system
- **Turbo + Yarn**: Monorepo management and optimized builds

#### **Development Infrastructure**
- **Yarn 3.5.1**: Modern package manager with workspace support
- **ESLint + Prettier**: Code quality and formatting
- **Jest + Vitest**: Comprehensive testing frameworks
- **TypeScript 5.7**: Advanced type system features

## 🎯 Core Features & Capabilities

### 1. **📝 Planning Phase**

Open-SWE implements a **dedicated planning step** that provides sophisticated codebase analysis and strategic task planning.

#### **Deep Codebase Understanding**
- **Repository Analysis**: Comprehensive scanning of project structure, dependencies, and architecture patterns
- **Context Extraction**: Intelligent understanding of existing code patterns and conventions
- **Task Decomposition**: Breaking complex requests into manageable, sequential steps
- **Risk Assessment**: Identifying potential challenges and dependencies

#### **Interactive Plan Review**
- **Plan Presentation**: Clear, structured presentation of proposed implementation strategy
- **Human Approval**: Ability to accept, edit, or reject proposed plans before execution
- **Plan Refinement**: Iterative improvement based on feedback and requirements
- **Alternative Strategies**: Recommendation of multiple approach options when applicable

### 2. **🤝 Human-in-the-Loop Integration**

The system provides **real-time collaboration** capabilities throughout both planning and execution phases.

#### **Live Communication**
- **Real-time Messaging**: Send instructions and feedback while tasks are running
- **Context-Aware Responses**: Agent understands and incorporates mid-task feedback
- **Non-Interrupting Workflow**: Feedback integration without stopping execution
- **Progress Updates**: Continuous status updates and milestone reporting

#### **Collaborative Decision Making**
- **Approval Gates**: Strategic pause points for human validation
- **Course Correction**: Ability to adjust strategy during execution
- **Quality Validation**: Human oversight of critical implementation decisions
- **Domain Expertise Input**: Integration of specialized human knowledge when needed

### 3. **🏃 Parallel Execution Architecture**

Open-SWE supports **unlimited concurrent task execution** in sandboxed cloud environments.

#### **Scalable Task Management**
- **Unlimited Parallelism**: Run multiple Open-SWE tasks simultaneously
- **Sandboxed Environments**: Each task executes in isolated cloud containers
- **Resource Optimization**: Intelligent allocation of computational resources
- **Conflict Resolution**: Automatic handling of concurrent modification conflicts

#### **Distributed Workflow Orchestration**
- **Task Independence**: Parallel tasks operate without interference
- **State Synchronization**: Coordinated state management across concurrent workflows
- **Progress Monitoring**: Real-time tracking of multiple parallel executions
- **Error Isolation**: Failures in one task don't affect others

### 4. **🧑‍💻 End-to-End Task Management**

Complete automation from task initiation through deployment and documentation.

#### **GitHub Integration**
- **Automatic Issue Creation**: Creates GitHub issues for task tracking
- **Pull Request Generation**: Generates PRs with comprehensive descriptions and change summaries
- **Issue Lifecycle Management**: Automatically closes issues when PRs are merged
- **Branch Management**: Creates and manages feature branches for development

#### **Quality Assurance Pipeline**
- **Automated Testing**: Runs existing test suites and creates new tests as needed
- **Code Review Preparation**: Generates detailed PR descriptions with implementation rationale
- **Documentation Updates**: Maintains project documentation alongside code changes
- **Compliance Checking**: Ensures adherence to project standards and conventions

## 🌐 Usage Methods & Integration Points

### 1. **🖥️ Web Application Interface**

#### **Full-Featured Web UI**
- **Public Demo**: Available at [https://swe.langchain.com](https://swe.langchain.com)
- **Task Creation**: Intuitive interface for defining and configuring tasks
- **Progress Monitoring**: Real-time dashboards showing task status and progress
- **Interactive Planning**: Web-based plan review and approval workflow
- **Result Management**: Comprehensive view of completed tasks and generated artifacts

#### **Key Web Features**
- **Visual Workflow**: Graphical representation of task execution flow
- **Live Chat Interface**: Real-time communication with the agent during execution
- **File Management**: Browse and review generated code changes
- **History Tracking**: Complete audit trail of all task activities

### 2. **📝 GitHub Integration**

Open-SWE provides **seamless GitHub integration** through issue labels, enabling developers to trigger tasks directly from their existing workflow.

#### **Label-Based Task Initiation**

##### **Standard Operations**
- **`open-swe`**: Standard mode with human plan approval required
  - Agent creates detailed plan and waits for human approval
  - Interactive planning phase with ability to modify approach
  - Full human oversight throughout execution

- **`open-swe-auto`**: Fully automated execution with no human intervention
  - Agent automatically accepts generated plan and proceeds with execution
  - Suitable for routine tasks and well-defined requirements
  - Complete end-to-end automation

##### **Enhanced Performance Modes**
- **`open-swe-max`**: Premium mode using Claude Opus 4.1 for maximum capability
  - Enhanced reasoning and problem-solving for complex tasks
  - Superior code quality and architectural decisions
  - Human plan approval required

- **`open-swe-max-auto`**: Premium automated mode with Claude Opus 4.1
  - Maximum AI capability with full automation
  - Ideal for complex tasks that require sophisticated reasoning
  - Combines premium model performance with automated workflow

#### **GitHub Workflow Integration**

```yaml
# Example GitHub Issue with Open-SWE Integration
Title: "Implement user authentication with JWT tokens"
Labels: ["open-swe-max", "enhancement"]
Body: |
  ## Requirements
  - Secure JWT-based authentication system
  - User registration and login endpoints
  - Password hashing with bcrypt
  - Integration with existing React frontend
  
  ## Acceptance Criteria
  - [ ] Backend API endpoints for auth
  - [ ] Secure token generation and validation
  - [ ] Frontend authentication flow
  - [ ] Comprehensive test coverage
```

**Automated Workflow:**
1. **Issue Detection**: Open-SWE monitors for labeled issues
2. **Context Analysis**: Analyzes issue description and repository context
3. **Plan Generation**: Creates comprehensive implementation plan
4. **Execution**: Implements solution according to plan
5. **PR Creation**: Generates pull request with detailed changes
6. **Issue Closure**: Automatically closes issue when PR is merged

## 🔗 Integration with Claude Code Sub-Agents

### Complementary Architecture

The Open-SWE system **complements rather than replaces** the Claude Code sub-agents, providing different but synergistic capabilities:

#### **Claude Code Sub-Agents** (Synchronous, Interactive)
- **Immediate Response**: Real-time assistance and code generation
- **Specialized Expertise**: 116+ domain-specific experts
- **Interactive Development**: Step-by-step collaborative coding
- **Quality Assurance**: Built-in review and validation processes

#### **Open-SWE** (Asynchronous, Autonomous)
- **End-to-End Automation**: Complete task lifecycle management
- **Strategic Planning**: Deep codebase analysis and implementation planning
- **Autonomous Execution**: Independent task completion with minimal oversight
- **GitHub Integration**: Native version control and project management

### Hybrid Workflow Patterns

#### **Complex Project Initiation**
```bash
# Phase 1: Strategic Planning with Open-SWE
GitHub Issue → open-swe-max → Implementation Plan → PR Creation

# Phase 2: Refinement with Claude Code Agents
@code-reviewer "Review the authentication implementation"
@security-auditor "Audit JWT token handling for vulnerabilities"
@test-automator "Add comprehensive test coverage"
```

#### **Iterative Development**
```bash
# Long-term autonomous development
GitHub Issues → open-swe-auto → Continuous implementation

# Real-time collaboration and refinement  
@react-pro "Optimize the login component performance"
@ui-designer "Improve authentication flow UX"
```

## 📊 Technical Specifications

### **LangGraph Configuration**

```typescript
// Graph Definitions
export const graphs = {
  programmer: "./src/graphs/programmer/index.ts:graph",
  planner: "./src/graphs/planner/index.ts:graph", 
  manager: "./src/graphs/manager/index.ts:graph"
};

// Authentication & Security
export const auth = "./src/security/auth.ts:auth";

// HTTP Application
export const app = "./src/routes/app.ts:app";
```

### **Key Dependencies**

```json
{
  "core": [
    "@langchain/langgraph@^0.3.8",
    "@langchain/anthropic@^0.3.26",
    "@langchain/core@^0.3.65"
  ],
  "integration": [
    "@octokit/rest@^22.0.0",
    "@octokit/webhooks@^14.0.2", 
    "@daytonaio/sdk@^0.25.5"
  ],
  "web": [
    "next@15",
    "react@19",
    "tailwindcss"
  ]
}
```

### **Development & Testing**

```bash
# Development server
yarn dev

# Build system
turbo build

# Testing suite
yarn test          # Unit tests
yarn test:int      # Integration tests  
yarn test:single   # Individual test execution

# Code quality
yarn lint          # ESLint validation
yarn format        # Prettier formatting
```

## 🎯 Use Cases & Scenarios

### **1. Autonomous Feature Development**

```markdown
**Scenario**: Implement complete user authentication system
**Method**: GitHub issue with `open-swe-max` label
**Process**: 
1. Agent analyzes existing codebase architecture
2. Creates comprehensive implementation plan
3. Implements backend API, database schema, frontend integration
4. Creates test suites and updates documentation
5. Generates PR with complete feature implementation
```

### **2. Legacy System Modernization**

```markdown
**Scenario**: Migrate PHP application to modern Node.js stack
**Method**: Series of `open-swe-auto` labeled issues
**Process**:
1. Systematic analysis of existing PHP codebase
2. Incremental migration strategy with backwards compatibility
3. Automated testing during migration process
4. Documentation and deployment pipeline updates
```

### **3. Continuous Integration Enhancement**

```markdown
**Scenario**: Ongoing code quality and feature development
**Method**: Combination of Open-SWE automation + Claude Code refinement
**Workflow**:
- Open-SWE: Autonomous implementation of well-defined features
- Claude Code: Real-time code review, optimization, and specialized expertise
- Integrated QA: Multiple validation layers ensuring code quality
```

## 🚀 Getting Started with Open-SWE

### **Local Development Setup**

```bash
# Navigate to Open-SWE directory
cd external_repos/open-swe

# Install dependencies (Yarn workspace)
yarn install

# Set up environment variables
cp apps/open-swe/.env.example apps/open-swe/.env
cp apps/web/.env.example apps/web/.env

# Configure LLM API keys in .env files
# ANTHROPIC_API_KEY=your-key-here
# OPENAI_API_KEY=your-key-here

# Start development servers
yarn dev
```

### **GitHub Integration Setup**

```bash
# 1. Configure GitHub App (for repository integration)
# 2. Set webhook URL for issue event handling
# 3. Configure repository permissions for PR creation
# 4. Add Open-SWE labels to repository label system
```

### **Web Application Access**

```bash
# Public demo (requires API keys)
https://swe.langchain.com

# Local development
http://localhost:3000  # Web interface
http://localhost:8080  # LangGraph API
```

## 🎉 Summary: Integrated AI Development Ecosystem

The Open-SWE integration transforms this repository into a **comprehensive AI development ecosystem**:

### **Dual-Mode Operation**
- **Synchronous**: Claude Code sub-agents for real-time collaboration
- **Asynchronous**: Open-SWE for autonomous task completion

### **Complete Coverage**
- **Immediate Assistance**: 116+ specialized Claude Code agents
- **End-to-End Automation**: Open-SWE for complete feature development
- **Quality Assurance**: Multi-layer validation and review processes

### **Flexible Integration**
- **Web Interface**: Full-featured application for task management
- **GitHub Native**: Seamless integration with existing development workflows
- **Hybrid Workflows**: Combine automated execution with specialized expertise

This integration provides developers with unprecedented flexibility: from quick code assistance to complete autonomous feature development, all within a cohesive, quality-assured system that scales from individual tasks to enterprise-level development workflows.
