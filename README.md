# LOCKED IN — Life OS

A tiny, offline-first personal gamification dashboard for building consistency across training, money, creative work, and actually enjoying life.

## Features

- Daily missions with XP rewards
- Levels and rank titles
- Current streak counter
- XP by life domain: Body, Freedom, Craft, Life, Discipline
- Weekly side quests: connection, adventure, pure joy
- Editable income/savings/social budget checkpoint (GEL defaults are examples)
- Weekly reflection checklist
- Exportable JSON backup
- Data stored locally in the browser using `localStorage`
- Responsive layout and system light/dark theme
- No dependencies, accounts, tracking, or network requests

## Run locally

Open `index.html` in a modern browser. Your progress is stored in that browser on that device.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `locked-in-life`.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under build and deployment, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to finish deploying. The published URL will appear in the Pages settings.

## Important data note

This version stores progress in browser-local storage. It does **not** sync progress between browsers or devices. Use **Export backup** to save a JSON copy. Clearing site data or switching devices may otherwise make progress unavailable.

## Customization

The mission definitions, XP values, ranks, side quests, and review prompts live near the top of the `<script>` section in `index.html`.
