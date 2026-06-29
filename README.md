# Immersive AI Training Platform

An AI-powered immersive training platform for Apple Vision Pro that combines local AI, interactive virtual reality, and adaptive scenario-based learning for forensic interviewing, public safety, healthcare, and professional training.

## Project Status

This repository is in early MVP planning and scaffold stage.

The first target use case is an immersive training prototype for forensic interviewing and Child Advocacy Center training workflows. The long-term product vision is a reusable scenario-based training engine that can support public safety, healthcare, education, and other high-stakes professional training domains.

## Core Principles

- Synthetic data only during development.
- No real victim data, case records, forensic interview transcripts, police reports, or personally identifiable information.
- Local/private AI preferred for sensitive training environments.
- Human-in-the-loop review for instructional design, scoring, and deployment decisions.
- Modular platform architecture so new training verticals can be added without rebuilding the whole system.

## MVP Components

- Apple Vision Pro / visionOS immersive prototype
- Scenario engine
- AI NPC dialogue module
- Scoring and feedback engine
- Instructor dashboard placeholder
- Documentation for architecture, security, deployment, and product requirements

## Suggested Repository Structure

```text
apps/
  visionos-app/
  instructor-dashboard/
packages/
  scenario-engine/
  ai-dialogue/
  scoring-engine/
  analytics/
  common/
docs/
  prd/
  architecture/
  security/
  hardware/
  roadmap/
  deployment/
tests/
  unit/
  integration/
.github/
  ISSUE_TEMPLATE/
  workflows/
```

## Engineering Model

ChatGPT acts as product/CTO layer. Codex acts as the software engineer. Human review remains required before client demos, deployments, or any use involving sensitive domains.

See `AGENTS.md` for Codex engineering instructions.
