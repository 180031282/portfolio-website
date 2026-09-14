# Portfolio — Lahari Dilli

Personal portfolio site: about, experience, and three featured open-source projects
([agentic-fraud-investigator](https://github.com/180031282/agentic-fraud-investigator),
[realtime-risk-scoring](https://github.com/180031282/realtime-risk-scoring),
[ai-pr-review-agent](https://github.com/180031282/ai-pr-review-agent)).

Plain HTML/CSS/JS, no build step, no dependencies — deployed as a Netlify static site.

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Deployed via the Netlify CLI / Netlify's GitHub integration; `netlify.toml` publishes the
repo root with no build command.
