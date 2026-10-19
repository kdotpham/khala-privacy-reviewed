# Privacy: Who Captures the Value?

Live site: https://kdotpham.github.io/khala-privacy-reviewed/

The original khala-privacy repository and live site remain unchanged.

Release metadata: November 2, 2026 · Privacy · 15 min read.

This review build contains 24 interactive slide compositions, a black photographic cover, functioning article/deck navigation, synchronized dark mode, restored hover details and graphic effects, and downloadable SVG/HTML exports.

Jack's latest pass limits slide 7's network-privacy comparison to Nym and UR (SN25). Their combined market cap is $30.6M at the supplied snapshot; the summary and valuation-gap text use that same scope. Slide footers have a dedicated clear area behind the logo in light and dark modes.

Agent-readable formats are generated directly from the editable slides: `report.html` (no JavaScript required), `report.md`, `report.json`, and `llms.txt`. The main page also includes a collapsed, server-rendered full transcript and Article JSON-LD. Chart labels, tables and interactive notes retain their supplied dates and qualifications. Sample data on slide 17 and illustrative scenarios on slide 23 are explicitly tagged. A targeted primary-source audit on 18 October checked the RPC privacy slide and UR (SN25) mechanism wording; the remaining research is not independently refreshed.

**Slide 17 contains SAMPLE DATA · NOT FOR POSTING. Replace the monthly placeholders before publishing the report as final.**

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

See [the 18 October research audit](Khala-Research-Audit-2026-10-18.html), also supplied as CSV and JSON. It records the previous 23-slide edition; its numbers precede the new Nullmask slide. The RPC privacy slide now identifies address-to-IP linking under a controlled observer setup and labels Ethereum mainnet versus testnet. UR (SN25) was not tested by that study. The UR (SN25) mechanism slide distinguishes design from the documented launch and labels the 200-fleet figure as a capacity limit. Deposit locking is distinct from guaranteed new market purchases. The older review files are historical.

Current build: `2026-10-19-nullmask-v9`. This remains a review draft: the sample chart and unresolved material evidence must be addressed before final public/client release.


## Nullmask update, 19 October 2026

Slide 9 compares Nullmask ($MASK), Aztec, Umbra, Venice and UR (SN25). Zcash remains on slide 10. New slide 11 explains Nullmask’s existing-wallet access, shielded-pool flow, fees, token-value-capture questions, operator visibility and roadmap. The coverage universe therefore contains six profiles; this is not a claim that every token is a small cap. The Nullmask market cap/FDV snapshot is 19 October; other peer market-cap figures remain dated 15 October. See `nullmask-research-2026-10-19.json` for exact references and qualifications. The earlier research audit remains historical.

The compact `editable-site.zip` omits the generated `dist/downloads/khala-slides.zip`; it is supplied as `khala-slides.zip` in the website root and recreated by `npm run generate`.
