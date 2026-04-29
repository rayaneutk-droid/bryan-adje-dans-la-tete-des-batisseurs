# Last Update

Use this file as the handoff context for any new Codex chat about the public site for **Dans la tete des batisseurs**.

## Non-Negotiable Rule

Never push or deploy publicly unless Rayane explicitly asks.

Do not send emails to Bryan or any third party without Rayane's final action-time confirmation.

## Project

Site repo local path: `C:\Users\rayan_xbgwrn1\Desktop\10 - Dans la tete des batissuers\Site vitrine`

Project owner/creative identity for public-facing naming: **Bryan Adje**.

Important link constraint: avoid public URLs that foreground Rayane's name. Prefer `bryan-adje` in the repository/project/deployment slug.

## Website

Static invite-facing site for **Dans la tete des batisseurs**.

Main files:

- `index.html`
- `styles.css`
- `script.js`
- `assets/logo-batisseurs.jpg`
- `assets/cover-batisseurs.jpg`
- `README.md`
- `.nojekyll`

## Current Direction

- Refondue as a private pre-launch invite page for Imran and Malick Diarrassouba.
- Site title, link wording, and public framing are oriented toward Bryan Adje.
- Keep the AI-generated logo because Bryan cares about it.
- Use a sober editorial and typographic direction, with the logo as the only visual asset.
- Do not use public portraits or scraped images before guest validation.
- Present the project vision, why the two brothers make a strong pilot episode, the image-promotion value, the before/during/after flow, and editorial comfort rules.
- Responsive orientation: desktop and mobile, with mobile menu and no horizontal overflow.

## Pilot Episode

Theme:

**Deux freres, deux business: comment batir jeune en Cote d'Ivoire ?**

Guests:

- Imran Diarrassouba: Golden Impact.
- Malick Diarrassouba: DGroup CI.

## Git State

Branch: `main`

Initial local commit:

- `57098e8 Create podcast showcase site`

Pushed commits:

- `57098e8 Create podcast showcase site`
- `7f01f96 Refine showcase site and add project memory`

GitHub repository:

`https://github.com/rayaneutk-droid/bryan-adje-dans-la-tete-des-batisseurs`

Public site:

- Bryan-facing short link: `https://is.gd/bryanadjebatisseurs`
- GitHub Pages source link: `https://rayaneutk-droid.github.io/bryan-adje-dans-la-tete-des-batisseurs/`

Note: GitHub Pages necessarily includes the GitHub account owner in the domain. A short Bryan-facing link was created to avoid showing Rayane's username in the visible URL. A cleaner future option is a custom domain or a Vercel project under a Bryan-facing slug.

## Publishing Plan

Previous public site was pushed to GitHub and made accessible to Bryan. On 2026-04-29, Rayane explicitly authorized pushing the private invite-facing refonte to GitHub.

Preferred repo/project slug:

`bryan-adje-dans-la-tete-des-batisseurs`

Published state:

- GitHub Pages is active and verified with HTTP `200`.
- Bryan-facing short link is active and verified: `https://is.gd/bryanadjebatisseurs`.
- Vercel CLI was not logged in locally and waited for interactive authentication, so GitHub Pages + a short Bryan-facing URL was used for now.

## Latest Implementation - 2026-04-29

- Rebuilt `index.html`, `styles.css`, and `script.js` as a private invite-facing page for Imran and Malick.
- Updated `README.md` to describe the new private invite direction.
- Hero is centered on `Imran & Malick Diarrassouba`.
- Sections now cover: vision, why the two brothers, image promotion, before/during/after flow, and editorial comfort.
- Local browser checks were run with Chrome through Playwright at desktop `1440x1100` and mobile `390x920`:
  - no console errors;
  - no horizontal overflow;
  - key hero and comfort sections present;
  - mobile menu opens and sets `aria-expanded=true`.
- In-app browser also loaded the local `file://` site with zero console errors.
- Push to GitHub is authorized by Rayane. No Vercel deployment and no email send was performed.

## Fresh Chat Startup Prompt

```text
Continue the Dans la tete des batisseurs private invite site.

Before doing anything, read:
- memoire/LAST_UPDATE.md
- index.html
- styles.css
- script.js

Important: never push/deploy unless I explicitly ask. The invite refonte was pushed only after Rayane explicitly authorized it. Avoid public URLs that foreground Rayane's name. Prefer Bryan Adje in the project slug.
```
