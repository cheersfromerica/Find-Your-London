# Find Your London

A ten-question taste quiz that matches you to one of twelve popular London neighbourhoods — vibe, budget, commute, and community, not postcode trivia. Available in English and Korean.

**Live site:** https://iriconic.github.io/Find-Your-London/

## Pages

- `index.html` — the quiz itself: ten questions, a preview grid of all twelve possible neighbourhoods, and a result page with a save-as-JPG share card.
- `how-it-matches.html` — a behind-the-scenes look at the matching logic: a flowchart of the scoring pipeline plus the full question-to-trait and area-to-trait data tables.

## How it works

Each answer nudges eight underlying traits (energy, community, affordability, green space, culture, family fit, connectivity, riverside character). After all ten questions, those traits are normalized and compared by distance against twelve fixed neighbourhood profiles — closest match wins.

Built as static, dependency-free HTML/CSS/JS — no build step, no backend.

---

© 2026 · [@cheers.from.erica](https://instagram.com/cheers.from.erica)
