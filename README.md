<div align="center">
  <h1>Digital Monkey</h1>
  <p><strong>Automation Engineer &amp; IT Consultant</strong></p>
  <p>Infrastructure, security, and agent workflows.<br>Creating tools to help you chill a bit longer.</p>
  <p>
    <a href="https://www.linkedin.com/in/muhammad-amien/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square" alt="Connect on LinkedIn"></a>
    <a href="https://github.com/sponsors/amiencoy"><img src="https://img.shields.io/badge/GitHub-Sponsor-DB2777?style=flat-square&logo=githubsponsors&logoColor=white" alt="Sponsor my open-source work"></a>
  </p>
  <p>
    <a href="#what-im-building">Projects</a> ·
    <a href="#recent-milestones">Updates</a> ·
    <a href="#engineering-toolkit">Toolkit</a> ·
    <a href="#work-with-me">Work with me</a>
  </p>
</div>

---

I build automation that connects infrastructure, security tools, and the people operating them. My work spans server hardening, infrastructure as code, CI/CD, ChatOps, and AI-assisted workflows.

I care about systems that are understandable, repeatable, and maintainable: clear scope, explicit permissions, useful logs, and a human decision where it matters.

## What I'm building

### Lophiarch — reconnaissance through ChatOps

**Formerly Reconnator · Released: [v2.2.2](https://github.com/amiencoy/lophiarch/releases/tag/v2.2.2)**

An AI-assisted reconnaissance product that brings Telegram, MCP tool orchestration, disposable scanner containers, and PDF reporting into one workflow. It supports local or hosted models through an OpenAI-compatible interface, with policy checks and explicit target authorization before active scans.

[Repository](https://github.com/amiencoy/lophiarch) · [Documentation](https://github.com/amiencoy/lophiarch/wiki) · [Releases](https://github.com/amiencoy/lophiarch/releases) · [Migration guide](https://github.com/amiencoy/lophiarch/blob/main/docs/MIGRATION.md)

### The growing ecosystem

| Project | What it does | Version / stage | Repository |
| :--- | :--- | :--- | :--- |
| **SCRYMR** | Discord security and incident-response sentinel with detection, policy checks, moderator approval, and audit records; dry-run by default. | `0.1.0.dev0` · pre-alpha, no tagged release | [Repository](https://github.com/amiencoy/scrymr) |
| **Parabiont Protocol** | Experimental signed context-carrier profile over A2A, with expiry, revocation, and an MCP gateway after policy filtering. | `v0.1.0` · experimental | [Repository](https://github.com/amiencoy/parabiont-protocol) |
| **Axionorm** | YAML-first agent policy as code with a working OPA/Rego evaluator and digest-bound context review. | `v0.1.0` · experimental | [Repository](https://github.com/amiencoy/axionorm) |
| **PARALAX MCP** | Policy-gated MCP tools and a combined installer for the local Axionorm → Parabiont → MCP flow; desktop configuration is generated for Gemini CLI/AionUi. | `v0.1.0` · experimental integration | [Repository](https://github.com/amiencoy/paralax-mcp) |
| **Discord Bot Notifier** | Self-hosted Discord alerts and slash commands with selectable GPT, Claude, Gemini, Mistral, Grok, Llama, or OpenAI-compatible local models. | `v0.2.0` source · live bot/provider setup required | [Repository](https://github.com/amiencoy/discord-bot-notifier) |
| **Lophiont** | Planned carrier connecting Lophiarch to external agents and graph systems, including a scoped BloodHound bridge. Formerly AnglerGhost. | Design stage · unversioned | [Repository](https://github.com/amiencoy/lophiont) |
| **Catapult** | Planned self-hosted encrypted credential storage and reusable, named API operations across applications. | Early concept · unversioned | [Repository](https://github.com/amiencoy/catapult) |

Each project has a defined responsibility: **Lophiarch** handles reconnaissance, **SCRYMR** handles Discord security workflows, **Parabiont Protocol** carries governed context, **Axionorm** evaluates authority, and **PARALAX MCP** exposes bounded tools to the receiving agent. **Discord Bot Notifier** is a separate Discord alert and model-control utility. **Lophiont** and **Catapult** remain design initiatives.

Axionorm, Parabiont Protocol, and PARALAX MCP have an experimental local integration; live Gemini desktop behavior and production deployment remain to be validated. The notifier's provider adapters have local tests, while Discord and provider calls require operators to configure their own credentials.

## Recent milestones

**September 2026**

- **Lophiarch v2.2.2:** published the patch release and completed the Reconnator → Lophiarch rebrand across the codebase, documentation, Wiki, and container publishing.
- **SCRYMR 0.1.0.dev0:** completed the SCREAMRRRR → SCRYMR rebrand. It remains pre-alpha, with dry-run as its default.
- **Axionorm, Parabiont Protocol & PARALAX MCP v0.1.0:** added a local OPA policy → signed A2A context → governed MCP flow, plus a combined installer. Live desktop integration still needs validation on the operator's machine.
- **Discord Bot Notifier v0.2.0:** published a self-hosted Discord bot and assistant workflow with per-model status, selected alert types, and multi-provider model commands. Each operator supplies their own bot and API credentials.
- **Lophiont & Catapult:** published their scopes and initial roadmaps; both remain design-stage work.

## How I approach engineering

- **Automate repeatable work.** Turn operational steps into versioned configuration and pipelines.
- **Keep authority explicit.** Separate what an AI model proposes from what a runtime may execute.
- **Build replaceable components.** Keep providers, tools, policy, and chat interfaces independently maintainable.
- **Leave evidence behind.** Make logs, reports, migration notes, and documentation part of the work.

## Engineering toolkit

| Area | Tools & technologies |
| :--- | :--- |
| **Infrastructure & orchestration** | Docker, Kubernetes, K3s, MicroK8s, Helm |
| **Infrastructure as code & configuration** | Terraform, Ansible, Pulumi, OpenTofu, Chef |
| **CI/CD & observability** | GitHub Actions, Jenkins, GitLab Runner, Prometheus, Grafana, ELK |
| **Security & compliance** | CIS-aligned hardening, Lynis, OpenSCAP, Chef InSpec |
| **AI & integrations** | MCP, OpenAI-compatible model APIs, local inference, Hybrid RAG, Telegram & Discord ChatOps |
| **Languages & application development** | Python, Go, FastAPI, Flask, Django, Streamlit, Gradio, Gin, Echo |
| **Cloud platforms** | AWS, Google Cloud, Microsoft Azure, Alibaba Cloud |

## Work with me

I work on infrastructure automation, server hardening and compliance auditing, CI/CD, ChatOps integrations, and Hybrid RAG applications.

Commercial engineering and deployment work is handled through **Draxis Digital**. I'm open to project discussions, technical collaboration, and consulting engagements. My Hybrid RAG customer-service chatbot work is also available for commercial discussions.

For project scope, product inquiries, or partnerships, reach me on [LinkedIn](https://www.linkedin.com/in/muhammad-amien/).

### Support the work

[GitHub Sponsors](https://github.com/sponsors/amiencoy) helps fund Lophiarch maintenance, CI/CD and security scanning, infrastructure testing, documentation, and future development. Sponsorship and commercial services are handled separately.

---

<p align="center"><sub>Built with code, coffee, and a healthy dislike of repetitive work.</sub></p>
