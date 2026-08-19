# PromptOps Toolkit

Local-first prompt registry baseline for versioned templates, tags, evaluation metadata, and later provider routing.

```bash
npm test
npm start
```

Endpoints: `GET /health`, `GET /api/prompts`, and `PUT /api/prompts` with `id`, `template`, optional `version`, and `tags`.

Future adapters can persist prompts in a database, render variables through a policy-aware template engine, and route evaluations to OpenAI, local models, or other providers. Keep prompt versions immutable once published in production.
