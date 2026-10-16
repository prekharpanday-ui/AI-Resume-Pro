AI Resume Pro V14 — Netlify AI setup

1. Upload this entire UNZIPPED folder to Netlify using a Git-connected deploy or Netlify CLI so that the Netlify Function is deployed. Simple drag-and-drop may deploy static files only; verify function exists under Functions.
2. Netlify Site configuration > Environment variables > Add variable: OPENAI_API_KEY. Never put the key in index.html, screenshots, or chat.
3. Trigger a fresh deploy after setting the variable. Optional OPENAI_MODEL defaults to gpt-4o-mini.
4. Visit site, complete form, click Generate with Real AI and approve the consent dialog.
5. Before PUBLIC promotion, add authentication or bot protection and server-side per-user rate limits/budget caps; the endpoint is currently PUBLIC and can generate API charges. Netlify usage and AI API can cost money.
6. If you cannot configure a backend yet, the built-in offline suggestions and PDF print still work.
7. AI generated skills are suggestions, not verified facts. Review before applying.

Note: this package is implementation-ready, but live AI is NOT active until an API key, deployment, and abuse controls are configured.
