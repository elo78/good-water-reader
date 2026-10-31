# Good Water Reader

A chemistry-based web tool that checks whether drinking water suits a person's body.

**Live site:** https://elo78.github.io/good-water-reader

## The problem
Some people react badly to waters that most people drink without harm. A single "safe" limit does not capture this, because the same dissolved minerals affect people differently.

## How it works
The user enters values from a bottle label or water test (pH, TDS, sodium, calcium, magnesium, sulfate, chloride, nitrate, fluoride, iron, alkalinity, temperature and toxic metals) and ticks personal sensitivities such as low-sodium diet, kidney concerns, infants, pregnancy, sensitive stomach, reflux or sensitive skin. The tool compares each value with guideline limits, tightens the limits for the selected sensitivities, and explains each result in chemical terms.

It also calculates the Langelier Saturation Index to show whether water is corrosive, balanced or scale-forming.

## Sources
Limits come from the WHO Guidelines for Drinking-water Quality. Some thresholds are conservative screening rules and are marked as such in the site's "Methods and sources" section.

## Limits
This is a screening and learning tool, not a medical device. It cannot detect germs, pesticides or heavy metals unless test values are entered, and it does not diagnose any condition.

## Planned
- Nigerian drinking-water standard values (NIS 554)
- Compare two waters
- PDF result download
- A log of personal reactions

## Built with
HTML, CSS and JavaScript. It runs in the browser, and no data is sent anywhere.

Built by Elo, 2026.
