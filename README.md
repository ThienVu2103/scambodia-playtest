# Scambodia public playtest

Current source: v0.5.2, based on the known-working master v0.3.2 with the Phase B/C day–night slice.

Open scambodia.json in GDevelop. Start: L enters the native multiplayer lobby, B starts local day–night play, N tests Night 1. All clients must use this same version. Enter, G, S and C retain the original master scenes.

This repair restores the canonical MultiplayerObject behavior and master auth/leave handling, uses PNG resources, and retains a game-start signal while the gameplay scene downloads. Local checks pass for all nine scenes, image loading, native receiver updates for five slots, delayed loading, and the day/night loop. These checks do not establish authenticated Internet-room or host-recovery acceptance.

Versioned source: versions/v0.5.2/scambodia.json. Earlier versions and immutable master history remain available. Updating this repository does not update a saved GDevelop cloud project or the gd.games release.
