# CoinCat Studio — Project Context for Claude

> Read this file first in every new conversation about CoinCat Studio.
> Update it at the end of every work session: change the status, the "Next step" and add a line to the Changelog.
> ALSO update the Google Doc (section 3) with every change: phase statuses, accounts, next steps.

Last updated: 2026-11-12

---

## 1. The studio

- **Name:** CoinCat Studio
- **Founders:** Bakr AMGHAR — **Founder** (art direction & code). Rayane BENLECHHAB — **Co-founder** (not active yet).
- **What we make:** mobile games (2D and 3D), any genre.
- **First game:** **GLAUDIRIUS** (subtitle "Blood & Glory" to confirm) — turn-based medieval gladiator RPG, Android, portrait, Godot 4. In development. Teaser page live on the website.
- **Engine:** Godot 4
- **Platform:** Android (Google Play) first. iPhone later (Rayane has a Mac).
- **Business model:** free games with ads (Google AdMob)
- **Languages:** English and French
- **Working style:** both founders work remotely and share everything through one GitHub organisation
- **Skill level:** beginners in programming and Godot. Bakr does the work; Claude is the main developer for the games.
- **Budget:** keep everything free where possible. No paid domain for now. Only planned cost: Google Play developer account (~$25 once).
- **Deadline:** none. Small and finished beats big and unfinished.

**Important:** the cat and the coin are ONLY the studio logo. The games are NOT about cats and do NOT have to use orange. Each game has its own style, characters and colors.

---

## 2. Studio accounts

| Service | Account / username | Status |
|---|---|---|
| Gmail (studio email) | coincatgames@gmail.com | ✅ Created |
| GitHub organisation | CoinCat-Studio — https://github.com/CoinCat-Studio | ✅ Created |
| Website | https://coincat-studio.github.io (repo CoinCat-Studio/CoinCat-Studio.github.io) | ✅ Live |
| TikTok | @coincatgames — https://www.tiktok.com/@coincatgames | ✅ Created |
| itch.io | coincatstudio — https://coincatstudio.itch.io/ | ✅ Created |
| YouTube | Not used (decided 2026-11-08) | ❌ Skipped |
| Discord server | Not used (decided 2026-11-08) | ❌ Skipped |
| LinkedIn (Bakr) | https://www.linkedin.com/in/bakr-amghar-0675b428b/ | ✅ On website |

**GitHub setup:** a separate studio GitHub account (linked to coincatgames@gmail.com) created the organisation and stays as a **backup Owner** only. Bakr and Rayane work daily with their **personal** GitHub accounts, invited to the organisation as **Owners**.

Username rule: use **coincatgames** where possible (GitHub organisation is CoinCat-Studio). Never store passwords in this file.

---

## 3. Reference document (do not change without asking)

- **Google Doc:** "CoinCat Studio · Studio Plan & Brand Guide (v1.0)"
- **Link:** https://docs.google.com/document/d/1VULyMAJ1pqPvj6iF5MsMPbQTNYdaSxLtcah05mdhwug/edit
- The founders edited it themselves. It is the official version. Do NOT modify it unless explicitly asked.

---

## 4. Brand

### Logos (files in this folder)
- `coincat-logo-main.png` — **Main logo:** pixel-art tabby cat paw raising a gold coin marked "CC", with the COINCAT wordmark below. For website home, splash screen, profile pictures, app icon.
- `coincat-logo-name.png` — **Name logo:** the word COINCAT in chunky gold-to-orange pixel letters, where the O is a gold "CC" coin with cat ears. For web headers, game credits, wide spaces.

