# bricolage

Tools I built because I needed them. Not on a schedule — on a need. Some solve my problems, some solve other people's. The fruit store checker (#06) exists because my friend counts inventory in winter gloves. The ACT matrix generator (#02) exists because I needed something to confront my own laziness and keep good habits visible. None of these are portfolio pieces in the traditional sense — they're proof that I default to building when something is broken.

## Projects

| # | Folder | Description | Stack | Live |
|---|--------|-------------|-------|------|
| 01 | `quote-wallpaper` | Fullscreen rotating display of 150+ book quotes with theme tags, word-by-word fade-in, and iOS Scriptable widget. | HTML, CSS, JS | — |
| 02 | `ACT-matrix` | Mobile-first ACT (Acceptance & Commitment Therapy) matrix tool. 4-quadrant daily logging, exports clean PNG for posting. | HTML, Canvas API, PWA | — |
| 03 | `easy-news` | Rewrites Japanese news articles at JLPT N3 level with furigana and text-to-speech. Powered by Claude API. | HTML, JS, Claude API, PWA | [Live](https://warm-zabaione-295e7b.netlify.app/) |
| 04 | `eisenhower-todo` | Eisenhower matrix TODO app. 4 priority quadrants with deadlines, persisted via Google Apps Script. | HTML, JS, Google Apps Script, PWA | — |
| 05 | `reading-timestamp` | Stamps the date on book-reading proof photos. Extracts EXIF datetime or manual input, composites a 1080×1080 image. | HTML, Canvas API, EXIF parsing, PWA | [Live](https://eloquent-madeleine-a66f77.netlify.app/) |
| 06 | `orot-fruits-checker` | OCR inventory checker for a fruit shop. Photo → Claude Vision extracts items → tap to check off. Glove-friendly UI. | React 18 (CDN), Claude Vision API, PWA | [Live](https://transcendent-tarsier-074d9f.netlify.app/) |
| 07 | `chaekgado` | Generates Instagram-ready images inspired by *chaekgado* (Korean bookshelf paintings). UI mockup — AI backend not yet connected. | HTML, CSS, JS | — |

## Tech Stack

Vanilla HTML/CSS/JS, React (CDN), Claude API (Sonnet), Google Apps Script, Canvas API, PWA (service workers + manifests). No build tools — everything runs from a single `index.html`.

## Notes

- Apps that use the Claude API require the user to provide their own API key at runtime (stored in localStorage, never hardcoded).
- The Eisenhower TODO backend uses a Google Apps Script endpoint. See `04-eisenhower-todo/config.example.js` for setup.
- *chaekgado* is a mockup — the generative AI pipeline is not yet implemented.

*New drops added as problems arise. Not on a schedule — on a need.*
