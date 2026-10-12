# LOCKED IN — Life OS v2

A gritty, Fight Club-inspired, offline-first gamification dashboard for consistent progress across training, money, creative work, and real-life experiences.

## Version 2 features

- Daily mission board with XP rewards
- Adaptive difficulty: Standard, Low-energy, and Push-day loadouts
- Missed-day reset protocol: a small 10-minute re-entry mission earns 10 XP; earned XP is never removed
- Levels, ranks, current streak, and XP by life domain
- Weekly side quests: connection, adventure, and pure joy
- Money checkpoint with editable GEL income, savings, and weekly social budget
- Weekly after-action review
- Exportable JSON backup
- Responsive, gritty industrial visual style with system light/dark support
- No dependencies, account, analytics, or network requests

## Run locally

Open `index.html` in a modern browser. Progress is saved to that browser's `localStorage`.

## Publish with GitHub Pages

1. Create a repository named `locked-in-life` on GitHub.
2. Upload `index.html`, `README.md`, and `.gitignore` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for deployment. The public URL is shown in the Pages settings.

## Data and privacy

All progress stays in local browser storage. It does not sync between browsers or devices. Export a JSON backup before switching devices or clearing browser data. Reset data clears the current browser's saved progress.

## XP system

- Daily missions: 10–20 XP each
- Weekly side quests: 25 XP each
- Reset mission: 10 XP, once per day
- Level threshold: 150 XP per level

## Adaptive day types

- **Standard:** do the useful version of the planned action.
- **Low-energy:** use the minimum viable version; prioritize recovery.
- **Push day:** optional extra focus only when sleep and recovery support it.

The dashboard does not punish missed days by deleting XP or demanding compensatory workouts. The reset mission is a gentle way to restart.

## Customize

Mission names, XP, descriptions, domains, ranks, and side quests are defined in the script in `index.html`.
