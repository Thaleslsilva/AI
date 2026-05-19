# Workflows

Automated workflow definitions for AI-powered pipelines.

## Supported Platforms

- **n8n** — Store exported `.json` workflow files here.
- **LangChain** — Chain definitions and pipeline scripts.
- **ComfyUI** — Saved workflow `.json` files.
- **Custom** — Any other automation scripts.

## Organization

Group workflows by platform or use case in subdirectories:

```
workflows/
├── n8n/
├── langchain/
└── custom/
```

## Adding a Workflow

1. Export your workflow from the platform (usually as JSON).
2. Place it in the appropriate subdirectory.
3. Add a short description of what it does at the top as a comment or in a README.
