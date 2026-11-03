# atoll-site

Landing page for Atoll (tryatoll.app). Static HTML served by GitHub Pages.

## Structure (2026-11-04)

- `index.html`: the whole landing page. Hero (island, boats, birds) → notify band → Today (phone drawn in HTML: hold to lock, legend hover) → Share (daily card rail) → Stats (phone with Week / Month / Year, glowing hotspots open sheets, weekly card rail) → details → plans → FAQ → final CTA
- `img/v2/island`: island frames exported from the app (`-exportIslandForTrial`)
- `img/v2/card-*`: share cards (`-exportShareForTrial`) composited on the app's sea backgrounds
- `img/v2/st-*`: Stats screens and sheets captured from the simulator
- `img/v2/kind`: legend icons (same SF Symbols and colours as the app)
- `privacy/`, `terms/`, `support/`: legal and support pages; `worker/`: waitlist signup Worker
- Keep copy short: one sentence, one phone and one thing to touch per section
- Local preview: `python3 -m http.server 5501`

