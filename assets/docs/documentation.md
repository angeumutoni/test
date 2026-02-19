# StoryCast Documentation

## Technical Summary

- Semantic HTML5 structure across all pages.
- Sass tokenized architecture with partials for colors, typography, spacing, layout, and components.
- Compiled CSS provided in `css/styles.css`.
- Responsive layout built with Grid + Flexbox.
- Container query used in `.media-card` to adapt CTA layout and heading size.

## Accessibility Checklist

- [x] Skip links on every page
- [x] Landmarks (`header`, `nav`, `main`, `footer`)
- [x] Keyboard-visible focus styles
- [x] Caption tracks on all video stories
- [x] Transcript file per story
- [x] Informative alt text for feature images
- [x] ARIA labels where helpful (e.g., main nav)
- [x] Sufficient color contrast intent for body text and controls

## Local Development

Run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
