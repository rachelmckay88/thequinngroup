# Quinn M&A — Industry Expertise pages: paste map

Each file is a Divi **Code Module** fragment (paste into a Code Module, `</>` icon — not a Text Module). One file = one full page body. Every CTA points to `/contact-us/`.

## Live pages (existing URLs)

| File | Page |
|---|---|
| `accounting-firms.html` | /industry-expertise/accounting-firms/ |
| `law-firms.html` | /industry-expertise/law-firms/ |
| `medical-businesses.html` | /industry-expertise/medical-businesses/ |
| `food-beverage-manufacturing.html` | /industry-expertise/food-beverage-manufacturing/ |
| `manufacturing.html` | /industry-expertise/manufacturing/ |
| `professional-service-firms.html` | /industry-expertise/professional-service-firms/ |

## New pages (create these, then paste)

| File | Create at (suggested slug) |
|---|---|
| `rural-property.html` | /industry-expertise/rural-property/ |
| `commercial-property-and-business.html` | /industry-expertise/commercial-property-and-business/ |

After creating the two new pages, add them to the Industry Expertise hub listing (and nav if wanted). Their secondary CTA points to /rural-property-ma/ and /commercial-property-ma/ respectively.

## Notes
- Icons are embedded in the CSS (background data-URIs) so WordPress can't strip them; dark-band text is pinned white with inline `!important` to beat Divi theme overrides.
- Content current as at July 2026, deliberately directional (no fragile hard figures).
- If a page renders blank after pasting: likely a security plugin (Wordfence/Sucuri) or a role lacking `unfiltered_html` — test with a tiny `<p>` snippet first.
