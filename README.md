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

| Project | What I'm building | Current stage |
| :--- | :--- | :--- |
| **[SCRYMR](https://github.com/amiencoy/scrymr)** | A Discord security and incident-response sentinel: detection, risk scoring, policy checks, moderator approval, and audit records. Formerly SCREAMRRRR. | **Pre-alpha** · dry-run by default |
| **[Parabiont Protocol](https://github.com/amiencoy/parabiont-protocol)** | An open-protocol initiative for persistent, governed agent attachment: consent, lifecycle, capability boundaries, and revocation. | **Design & specification** |
| **[Axionorm](https://github.com/amiencoy/axionorm)** | Agent policy as code: a YAML-first initiative for portable authority and governance rules, with an optional OPA/Rego backend planned. | **Specification planning** |
| **[Lophiont](https://github.com/amiencoy/lophiont)** | A planned carrier connecting Lophiarch to external agents and graph systems, with a BloodHound bridge in scope. Formerly AnglerGhost. | **Design stage** |
| **[Catapult](https://github.com/amiencoy/catapult)** | A design for self-hosted encrypted API-key storage and reusable, named API operations across applications and languages. | **Early concept** |

The direction is to give each project a clear responsibility: **Lophiarch** handles reconnaissance, **SCRYMR** handles Discord security workflows, **Lophiont** explores the carrier role, **Parabiont Protocol** describes attachment, and **Axionorm** describes authority. **Catapult** explores a separate credential and API-access layer.

The protocol and carrier relationships are design targets. Parabiont Protocol, Axionorm, Lophiont, and Catapult do not yet ship stable implementations or claim completed interoperability.

## Recent milestones

**September 2026**

- **Lophiarch v2.2.2:** published the patch release; completed the Reconnator → Lophiarch rebrand across the current codebase, documentation, Wiki, and container publishing.
- **SCRYMR:** completed the SCREAMRRRR → SCRYMR rebrand, including the Python package and entry point, with migration notes for existing configurations.
- **New public projects:** launched the Parabiont Protocol, Axionorm, and Lophiont repositories with their scope, boundaries, and initial roadmaps.
- **Next focus:** modular agent components, clearer policy contracts, and documented integration boundaries.

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
