# Skills Directory

**Welcome to the skills folder!** This is where 1000+ specialized AI skills live, organized into 15 categories.

## What Are Skills?

Skills are specialized instruction sets that teach AI assistants how to handle specific tasks — like expert knowledge modules you can load on-demand.

**Analogy:** Just like consulting different experts (a designer, a security researcher, a marketer), skills let your AI become a domain expert when you need it.

---

## Folder Structure

```
claude-skills/
├── 01-azure/                  # Azure & Microsoft 365 SDK skills
├── 02-ai-agents-llm/          # AI agents, LLM tools, RAG, prompting
├── 03-cloud-devops/           # Cloud, DevOps, CI/CD, infrastructure
├── 04-security/               # Security testing, auditing, pen testing
├── 05-frontend/               # Frontend frameworks, UI/UX, design
├── 06-backend/                # Backend, APIs, languages, frameworks
├── 07-mobile/                 # Mobile development (iOS, Android, etc.)
├── 08-automation/             # SaaS integrations & workflow automation
├── 09-data-ml/                # Data engineering, ML, databases
├── 10-testing-qa/             # Testing, QA, code review, debugging
├── 11-documentation/          # Docs, office files, wikis, writing
├── 12-planning-workflow/      # Planning, architecture, workflow design
├── 13-business-marketing/     # Business, marketing, SEO, legal
├── 14-system-infra/           # System admin, networking, Linux
└── 15-meta-skills/            # Skill management & Claude tooling
```

Each skill folder contains:
```
skill-name/
├── SKILL.md        # Main skill definition (required)
├── scripts/        # Helper scripts (optional)
├── examples/       # Usage examples (optional)
└── resources/      # Templates & resources (optional)
```

---

## How to Use Skills

**Step 1:** Make sure skills are in your agent's skills directory (`.claude/skills/`, `.agent/skills/`, etc.)

**Step 2:** Invoke a skill with the `@` symbol:
```
@brainstorming help me design a todo app
@stripe-integration add payment processing to my app
@ethical-hacking-methodology assess this web app
```

**Step 3:** The AI loads that skill's knowledge and helps with specialized expertise.

---

## Skill Categories

### 01 — Azure (121 skills)
Azure SDK & Microsoft 365 integrations across .NET, Java, Python, TypeScript, and Rust.

| Skill | Description |
|-------|-------------|
| `@azure-ai-projects-py` | Azure AI Foundry projects in Python |
| `@azure-openai-dotnet` | Azure OpenAI integration for .NET |
| `@azure-cosmos-py` | Cosmos DB operations in Python |
| `@azure-storage-blob-ts` | Azure Blob Storage in TypeScript |
| `@azure-functions` | Azure Functions development |
| `@azure-identity-py` | Azure authentication & identity |
| `@m365-agents-ts` | Microsoft 365 agents in TypeScript |
| `@azd-deployment` | Azure Developer CLI deployments |

---

### 02 — AI Agents & LLM (70 skills)
Building, orchestrating, and optimizing AI agents, LLM apps, and prompt pipelines.

| Skill | Description |
|-------|-------------|
| `@agent-orchestration-multi-agent-optimize` | Optimize multi-agent systems |
| `@autonomous-agents` | Build self-directing AI agents |
| `@langchain-architecture` | LangChain app architecture |
| `@langgraph` | LangGraph stateful agent workflows |
| `@rag-engineer` | Build RAG pipelines |
| `@prompt-engineering` | Write effective prompts |
| `@mcp-builder` | Build MCP servers |
| `@llm-evaluation` | Evaluate LLM outputs |
| `@crewai` | Multi-agent CrewAI workflows |
| `@voice-ai-development` | Voice AI app development |

---

### 03 — Cloud & DevOps (65 skills)
Cloud platforms, containerization, CI/CD, infrastructure-as-code, and observability.

| Skill | Description |
|-------|-------------|
| `@kubernetes-architect` | K8s cluster design & management |
| `@terraform-specialist` | Advanced Terraform IaC |
| `@docker-expert` | Docker containers & Compose |
| `@github-actions-templates` | GitHub Actions CI/CD templates |
| `@aws-serverless` | AWS Lambda & serverless patterns |
| `@gcp-cloud-run` | Google Cloud Run deployments |
| `@helm-chart-scaffolding` | Helm chart creation |
| `@observability-engineer` | Metrics, logs, tracing setup |
| `@gitops-workflow` | GitOps deployment patterns |
| `@vercel-deployment` | Vercel app deployments |

---

### 04 — Security (71 skills)
Penetration testing, vulnerability scanning, threat modeling, and security auditing.

