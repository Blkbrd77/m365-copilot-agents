# M365 Copilot Agents Repository

This repository provides configuration, best practices, and sample templates for setting up Microsoft 365 Copilot agents in Studio, specifically designed to assist with:

- Migrating Microsoft Access databases to Power Apps and Power Automate using Dataverse as the database layer
- Providing senior developer guidance for junior devs on modernizing legacy apps
- Ensuring security and maintainability best practices throughout migration and integration

## Structure

- `agents/`: Copilot agent configurations (YAML)
- `configs/`: Connection/configuration samples (Dataverse, Power Platform, etc)
- `docs/`: Guidance on exports and best practices
- `samples/`: Example project exports and data files

## Getting Started

1. Review the agent YAML in `agents/` to onboard your Copilot agent in Studio.
2. Follow `docs/exports-guidance.md` to collect the maximum context for your migration use case.
3. Use sample configs and exported data as references/templates.

## First Use Case: Access-to-PowerApps Senior Dev Agent

This agent:
- Guides the extraction of Access structure and relevant exports from Power Apps, Power Automate, and Dataverse.
- Advises and mentors junior developers in the migration process.
- Provides up-to-date best practices on security, maintainability, and ease of use.

## How to Use

1. Export your existing Access, Power Apps, Power Automate, and Dataverse data as described in `docs/exports-guidance.md`.
2. Fill in the agent configuration in `agents/access-to-powerapps-senior-dev.yaml` with your project details.
3. Connect your agent in Copilot Studio.

---
For contributions, please submit issues or pull requests.