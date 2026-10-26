# Nivara - run in VS Code

Files: index.html (the whole app), sw.js (offline cache), manifest.json.

Camera, microphone and GPS only work on http://localhost or https, NOT by double-clicking the file. Pick one option:

Option A - Live Server (easiest)
1. Install the "Live Server" extension in VS Code.
2. Open this folder (File > Open Folder).
3. Right-click index.html > "Open with Live Server".

Option B - Node
1. Open the terminal in VS Code (Ctrl + `).
2. Run: npm start
3. Open http://localhost:5500 in Chrome.

Option C - Python
1. Run: python -m http.server 5500
2. Open http://localhost:5500 in Chrome.

Use Chrome or Edge: speech recognition needs it. Load the page once while online so the offline cache is created.
