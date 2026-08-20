# Box United Principal Hub

Static site for school leaders running **Fight Like A Girl**, fall 2026.
Published with GitHub Pages from the repository root — `index.html` is the entry point.

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The four-step principal hub: welcome, collateral, coach, equipment |
| `<School>-EN.dc.html` / `-ES.dc.html` | Two-page flyer per school. Page 1 is the full flyer; page 2 holds two identical half-page folder inserts. Print or "Save as PDF" from the browser. |
| `Email-<School>-EN.html` / `-ES.html` | Send-ready parent email. The subject line is an HTML comment on line 1. |
| `assets/` | Logos, stickers, photography, registration QR codes, principal overview PDF |
| `_ds/`, `support.js`, `doc-page.js` | Brand tokens and the page/print runtime the flyers use |

## Before you publish

1. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
2. Paste your Google Form embed URLs into the `FORMS` object near the top of the script in `index.html`: `FORMS.coach`, `FORMS.equipment`, `FORMS.agreement`. While a value is empty the page shows a labelled placeholder in that step.
3. Share `https://box-united.github.io/School-Start-Info/` with principals.

## Program facts baked into the collateral

- Ten weeks: week of September 14 through week of November 16, 2026.
- Equipment drop-off window: September 8–11, 2026 (September 7 is Labor Day).
- Virtual coach training: opens September 1, due September 14, 2026.
- In-person coach training: September 12, 2026 at Chicago Youth Boxing Club.
- Signing deadlines: soft August 21, hard September 5, 2026.
- Family registration: https://boxunited.org/pages/youth
- Grades 4–8 at every school except Farragut Career Academy (9–12).
- Contact: programs@boxunited.org for curriculum and online sign-up questions.
