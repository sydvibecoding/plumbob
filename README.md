# Plumbob — Sims 4 Life Path Generator

> *Your sim's destiny, decided.*

A single-page web app that generates randomised life paths for Sims 4 characters. Built for players who open a new save and immediately think — *"but what should they actually do with their life?"*

![Plumbob app screenshot](screenshot.png)

---

## Features

- **Pure Chaos mode** — fully random across all categories and packs
- **Guided Fate mode** — filter by category before rolling
- **114 life path entries** sourced directly from the Sims 4 wiki, including:
  - 41 full-time careers with real in-game branch titles (Astronaut → Space Ranger or Interstellar Smuggler, etc.)
  - 11 part-time jobs with top-level titles (Simfluencer → Mega-Simfluencer, etc.)
  - 8 freelance agencies
  - 12 university degrees
  - 26 business types — including 17 small business types from Businesses & Hobbies (coffee shop, pottery studio, tattoo parlor, comedy club, paranormal agency, and more)
  - 16 stay-at-home lifestyles
- **Reroll** within the same category
- Animated plumbob, smooth result transitions, keyboard accessible

---

## How to use

Open the app → choose Pure Chaos or Guided Fate → click **Generate My Destiny** → play your sim.

**Live app:** [sydvibecoding.github.io/plumbob](https://sydvibecoding.github.io/plumbob)

---

## Data sources

Career branch titles, part-time job levels, and freelancer agencies are scraped from the [The Sims Wiki](https://sims.fandom.com) via the official MediaWiki API (`sims.fandom.com/api.php`). Business types are derived from the Small Business activity categories introduced in *The Sims 4: Businesses & Hobbies*. Vibe text is original.

---

## Tech

No framework, no build step. One HTML file.

- [Fraunces](https://fonts.google.com/specimen/Fraunces) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- [Lucide](https://lucide.dev) icons via unpkg
- Vanilla JS

---

## Adding a screenshot

Take a screenshot of the live app and save it as `screenshot.png` in the root of this repo, then push. The README will pick it up automatically.
