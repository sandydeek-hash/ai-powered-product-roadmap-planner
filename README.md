# AI-Powered Product Roadmap Planner

An AI-assisted roadmap planning tool concept for product managers — designed to take a messy backlog and turn it into a defensible, stakeholder-ready quarterly roadmap, with the AI explaining its reasoning at every step.

This repo contains a **product vision document** and a **clickable HTML prototype** built to explore the concept end-to-end.

## Contents

| File | What it is |
|---|---|
| `product-roadmap-planner-vision.html` | Product vision document — problem statement, the 6-stage planning flow, design principles, and open questions. Open this first for context. |
| `product-roadmap-planner-prototype.html` | Interactive prototype of the tool itself. Self-contained HTML/CSS/JS — no build step, no dependencies. |

## The 6-Stage Planning Flow

1. **Capture** — Import backlog items and planning constraints; AI auto-tags each item (effort, theme, impact, risk).
2. **Prioritize** — Score and group items using a framework (RICE / ICE / MoSCoW).
3. **Organize** — Arrange the prioritized backlog into a quarter-by-quarter plan (drag-and-drop swimlanes, team velocity).
4. **Validate** — AI-driven health check on the draft roadmap (capacity, risk, dependency conflicts).
5. **Communicate** — Generate a narrative / executive-ready summary of the roadmap.
6. **Monitor** — Ongoing tracking after the roadmap ships, with AI surfacing changes as conditions evolve.

## Design Principles

- **AI assists, PM decides** — every AI action can be overridden.
- **Strategy before features** — roadmaps start from objectives, not a feature list.
- **Explainability over automation** — the value is auditable, shareable reasoning, not just speed.
- **Living, not static** — the roadmap updates as context changes.

## How to view this project

You don't need to install anything or run any code — both files are static HTML you can open straight in a browser.

- **Fastest way:** download the file and double-click it (or drag it into a browser window).
- **From GitHub without downloading:** GitHub doesn't render HTML files live on its own pages, so use one of these:
  - [htmlpreview.github.io](https://htmlpreview.github.io) — paste in the raw GitHub URL of a file to view it instantly.
  - **GitHub Pages** — turns this repo into a real hosted site (see setup steps below).

## Status

This is a concept prototype used to pressure-test the product thinking and interaction design — it is not a production build and has no backend. See the vision document's "Open Questions" section for what's still undecided.

## Author

Sandhya — Senior Technical Product Manager. Prototype built with the assistance of Claude.
