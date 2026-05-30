# eidos.

> The last browser for knowledge workers.

A manifesto on how a browser should be like - written by Fritz and Yongkang, May 2026.

---

## What is eidos?

Knowledge workers spend their whole day in a browser. It is basically our OS. And right now it has little personality, little memory, little taste.

Not another AI browser that automates tasks for you — but one that thinks *with* you. Intent-aware, not prompt-driven. A browser that reads your attention, learns your workflows, and compounds over time.

The six things we are building toward:

1. **Intent-aware.** Based on what you are doing, it proactively recommends actions instead of waiting for a prompt.
2. **Learns your workflows.** Recurring tasks become reusable skills — automatically.
3. **Your second brain.** Saves, enriches, and retrieves what you have read and thought.
4. **Contextmaxxing.** Through integrations and past behaviour, it becomes genuinely yours over time.
5. **Fully customizable.** Layout, colours, style — rich, luxurious, studio-like.
6. **Accessible everywhere.** Apple Watch, phone, laptop. Text it, click it, speak to it.

---

## About this repo

This is the eidos landing page — a single `index.html` file styled as the first-ever web browser (NCSA Mosaic, 1993). It is our way of thinking about the history of the browser while pointing at where it could go.

### What the site does

- **Draggable, resizable windows** — the Mosaic chrome is fully interactive; you can move and resize it like a real desktop app
- **Multi-window navigation** — ◀ ▶ buttons cycle through the manifesto, fritzdutz.com, yongkang.dev, and the follow page
- **Minimize to dock** — windows minimize into folder icons with an animated scale transition; clicking restores them
- **Follow page** — an embedded subscribe form backed by Supabase; no third-party embed, no external redirects

### Stack

| Layer | Choice |
|---|---|
| Markup / styles / logic | Vanilla HTML, CSS, JS — no framework |
| Font | IBM Plex Mono |
| Subscribe backend | Supabase (REST API, anon key, RLS-gated insert) |
| Hosting | Vercel |
| Analytics | Vercel Analytics + Speed Insights |

---

## Follow along

Follow updates by subscribing directly on the site.

— Fritz & Yongkang
