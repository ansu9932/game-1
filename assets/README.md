# Assets — your faces & photos 💖

The game looks for two face images for the character heads:

- `ansu_face.png`        → Ansu's head
- `sayantani_face.png`   → Sayantani's head

Drop square PNGs (e.g. 256×256 or 512×512) with these exact names into this
`assets/` folder and they will appear on the front of each character's box head.

**If the files are missing, the game automatically draws a cute cartoon
fallback face** (with a smile + name), so everything still works out of the box.

## Tips
- Use a clear, front-facing crop of the face for best results.
- Square images look best (they map onto a square head face).
- The photo gallery (behind the `babe` portal) uses generated placeholder
  pictures. To use real memories, replace the `makePhotoTexture()` images in
  `index.html` with `THREE.TextureLoader` calls pointing at files you add here
  (e.g. `./assets/memory1.jpg`).
