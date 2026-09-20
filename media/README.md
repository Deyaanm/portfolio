Put artwork files in the matching folder, then reference them in `artworkData` inside `deyaan-portfolio-current.html`.

Examples:

```js
{ type: "text", text: "Short project description." }
{ type: "image", src: "media/la-grand-central/photo.jpg", alt: "Installation view", caption: "2026" }
{ type: "gif", src: "media/la-grand-central/loop.gif", alt: "Animated study" }
{ type: "video", src: "media/la-grand-central/video.mp4", poster: "media/la-grand-central/poster.jpg", caption: "Video documentation" }
{ type: "gallery", items: [
  { src: "media/la-grand-central/detail-1.jpg", alt: "Detail 1" },
  { src: "media/la-grand-central/detail-2.jpg", alt: "Detail 2" }
] }
{ type: "file", src: "media/la-grand-central/process.pdf", label: "Download process PDF" }
```

For many large files, do not send them through chat. Keep them in this folder, upload the whole site folder to your host, or use public URLs from a storage service.

Project folders:

- `about-me` (use `portrait.jpg`, `portrait.jpeg`, `portrait.png`, or `portrait.webp`)
- `la-grand-central`
- `cathedral`
- `kindergarten`
- `to-split`
- `passerbyes`
- `tree-filters`
- `danish-metal`
- `y-intersection`
- `evaluations`
- `liquid-refraction`
- `camera-study`
- `urban-mound`
- `tokyo-street`
- `2-worlds`
