## Portfolio

Personal portfolio site for **Pyae Phyo Kyaw ("Ash")** — Software Engineering student and Technical Assistant at Asia Pacific University (APU), Malaysia, with a focus on web design and creative digital work.

A single-file, dependency-light static site — no build step, no backend, ready to host on GitHub Pages.

## Design

A light theme with a pink accent, built around a "signal" motif: a thin animated pulse line runs between sections and doubles as the page's signature visual element.

- **Palette** — off-white background, soft pink surface panels, deep pink accent, warm neutral ink for text
- **Type** — Archivo Black for display headings, Inter for body copy, IBM Plex Mono for labels, tags, and the terminal-style detail (`// about`, `$ whoami`, stat readouts)
- **Interaction** — a tab group in the hero (Student / Technical Assistant / Developer / Creative) swaps a description readout without a page reload

## Sections

| Section | Content |
|---|---|
| Hero | Name, tagline, and the interactive role tabs |
| About | Quick-facts card (program, school, role, location) plus a short bio |
| Services | Web Design, Photography, Social Media, Art Direction |
| Contact | A form that opens the visitor's email client pre-filled (`mailto:`), plus direct email/phone and social links |

## Tech

- Plain HTML, CSS, and vanilla JavaScript — no framework, no bundler
- Google Fonts (Archivo Black, IBM Plex Mono, Inter) loaded via CDN
- Fully responsive, keyboard-focus visible, and respects `prefers-reduced-motion`

## Running locally

No build step required — just open the file:

```bash
open Portfolio.html
```

or serve it locally:

```bash
python3 -m http.server 8000
```

## Deploying to GitHub Pages

1. Make sure `Portfolio.html` is at the root of the `main` branch
2. In the repo, go to **Settings → Pages**
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`
4. Save — the site will be live at `https://ash1537.github.io/Portfolio`

## To do

- [ ] Swap in real social links (Instagram, TikTok, Snapchat, WhatsApp, Facebook — currently placeholders)
- [ ] Add a profile photo and/or project screenshots
- [ ] Wire the contact form to a real form backend if a `mailto:` link isn't preferred

## Contact

- Email: thedot1537@gmail.com
- Phone: +60 182 110 826
