<!--
Sync Impact Report:
- Version change: 0.0.0 → 1.0.0
- List of modified principles:
  - [PRINCIPLE_1_NAME] → I. Technology Stack
  - [PRINCIPLE_2_NAME] → II. Database
  - [PRINCIPLE_3_NAME] → III. Authentication and Authorization
  - [PRINCIPLE_4_NAME] → IV. Configuration and Secrets
  - [PRINCIPLE_5_NAME] → V. Development and Tooling
- Added sections:
  - UI and Deployment
- Removed sections:
  - None
- Templates requiring updates:
  - ✅ .specify/templates/plan-template.md
  - ⏳ .specify/templates/spec-template.md
  - ⏳ .specify/templates/tasks-template.md
  - ✅ .gemini/commands/constitution.toml
- Follow-up TODOs:
  - None
-->
# account-view Constitution
<!-- This constitution outlines the core principles and standards for the account-view project. -->

## Core Principles

### I. Technology Stack
The project MUST use the .NET Aspire v9.5 template with .NET 10, ASP.NET Core Blazor in Interactive Server render mode, and the latest version of C#.

### II. Database
PostgreSQL MUST be used for all SQL storage.

### IV. Configuration and Secrets
Configuration and secrets MUST be managed using .env files.

### V. Development and Tooling
Development MUST utilize the .NET Aspire command-line tools and templates.

## UI and Deployment

- **User Interface:** Web pages MUST be sleek and modern, using modern CSS.
- **Deployment:** The project MUST be easily deployable to production using Docker Compose.

## Development Workflow

All development should follow the Red-Green-Refactor cycle of Test-Driven Development (TDD). All new features or bug fixes must start with a failing test.

## Governance

This Constitution is the supreme governing document for this project. All development practices, architectural decisions, and code contributions must align with its principles. Amendments to this constitution require a formal proposal, review, and approval process.

**Version**: 1.0.0 | **Ratified**: 2025-09-28 | **Last Amended**: 2025-09-28
