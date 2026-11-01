# Build this as a single HTML file: L HOPKINS — SPEED / PRESSURE / CLASS OF 2030

Create a complete, polished athlete website for L Hopkins. Translate the supplied KIMI / GRIDO1 reference into L's world: sprinting, long jump, Xavier flag football, and her first year of high school. Preserve its editorial scale, precise framing, layered photography, animated data, and deliberate scroll choreography. Make the result feel unmistakably personal to L.

Deliver one working `index.html` with inline CSS and JavaScript. No framework, build step, or placeholder sections. External fonts, approved photographs, and video may load from the URLs below; this is a single-file implementation, not an offline asset bundle. Implement the finished page, including mobile layouts and functioning links. Do not publish or replace an existing site as part of this build.

## 1. Editorial direction

L is a Xavier College Preparatory freshman, Class of 2030, in Phoenix. She wears #7 in flag football and competes in sprints and long jump with Tha Truth Track Tribe. She is a 2025 USATF National Junior Olympic girls 13–14 long-jump champion.

The central idea is **speed that carries across sports**. Track establishes the performance foundation; football shows that speed in a different setting; school life gives the athlete a human context. Write with the precision of a sports reporter and the confidence of a great athlete profile. Use short, specific sentences. Avoid invented quotes, generic motivational filler, recruiting promises, and exaggerated rankings.

The current editorial moment is October 31, 2026: L has 16 sacks, has missed two games with an injury, and Xavier is approaching Senior Night and its last regular-season home game. Homecoming follows later that week. Keep the page celebratory and grounded. The injury is context, not the entire story.

Suggested page title: `L Hopkins | Track & Field + Flag Football | Xavier 2030`.

Suggested hero line: **SPEED ON THE TRACK. PRESSURE ON THE FIELD.**

Suggested closing line: **THE NEXT CHAPTER IS STILL BEING WRITTEN.**

## 2. Current facts — these override older project copy

Use one clearly organized data object for facts, results, events, media, and links. Render repeated numbers from that object so the hero, football panel, and captions cannot disagree.

### Football update supplied by the family, October 31, 2026

- **16 sacks** is the current family-reported total. It supersedes the older 10-sack public snapshot and 12-sack family snapshot.
- L has missed **two games with an injury**. The specific games and her return date are not established here. Do not assign injury absences to particular dates, describe a diagnosis, or say she will play November 3.
- Xavier did **not play St. Mary's**. The October 1 fixture is marked canceled on the school's athletics calendar. It is not a loss, a completed game, or one of L's injury absences.
- Do not reuse `12 sacks in 5 games`, `2.4 sacks/game`, or `5 of 11 games` as current data. Do not calculate a new average without a verified count of L's appearances and the scope of the 16-sack total.
- Other older football statistics and rankings are historical. Leave them out of the current feature unless freshly verified and dated.

Visible source note next to the current number: `Family update · Oct 31, 2026`.

### The week ahead

| Date | Event | Meaning |
| --- | --- | --- |
| Tuesday, November 3, 2026 · 6:00 PM | Xavier vs. Desert Vista · at Xavier | Senior Night and last regular-season home game; Senior Night designation supplied by family |
| Thursday, November 5, 2026 · 6:00 PM | Xavier at Corona del Sol | Last regular-season game listed on the reviewed schedule; away |
| Saturday, November 7, 2026 | Homecoming | Listed by Xavier Mothers' Guild; school-life event, separate from the November 3 game |

Times use America/Phoenix. Do not label November 3 the final game of the season: November 5 is still scheduled, and postseason participation is not established. L is a freshman celebrating the senior class, not a graduating senior. Do not call November 3 the homecoming game or give the dance an invented time or location.

Source links:
- Schedule: https://azpreps365.com/teams/football-flag/13666-xavier/208019-varsity
- Canceled St. Mary's fixture: https://www.xcp.org/athletics/athletics-calendar
- Homecoming date: https://xcpmg.org/senior

For the schedule component, show the two remaining football games and a visually distinct Homecoming card. A small expandable schedule note may explain the canceled October 1 fixture. Do not fabricate results for recent fixtures whose scores have not been confirmed. Do not infer L's attendance from a team schedule.

Treat this as an **October 31 editorial snapshot**. Store that date explicitly. If the page is viewed after an event, remove any automatic “upcoming” badge or countdown; preserve its date and do not invent a result. Do not display “live” on static data.

## 3. Verified performance material

Use event-specific labels and link each result to its source. Athlete rankings, meet placement, and personal bests are different things. Keep the age group or division visible.

