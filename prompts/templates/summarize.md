# Summarize Text

**Use case:** Condense long documents, articles, or notes into a concise summary.

**Variables:**
- `{{text}}` — The content to summarize
- `{{length}}` — Desired summary length (e.g., "3 bullet points", "one paragraph")

---

## Prompt

```
Summarize the following text in {{length}}. Focus on the key points and omit filler.

Text:
{{text}}
```
