# StoryCast - Accessible Media Feature Microsite

StoryCast is a framework-free microsite focused on accessible audio/video storytelling with semantic HTML, Sass architecture, responsive layouts, and WCAG 2.1 AA-minded patterns.

## Project Structure

- `index.html` — Home page with featured stories and navigation
- `about.html` — Mission, accessibility commitments, and participation details
- `story/` — Four story detail pages
  - `story-river-echoes.html`
  - `story-midnight-library.html`
  - `story-market-morning.html`
  - `story-train-window.html`
- `sass/` — Sass source
  - `_colors.scss`
  - `_typography.scss`
  - `_spacing.scss`
  - `_layout.scss`
  - `_components.scss`
  - `main.scss`
- `css/styles.css` — Compiled stylesheet
- `assets/`
  - `captions/` — `.vtt` caption files
  - `transcripts/` — story transcript files
  - `docs/`
    - `research-planning.md` (IA, sitemap, mockup guidance)
    - `documentation.md` (implementation and accessibility checklist)

## Information Architecture (Sitemap)

```text
Home (index.html)
├── About & Access (about.html)
└── Story Details
    ├── River Echoes (story/story-river-echoes.html)
    ├── Midnight Library (story/story-midnight-library.html)
    ├── Market Morning (story/story-market-morning.html)
    └── Train Window (story/story-train-window.html)
```

## Accessibility Checklist (Implemented)

- Semantic landmarks and sectioning elements (`header`, `nav`, `main`, `article`, `section`, `footer`)
- Skip link for keyboard users
- Visible focus styles with high contrast
- Color contrast chosen for AA-friendly legibility
- Caption tracks for videos (`<track kind="captions">`)
- Linked full transcripts for each story
- Descriptive link text and ARIA labels where beneficial
- Responsive, reflow-friendly layouts with Grid/Flexbox and container queries

## Running Locally

1. Open the folder in any static server.
2. Example:
   ```bash
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000`.

## Mockups and Research Artifacts

- See `assets/docs/research-planning.md` for IA, content hierarchy, and mockup notes.
- Figma mockup link placeholder: `https://www.figma.com/file/storycast-accessible-microsite` (replace with your final class submission file).
