# Scambodia public prototype v0.3.1

## Latest multiplayer movement fix — v0.3.2

[Open pinned GDevelop Editor source](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2F9d2536bc02ef903dd5e896fff32bb3931656a615%2Fscambodia.json). Save current work and reopen this link on both clients; saved cloud projects and older gd.games builds do not auto-update.

Start → **L** → open native lobbies, join the same room and let the host start. Both clients must show **SOURCE v0.3.2 GAME-003 sync | OnlineArena**. Move player1 with WASD and confirm player2 sees it; then reverse. Host H should increment the shared probe on both; nonhost H must not. Esc leaves through native cleanup. **C/CharacterLab and Enter/DormGraybox are offline tests**, not network gameplay.

The five online sync behaviors now use native canonical MultiplayerObject names, including all ownership references. The old NetSync name allowed local movement but the installed native receive handler dropped incoming positions. Two-runtime regression reproduced the old frozen observer and verified corrected bidirectional updates across five slot pairings; owner/migration/stopped-game/disconnect guards and retained offline scenes also pass. Fixtures replace account/membership/transport only; real two-account movement and five-client/recovery/checkpoint acceptance remain to be confirmed. The owner reports real joining now succeeds. All21PNG bytes, browser export paths and pinned project bytes are verified. No gd.games release.

Older increment notes and links below are historical.


Native GDevelop visual-event prototype with existing PNG placeholders. This increment adds a local Z01 dormitory graybox with five sleeping places, a sketch desk, a window observation point and a closed exit. Furniture and walls are geometry placeholders; this is not production art or the complete Map01.

Open the source in GDevelop Web Editor:
https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2Fmaster%2Fscambodia.json

At Start: Enter opens the dorm, G opens the retained v0.2.3 movement lab, L opens the native multiplayer spike, and S opens StatsSandbox. In DormGraybox/Graybox: 1–5 select a role, WASD/arrows move, Z zooms out, X zooms in, R resets zoom and Esc returns. In the dorm, approach the labeled desk/window/exit and press E for local context feedback. These interactions do not grant items, save progress, reveal a full map or count as escape.

Five local placeholders are not five online players. The reported two-player connection failure after Start remains unresolved. OnlineLobby and OnlineArena are retained unchanged; five-client, ownership replication, reconnect, host migration and checkpoint acceptance have not passed.

Save existing Editor work before opening a newer source. Public source, imported Editor projects, saved Cloud copies and gd.games live builds are separate versions and do not automatically synchronize. This GitHub update does not publish a gd.games release; the owner controls Cloud save/release actions while preserving game identity.

Only public prototype content belongs here. No custom game scripts, account tokens, private design catalog or production character/movie art are included.

## GAME-006 offline stats sandbox

Pinned editor source: https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2F291dc827687fd9c9aa50c71a1b75de4dd7ab1592%2Fscambodia.json

Reopen the new source, Preview Start and press S. In StatsSandbox only: WASD/arrows move, Shift sprints, 1–5 selects, R rests while stationary in the marked safe area, X applies test damage, F spends Focus, hold H rescues a selected downed actor near active CH04, G tests capture, Backspace resets and Esc returns. CH04 has one test bandage; three X presses down a fresh actor. A six-second rescue yields HP25 and spends one bandage; interruption spends none. Capture/expiry freezes pending recovery until reset.

Native compile/export, 27 runtime scenario groups in the standalone and public asset-mirror build, and remote PNG/export filename checks passed. Local authorization/replay inputs are test guards, not network security proof. Real multiplayer authority, guard capture/confiscation and versioned checkpoint integration remain pending. Existing dorm, movement and lobby scenes are preserved. No gd.games release is performed.

## GAME-003 lobby diagnostics v0.3.1

Pinned source: https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2F883075a6860a81b345d5d39e88bd1787c211783d%2Fscambodia.json

Save existing Editor work and reopen this source. Preview Start, press L, then Enter/L to open native lobbies. Both players must use the same running v0.3.1 preview/test build; an older gd.games release does not auto-update from GitHub or the Editor. Check the HUD identifier SOURCE v0.3.1 GAME-003 diagnostics.

Esc closes the lobby panel without leaving the scene. Release and press Esc again to leave the room and return safely; sign-in windows use their native close. After Join fails, close the native overlay to read the canvas HUD. Record current and last nonempty lobby ID, slot/count, auth/running/migrating flags, sequence/time and the exact error on both clients. Do not share account tokens, emails or full network URLs. Last observations remain scene-local; they reset on scene entry.

Native compilation, nine focused diagnostic groups and retained-scene smoke checks passed. Room/ownership tests use explicitly stubbed native flags; real two/five-client connection and the reported peer-join error are not declared fixed. The trusted private co-op authority, reconnect/host migration and checkpoint gates remain open. All offline scenes, identity, globals and named PNG assets are preserved. This source update performs no gd.games release.


## CH01 dedicated run pilot — CH01-RUN-024

[Open the pinned project in GDevelop Editor](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2Ffd560fe4743523b45360a7e5f26e5d911e7edfbf%2Fscambodia.json). Save current work and reopen this link; saved cloud copies and gd.games releases do not auto-update.

Preview Start → C. WASD/arrows walk; hold either Shift to use dedicated RunFront/RunBack sprites with native left mirroring. Release Shift to walk, stop to idle. Check all four screen quadrants, opposite arm swing, turns, and either/both Shift keys. Z/X zoom, R reset, Esc return. Roles2–5 remain placeholders.

Running now has8new poses: extended contact, passing flight, opposite midstance and recovery flight per view. Original idle/walk remain unchanged. Eight browser groups passed, including36frame/flip cases,72collision observations,48moving transitions and both staggered Shift-release orders. All21PNG bytes and browser export paths verified; pinned project bytes match reviewed compact export. This is a four-frame character pilot, not final production animation or live co-op acceptance. No gd.games release.
