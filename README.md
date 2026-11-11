# Scambodia — public prototype

**[Open in GDevelop Web Editor](https://editor.gdevelop.io/?project=https%3A%2F%2Fraw.githubusercontent.com%2FThienVu2103%2Fscambodia-playtest%2Fmaster%2Fscambodia.json)**

Native no-code GDevelop project with seven embedded original SVG placeholder assets. No desktop installation is required for the URL workflow. Internal documentation, source discussion, complete mission/map/ability catalog and credentials are not included. The main game-design repository is separate.

## Try it

Open scene **Start**, choose **Preview**, then click the game canvas. Press **Enter** for **Graybox**. Use **1–5** to choose a local role, **WASD/arrows** to move, and **Esc** to return.

Five placeholders share one local session; this is **not five-player online play**. Multiplayer, KPI, fog, full missions and checkpoint gameplay are not implemented. Placeholder names/roles are working design, not final character art. Movement is not bounded to the floor graphic; Esc returns to Start.

## Project

`scambodia.json` is self-contained: native global variables and built-in event sheets/behaviors, no handwritten JavaScript events or custom extensions. Local GDevelop Core 5.6.269 load/code generation/HTML5 export passed; original portable runtime smoke checked scene switching, role selection and movement. The public payload removes the internal planning catalog while preserving the same sandbox event sheets.

Opening a GitHub URL creates an editor copy; saving in GDevelop does not commit changes back to this repository. Keep cloud/editor saves and GitHub source in sync deliberately. The official GDevelop MCP connection is desktop-only and is not enabled by this public link.
