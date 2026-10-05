# The Odds

**What were yours?** → [www.whatwereyourodds.com](https://www.whatwereyourodds.com)

The Odds is a short, free calculator that shows people the structural odds of their own life outcomes, given the conditions they started with. Nine scored questions about background (gender, race and ethnicity, parents' origin and education, neighborhood, household stability, schooling, access to guidance, and current income) produce a structural difficulty percentile, a plain-language difficulty mode, "1 in X" odds, and a portrait of the typical path from that starting point.

The tool is built to make an invisible sorting system visible, not to assign guilt. *Potential is everywhere. Conditions are not.*

## Methodology

Each starting condition is assigned a multiplier reflecting the relative probability of reaching above-median educational and economic outcomes from that condition, drawn from peer-reviewed research (administrative data, audit studies, and natural experiments where available). Multipliers compound across inputs, three empirically documented interaction effects adjust for variables that moderate each other, and the resulting score is converted to a percentile on a log scale. The model simplifies; it does not claim to account for any individual life. The full list of sources and the reasoning behind each multiplier is on the site's "How are these odds calculated?" page.

## Privacy

Everything runs in your browser. There is no backend, no account, and no stored answers. The site uses Google Analytics for page-level traffic only.

## Technical notes

A single self-contained `index.html` (HTML, CSS and vanilla JavaScript), hosted on GitHub Pages. The only external requests are Google Fonts and Google Analytics.