| Skill | Description |
|-------|-------------|
| `@ethical-hacking-methodology` | Structured pen test methodology |
| `@burp-suite-testing` | Web app security with Burp Suite |
| `@metasploit-framework` | Exploit development & testing |
| `@threat-modeling-expert` | STRIDE threat modeling |
| `@security-audit` | Comprehensive security auditing |
| `@red-team-tactics` | Red team attack simulation |
| `@vulnerability-scanner` | Automated vulnerability scanning |
| `@incident-responder` | Incident response procedures |
| `@malware-analyst` | Malware analysis & reverse engineering |
| `@api-security-testing` | API security assessment |

---

### 05 — Frontend (84 skills)
React, Angular, Next.js, TypeScript, UI/UX design, and web development.

| Skill | Description |
|-------|-------------|
| `@react-best-practices` | Modern React patterns & hooks |
| `@nextjs-best-practices` | Next.js App Router development |
| `@angular-best-practices` | Angular architecture & patterns |
| `@typescript-expert` | Advanced TypeScript techniques |
| `@ui-ux-pro-max` | Professional UI/UX design |
| `@tailwind-design-system` | Tailwind CSS design systems |
| `@react-state-management` | State management patterns |
| `@graphql-architect` | GraphQL schema & resolver design |
| `@web-artifacts-builder` | Build React + Tailwind apps fast |
| `@threejs-skills` | 3D web experiences with Three.js |

---

### 06 — Backend (98 skills)
Server-side development, APIs, databases, frameworks, and programming languages.

| Skill | Description |
|-------|-------------|
| `@python-pro` | Expert Python development |
| `@golang-pro` | Expert Go development |
| `@rust-pro` | Expert Rust development |
| `@java-pro` | Expert Java development |
| `@fastapi-pro` | FastAPI Python web services |
| `@nestjs-expert` | NestJS backend architecture |
| `@microservices-patterns` | Microservices design patterns |
| `@api-design-principles` | RESTful API design best practices |
| `@senior-fullstack` | Full-stack development expertise |
| `@event-sourcing-architect` | Event sourcing & CQRS |

---

### 07 — Mobile (15 skills)
iOS, Android, cross-platform, and game development.

| Skill | Description |
|-------|-------------|
| `@ios-developer` | iOS app development |
| `@android-jetpack-compose-expert` | Jetpack Compose UI |
| `@flutter-expert` | Flutter cross-platform apps |
| `@react-native-architecture` | React Native app structure |
| `@swiftui-expert-skill` | SwiftUI interface development |
| `@expo-deployment` | Expo app deployment |
| `@unity-developer` | Unity game development |
| `@unreal-engine-cpp-pro` | Unreal Engine C++ development |

---

### 08 — Automation & Integrations (143 skills)
SaaS platform integrations, workflow automation, and third-party API connections.

| Skill | Description |
|-------|-------------|
| `@n8n-node-configuration` | n8n workflow automation |
| `@zapier-make-patterns` | Zapier & Make.com workflows |
| `@slack-bot-builder` | Slack bot development |
| `@github-automation` | GitHub API automation |
| `@shopify-development` | Shopify app & theme development |
| `@stripe-automation` | Stripe payment automation |
| `@salesforce-development` | Salesforce development |
| `@hubspot-integration` | HubSpot CRM integration |
| `@odoo-module-developer` | Odoo module development |
| `@telegram-bot-builder` | Telegram bot creation |

---

### 09 — Data & ML (41 skills)
Data engineering, machine learning, databases, SQL, and analytics.

| Skill | Description |
|-------|-------------|
| `@ml-engineer` | Machine learning engineering |
| `@mlops-engineer` | ML pipeline operations |
| `@data-engineer` | Data pipeline development |
| `@postgresql-optimization` | PostgreSQL performance tuning |
| `@vector-database-engineer` | Vector DB setup & optimization |
| `@dbt-transformation-patterns` | dbt data transformation |
| `@spark-optimization` | Apache Spark performance |
| `@sql-pro` | Expert SQL development |
| `@airflow-dag-patterns` | Apache Airflow DAG design |
| `@rag-implementation` | RAG system implementation |

---

### 10 — Testing & QA (57 skills)
Test-driven development, code review, debugging, performance, and quality assurance.

| Skill | Description |
|-------|-------------|
| `@test-driven-development` | TDD red-green-refactor cycle |
| `@systematic-debugging` | Root-cause-first debugging |
| `@playwright-skill` | Playwright E2E testing |
| `@code-reviewer` | Elite code review expert |
| `@e2e-testing` | End-to-end test strategy |
| `@performance-engineer` | Performance analysis & optimization |
| `@receiving-code-review` | Handle review feedback properly |
| `@requesting-code-review` | Request reviews before merging |
| `@create-pr` | Create well-structured PRs |
| `@vibe-code-auditor` | AI-generated code quality audit |

---

### 11 — Documentation & Office (34 skills)
Technical writing, office documents, wikis, and communication.

