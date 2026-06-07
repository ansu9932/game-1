# Assets — your faces & photos 💖

The game looks for two face images for the character heads:

- `ansu_face.png`        → Ansu's head
- `sayantani_face.png`   → Sayantani's head

Drop square PNGs (e.g. 256×256 or 512×512) with these exact names into this
`assets/` folder and they will appear on the front of each character's box head.

**If the files are missing, the game automatically draws a cute cartoon
fallback face** (with a smile + name), so everything still works out of the box.

## Music (two looping tracks)

The game now uses a dual-track soundtrack — drop these MP3s here:

- `romantic_bgm.mp3`  → soft, emotional romantic instrumental that loops
  gently from the moment you start playing.
- `apocalypse.mp3`    → the "Apocalypse" song. The instant the Secret Portal
  opens (password **`baby`**), the romantic track fades out and this one
  takes over, looping for the rest of the game (including in the gallery).

If a file is missing the game still runs (it just plays silence for that
track) — and the 🔊 Mute button always controls whichever track is active.

## Tips
- Use a clear, front-facing crop of the face for best results.
- Square images look best (they map onto a square head face).
- The photo gallery (behind the `babe` portal) uses generated placeholder
  pictures. To use real memories, replace the `makePhotoTexture()` images in
  `index.html` with `THREE.TextureLoader` calls pointing at files you add here
  (e.g. `./assets/memory1.jpg`).
