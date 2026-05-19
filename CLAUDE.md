# CLAUDE.md

This file provides guidelines for Claude when working in this repository.

## Repository Purpose

This is a personal AI tools and workflows repository. It stores scripts, prompts, agent configs, and automation workflows used in daily AI-assisted work.

## Repository Structure

- `tools/` — Standalone scripts and AI-powered utilities
- `workflows/` — Workflow definitions for automation platforms
- `prompts/` — Prompt templates organized by use case
- `agents/` — Agent configuration files
- `configs/` — Configuration templates (never commit real secrets)
- `docs/` — Documentation and guides

## Guidelines

- Never commit real API keys or secrets. Use `configs/.env.example` as a template.
- Keep prompt files in Markdown format inside `prompts/`.
- Document any new tool in its directory's `README.md`.
- Prefer small, focused scripts over monolithic ones in `tools/`.
