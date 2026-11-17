# Scambodia v0.6.10 — remote teammate motion

Remote teammate skins and labels now follow native motion through a small local visual smoothing filter. Facing and walk/run cadence resist packet corrections; blocked poses settle, visible stop travel retains movement animation, and capture/placement/context/identity changes reset the filter. Your own character and camera remain immediate. Native driver positions, collision, prediction, authority and outgoing object packets are unchanged. Only built-in visual events/native Multiplayer and native local LinkedObjects are used.

## Remote motion retest

1. Everyone reopens **v0.6.10**, waits for assets, chooses Preview and focuses the canvas. Press L and create a new same-version room. Cloud saves and published builds do not auto-update.
2. Keep Út Sen/player2 stationary. Move K’Nam/player1 straight for several seconds, sprint, stop and reverse. Út Sen's camera must stay still; K’Nam should keep a coherent moving pose without correction-driven facing flashes/backsteps under ordinary delivery.
3. Walk up/down/diagonally and turn. Swap the moving/observing players, then repeat for roles3–5. Names should follow the visible character. The other person's image has a small visual following delay; your own controls/camera do not.
4. During night play check stopped/blocked motion, capture/release and normal phase transitions. Large corrections and known lifecycle changes prioritize position reset. Prolonged stalls can still use native stale prediction until fresh data/disconnect detection; this patch does not solve that deferred problem.
5. Retest Q/N with the retained checklist below. Report version, sending/receiving roles, walk/sprint/stop/turn and whether the character or whole camera jitters if a problem remains. No credentials/tokens needed.

Verification passes:1300 native motion/edge assertions,546 retained online input/message checks and1316 retained gameplay/authority/routes checks;9scene native compilation/metadata/roundtrip and51PNG bytes/decode. A real-key/full-render local native sender/receiver sample reproduces old pose/backstep faults and removes them in the candidate. Explicit local transport/membership fixtures do not establish authenticated Internet or target-device FPS acceptance.


The retained v0.6.9 repair restores online request delivery for roles2–5: Q rest, N readiness and the other request-based controls now initialize their native ownership on every peer. K’Nam/slot1 and existing host authority remain. The v0.6.8 art, map, five roles and existing guard bots are retained. Native local tests pass; actual Internet/rejoin/host-loss acceptance remains open.

## Online Q/N retest

1. Every player must reopen **v0.6.10** from the same pinned source, Preview, click the canvas, and press **L** for native online lobbies. Use separate accounts and create a **new room**. An old Cloud copy or published build does not auto-update; avoid mixing versions.
2. Join with player1 and one other slot2–5 first. Host starts after both clients have loaded. Online, each player controls their assigned role;1–5 switching is offline only.
3. During work, spend stamina, stop moving and **hold Q** for2–3 simulation seconds. Stamina should rise on that client and the host; release Q and it should stop. Moving prevents recovery; Q is not a preparation-phase heal. Repeat for the other roles and during both nights when stationary/free.
4. Follow the shown J/K/L work target. Host grades with F or waits for the timer. During preparation each connected player releases/presses **N** once. One ready player must not advance a two-player room; empty slots must not block it.
5. When all connected players are ready, **host presses Enter** to start the night. N marks readiness; it does not independently skip the phase. Nonhost Enter must have no effect. Repeat with all five accounts when available.
6. Retest the same roles' B/U/C preparation purchases/heal/food, H ability and night E interaction. Let each action key go before pressing again. Record both clients' source version, assigned slot, phase, stamina/readiness and exact behavior if anything fails; never send tokens or credentials.

Verification:546 new native ownership/input/message/keyboard checks and1316 retained gameplay/authority/receiver/loading checks pass; all9 scenes compile, all51 public PNG responses match hashes and decode. Tests use explicit local runtime/membership/transport fixtures; they do not establish authenticated Internet acceptance.

## Retained playable art


Five distinct civilian characters, animated enemy guards and original isometric environment art now dress the existing two-day/two-night slice. Dorm furniture, work desks, cargo, cover, concrete obstacles and gates follow the original playable map. This is a first art pass for the six-by-six night slice; the full eleven-zone campaign is still future work.

The guards patrol, detect and capture using the existing native AI. The other four roles are controlled by players or by switching1–5 offline; they are not AI companions. A gold foot marker identifies your selected role, and nearby foreground dressing fades when it hides that role. Unknown-cell dressing and guards stay hidden.

## First session, step by step

1. Open this version in GDevelop Editor, wait for assets, choose Preview and click the canvas. Click **B — BẮT ĐẦU CÂU CHUYỆN**, or press B. L opens the online-room route; use the same source version on every client.
2. Start offline. Press1 to select K'Nam, stand near the computer desk and follow the **current J/K/L key shown on screen**. Release after each file; the target changes. Reach5/5, then repeat for roles2–5 before the90-second Day1 clock ends. Role5 starts just outside the desk range: move slightly left. Q rests; F grades the shift early.
3. During preparation, buy/heal/eat with B/U/C before pressing N. Offline, select each role1–5 and press N to ready them. When everyone is ready, Enter starts the night.
4. Night1: stop unseen and press/release E at the three yellow papers A/B/C. Remember their symbols, explore at least11 tiles, and enter their A→B→C symbol order near G1 using J/K/L. Go through the opened gate and E at the exit. Enter advances to Day2. Use V to learn sight fields, hide with C while stationary on green cover, and wait for a safe patrol window. If captured, wait for native release; if the night fails, Enter still advances to Day2.
5. Day2 has quota6 per role and100 seconds. In preparation, the optional cargo box accepts J/K/L/P for1/2/3/4; its solution2/4/1 is K→P→J. Watch the3/3 progress, ready each role with N and Enter into Night2.
6. Night2: E at dorm(0,0) picks up the cargo detector. Its carrier E at G2(4,4) installs it. Read the three papers, solve the G2 board using I/O to select row/column, J/K/L/P for1–4, Backspace to clear and R to check. After opening G2, E inside gets the plan; bring each active role to the dorm and E to confirm safe return. This ends the chapter, not the whole escape campaign.
7. Recovery remains available: H held8 seconds unseen at G2 recalls/rebuilds the same uninstalled detector. If G1 was not opened, follow the visible H-at-dorm recovery instruction. Captures confiscate only the carried detector; installed equipment and committed puzzle progress remain.
8. Optional recipe route: leave Day2 cargo unsolved. Night2 E at A(1,0) claims one component; E at B(3,2) claims one scrap. Release/press E again at B for automatic5-second work. Only completion spends stock; owner E, movement, detection or conflicting ability interrupts without cost. Carry the result to G2 and E to install. Supplies are finite; existing stashed/carried/installed output blocks another craft.

Tab shows details/help. WASD/arrows move, Shift sprints, Q rests, H uses the selected role's ability. Bảy Lành's G is an unverified patrol impression; Night2 F corroborates an H/A note after physical E evidence. H>G>F. Esc returns/leaves through the native flow. Let interaction keys go between actions.

T remains a separate Night2 tutorial with the detector already installed. Other retained test scenes are listed under Start's Tab help.

Built-in visual events/behaviors/native Multiplayer only. UUID, original nine scenes, original29 PNGs, collision/authority and gameplay are retained;22 original PNGs are added. CH01 retains its existing directional idle/walk/run; the new roles/guards currently have front idle/two-pose walk with native mirroring. Owner art/gameplay acceptance, reference-device FPS, Internet5/rejoin/host-loss, pre-disconnect input freshness, Storage-blocked checkpoint, remaining kits and full campaign remain open. Source publication does not overwrite Cloud or publish gd.games. Immutable prior source versions remain available.