| Date | Event | Result | Source |
| --- | --- | --- | --- |
| June 19, 2025 | Nike Outdoor Nationals · middle-school girls 100m | Bronze · 12.30 | https://live.athletictiming.net/meets/54378/events/individual/2064961 |
| July 25, 2025 | USATF National Junior Olympics · girls 13–14 long jump | National champion · 5.17m | https://results.adkinstrak.com/meets/54731/events/individual/2109552 |
| March 2026 | New Balance Nationals Indoor · middle-school girls 60m | Bronze · 7.59 | https://flashresults.com/2026_Meets/Indoor/03-12_NBIN/701-2_compiled.htm |
| March 2026 | New Balance Nationals Indoor · middle-school girls long jump | Bronze · 5.28m | https://flashresults.com/2026_Meets/Indoor/03-12_NBIN/723-1_compiled.htm |
| June 13, 2026 | Arizona Junior Olympics · girls 13–14 200m | First · 25.58 | https://live.athletic.net/meets/74867/events/individual/2818609 |
| June 22, 2026 | Nike Outdoor Nationals · middle-school girls 100m | Fourth · 12.08 · wind +0.3 | https://live.athletictiming.net/meets/74712/events/individual/2836029 |

The hero can use `12.08 / 100M`, `7.59 / 60M`, and `16 / SACKS`, with the track event context and football update date available immediately beneath or through clear source links.

Do not call 5.17m or 5.28m her personal best: they are marks from specific national meets. Existing material differs between 5.47m and 5.48m for her longer mark. Omit a long-jump personal-best tile until that discrepancy is reconciled. Do not use the unverified aggregate “9x All American,” broad “No. 1 in everything,” or “fourth in the country” without the specific competition and division.

## 4. Design system

Use the reference's sharp editorial language: oversized condensed headings, compact technical labels, asymmetric rails, corner brackets, stepped photograph plates, subtle grids, fine rules, and generous negative space. Avoid turning the page into a wall of identical rounded cards.

