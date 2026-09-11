# The Magic of Larry Warshaw

Static website — six hand-written HTML pages, no build step.

| File | Page |
| --- | --- |
| `index.html` | Home |
| `magic.html` | Video |
| `about.html` | About Larry |
| `testimonials.html` | Praise |
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

## Still to add

- `Ring-129-LPW-Profile.pdf` — drop the bio PDF in beside the HTML files; `index.html` and `about.html` already link to it.
- The show video — replace the play-button placeholder in `magic.html` (and the poster on `index.html`) with an `<iframe>` or `<video>`.
