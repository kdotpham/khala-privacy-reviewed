# Privacy: Who Captures the Value?

Live site: https://kdotpham.github.io/khala-privacy-reviewed/

The original khala-privacy repository and live site remain unchanged.

Release metadata: November 2, 2026 · Privacy · 15 min read.

This review build contains 23 interactive slide compositions, a black photographic cover, functioning article/deck navigation, synchronized dark mode, restored hover details and graphic effects, and downloadable SVG/HTML exports.

**Slide 16 contains SAMPLE DATA · NOT FOR POSTING. Replace the monthly placeholders before publishing the report as final.**

## Edit and rebuild

Install Node.js and Python 3, then run:

```
npm install
npm run generate
npm run verify
```

- `source/index.html`: editable slide content and original layout styles.
- `feedback-v2.css`: final layout and dark-theme corrections; also embedded in the source HTML.
- `slide-runtime.js`: interactive behavior within individual slides.
- `base-assets/privacy.js`: article/deck navigation, modal expansion and theme synchronization.
- `base-assets/privacy.css`: article and modal styling.
- `site-meta.json`: report title, release date and reading time.
- `source/cover.svg`: portable thumbnail with outlined Inter Tight type.
- `source/og.png`: final black cover artwork, with exact Inter Tight lettering and the original Khala logo.
- `dist/`: deployable multi-file article and individual slide exports.
- `github/`: self-contained root index and slide ZIP, created by self-contained.cjs.

Deploy `dist/`, or use the root files in `github/` for GitHub Pages (`main`, `/ (root)`). Keep `.nojekyll` in the publishing root.

The supplied research was not independently re-verified. The previous review table is a historical audit, not a claim that its original findings remain unresolved.
