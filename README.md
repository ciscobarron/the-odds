# The Odds

**What were yours?** → [www.whatwereyourodds.com](https://www.whatwereyourodds.com)

The Odds is a short, free calculator that shows people the structural odds of their own life outcomes, given the conditions they started with. Ten short questions (after a first name) cover gender, race and ethnicity, parents' origin and education, neighborhood, household stability, schooling, and access to guidance; eight of them feed the score, while birth decade and current income are context only. The answers produce a structural difficulty percentile, a plain-language difficulty mode, "1 in X" odds, and a portrait of the typical path from that starting point.

The tool is built to make an invisible sorting system visible, not to assign guilt. *Potential is everywhere. Conditions are not.*

## Methodology

Each starting condition is assigned a multiplier reflecting relative structural difficulty, anchored in peer-reviewed research (administrative data, audit studies, and natural experiments where available). The specific values are informed judgment calls, not fitted statistical estimates. Multipliers compound across inputs, and three documented interaction effects adjust for variables that moderate each other. The product is converted to a 1-99 index on a log scale, which sets the difficulty percentile and mode; it is a scaled difficulty score, not a measured population percentile.

The "1 in X" odds are a separate calculation: the estimated probability that someone with your starting conditions ends with exactly the schooling you reported. It uses an ordered-logit model over seven credential levels, calibrated to Census 2022 attainment shares and the Pell Institute's bachelor's-attainment gap between the top and bottom family-income quartiles. The calibration relies on rough population shares and treats inputs as independent, so the output is an order-of-magnitude estimate. The model simplifies; it does not claim to account for any individual life. The full list of sources and the reasoning behind each multiplier is on the site's "How are these odds calculated?" page.

## Privacy

Everything runs in your browser. There is no backend, no account, and no stored answers. The site uses Google Analytics for page-level traffic only.

## Technical notes

A single self-contained `index.html` (HTML, CSS and vanilla JavaScript), hosted on GitHub Pages. The only external requests are Google Fonts and Google Analytics.