### Logo rules
- Scale only by whole numbers (2x, 3x, 4x). In Godot, texture filter = Nearest.
- Leave empty space around the logo (at least the coin's width).
- Use on light cream or dark ink backgrounds, not busy pictures.
- No stretching, rotating, recoloring or effects.

### Studio colors (studio material only, not the games)
| Name | HEX | Use |
|---|---|---|
| Coin Gold | #FFD23F | Main brand color, buttons |
| Sun Yellow | #FFDA4A | Highlights, sparkles |
| Tangerine | #F58E1E | Accents, links |
| Ember | #D96A12 | Shadows, pressed buttons |
| Tabby | #F7A02A | Paw in the logo |
| Cream | #FFF6EA | Cards, light boxes |
| Paper | #FFFBEF | Page backgrounds |
| Midnight Ink | #2A1B33 | Text, outlines, dark backgrounds |

Palette files: `coincat-palette.png` (image), `coincat-palette.gpl` (import into LibreSprite / Aseprite / GIMP), `coincat-palette.hex` (plain list).

### Fonts
- **Press Start 2P** — titles, buttons, short labels (Google Fonts, free)
- **Pixelify Sans** — body text, menus, website (Google Fonts, free)

### Tone
Friendly, short, clear. Write like a game, not a company ("Play again?" not "Would you like to restart the session?").

---

## 5. Tools

| Tool | For | Cost |
|---|---|---|
| Godot 4 (standard, GDScript — NOT .NET) | Making the games. On Windows launch the normal .exe (not _console) | Free |
| GitHub + GitHub Desktop | Sharing and saving work | Free |
| LibreSprite or Piskel | Pixel art | Free |
| Google AdMob | Ads | Free (pays us) |
| GitHub Pages | Website hosting | Free |

### Teamwork rules
1. Pull before you start (GitHub Desktop).
2. Commit and Push when you finish, with a short note.
3. Never edit the same scene at the same time. Say in chat what you work on.
4. One shared to-do list.
5. One shared group chat for messages and calls.

---

## 6. Roadmap and status

| # | Phase | What we do | Status |
|---|---|---|---|
| 1 | Brand | Name, logos, colors, fonts, brand guide | ✅ Done |
| 2 | Online accounts | Studio Gmail ✅, GitHub org ✅, TikTok ✅, itch.io ✅ (no YouTube, no Discord) | ✅ Done |
| 3 | Website — LIVE at https://coincat-studio.github.io (source: CatCoin/website) | Home, Games, About us, Contact, Privacy Policy on GitHub Pages (Privacy Policy + app-ads.txt needed for Google Play / AdMob) | ✅ Done |
| 4 | Tools setup (NEXT) | Install Godot 4 + GitHub Desktop, starter project (portrait phone settings, CoinCat splash screen, simple menu), one-page Git guide | To do |
| 5 | Learning | Godot basics (scenes, sprites, touch, scripts) + one tiny practice game together (e.g. tap-to-jump) | To do |
| 6 | First release | Small real game, AdMob ads, publish on Google Play, add to website, share clips | To do |

---

## 7. ▶ NEXT STEP

Phase 4 — Tools setup:
1. Install Godot 4 and GitHub Desktop on both computers.
2. Export the app icon (Android sizes) and the splash screen for Godot.
3. Create the starter project repo in the CoinCat-Studio organisation (portrait phone settings, CoinCat splash screen, simple menu) + one-page Git guide.
4. Then Phase 5: learn the Godot basics together and start the practice game.

### Website notes
- **MOTO LOCO!** = main featured game on the website (teaser strip under the hero + first card in "Our games"). Page: `website/games/moto-loco.html` (bright style: purple #6A1FE0 → magenta #E23C9A → coral #FF5B5B, yellow #FFD93B, ink #160B2E; fonts Russo One + Rubik). Intro "READY · SET · GO!", speed-line canvas, moving road, trailer in a phone frame (muted autoplay loop + "Play with sound" button), ticker tapes, features with screenshots, count-up stats. Clicking it on the home page plays the "FULL THROTTLE!" transition (site zooms + blurs, purple/pink speed-line wipe).
- `website/games/motoloco/` = web-optimized MOTO LOCO! files to upload: `trailer.mp4` (720x1280 H.264, ~7 MB), `trailer-poster.webp`, `keyart.webp` + `keyart-small.webp` (straightened key art from end_card), `shot-combo.webp`, `shot-speed.webp`, `shot-bikes.webp`, `share.jpg` (social preview). The originals in `website/games/MOTO LOCO!/` (46 MB trailer, PNGs) must NOT be uploaded.
- GLAUDIRIUS is now the second card; its cold card + freeze transition are unchanged.
- `website/games/glaudirius.html` = GLAUDIRIUS teaser page (dark, cold palette: night #05080F, navy #12203A, steel #3E6E9E, frost #8FB8E0, ice #CFE3F5, blood #B3202A, gold #E8B04B; fonts Cinzel + Pixelify Sans). Clicking the game on the home page plays a "freeze" transition (site turns cold, sword slash, "THE ARENA AWAITS").
- `website/games/glaudirius-cover.jpg` and `glaudirius-logo.png` = web-optimized versions of the game's key art and logo (the big originals GLAUDIRIUS_logo.png / GLAUDIRIUS_name_logo.png don't need to be uploaded).
- Files: `website/index.html` (Home, Games, About, Contact), `website/privacy.html` (Privacy Policy for AdMob, review before first release), `website/assets/` (logos, favicon).
- To add a game: edit the `GAMES` list at the bottom of index.html (title, description, image, page, link, status, button, style). `style`: "moto" (bright + full throttle transition), "cold" (icy + freeze transition) or "" (normal). First in the list = first card.
- Still to add before the first release: `app-ads.txt` (needs the AdMob publisher ID).

---

## 8. Changelog

- **2026-11-08** — Project kickoff. Plan defined. Name "CoinCat Studio" chosen. Logos finalised (paw + CC coin, and COINCAT wordmark with coin O), 8-color palette, fonts. Google Doc brand guide created and edited by the founders (v1.0, official). This context folder created. Phase 1 done.
- **2026-11-08** — Phase 2 started. Studio Gmail created: coincatgames@gmail.com. Decided: free Gmail now, own domain + professional email later (around first release). Username for all platforms: coincatgames.
- **2026-11-08** — GitHub organisation CoinCat-Studio created (studio account = backup Owner, founders use personal accounts). TikTok @coincatgames created. Phase 3 started: website built (Home, Games, About, Contact, Privacy Policy), saved in CatCoin/website, waiting to be uploaded to GitHub Pages.
- **2026-11-08** — Website: added founder photos (assets/bakr.jpg, assets/rayane.jpg) and Bakr's LinkedIn link (team card + contact).
- **2026-11-08** — Website LIVE on GitHub Pages: https://coincat-studio.github.io. Phase 3 done. To update: upload changed files to the repo CoinCat-Studio.github.io (Add file › Upload files).
- **2026-11-08** — itch.io created: https://coincatstudio.itch.io/. Decided NOT to use YouTube. Phase 2: only Discord left.
- **2026-11-08** — Decided NOT to use Discord (team uses a shared group chat). Phase 2 done. Next: Phase 4 (Tools setup). Google Doc updated to match (phase statuses, accounts, tools, next steps).
- **2026-11-08** — Decided: Godot 4 standard version with GDScript (not the .NET/C# version). On Windows, launch the normal Godot .exe; the _console .exe is only for seeing extra error logs.
- **2026-11-11** — Roles updated: Bakr = Founder (art direction, code, everything), Rayane = Co-founder. Website: GLAUDIRIUS added as the next game (home teaser strip + cold game card + freeze transition) and new teaser page games/glaudirius.html. Google Doc updated (founders, Phase 3, Phase 6).
- **2026-11-12** — Website: MOTO LOCO! (endless motorcycle runner) added as the main featured game, "Coming soon". New page games/moto-loco.html with its own bright speed style, trailer (compressed 46 MB → ~7 MB), and "FULL THROTTLE!" transition from the home page. Home teaser strip + first card now MOTO LOCO!, GLAUDIRIUS second (cold transition kept). Optimized assets in games/motoloco/ (originals in games/MOTO LOCO! stay out of the upload). Checked on desktop (1440px) and phone (390px). Also: Bakr card now "Founder. Art direction & code.", "2D" removed from the site texts (we make 2D and 3D mobile games). Pushed to the website repo with git (not the web upload).
