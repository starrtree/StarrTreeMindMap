# StarrTree Mind Map

An animated, editable brand idea map rooted in Music (blue), Tech (yellow), and Media (orange).

## Run

Serve this folder with `python3 -m http.server 8080` and open http://localhost:8080. No build step. The 3D model and model-viewer library load from Cloudinary and a pinned CDN. The private hosted edition bundles those assets locally.

## Interaction

Tap the 3D StarrTree symbol to cycle: symbol → categories → all words → categories → symbol. Tap an orb to open its words; switching orbs collapses the previous branch. Tap any word to edit or move it. Capture an idea suggests a branch using keywords; you can override it. Manage & backup supports moving, removing, JSON export, and merging imports.

## Storage

Ideas persist in localStorage for the current browser/device, without account sync or server storage. Export regular backups. If browser storage is blocked, a warning asks you to export. Initial ideas were transcribed from Max Starr's whiteboard; labels can be corrected in the editor.

The map is an idea garden, separate from StarrTrack and daily task execution. It does not assign deadlines or make captured ideas commitments.

## Assets

StarrTree 3D model and StarrSeed SVG supplied by Max Starr. model-viewer is pinned to 4.1.0 (Apache 2.0). No credentials are included.
