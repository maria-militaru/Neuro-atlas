# Maria's Neuro Atlas

An interactive 3D brain atlas. Static site: no build step, no server.

Files
- index.html  the whole app
- brain.txt   the brain meshes and MRI volume (about 12 MB), loaded by the app
- vercel.json cache settings for Vercel

Run locally: open a terminal in this folder and run `npx serve .`, then visit the address it prints.
(Opening index.html directly from your files will not work, because the browser blocks it from loading brain.txt.)
