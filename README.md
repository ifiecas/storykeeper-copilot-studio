
See `/docs/architecture.png` for the full diagram.

## Repo contents

- `/solution` — Power Platform managed solution (`.zip`), includes the Dataverse tables, the four Copilot Studio agents, and the Power Pages site
- `/docs` — architecture diagram and supporting documentation
- `README.md` — this file

## Setup

1. Import the managed solution from `/solution` into a Dataverse environment via [make.powerapps.com](https://make.powerapps.com) → Solutions → Import.
2. Publish the four agents in Copilot Studio: **Storykeeper**, **Memory Keeper**, **Wellbeing**, **Family Companion**.
3. Publish the Power Pages site and invite family members as portal contacts.
4. Seed at least one **Person** record and a few **Memory** entries so the first conversation has something to work with.

## Built with

- Copilot Studio (GitHub Copilot harness)
- Microsoft Dataverse
- Power Pages
- Dataverse MCP Server

## Author

**Ivy Fiecas**
hello@ifiecas.com · [ifiecas.com](https://ifiecas.com) · [linkedin.com/in/ifiecas](https://linkedin.com/in/ifiecas)

Built for the Microsoft Agent-a-thon: Level 2 Maker.
