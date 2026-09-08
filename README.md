# The Magic of Larry Warshaw

Static website — six hand-written HTML pages, no build step.

| File | Page |
| --- | --- |
| `index.html` | Home |
| `magic.html` | The Magic (video reel) |
| `about.html` | About Larry |
| `gallery.html` | Gallery |
| `testimonials.html` | Testimonials |
| `contact.html` | Contact / Book |

Fonts load from Google Fonts. Photos live in `img/` and are all genuine photos of Larry.
The reel on `index.html` and `magic.html` is still a play-button placeholder — swap it for an
`<iframe>` (YouTube/Vimeo) or a `<video>` tag when the footage is ready.

## Local preview

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy

Static site, no framework. On Vercel: Framework Preset **Other**, Build Command empty,
Output Directory `.` (or `site` if this folder sits inside a larger repo).
