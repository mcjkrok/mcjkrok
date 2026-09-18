## Hi, I'm Maciej Krok 👋

Third-year IT student at **DSW Wrocław**, building things at the intersection of
**DevOps, Cloud and AI** — mostly Python services with the full delivery chain around
them: containers, Kubernetes, CI/CD and monitoring. Currently looking for a junior
DevOps / Cloud / AI role.

Everything below runs, is tested, and is documented in English.

### Projects

| Project | What it is |
|---|---|
| **[ai-platform-starter](https://github.com/mcjkrok/ai-platform-starter)** | A miniature internal AI platform: an LLM gateway with Docker, Kubernetes (kustomize base/overlays), CI/CD and **Prometheus + Grafana** monitoring. |
| **[nexus](https://github.com/mcjkrok/nexus)** | A fully offline AI assistant on **Ollama** — PySide6 GUI, function calling across 30 tools, semantic memory on ChromaDB, speech in and out. No cloud involved. |
| **[status-watch](https://github.com/mcjkrok/status-watch)** | Serverless uptime monitor running entirely on **GitHub Actions** cron, publishing a status page to GitHub Pages. Zero infrastructure, zero cost. |
| **logsage** *(in progress)* | AI log analyzer on FastAPI + OpenAI API, deployed to Kubernetes through a GitOps loop. Repository will be published once it is finished. |

### Working with

`Python` `FastAPI` `Docker` `Kubernetes` `ArgoCD` `GitHub Actions` `Prometheus` `Grafana`
`Linux` `Git` `Ollama` `OpenAI API` `SQLite` `ChromaDB`

### A few things I care about

- **Deployments that are actually verified.** Manifests that pass a linter but fail on a
  real cluster are not done — I run them before claiming they work.
- **Documenting the decisions, not just the commands.** Most of my READMEs have a "design
  decisions" section explaining the trade-offs and the traps I hit.
- **Local-first where it makes sense.** Several projects run entirely offline, because
  sending logs or personal context to a third-party API is often not an option.

### Contact

🌐 [mcjkrok.github.io](https://mcjkrok.github.io/) · 📧 [mcjkrok@gmail.com](mailto:mcjkrok@gmail.com) · 📍 Wrocław, Poland
