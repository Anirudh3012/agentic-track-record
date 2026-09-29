# Agentic track record

A single-page site covering agent systems I built and rebuilt in 2026: architecture, business case, iteration history, tools and methods. It draws on a multi-tenant GRC platform's AI backend and an autonomous pentest engine consolidated into a managed-VAPT product.

Client, tenant, host and credential details are left out on purpose. Figures come from my own engineering notes and are point-in-time.

## Run it

It is one HTML file with no build step.

```sh
open index.html
```

Fonts load from Google Fonts and motion comes from [Anime.js](https://animejs.com/) on cdnjs, so it needs a network connection for the full look. Light theme only. Respects `prefers-reduced-motion`.
