# Paywall Audit — Air Apps

**Live:** https://bterzic123.github.io/air-apps-paywall-audit/

Four ranked ideas for the Translate Now paywall, each backed by a number from Adapty's
[State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=air-apps),
plus a clickable rebuild of the paywall and the close moment in Air Apps' own design.
The prototype has a Today / Proposed switch and numbered report pins.

## The ideas

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Catch “Not now” with your monthly plan (19,99 €, 7-day free trial) | 4.5: only 4% of apps show a second paywall on close; it converts at 0.88× the main one | ARPU +10–15% · based on Adapty data |
| 2 | Show how the 3-day trial works (three dates, trial named on the button) | 5.3 trial explainer; 3.4: 24% of trial paywalls show a timeline; Table E: 40% of US trials cancelled within 24 h | ARPU +12–36% · observed in winning A/B tests |
| 3 | Put the 4.7 from 377K ratings by the button | 5.3 social proof; 3.1: 27% of top paywalls use it | CR +10–30% · observed in winning A/B tests |
| 4 | Hold “Not now” for three seconds | 5.3 close delay; 3.7: 22% delay, most often 3–5 s | CR +8–15% · observed in winning A/B tests |

## Benchmark slice

App Store data, Oct 2025–Sep 2026, **all categories** (the report has no Reference category), **US**
(Translate Now's biggest App Store market).

## Grounding

Prices (9,99 €/week with a 3-day trial; 19,99 €/month with a 1-week trial) come from Air Apps' own
paywall and purchase sheets (EUR storefront). The $14.99/week US price and the 4.7 from 377K ratings
come from the US App Store listing. Copy, wordmark, emoji list, the Air Apps Plans card and the
sign-up screen are taken from the live app.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own
data, not measured results for Air Apps.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. `?open=proto` opens the prototype directly.
