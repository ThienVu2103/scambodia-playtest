# Scambodia public prototype v0.3.1

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


## CH01 character pilot — CH01-PILOT-024

This project adds CharacterLab with the selected compact pixel-art CH01, front/rear idle and alternating walk poses, and native mirrored left facings. The rear alternate step was redrawn after owner feedback to remove twisted crossed knees. This is a local art pilot; it does not resolve the two-player join error or satisfy five-client multiplayer acceptance. Other characters remain placeholders; Shift reuses the walk cycle.

Preview Start, press C, then WASD/arrows to walk; Shift faster walk, Z/X zoom, R reset zoom, Esc return. Look for CH01-PILOT-024. Open scambodia.json in GDevelop with network access for immutable PNG resources. Saved cloud copies and gd.games releases do not auto-update.

Verification: Core5.6.269 seven-scene export, 17 browser groups, all six runtime frame resources, stable 80px alpha height, 28×14 foot collision, mirrored facings and retained scene navigation. Published source bytes and all13 PNGs verified against the tested payload.

[Open pinned CH01 character pilot in GDevelop Editor](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2F0bd532e691ac340cd3520114b53f1f28873f293d%2Fscambodia.json).

Preview Start → C. Verify CH01-PILOT-024, walk in four screen quadrants, stop/turn, and test Shift.
