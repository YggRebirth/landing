# 🌳 Ygg-Rebirth — Temporary Landing Page

Official temporary landing page for **Ygg-Rebirth**, an independent **2.5D fantasy MMORPG currently in development**.

This repository contains the lightweight public website used at **[yggrebirth.com](https://yggrebirth.com/)** while the game, its world and its full web presence are still being developed.

> **The world is still being built. Welcome beneath the branches of Yggdrasil.**

## About Ygg-Rebirth

Ygg-Rebirth is a fantasy MMORPG built around exploration, character progression, combat, professions, creatures, worldbuilding and the mysteries surrounding Yggdrasil.

The project is in active development. There is currently **no public playable build and no announced release date**.

The purpose of this landing page is intentionally simple: provide an official home for the project, communicate its identity without revealing too much, and direct visitors toward the public channels where development is being shared.

## Official links

- **Website:** https://yggrebirth.com/
- **itch.io:** https://yggrebirth.itch.io/ygg-rebirth
- **YouTube:** https://www.youtube.com/@YggRebirth
- **TikTok:** https://www.tiktok.com/@yggrebirth
- **Discord:** https://discord.gg/JQfGgRtuj

`ygg-rebirth.com` is intended to redirect permanently to `yggrebirth.com`.

## Current landing page

The current site is a deliberately small, static one-page website featuring:

- responsive hero section and official Ygg-Rebirth branding;
- active-development status and short project introduction;
- restrained lore/world presentation;
- lightweight overview of exploration, progression and professions;
- links to the official Ygg-Rebirth community and media channels;
- SEO metadata, Open Graph metadata and structured `VideoGame` data;
- `robots.txt` and `sitemap.xml`;
- no analytics, cookies, external fonts, frameworks or third-party scripts.

This is **not the final Ygg-Rebirth website**. It is a temporary public-facing landing page that will evolve or be replaced as the project approaches broader public testing.

## Repository structure

```text
.
├── index.html
├── README.md
├── README-DEPLOY.txt
├── robots.txt
├── sitemap.xml
└── assets/
    ├── home-bg.png
    ├── ygg-rebirth-cover.png
    └── ygg-rebirth-logo.png
```

Everything required by the landing page is kept locally in the repository.

## Local preview

No build step is required.

You can open `index.html` directly in a browser, or serve the folder locally for a more realistic preview:

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080/
```

Any simple static HTTP server will work.

## Deployment

Upload the contents of the repository to the web root for:

```text
https://yggrebirth.com/
```

Recommended production setup:

1. Serve the site over HTTPS.
2. Keep `https://yggrebirth.com/` as the canonical URL.
3. Redirect `https://ygg-rebirth.com/` to `https://yggrebirth.com/` with a permanent `301` redirect.
4. Keep the current files under `assets/` available at the same paths unless references in `index.html` are updated as well.
5. Update `sitemap.xml`, canonical metadata and social-preview metadata if the public URL structure changes.

See [`README-DEPLOY.txt`](./README-DEPLOY.txt) for the compact deployment checklist.

## Development status

The website and the game are both works in progress.

Public visuals, wording, links and presentation may change as Ygg-Rebirth develops. The landing page intentionally avoids exposing internal roadmaps, unreleased systems or unfinished game content that is not ready for public presentation.

## AI-assisted production

Ygg-Rebirth uses generative AI as part of selected production workflows, including some visual and audio asset creation. Generated material may be selected, refined, adapted and integrated through dedicated development pipelines.

Creative direction, game design, implementation decisions and project ownership remain human-led.

## Rights and usage

This repository is published as the website source for the official Ygg-Rebirth landing page.

Unless explicitly stated otherwise, **Ygg-Rebirth names, branding, logos, artwork, visual assets and project-specific content are not granted for reuse, redistribution or commercial use by the presence of this repository**.

Third-party components or assets, if introduced later, will retain their respective licenses and notices.

---

**Ygg-Rebirth**  
*An independent 2.5D fantasy MMORPG currently in development.* 🌳
