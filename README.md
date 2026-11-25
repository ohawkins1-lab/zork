# Zork Trilogy — personal iPhone web app

Zork I, II and III (MIT-licensed source from github.com/historicalsource, © 2025 Microsoft)
running on a small built-in Z-machine interpreter, with a touch-friendly interface.

## Install on your iPhone (works offline)
1. Create a new GitHub repository (it can be private only on a paid plan; public is fine).
2. Upload every file in this folder to the repository's root.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After a minute, open https://YOUR-NAME.github.io/REPO-NAME/ in Safari on the iPhone.
5. Tap Share → Add to Home Screen.
Open it once while online; after that it works offline.

Saves and autosave live in the browser storage of that home-screen app, on that phone only.

## Tips
- Tap any word in the story to add it to your command line.
- Chips with "…" (take, open, examine…) start a command; tap an object word to finish it.
- Tap a past command to put it back in the input.
- Undo button (or type "undo") rewinds one move — the original games don't have undo.
- The game's own SAVE and RESTORE commands open six save slots per game.

## Room scenes
Each room is drawn as a small 3D scene above the text, generated on the phone from the room's
name, its description and the objects the game reports in it (three.js, no images or models):
stylised two-band lighting with a sunlit rim, physical sky, sun/lantern shadows, N8AO ambient
occlusion, bloom, instanced wind-blown grass, swaying trees and drifting dust.
Quality steps down automatically if the phone can't keep up.
Turn them off under Menu → Hide room scenes. They hide themselves while the keyboard is open.
Credits: three.js (MIT), N8AO by N8python (CC0), grass technique after spacejack/terra (MIT shader
code) and al-ro, toon approach after ciro-unity/BotW-ToonShader, generator patterns from
Noniv/atlantis (MIT, © 2026 Maksymilian Dendura).
