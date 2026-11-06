# batuarchv

Portfolio site — cover art & visuals, Wii mode. Static HTML on GitHub Pages: https://batuarchv.github.io

## Editing the site (no code)

Open **https://batuarchv.github.io/edit/**

- Left: channels per page — drag to reorder or move between pages, eye icon hides a channel.
- Middle: live preview of the real site. *Seç* = click a tile to edit it, *Gez* = use the site normally.
- Right: settings of the selected channel (tile style, opening banner, texts, images) or *Profil & iletişim*.
- Drop JPG/PNG/WebP/MP4 files on a channel's *Görseller* area — they are resized automatically.
- Changes are kept as a draft in your browser until you press **Yayınla**. The site updates ~1 minute later.
- First publish asks for a GitHub token once (fine-grained, only this repo, *Contents: Read and write*).

## Files

- `assets/data.js` — all content (the editor writes this file).
- `assets/img/` — images (`name.webp` + `name-s.webp` thumbnail). Editor uploads go to `assets/img/u/`.
- `assets/video/` — videos uploaded from the editor.
- `assets/cursors/` — the custom HiDPI Wii cursor pack.
- `index.html` — the site. `edit/index.html` — the editor.
