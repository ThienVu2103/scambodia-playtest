# Scambodia — public no-code prototype v0.2.1

## v0.2.1 publishing-package correction

**[Open exact v0.2.1 in GDevelop](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2Fb20769ec0f73133229a70eb30732ea74a2390246%2Fscambodia.json)**

Open this new version and check the subtitle says v0.2.1 before retrying Share → gd.games. A previously saved cloud copy still contains the old package until you deliberately update it.

Corrected a reproduced browser-export defect: embedded data URIs became file names 335–26,639 bytes long. Assets now export as block.svg, role-1.svg through role-5.svg and sandbox.svg (9–11 bytes). Core export, browser regression and a diagnostic archive pass. The user's gd.games log only said BadRequest: null; successful server publication has **not** yet been verified, and another backend/account issue may still remain.


**[Open latest project in GDevelop Web Editor](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2Fmaster%2Fscambodia.json)** · **[Open exact v0.2 build](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2F46c70c8a2c2efdb450b74d3282d8fe8f9e29242b%2Fscambodia.json)**

This repository contains only the public prototype and its instructions. Seven original geometric SVG assets are stored in assets/ with short file names and loaded from pinned public URLs. Internal documents, source conversations, full campaign catalog and credentials are excluded; the main design repository remains private.

## Test this version

Open scene Start and choose Preview. Click the game canvas for keyboard focus. The title should show **Public test v0.2.1**.

- **Enter:** original offline sandbox. **1–5** selects a local role; WASD/arrows move; Esc returns.
- **L:** native online test flow. In OnlineLobby use Enter/L to open GDevelop's native sign-in/lobby UI. Account/game registration and actual dashboard settings are required.
- **OnlineArena:** only a connected player's fixed slot/owned actor should accept movement; local number-key role switching is absent. Host can press H for a shared probe; Esc requests leave.

## Verified and pending

GDevelop Core 5.6.269 loaded/compiled/exported all four scenes with zero diagnostics. Offline browser regression passed. Static event checks confirm slot/ownership input guards and host-only probe. This is event wiring, **not proof that five clients can play together**.

Native account/lobby service, five-client replication, reconnect, host migration and checkpoint recovery remain unverified. A locally exported test displayed “player accounts are only available for published games”; private cloud identity and account registration cannot be inherited automatically from this GitHub file. Do not interpret GitHub-public source as a published gd.games game or an authenticated lobby. No fake multiplayer or custom backend is used.

GDevelop Web Editor opens a copy. A project already saved in your GDevelop cloud account does not automatically update when GitHub changes. Open the new version link, inspect it, and deliberately save the version you want to keep. Service/account settings on an older cloud copy may need to be reconciled.

Placeholders are not final map/character art. Full KPI, fog, capture, mission gameplay and bounded-floor traversal are not implemented. Built-in GDevelop events/behaviors only, no handwritten JavaScript blocks or custom extensions. Official MCP is desktop-only and is not connected by this link.
