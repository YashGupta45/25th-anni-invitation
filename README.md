# Rohit & Archana · Silver Jubilee invitation

A static site: no build step.

- `index.html`: the invitation
- `photos/`: the six story photos and the blurred hero background
- `audio/janam-janam.mp3`: the song that plays when the book is opened

## Deploy on Vercel
1. Push this folder to a GitHub repository (index.html at the repo root).
2. In Vercel: Add New → Project → import the repo.
3. Framework preset: **Other**. Leave the build command and output directory empty, then Deploy.

To preview locally, run a small server from this folder (for example `python3 -m http.server`)
and open http://localhost:8000. If you double-click index.html instead, some browsers
won't fade the music in.
