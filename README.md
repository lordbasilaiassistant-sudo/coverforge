# CoverForge

**CoverForge** is a free, 100% client-side cover designer for indie authors, podcasters and musicians. Type a title, author and tagline, pick a vibe, and it composes a striking **book (2:3), podcast/album (1:1) or wide (16:9)** cover from *generative typographic + geometric art* rendered live on an HTML canvas — eight art-directed styles, ten curated palettes and real Google Font pairings. No AI image generation (so no slop), no signup, no server, no watermark. Export a print-ready PNG up to 2400px in one click.

**Live → (set on deploy)**

## How it works
- **Free tier (keyless, runs entirely in your browser):** choose a style (Aurora, Monolith, Bauhaus, Spectrum, Eclipse, Strata, Brutalist, Prism), a palette, a format and a type pairing. Toggle film grain, vignette and uppercase. Hit **Shuffle** to reseed the generative composition, then **Export PNG**. Nothing is ever uploaded — every pixel is drawn from your inputs with the Canvas API.
- **Pro tier (bring-your-own-key AI copywriter):** paste your own **GLM (z.ai)** API key and describe what your project is about + the vibe. CoverForge calls the GLM API *directly from your browser* (`glm-4.5-flash`) to suggest 4 sharp, non-generic title / subtitle / tagline concepts, with a quality gate that strips clichés. Click a concept to drop it straight onto the cover. Your key is stored only on the page and is sent only to the official GLM endpoint — never to us (there is no server).

## Build
Single self-contained `index.html` (inline CSS/JS, fonts from Google Fonts CDN). Static — deploy anywhere (e.g. GitHub Pages). No backend, no tracking, no dependencies.

## Affiliate disclosure
The "Get a GLM key" links (`z.ai`) are **referral links** — if you subscribe through them we may earn a small commission (and you get 5% off), which helps keep CoverForge free. The full designer works without any key; the affiliate link is only for the optional Pro AI copywriter.
