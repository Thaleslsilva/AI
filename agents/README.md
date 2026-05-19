# Agents

AI agent configurations and definitions.

## What Goes Here

- Agent system prompts and personas
- Tool/function definitions for agents
- Agent configuration files (YAML, JSON, TOML)
- Multi-agent orchestration specs

## Structure

Organize agents by purpose or platform:

```
agents/
├── assistant/      # General-purpose assistant configs
├── code-review/    # Code review agent definitions
└── research/       # Research and information gathering agents
```

## Adding an Agent

1. Create a subdirectory named after the agent's purpose.
2. Include a `config.yml` (or `.json`) with the agent definition.
3. Store the system prompt in a `system-prompt.md` file.
4. Document capabilities and limitations in a `README.md`.
