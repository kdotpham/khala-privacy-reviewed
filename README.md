# Privacy: Who Captures the Value?

Live site: https://kdotpham.github.io/khala-privacy-reviewed/

The original khala-privacy repository and live site remain unchanged.

Release metadata: November 2, 2026 · Privacy · 15 min read.

This review build contains 23 interactive slide compositions, a black photographic cover, functioning article/deck navigation, synchronized dark mode, restored hover details and graphic effects, and downloadable SVG/HTML exports.

Jack's latest pass limits slide 7's network-privacy comparison to Nym and UR (SN25). Their combined market cap is $30.6M at the supplied snapshot; the summary and valuation-gap text use that same scope. Slide footers have a dedicated clear area behind the logo in light and dark modes.

Agent-readable formats are generated directly from the editable slides: `report.html` (no JavaScript required), `report.md`, `report.json`, and `llms.txt`. The main page also includes a collapsed, server-rendered full transcript and Article JSON-LD. Chart labels, tables and 149 interactive notes retain their supplied dates and qualifications. Sample data on slide 16 and illustrative scenarios on slide 22 are explicitly tagged. A targeted primary-source audit on 18 October checked slide 15 and UR (SN25) mechanism wording; the remaining research is not independently refreshed.

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
- `agent-readable.cjs`: generates the HTML transcript, Markdown, structured JSON and format index from the slides; do not edit generated report files independently.
- `source/cover.svg`: portable thumbnail with outlined Inter Tight type.
- `source/og.png`: final black cover artwork, with exact Inter Tight lettering and the original Khala logo.
- `dist/`: deployable multi-file article and individual slide exports.
- `github/`: self-contained root index and slide ZIP, created by self-contained.cjs.

Deploy `dist/`, or use the root files in `github/` for GitHub Pages (`main`, `/ (root)`). Keep `.nojekyll` in the publishing root.

See [the 18 October research audit](Khala-Research-Audit-2026-10-18.html), also supplied as CSV and JSON. It covers all 23 slides, records corrections and separates verified findings from unresolved evidence. Slide 15 now identifies address-to-IP linking under a controlled observer setup and labels Ethereum mainnet versus testnet. UR (SN25) was not tested by that study. Slide 17 distinguishes design from the documented launch and labels the 200-fleet figure as a capacity limit. Deposit locking is distinct from guaranteed new market purchases. The older review files are historical.

Current build: `2026-10-18-audit-v8`. This remains a review draft: the sample chart and unresolved material evidence must be addressed before final public/client release.
