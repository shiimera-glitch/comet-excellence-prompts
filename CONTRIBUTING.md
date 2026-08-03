# Contributing to Comet Excellence Prompts

Thank you for considering a contribution. This repository is a curated, quality-first knowledge base — not a generic prompt dump. Please read the criteria below before submitting a PR.

## Criteria for Inclusion

A new prompt, workflow, or best practice will only be accepted if it is:

- **Battle-tested** — used in a real project, not theoretical
- **Measurable improvement** — demonstrably better than a naive baseline (fewer tokens, fewer iterations, higher accuracy)
- **Well-documented** — includes context, example input/output, and a verification checklist
- **Domain-specific** — solves a concrete problem, not generic advice like "be clear and concise"

## How to Contribute

1. Fork the repository
2. Add your prompt under `/prompts/<category>.md` following the existing template structure (Task / Context / Output / Verification)
3. If introducing a new category, update the README Table of Contents
4. Open a pull request with a description of where/how the prompt was validated

## Style Guidelines

- Use the standard template: `## Task`, `## Context`, `## Output Format`, `## Verification`
- Keep prompts concise — token efficiency is a core goal of this project
- Avoid vague instructions ("make it better") in favor of specific, measurable objectives
- Include a good/bad example where useful

## Scope

This project is intentionally lightweight: markdown documentation and prompt templates only. Please do not propose hosted services, databases, or infrastructure dependencies — the goal is a zero-dependency, easily forkable knowledge base.

## Code of Conduct

Be respectful and constructive in reviews and discussions.
