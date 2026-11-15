# ReXtend — Project-Aware Software Engineering Skill

**ReXtend = Re-engineer + Extend.**

**Understand deeply. Engineer naturally. Extend confidently.**

ReXtend is a reusable, evidence-driven Agent Skill that helps an AI agent build and maintain a deep understanding of an existing software project, then use that context throughout the engineering lifecycle. It is designed for more than reverse engineering: it supports architecture-aware feature development, customization, debugging, refactoring, test design, quality assurance, and continuous project evolution.

ReXtend works with remote repositories, local Git checkouts, non-Git project folders, running applications, and multi-project workspaces. Git is optional.

## What ReXtend helps an agent do

- **Understand:** Discover product behavior, domain concepts, architecture, modules, dependencies, APIs, data models, integrations, and runtime flows.
- **Remember:** Build and maintain a durable, evidence-backed project knowledge base instead of relying on conversation memory.
- **Design:** Turn requirements into project-fitting technical designs, impact analyses, acceptance criteria, and implementation plans.
- **Extend:** Implement features and customizations that follow existing architecture, conventions, UX patterns, permissions, and data contracts.
- **Improve:** Diagnose defects, refactor safely, identify technical debt, and assess security, performance, and reliability.
- **Test:** Design and execute staged unit, integration, contract, API, UI, E2E, regression, security, performance, and acceptance test suites.
- **Validate:** Compare expected and actual behavior, verify compatibility, and keep documentation aligned with the code.

## Get the skill

The complete installable package—including `SKILL.md`, detailed playbooks, project documentation templates, and inventory scripts—is available here:

**[Download ReXtend v1.2.0](https://github.com/KunalGupta25/ReXtend/raw/main/rextend-v1.2.0.zip)**

Extract the archive and install the `rextend/` folder in the skills directory supported by your AI agent. The skill identifier is `rextend` (lowercase).

## Supported project sources

1. Remote Git repository URL or accessible hosted repository.
2. Local Git clone, checkout, or worktree.
3. Existing local project folder without Git or commit history.
4. Existing configured or running application, with source when available.
5. Monorepo, multi-package workspace, or collection of related repositories.

## Engineering principles

- Evidence before conclusions; record provenance and confidence.
- Understand affected behavior before changing it.
- Respect the existing architecture and UX conventions.
- Start read-only and preserve user changes.
- Do not expose secrets or sensitive project data.
- Use small, reviewable, testable vertical slices.
- Design tests from requirements, architecture, risks, and observed behavior.
- Keep project knowledge synchronized with code and verified runtime behavior.

## Version

`1.2.0`
