# AGENTS.md

This file provides standing instructions for Codex and other AI coding agents working in this repository.

## Role

Codex is the software engineer for this project. It should implement scoped tasks, create clean commits, update documentation, and avoid expanding scope without explicit instruction.

## Project Goal

Build an AI-powered immersive training platform beginning with an Apple Vision Pro forensic interviewing training prototype. The architecture should support future scenario packs for public safety, healthcare, education, and professional training.

## Security and Data Rules

- Use synthetic data only.
- Never add real child victim data, forensic interview transcripts, case details, police reports, CAC records, or personally identifiable information.
- Do not create sample data that resembles a real case.
- Avoid sensitive or graphic training content unless explicitly approved in a separate instructional design document.
- Assume future deployments may require local/private AI operation.

## Engineering Rules

- Keep modules small and clearly named.
- Add README files to major folders explaining purpose and setup assumptions.
- Prefer testable business logic separated from UI code.
- Document architectural decisions in `docs/architecture/`.
- Do not introduce paid services, cloud dependencies, or external APIs without documenting why they are needed.
- Use placeholder interfaces where the final provider is undecided.

## MVP Scope

Initial MVP should include:

- visionOS/Unity prototype placeholder
- scenario engine package
- AI dialogue package
- scoring engine package
- instructor dashboard placeholder
- synthetic scenario examples
- documentation scaffold

## Definition of Done

A task is done when:

- The requested code or docs are added.
- The change is scoped and readable.
- Synthetic data rules are followed.
- Setup or usage instructions are documented.
- Tests or test placeholders are included where practical.
