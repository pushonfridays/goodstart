# A good start

An opinionated repository structure that focuses on "best practices" designed to ensure clear and consistent documentation, scalability of the codebase/structure and overall project. All decisions are documented in detail within `docs/decisions`.

## Description

> [!NOTE]  
> You should update this section to fit your needs, following the guidance provided

**The repository description serves as a clear and concise overview of the project's goals, helping developers and stakeholders quickly understand its purpose. It outlines the core principles, development practices, and organizational standards that guide the project's implementation. This section should highlight the project's unique value proposition and main objectives.**

## Getting started

> [!NOTE]  
> You should update this section to fit your needs, following the guidance provided

**This section provides step-by-step instructions for setting up and running the project locally. Follow these guidelines to ensure a smooth development experience.**

### Repository structure

| Folder | Description |
|--------|-------------|
| `docs/architecture` | Architecture documentation, diagrams and technical specifications |
| `docs/decisions` | Architectural Decision Records (ADRs) documenting project decisions and their context |
| `docs/runbooks` | Step-by-step procedures for common operational tasks, day-1, day-2 and troubleshooting guides |
| `operations` | Infrastructure and deployment configurations |
| `services` | Project services and core codebase dedicated to your application(s) |

### Prerequisites

> [!NOTE]  
> You should update this section to fit your needs, following the guidance provided

**Providing a `.devcontainer` which includes all the required prerequisites is a good way to ensure a consistent environment for all contributors to contribute to the codebase quickly.**

Outlying those prerequisites is still important for shared understanding.

> [!WARNING]  
> You should never provide credentials, access keys or tokens within the repository prerequisites. If you require identifying or sharing such information, ensure it follows your organisations guidelines.

- List required software and tools
- Minimum system requirements

### Installation

1. Clone the repository
2. Install dependencies
3. Configure environment variables
4. Set up local development environment

## Contributing

### Coding standards

> [!NOTE]  
> You should update this section to fit your needs, following the guidance provided

**Documenting how contributors should work within your codebase ensures consistency, shared understanding and reduces friction for new contributors.**

**We have included a template below, and also within `docs/runbooks/01-contributing-coding-standards`. If you have an extensive amount of documentation for your coding standards, we suggest using the `docs/runbook` directory to maintain a succinct README.**

### Style guide

Maintains consistent code formatting and organization through automated tooling and linting configurations. All code should adhere to language-specific style guides.

### Testing standards

- Unit tests required for all new code
- Integration tests for critical paths
- Minimum test coverage requirements
- Test naming conventions

### Documentation requirements

- Clear function/method documentation
- API documentation for public interfaces
- Comments explaining complex logic
- Up-to-date README files

### Code review process

- Required reviews before merging
- Review checklists
- Performance and security considerations
- Code quality metrics

### Version control

- Branch naming conventions
- Commit message format
- Pull request templates
- Release tagging standards
