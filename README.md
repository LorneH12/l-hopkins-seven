# L Hopkins / Seven

A cinematic athlete profile for L Hopkins: track, long jump, Xavier flag football #7, and Class of 2030. Built from the owner-approved adaptation of the KIMI reference.

## Open the site

Open `index.html` in a modern browser. No install, framework, build step, backend, or WebGL support is required. The complete interface, styles, and interaction code are in that file. Google Fonts and the approved photos/video load remotely, so an internet connection is needed for those assets. System fonts and readable content remain if assets fail.

Live site: https://lorneh12.github.io/l-hopkins-seven/ . Published through GitHub Pages from main / root. The owner approved making the repository public. Existing L Hopkins sites were not modified.

## Files

- `index.html` — complete website.
- `PROMPT.md` — full approved design and content brief.
- `VALIDATION.md` — browser checks and known limitations.
- `.nojekyll` — ready for ordinary static hosting if publication is requested.

## Editorial snapshot

October 31, 2026. The family's current update is **16 sacks** and **two games missed with an injury**. St. Mary's was canceled and not played. November 3 against Desert Vista is Senior Night and the last regular-season home game; November 5 at Corona del Sol is the later scheduled regular-season game. Homecoming is November 7. No injury return or postseason participation is promised.

The site links meet results, the Xavier athletics calendar, AZPreps365, and the Xavier Mothers' Guild directly. The family is the source for the current sack total, injury absences, and Senior Night designation. No per-game average is inferred. The long-jump marks are meet results, not personal-best claims.

## Content maintenance

The inline `ATHLETE` object holds current football facts and event dates. Elements marked `data-sacks` are synchronized from it. The HTML contains a complete static version for no-JavaScript access: update those fallback values at the same time. Track results and citations are deliberately present in semantic HTML; keep the timeline and table synchronized when changing a result. Update the editorial date, calendar context, and README after new family information arrives. The hero's “Next at home” label becomes “Home finale · 2026” after the scheduled November 3 start; the dated October 31 story remains an archive snapshot.

## Media and credits

Images are referenced from `https://lorneh12.github.io/l-hopkins-site/media/`:

- `hero-portrait.webp`, `portrait-football.webp`, `football-close.webp`, `portrait-school.webp`: Family.
- `nike-100m-final.mp4`, `nike-poster.jpg`: RunnerSpace; original broadcast credit retained.

Provenance: [main project asset register](https://github.com/LorneH12/l-hopkins-site/blob/main/docs/ASSETS.md).

No generated likeness, altered uniform, helmet, race-car assets, or unapproved montage playback is used. No private contact information, form endpoint, analytics, or tracking integration is included. Media remain the property of their respective owners; this repository does not grant a new media license.

## Interaction

Native scrolling; a single event-driven animation loop for a small photo spring, desktop section recession, and timeline progress. Lightweight once-only text entrances use the browser animation API. The loop sleeps when settled and pauses while the document is hidden. Reduced motion removes parallax, entrances, and the sticky stack. The native modal menu supplies keyboard trapping and Escape behavior; closing it restores focus. The video loads on demand, never autoplays sound, and pauses when out of view.