| Skill | Description |
|-------|-------------|
| `@docx-official` | Create & edit Word documents |
| `@xlsx-official` | Excel spreadsheets & formulas |
| `@pptx-official` | PowerPoint presentations |
| `@pdf-official` | PDF handling & form filling |
| `@doc-coauthoring` | Collaborative document writing |
| `@wiki-architect` | Documentation site architecture |
| `@internal-comms` | Internal announcements & reports |
| `@readme` | Write clear README files |
| `@api-documentation-generator` | Auto-generate API docs |
| `@postmortem-writing` | Incident postmortem documents |

---

### 12 — Planning & Workflow (38 skills)
Architecture planning, workflow design, domain modeling, and project execution.

| Skill | Description |
|-------|-------------|
| `@brainstorming` | Design & ideate before coding |
| `@writing-plans` | Write detailed implementation plans |
| `@executing-plans` | Execute plans with checkpoints |
| `@domain-driven-design` | DDD strategic & tactical patterns |
| `@c4-architecture-c4-architecture` | C4 architecture diagrams |
| `@conductor-setup` | Multi-track project orchestration |
| `@using-git-worktrees` | Parallel work with Git worktrees |
| `@verification-before-completion` | Verify before claiming done |
| `@finishing-a-development-branch` | Complete dev branches cleanly |
| `@ddd-strategic-design` | Domain-driven strategic design |

---

### 13 — Business & Marketing (95 skills)
SEO, content marketing, business analysis, legal, operations, and growth.

| Skill | Description |
|-------|-------------|
| `@seo-content-writer` | SEO-optimized content writing |
| `@seo-audit` | Comprehensive SEO site audit |
| `@product-manager-toolkit` | PM frameworks & templates |
| `@startup-analyst` | Startup analysis & evaluation |
| `@business-analyst` | Business requirements analysis |
| `@marketing-ideas` | Creative marketing campaigns |
| `@paid-ads` | PPC & paid advertising strategy |
| `@legal-advisor` | Legal document review & advice |
| `@pricing-strategy` | Product pricing frameworks |
| `@launch-strategy` | Product launch planning |

---

### 14 — System & Infrastructure (10 skills)
Linux, networking, system administration, and low-level programming.

| Skill | Description |
|-------|-------------|
| `@linux-troubleshooting` | Diagnose & fix Linux issues |
| `@linux-shell-scripting` | Bash & shell script development |
| `@network-engineer` | Network design & troubleshooting |
| `@powershell-windows` | Windows PowerShell automation |
| `@arm-cortex-expert` | ARM Cortex embedded development |
| `@os-scripting` | OS-level scripting patterns |
| `@distributed-debugging-debug-trace` | Distributed system debugging |

---

### 15 — Meta Skills (67 skills)
Skill management, Claude tooling, workflow utilities, and miscellaneous experts.

| Skill | Description |
|-------|-------------|
| `@skill-creator` | Create new skills or update existing ones |
| `@skill-builder` | Build skill collections |
| `@commit` | Git commits with good messages |
| `@claude-code-guide` | Claude Code features & usage |
| `@mcp-builder` | Build MCP servers |
| `@brand-guidelines` | Apply brand design standards |
| `@research-engineer` | Deep technical research |
| `@tutorial-engineer` | Write developer tutorials |
| `@deep-research` | Comprehensive research workflows |
| `@personal-tool-builder` | Build custom personal tools |

---

## Finding Skills

```bash
# Browse a category
ls 05-frontend/

# Search across all categories
ls */  | grep "react"

# Find skills matching a keyword
find . -name "SKILL.md" | xargs grep -l "keyword" 2>/dev/null
```

---

## Popular Skills to Try

**For developers:**
- `@brainstorming` — Design before coding
- `@test-driven-development` — Write tests first
- `@systematic-debugging` — Fix bugs methodically
- `@react-best-practices` — Modern React patterns
- `@senior-fullstack` — Full-stack expertise

**For DevOps:**
- `@kubernetes-architect` — K8s design
- `@terraform-specialist` — IaC best practices
- `@github-actions-templates` — CI/CD pipelines

**For security:**
- `@ethical-hacking-methodology` — Security basics
- `@burp-suite-testing` — Web app pen testing
- `@threat-modeling-expert` — STRIDE threat modeling

**For AI/ML:**
- `@rag-engineer` — Build RAG systems
- `@prompt-engineering` — Effective prompting
- `@mlops-engineer` — ML pipeline operations

---

## Creating Your Own Skill

Use `@skill-creator` to generate a new skill, or follow this structure:

```markdown
---
name: my-skill-name
description: "What this skill does"
---

# Skill Title

## Overview
[What this skill does]

## When to Use
- Use when [scenario]

## Instructions
[Step-by-step guide]

## Examples
[Code examples]
```

Place the folder in the most relevant category directory.

---

**Total: 1009 skills across 15 categories**
