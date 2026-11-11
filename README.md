# Scambodia public prototype v0.2.2

This GDevelop project uses built-in visual events and PNG placeholder art. It contains Start, Graybox, OnlineLobby and OnlineArena. Actual multiplayer remains under validation.

Open in GDevelop Web Editor:
https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2Fmaster%2Fscambodia.json

v0.2.2 replaces SVG assets with PNG. The published v0.2.1 server sends SVG files as application/octet-stream; Chromium image decoding fails and the loader stalls. Diagnostic correction of SVG MIME type reaches Start; PNG replacement under the same MIME type reaches Graybox. Local native export and role/movement smoke pass. A real v0.2.2 gd.games release must still be published by the project owner.

A cloud-saved copy does not automatically receive GitHub changes. Open this version, save the updated project to GDevelop Cloud, and publish the updated game from your account. Preserve your existing game identity. Enter opens local Graybox; 1–5 select roles; WASD/arrows move; Escape returns; L opens the multiplayer spike.

Only public prototype content belongs here. Private design documents and full content catalogs stay in the private repository.
