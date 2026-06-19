# n8n AI Automation Roadmap

A reusable operating system for learning, designing, documenting, and delivering n8n automation systems.

This repository is a public reference kit for AI automation, workflow engineering, API integration, prompt design, and maintainable automation delivery.

## Purpose

Use this repo as a practical reference when building n8n workflows for learning, portfolio work, freelance delivery, or professional automation design.

It is not a storage location for client secrets, employer data, private credentials, proprietary workflows, or confidential business information.

## Operating Principles

- Document before building.
- Design small workflows before large systems.
- Separate requirements, architecture, workflow logic, testing, and handover.
- Use environment variables and credential managers for secrets.
- Keep reusable workflow patterns generic and client-safe.
- Review AI-generated workflows before execution.

## Core Use Cases

- n8n workflow planning
- AI automation learning
- API integration practice
- Portfolio automation projects
- Client-safe automation templates
- Prompt and agent workflow experiments
- Professional reference while using Claude Code, Copilot, or other AI tools

## Repository Structure

```text
AGENTS.md                 Agent and AI-tool instructions
README.md                 Repository overview
LICENSE                   MIT license
.gitignore                Local and secret-file exclusions
docs/                     Operating docs and standards
templates/                Reusable planning and delivery templates
workflows/                Example or exported n8n workflows
prompts/                  Prompt patterns and AI workflow instructions
examples/                 Code and API examples
roadmap/                  Learning roadmap
resources/                Curated learning references
```

## Recommended Workflow

1. Define the business problem.
2. Write a workflow charter.
3. Identify trigger, inputs, outputs, systems, and risks.
4. Design the workflow architecture.
5. Build the workflow in n8n.
6. Test happy path and failure cases.
7. Document credentials, maintenance, and handover notes without exposing secrets.
8. Review before reuse in client or work environments.

## Core Documents

- [Agent Instructions](AGENTS.md)
- [n8n Operating System](docs/operating-system.md)
- [Workflow Standard](docs/standards/workflow-standard.md)
- [Workflow Charter Template](templates/workflow-charter.md)
- [AI Workflow Prompt Template](templates/ai-workflow-prompt-template.md)

## Public Use Rule

This repository is designed to be safe for public reference.

Do not commit:

- API keys
- access tokens
- OAuth secrets
- exported credentials
- client data
- employer data
- internal company process details
- private screenshots
- production webhook URLs

## License

MIT License.