# Horse Racing Companion website

Static, dependency-free marketing and App Store compliance site.

Production URL: <https://horseracingcompanion.com/>

Stable App Store Connect URLs:

- Marketing: `https://horseracingcompanion.com/`
- Support: `https://horseracingcompanion.com/support/`
- Privacy policy: `https://horseracingcompanion.com/privacy/`
- Privacy choices: `https://horseracingcompanion.com/privacy/#choices`
- Terms: `https://horseracingcompanion.com/terms/`
- Accessibility: `https://horseracingcompanion.com/accessibility/`
- Age suitability: `https://horseracingcompanion.com/age-suitability/`
- Service status: `https://horseracingcompanion.com/service-status/`
- App Review information: `https://horseracingcompanion.com/review-information/`

The public site is mirrored to the `main` branch of the dedicated public
`bpollak/horse-racing-companion-site` repository. The application and algorithm
source remain private. To preview locally, serve the `website` directory with
any static HTTP server.

Season and review maintenance:

- Keep public pricing evergreen: the app and App Store are the authority for
  the exact season, price, and access end date shown before purchase.
- Keep retrospective performance headlines off the marketing page unless they
  are dated, versioned, economically complete, and approved for publication.
- The initial live record was approved for publication on 2026-08-23. Keep its
  date range, model/policy version, denominator, match definition, passes, and
  hypothetical minimum-stake return together whenever the headline is updated.
- Keep the full DMTC non-affiliation statement and no-wager boundary on every
  public page.
- Leave the App Store badge as “Coming soon” until the listing is live, then
  use the US App Store URL documented in `index.html`.
- Mirror this directory manually after every approved public-site change;
  pushing the application repository does not update production.