Palette (owner update: use Xavier's current xcp.org website colors):
- Dark navy: `#083350`
- Navy: `#0e5586`
- Blue: `#518db7`
- Gold: `#e7b744`
- White: `#ffffff`
- Supporting neutral: `#dadada`

Source: https://bbk12e1-cdn.myschoolcdn.com/ftpimages/845/SiteStyle/1730/SiteStyle134081358080263650.css . These are the current website's named color tokens. Replace previous green accent directions with gold and dark surfaces with Xavier navy. Use navy text on gold buttons.

Identity mark: the L and the 7 must be the exact same geometric shape. Define one SVG path, reuse it unchanged, and rotate the second instance 180 degrees to read as 7. Separate them with a slim slash. Do not use two unrelated font characters.

Typography: Oswald 500/600/700 for display; Space Grotesk 400/500/600 for body and metadata. Include good system fallbacks. Main name approximately 96–160px on large desktops, fluid with `clamp()`, approximately 56–80px on phones as space allows. Body text at least 16px; essential metadata at least 12–14px. Do not scale the root font down to fit a desktop canvas.

Desktop reference width: 1440px. Outer gutters: 32px desktop, 24px tablet, 20px phone. Buttons approximately 50px tall with an 8px clipped corner, a 1px outline, and a small directional arrow. Keep the frame and text aligned during hover animations.

Create a simple typographic `L HOPKINS / 07` identity. Jersey 7 is real; decorative “athlete_007” is optional design notation, never an official ranking. Do not carry over KIMI, GRIDO1, Mercedes, Italian flags, racing sponsors, cars, racing helmets, championship points, or F1 circuits.

## 5. Page structure and exact content direction

### A. Hero — L Hopkins

Build a full-height editorial opening around a real photograph of L. On desktop, position the identity on the left, the photograph center/right, and two compact bracketed information panels toward the right edge. Keep all text clear of her face and jersey number. The composition should feel athletic and intentional before animation loads.

Header: typographic identity; links to `Season`, `Results`, `Film`, and `Beyond the field`; compact menu button on narrow screens.

Hero copy:

> L HOPKINS
>
> SPEED ON THE TRACK.
> PRESSURE ON THE FIELD.
>
> Xavier College Preparatory · Class of 2030
> Sprints / Long jump / Flag football #7

Panel 1: `CURRENT SEASON` / `16 SACKS` / `Family update · Oct 31, 2026`.

Panel 2: `NEXT AT HOME` / `NOV 03 · 6 PM` / `DESERT VISTA` / `Senior Night`.

Primary action: `WATCH FILM`, anchors to the film player. Secondary: `VIEW RESULTS`, anchors to the sourced result section. A small Instagram link is a follow action, not a recruiting contact channel.

On phones, place name, portrait, key facts, and actions in a deliberate vertical sequence. Preserve both key facts; move the panels below the photo rather than hiding their information. Do not let the photo compete with legibility.

### B. The season — 16 sacks

Dark field, huge `16`, slim rule, compact source line. Pair a game photograph with this copy:

> **A FRESHMAN SEASON. AN IMMEDIATE IMPACT.**
>
> L has recorded 16 sacks for Xavier this season. She has missed two games with an injury. The Gators host Desert Vista on November 3 for Senior Night and their final regular-season home game, then travel to Corona del Sol on November 5.

Keep the injury statement restrained and factual. Do not write “back for Senior Night,” “fully recovered,” “playing through pain,” or a fictional comeback account.

Replace the racing circuit with a stylized flag-football field or abstract parallel sprint lanes. Fine dashed lines, distance ticks, a slow highlight sweep, and a subtle number 7 create the technical visual language. A decorative route must be labeled as illustration if it could be mistaken for actual play analysis. Do not invent sack locations, player tracking, or game telemetry.

Use a pixel-grid dissolve at the section edge, adapted from the reference's chequered seam. Keep it quiet enough that the photograph and number remain the focus. Any animated dots or route marks are decorative and hidden from assistive technology.

### C. The progression — results earned

Heading: `RESULTS EARNED.`

Create a chronological, alternating photo-and-result timeline using the six track results above, with the two March 2026 podiums grouped into one entry. Add a final Fall 2026 football entry with `Xavier · Freshman · #7 · 16 sacks` and its family source date. This produces six meaningful milestones; do not pad the timeline with invented childhood dates or achievements to match the original's seven rows.

Use stepped/chamfered photo frames, oversized year labels, and a thin vertical progress rail. Desktop plates alternate left, wide center, right as content allows. On phones, use a readable single column with dates and source links outside the images. Long meet names must wrap naturally.

A photograph may illustrate the athlete without depicting that exact meet. Label it honestly; never imply the available football portrait documents a track championship. When no event-specific photo is available, use a clean typographic result plate or a clearly labeled archive portrait. Do not synthesize medal ceremonies.

Include a compact, accessible full-results table or list beneath the visual timeline. Visible columns: event, division, mark, place, source. The decorative timeline must not be the only way to retrieve these facts.

### D. Beyond the field — school and the week ahead

Transition to a light surface. Use L's real school portrait and restrained contour lines. Headline: `MORE THAN A STAT LINE.`

Copy:

> A freshman year is made of more than competition. For L, this week brings a home finale with the Gators, a celebration of the senior class, and Homecoming ahead.

Feature block:

> **ONE MORE NIGHT AT HOME.**
> Xavier vs. Desert Vista
> Tuesday, November 3 · 6:00 PM
> Senior Night · Last regular-season home game
>
> A night to recognize Xavier's seniors as L's first high-school football season heads toward the end of its regular-season schedule.

Calendar band: November 3 home game, November 5 away game, November 7 Homecoming. Highlight the home game with corner brackets; mark Homecoming as `SCHOOL LIFE`, not a football fixture. Use explicit dates instead of ambiguous numeric dates alone. The three events remain available on phones.

Provide a `TEAM SCHEDULE` link to AZPreps365 and a `SCHOOL EVENT SOURCE` link to the Mothers' Guild. Keep any family-only Senior Night attribution in the source detail. Do not imply that the public schedule independently labels it Senior Night.

Do not invent GPA, academic awards, scholarships, offers, or commitments. The school portrait and Class of 2030 identity are sufficient for this section. Homecoming is school context; do not assert L's personal attendance plans.

### E. Film — see the speed

Create a dedicated, usable film section integrated with the same design system. Use a large poster, clear play button, actual HTML video controls, and concise sport/event labels. Do not make visitors fight a scroll-scrub animation to watch the race.

Primary feature: Nike Outdoor Nationals 100m final, with the event result and RunnerSpace credit. Optional secondary feature: the approved family highlights excerpt. Never autoplay sound. Load posters initially; defer video downloads until interaction. Keep controls available on phones and by keyboard.

For the family montage, only the first 31 seconds are approved for this website presentation; later footage includes another student. Use a genuinely trimmed approved excerpt if available. If the only available file is the full 41.5-second montage, omit that player and use the Nike race instead. Do not expose unapproved footage through seeking and rely only on a timeupdate loop to conceal it.

### F. Footer — follow the next chapter

Finish with an ink inset surrounded by a 12–16px green border, large condensed text, subtle contour artwork, and a real athlete image only if it improves the layout.

Heading: `THE NEXT CHAPTER IS STILL BEING WRITTEN.`

Links: Instagram, Athletic.net, MileSplit, Results, Back to top. A secondary `SUPPORT L'S JOURNEY` link may use the supplied Cash App destination. Keep following, support, and parent contact visibly distinct. Do not invent sponsor logos, a live store, campaign progress, or tax-deductibility claims.

No fake working contact form. If a verified parent relay endpoint is supplied later, wire it with actual delivery and error states. Until then, omit the form. Never publish personal parent email addresses in this file or route recruiting inquiries to a minor's private messages.

Include discreet photo/video credits and `Updated October 31, 2026`. Identify the site as L's athlete profile, not an official Xavier athletics website.

## 6. Motion and interaction specification

Keep the original reference's choreography, but make effects serve this content.

### Shared animation system

Use one `requestAnimationFrame` loop for active motion. Native scrolling is sufficient; Lenis is optional if needed for the intended feel. If used, initialize it once and run it from the shared loop. Do not combine competing smooth-scroll controllers. Respect browser navigation, anchor links, and restored scroll positions; do not forcibly reset every visit to the top.

Use a spring integrator or equivalent interruptible animation for reveals and panels. Suggested stiffness/damping: reveal 90/26, image panels 170/24, menu 190/26. Use seconds consistently for the solver, clamp elapsed time to 64ms, and substep after long frames. Stop updates once values settle. Prefer transforms and opacity; avoid per-frame layout changes to `top`, width, and height.

Hero entrance sequence: header immediately, identity at approximately 180ms, panels at 600ms, actions at 900ms. Translate text at most 20px. Keep real text in the document before animations initialize. Do not flash an empty screen while waiting for scripts.

### Hero visual treatment

The real photo is the base experience. A subtle green scan or contour sweep can pass across the frame; a decorative #7 outline can resolve behind her. On a precise pointer, allow at most 6–10px of independent background/photo movement. Do not warp L's face, anatomy, uniform, or jersey number.

Do not reuse the helmet GLB or its burn shader. No verified L-specific depth/normal maps or 3D likeness are supplied. Do not invent those asset paths or generate a replacement person. Optional WebGL should draw only abstract background contours, particles, or lines. If WebGL fails, the photograph and CSS/SVG composition remain complete.

An intro mark may resolve briefly, but it must not block access to the page. Avoid a fake loading percentage. Never tie content visibility to all remote assets succeeding.

### Layered scroll

On sufficiently wide and tall screens, the hero and season may form the reference's layered sticky stack. As the next section covers the previous, recede the prior section toward scale 0.94 and apply up to 0.35 shade. Keep text usable and avoid nested scroll containers. The timeline remains in normal flow. Disable stacking on small screens, short viewports, and reduced-motion settings.

### Timeline

Draw the progress rail as the visitor moves through the entries. A small square marker can rotate gently; it must finish at the last milestone, not beyond it. Photo parallax range should stay within approximately 20–40px and never reveal empty image edges. Year text reveals once. Hover emphasis must also work with focus and must not hide the other results.

### Calendar and buttons

Stagger event cards by approximately 90ms. The featured home-game bracket may spread by 5px on hover/focus. Do not use a pulsing “live” status for a future event. Button fills move from left to right in roughly 200–250ms; arrow travel at most 4px. Menu transitions are interruptible.

### Performance tiers

- Desktop: subtle parallax, layered scroll, modest animated line work.
- Mobile/coarse pointer: static composition with short reveals; no cursor effects, expensive blur, or oversized particle fields.
- Reduced motion: immediate content, no parallax, no scroll smoothing, no continuous effects, no entrance sweep.
- Hidden/offscreen: pause decorative rendering and video; resume only when relevant.

Do not reproduce the original 8,004-dot map or thousands of lines of helmet shader code merely to preserve implementation complexity. Match its visual intention with a small, purposeful system. Cap canvas pixel ratio at 1.5–2 and handle resize/context loss cleanly.

## 7. Real media and reference projects

Use the current main site's approved media register as the authority on provenance:
https://github.com/LorneH12/l-hopkins-site/blob/main/docs/ASSETS.md

Media base URL: `https://lorneh12.github.io/l-hopkins-site/media/`

| File | Purpose | Credit / constraint |
| --- | --- | --- |
| `hero-portrait.webp` | Hero portrait | Family; real source photo, cropped 1000×1800 |
| `football-close.webp` | Wide football photo | Family |
| `football-close-phone.webp` | Phone football crop | Family |
| `football-whole.webp` | Football supporting image | Family |
| `portrait-football.webp` | Football portrait | Family |
| `portrait-school.webp` | School portrait cutout | Family; existing background-removed original photo |
| `portrait-track.webp` | Track portrait cutout | Family; lower-resolution source, use at modest size |
| `team.webp`, `team-phone.webp` | Team context | Pattysflicks |
| `nike-100m-final.mp4`, `nike-poster.jpg` | Race film and poster | RunnerSpace; preserve credit |
| `montage.mp4`, `montage-poster.jpg` | Reference for family highlights | Full video is not approved for unrestricted playback; see 31-second excerpt rule |

Check that selected media loads and inspect framing before finalizing. Do not assume a file has transparency from its name. Use the school/track cutouts where transparency is present; frame opaque photographs intentionally. Preserve faces, body proportions, clothing, colors, and number 7. No generated or reconstructed likeness, uniform replacement, fake action photograph, or AI-edited portrait. No tackle-football helmet or pads.

Remote images used as WebGL textures require CORS support. If unavailable, use normal HTML images and decorative canvas behind them. Do not proxy or download media merely to bypass access restrictions. Preserve documented attribution; do not imply new ownership or endorsement.

Research/design references, not sources of current unverified claims:
- Main: https://lorneh12.github.io/l-hopkins-site/
- Flight: https://lorneh12.github.io/l-hopkins-flight/
- Story: https://lorneh12.github.io/l-hopkins-story/
- Historical prototype: https://lorneh12.github.io/l-hopkins-next/
- Original result-rich site: https://l-hopkins-athlete.t94rpvbjtf.chatgpt.site/

Do not copy the historical prototype's generated imagery or carry its old statistics into the new page. This prompt's October 31 corrections take precedence.

Destinations:
- Instagram: https://www.instagram.com/l.h0pkins/
- Athletic.net: https://www.athletic.net/athlete/16340968/track-and-field/all
- MileSplit: https://az.milesplit.com/athletes/12776709-l-hopkins
- Family support: https://cash.app/$LHopkins7

## 8. Responsive behavior, accessibility, and resilience

At 1280px and above, use the full editorial layout. At 768–1279px, simplify overlapping rails and reduce parallax. Below 768px, use normal-flow sections, readable captions, full-width media, and stacked event cards. At 320px, no horizontal overflow, clipped buttons, or truncated meet names. Let content determine section height instead of copying the reference's rigid phone heights.

One h1: L Hopkins. Each major section has a meaningful h2. Use semantic landmarks, a skip link, real anchors, visible focus states, and 44px minimum interaction targets. Preserve 200% zoom usability. Use actual table semantics for tabular results. Image alt text should describe what is visible without inventing the event. Decorative canvases, brackets, and contours are hidden from assistive technology.

If text is split into animated words, expose exactly one readable copy to screen readers. A mobile menu must manage focus, close with Escape, restore focus to its trigger, and make the background inert while open. Videos need controls, clear labels, and a useful text description; preserve available captions.

Content must remain readable when JavaScript, remote fonts, optional animation libraries, WebGL, or individual media files fail. A failed photo should retain its caption and a calm fallback surface. Log technical URLs/errors to the console, not as intrusive developer banners in the visitor experience. Give video failures a meaningful message and a working source link when available.

## 9. Completion criteria

Return the finished single HTML file and a short account of what was checked. Verify desktop and phone layouts, keyboard navigation, menu behavior, source links, media controls, reduced motion, and the no-WebGL fallback. Fix observed defects before delivery.

Content checks are mandatory:
1. Current sacks read 16 everywhere, labeled with the family update date.
2. Two injury absences are stated without invented dates or a promised return.
3. St. Mary's is canceled/unplayed and excluded from played-game claims.
4. November 3 is Senior Night and the last regular-season HOME game; L remains Class of 2030.
5. November 5 away at Corona del Sol remains visible as the later scheduled football game.
6. November 7 Homecoming is a separate school event.
7. Track results retain competition, division, mark, placement, and source.
8. All photographs depict the real L; racing assets and generated likenesses are absent.
9. No private contact details, fabricated form success, unapproved montage footage, or invented statistics appear.

The finished experience should have the reference's ambition and precision while telling L's actual story: national track results, an impactful freshman flag-football season, and a school year still unfolding.
