# Background asset credits

## `rain-forest.mp4` / `rain-forest-poster.jpg`

- **Title:** "Gloomy forest full of trees during a rainy afternoon"
- **Source:** Mixkit — item 22729
  - Page: https://mixkit.co/free-stock-video/gloomy-forest-full-of-trees-during-a-rainy-afternoon-22729/
  - CDN: https://assets.mixkit.co/videos/22729/22729-720.mp4
- **License:** Mixkit Stock Video Free License
  - https://mixkit.co/license/#videoFree
  - Free for commercial and personal use.
  - Attribution is **not** required (credited here anyway, for traceability).
  - Not to be redistributed as a standalone stock asset.

### Why 720p

The 720p rendition (4.1 MB) is used instead of the 1080p rendition (33.4 MB) so the
homepage stays light. It is fully blurred behind a dark overlay, so the resolution
difference is not visible.

### Processing applied at runtime

No re-encoding. The black-and-white look and the darkness needed for text
legibility are applied in CSS via `filter: grayscale(1) brightness(.62)
contrast(1.18)` on `.bg-video` in `../style.css`.

### Replacing this asset

Drop a new file at `rain-forest.mp4` (and optionally `rain-forest-poster.jpg`),
or point `.bg-video` / the `<video>` tag at different files. Keep `muted`,
`autoplay`, `loop` and `playsinline` on the tag or mobile browsers will not
autoplay it.
