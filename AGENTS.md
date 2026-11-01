# Chaotive brand direction

## Current authoritative state

As of 2026-11-01, the user-selected final candidate for this iteration is SYMBOL prototype 35 + frozen BRANDNAME prototype 1 = LOGO prototype 44. Preserve these assets as the iteration baseline. Do not continue design changes unless requested; future revisions use new numbered prototypes. This is the final candidate for this iteration, not a declaration that no future iteration is possible. Read `DESIGN-DETAILS.md` for construction, formulas and constraints. This state supersedes conflicting historical notes below.

## User-facing communication

- Show design results, image previews, meaningful visual changes and links to the relevant logo assets or showcase.
- Do not show CJS, JavaScript or other implementation code, helper scripts, code snippets, or routine technical command details to the user unless explicitly requested. These are irrelevant to the user's design review.
- Keep progress updates and final responses focused on the artwork and design decisions.

## Pending exact letterform requirement

The user requires both enclosing Cs to reproduce the actual skeleton of the C in frozen BRANDNAME prototype 1, rather than merely share angular styling. Preserve the letter's proportions, clipped shoulder, terminal construction and corner geometry; mirror the same shape for the right C. SYMBOL prototype 17 / LOGO prototype 23 are unsuccessful exploratory reconstructions, not the accepted current design. SYMBOL 16 / LOGO 22 remain the last current design until a faithful letter-derived replacement is verified. The available frozen wordmark is a raster PNG, so do not claim an exact source-vector match from an approximate redraw.

The brand folder and source prototypes have been checked: they contain generated PNGs, not original vector letterforms. Do not ask the user to supply a vector that this project never produced. A clipped source-C reference is saved in SYMBOL_prototype18/wordmark-c-reference.svg. SYMBOL 18 / LOGO 24 test direct raster-letter reuse, but their heavy letter bodies and orbit arrangement are exploratory and do not replace the current design. Future refinement should derive a thin enclosing skeleton from that source C while preserving the established layout.

## Project intent

Chaotive is the videogame studio brand of an individual developer. The name means **creative chaos**. The identity should express that meaning while feeling distinctive, professional, and suitable for an independent game studio.

The symbol's inspirations also include **electricity, circuitry, and energy**. Its connected paths, circuit-like nodes, and central spark can express creative energy flowing through the identity. These complement the existing Creative Chaos and orbital ideas; this documentation addition does not request an artwork change.

## Logo brief

- Start from `logo original.png` as the reference for the redesign.
- Modernize the identity while preserving a recognizable connection to the original.
- Draw inspiration from the character of classic game studio identities such as id Software, Black Isle, Broderbund, and Bitmap Brothers. Develop an original identity rather than copying their logos.
- Make the logo suitable for videogame studio branding across game screens, websites, storefronts, and other applications.

## Application showcase

- Provide an HTML page that demonstrates the new logo across different use cases and backgrounds.
- Show enough variation to assess readability, contrast, and the identity's character in context.

## Prototype recordkeeping

- Preserve assembled identity directions in their numbered `LOGO_prototypeN/` folders.
- Version current work in three independent tracks: `LOGO_prototypeN/`, `BRANDNAME_prototypeN/`, and `SYMBOL_prototypeN/`.
- LOGO means the assembled BRAND NAME + SYMBOL lockup. BRAND NAME is the wordmark alone. SYMBOL is the graphical mark alone.
- BRANDNAME prototype 1 is frozen until the user explicitly reopens that track. Continue current design work only in SYMBOL; create a corresponding new LOGO version when assembling an updated symbol with the frozen brand name.
- Never overwrite an earlier prototype when starting a new direction.
- Add or update `README.md` inside every prototype folder with its version number, date, parent prototype, status, direction, changes from the preceding version, and included files.
- Update the prototype table and latest-version marker in the root `README.md` whenever a prototype is added or materially revised.
- Update the root `logo-showcase.html` whenever any track changes. It must show the current SYMBOL, BRAND NAME, and assembled LOGO separately and as the equation SYMBOL + BRAND NAME = LOGO, followed by the full assembled-logo history. Embed every asset directly as a PNG data URI so the page remains one standalone HTML file with no server or asset dependencies.
- Keep the exact generation prompt and a self-contained HTML showcase with each prototype whenever those artifacts exist.

## Current exploration

The user likes prototype 1 and requested a saved snapshot in `LOGO_prototype1/`. Keep that direction available for comparison. Subsequent work was developed in `LOGO_prototype2/`: a slightly more modern evolution retaining the general idea, designed to work as a square image from the outset rather than only as a horizontal logo. The square composition is a user requirement; the A/C emblem and stacked name are the current implementation exploration.

Prototype 3 replaces the large A/C emblem with a large CC monogram for Creative Chaos. It should retain a square-first composition, use softer edges, and return to a styled version of prototype 1's CHAOTIVE wordmark below. Each large C may include one restrained supporting symbol: a creative spark for the first C and fragmented orbital nodes for the second C.

Prototype 4 preserves prototype 3 and refines the CC into opposing inward-facing forms: the left crimson C remains normal and the right navy C is mirrored. The smaller CHAOTIVE wordmark matches the emblem width, gives every letter equal scale, and alternates crimson and navy across the exact name. Keep the two-color system unless a later request explicitly introduces a third color.

Prototype 5 returns to prototype 3's favored wordmark styling. CHAO is navy and TIVE is crimson. The first C is crimson and represents chaos with clear orbital fragments; the second C is navy and represents creativity with clear sparks. The complete CC symbol and CHAOTIVE wordmark must share the same intended left and right guides within the square canvas.

Prototype 6 preserves prototype 5's wordmark. The crimson normal C and mirrored navy C face inward and connect at their top and bottom terminals to read as one two-color emblem. Keep the simplified three-node orbit inside the chaos C and the simplified two-spark motif inside the creativity C. The C bodies define the clean outer boundary.

The identity is now split into three tracks. BRANDNAME prototype 1 freezes the navy CHAO / crimson TIVE wordmark. SYMBOL prototype 6 is the active exploration: its fine angular opposing Cs connect diagonally into an enlarged orbit through narrow tapered conduits, while a proportionally larger four-point spark dominates the center. LOGO prototype 12 preserves the established upper-two-thirds symbol / lower-third wordmark square lockup.

## Active identity decisions

- **Working track:** Continue iterating only on SYMBOL unless the user explicitly reopens BRAND NAME. Each accepted symbol iteration also receives a new assembled LOGO version.
- **Frozen wordmark:** BRANDNAME prototype 1 remains unchanged. Preserve the exact CHAOTIVE spelling, custom letterforms, proportions and kerning. CHAO is navy and TIVE is crimson.
- **Spark:** Preserve the approved four-point curvature and exact center. SYMBOL prototype 6 intentionally enlarges its footprint from 200 to 250 units so it remains the dominant idea in the assembled logo.
- **C enclosure:** Keep the connected opposing-C concept, crimson left half, navy right half, interlocking top/bottom seam and fully closed far-right navy boundary. Use a wide 3:2 enclosure with a band near 6.5% of enclosure height so it remains a secondary frame. Its 45-degree chamfers, clipped corners and angular center transitions should feel related to the frozen wordmark.
- **Orbit system:** Use one clean continuous crimson circle centered exactly on the spark. Keep exactly three planets, with their centers directly on the orbit line and the line continuing beneath them so no planet appears detached. The current balanced arrangement uses 120-degree spacing and only subtle size differences.
- **Frame-to-orbit connections:** The left crimson C feeds from its upper inner/right terminal into the orbit's upper-right quadrant. The right navy C feeds from its lower inner/left terminal into the orbit's lower-left quadrant. Use narrow angular conduits that taper from about 20 units at the frame to 10 at the orbit. The orbit itself narrows to 10-unit approach arcs around both junctions and uses an 18-unit main stroke.
- **Hierarchy:** The orbit-and-spark Creative Chaos idea is the primary read; the enclosing Cs are a lighter supporting structure. This decision is informed by official game-brand references documented in `SYMBOL_prototype5/research-notes.md`, without copying their geometry.
- **Composition:** SYMBOL is a transparent wide 3:2 component. The assembled LOGO remains square: reserve its upper two-thirds for SYMBOL and its lower third for the frozen BRAND NAME. Both share the same visible left and right guides and vertical center axis.
- **Production geometry:** SYMBOL prototypes 2 onward have editable SVG masters and transparent PNG exports. Prefer deterministic SVG edits for precise geometry; use the PNGs in the self-contained HTML showcase.
- **Palette and finish:** Match BRANDNAME prototype 1 using its sampled dominant colors: crimson `#FB011C` and navy `#013787`. Use these as flat solid symbol colors. Avoid unrelated hues, shading, glows, dust, grain, stray particles, backgrounds and raster artifacts.

The first generated concept retains the original's oversized red A and dark lettering, with angular forms and controlled collisions. This is an initial design direction, not a confirmed final identity.

- Original reference: `logo original.png`
- First logo concept: `output/imagegen/chaotive-logo-v1.png`
- Generation prompt: `output/imagegen/chaotive-logo-v1-prompt.txt`
- Local application showcase: `logo-showcase.html`

The showcase includes light and dark backgrounds, monochrome treatments, a game splash screen, a studio website header, illustrative store artwork, and interactive background and scale controls. Mockup copy and artwork are illustrative and do not represent announced games or confirmed brand messaging.

## Latest decisions — 2026-10-31

Current: SYMBOL prototype 8 + frozen BRANDNAME prototype 1 = LOGO prototype 14. Independent Cs have no direct top or bottom connection. Left C joins only the upper orbit; right C joins only the lower orbit. C strokes are 18 units and orbit strokes 42 units, with clear breaks before the two junctions. The centered spark uses a crisp diagonal split of crimson #FB011C and navy #013787. These decisions supersede earlier continuous-orbit and single-color-spark rules.

## Latest decisions — 2026-11-01

Current: SYMBOL prototype 9 + frozen BRANDNAME prototype 1 = LOGO prototype 15. Spark uses one solid #7E1C52, the equal RGB mix of crimson #FB011C and navy #013787. Orbit left arc is crimson and right arc navy, divided at the C junctions. Each independent C grows from an 8-unit free terminal to a 42-unit orbit junction. Preserve the orbital breaks and square assembled layout. These decisions supersede the earlier split-color spark and uniform C weights.

## Latest decisions — SYMBOL 10 / LOGO 16

Current: SYMBOL prototype 10 + frozen BRANDNAME prototype 1 = LOGO prototype 16. Orbit colors are inverted from SYMBOL 9: right crimson #FB011C, left navy #013787. Each circular arc progressively tapers from 42 units at its originating C junction to 8 units before the opposite junction. Planets follow their arc color. Preserve the single purple spark #7E1C52, tapered independent Cs and square layout.

## Latest decisions — SYMBOL 11 / LOGO 17

Current: SYMBOL prototype 11 + frozen BRANDNAME prototype 1 = LOGO prototype 17. Each C joins its matching-color orbit arc as one continuous ribbon, with tangent-aligned edges and equal 42-unit junction thickness. Orbit ends taper to 8 units and terminate in exactly two small dots on the vertical centerline above and below the spark. Spark returns to a crisp diagonal crimson/navy split. These supersede earlier three-dot and mixed-purple decisions.

## Latest decisions — SYMBOL 12 / LOGO 18

Current: SYMBOL prototype 12 + frozen BRANDNAME prototype 1 = LOGO prototype 18. Each orbit must follow the exact 45-degree direction of its incoming C diagonal. Reshape the orbit rather than bending the incoming line. Both entries are rotationally symmetric with matching tangents. Preserve two endpoint dots, two-color spark, palette and taper.

## Latest decisions — SYMBOL 13 / LOGO 19

Current: SYMBOL prototype 13 + frozen BRANDNAME prototype 1 = LOGO prototype 19. Reduce visible symbol width by 25% by bringing the two outer C sides inward equally. Preserve inner orbit and spark dimensions, height, endpoint dots, connection angles and line weights. The narrower symbol supersedes the earlier shared-width requirement in the assembled logo.

## Latest decisions — SYMBOL 14 / LOGO 20

Current: SYMBOL prototype 14 + frozen BRANDNAME prototype 1 = LOGO prototype 20. Add radius-15 dots to both free C beginnings, matching the orbit endpoint dots: crimson lower terminal and navy upper terminal. All prior dimensions, taper, matching entry angles and two-color spark remain preserved.

## Latest decisions — SYMBOL 15 / LOGO 21

Current: SYMBOL prototype 15 + frozen BRANDNAME prototype 1 = LOGO prototype 21. All four dots must share the vertical centerline x=600 through the spark center and symbol canvas. Extend thin C free terminals to the guide so dots stay attached. Preserve all other geometry.

## Latest decisions — SYMBOL 16 / LOGO 22

Current: SYMBOL prototype 16 + frozen BRANDNAME prototype 1 = LOGO prototype 22. Refine outer C contours using precise guides, crisp 45-degree corner miters and deliberate angular cuts related to the wordmark. Use rotational symmetry and integrated free terminals. Preserve orbit flow, tapered weights, aligned dots and two-color spark.

## Clarified requirement — centerline, 2026-11-01

The user clarified that the enclosing C centerline must follow the brand-name C centerline, while its stroke width can differ. Direct reuse of the heavy raster silhouette is unnecessary. SYMBOL prototype 19 / LOGO prototype 25 record a letter-derived centerline exploration; the same path is mirrored horizontally for the right C. Source tracing is in SYMBOL_prototype19/c-centerline-reference.svg. Orbit attachments in this study need further aesthetic refinement; do not describe the raster-derived trace as a mathematically exact original font skeleton.

## Right C orientation clarification

SYMBOL prototype 20 / LOGO prototype 26: right C must be the left C rotated 180 degrees (both horizontal and vertical inversion), not a horizontal mirror alone. Its upper/lower asymmetry and inward return must invert too. Current orbit attachments remain an exploratory arrangement requiring refinement.

## Latest decisions — SYMBOL 21 / LOGO 27

Current: SYMBOL prototype 21 + frozen BRANDNAME prototype 1 = LOGO prototype 27. Restore dots at free C beginnings. C widths grow progressively from 8 to 42 units toward the orbit. Each C and orbit must form a continuous contour with no separate crossing connector or protruding stub. Keep the spark interior clear. Right C retains 180-degree inversion. This supersedes the crossing attachment studies.

## Latest decisions — SYMBOL 22 / LOGO 28

Current: SYMBOL prototype 22 + frozen BRANDNAME prototype 1 = LOGO prototype 28. Each orbit starts straight in the exact direction of the final C segment, with identical thickness at the join. Reshape the orbit to achieve this and preserve spark clearance. Preserve taper, dots, palette and inverted right C.

## Latest decisions — SYMBOL 23 / LOGO 29

Current: SYMBOL prototype 23 + frozen BRANDNAME prototype 1 = LOGO prototype 29. The top C line flows directly into the top orbit on a continuous horizontal tangent, with no hard step, vertical detour or kink. Opposite transition uses 180-degree symmetry. This supersedes the stepped entry in SYMBOL 22. Preserve taper, dots and clear spark interior.

## Archive pruning

The user requested deletion of LOGO prototypes 25–28. Those assembled-logo folders and showcase entries are removed. Their SYMBOL prototypes 19–22 remain available. Historical mentions above describe deleted assemblies; do not recreate them automatically. LOGO 29 / SYMBOL 23 remain current. Preserve numbering gaps.

## Latest decisions — SYMBOL 24 / LOGO 30

Current: SYMBOL prototype 24 + frozen BRANDNAME prototype 1 = LOGO prototype 30. Free C dot centers align vertically with lateral orbit centerline extrema: crimson x=415 and navy x=785. This supersedes the earlier common-centerline alignment for C beginning dots. Preserve all other geometry.

## Latest decisions — SYMBOL 25 / LOGO 31

Current: SYMBOL prototype 25 + frozen BRANDNAME prototype 1 = LOGO prototype 31. Orbit uses hard straight segments and clipped 45-degree corners matching the Cs instead of rounded curves. Preserve continuous joins, taper, dot alignment, two-color spark and inverted right C. This supersedes earlier rounded-orbit geometry.

## Latest decisions — SYMBOL 26 / LOGO 32

Current: SYMBOL prototype 26 + frozen BRANDNAME prototype 1 = LOGO prototype 32. Entire symbol enlarged uniformly by 25% in the assembled square logo, around its existing center. Preserve relative component geometry; brand name stays unchanged. Standalone export is 1125×1000.

## Latest decisions — SYMBOL 27 / LOGO 33

Current: SYMBOL prototype 27 + frozen BRANDNAME prototype 1 = LOGO prototype 33. Spark uses straight facets and hard corners, preserving its four points, exact center, size and diagonal two-color split. This supersedes curved spark geometry. Preserve the enlarged symbol and angular orbit.

## Latest decisions — SYMBOL 28 / LOGO 34

Current: SYMBOL prototype 28 + frozen BRANDNAME prototype 1 = LOGO prototype 34. Maximum symbol C stroke matches the frozen wordmark C main stem at actual assembly scale: approximately 56.85 rendered pixels, or 43.522 symbol units. Preserve 8-unit free beginnings and progressive widening. All angular shapes, dots and spark remain preserved.

## Latest layout — LOGO 35

Current: unchanged SYMBOL prototype 28 + frozen BRANDNAME prototype 1 = LOGO prototype 35. Balanced square stacked lockup: symbol approximately 90% of wordmark visible width, shared center axis, deliberate gap and balanced outer margins. Component shapes unchanged. These optical proportions supersede the earlier oversized symbol allocation for the assembled logo. There is no universal industry symbol-to-wordmark ratio; references support consistent proportions, clear space and legibility.

## Latest layout — LOGO 36

Current: unchanged SYMBOL prototype 28 + frozen BRANDNAME prototype 1 = LOGO prototype 36. Symbol and wordmark must read as one unit. Preserve LOGO 35 component scales but reduce their visible gap by 70 units to approximately 40 units on the 1254-square canvas, moving each component 35 units toward the other. This supersedes LOGO 35 separation.

## Latest layout — LOGO 37

Current: unchanged SYMBOL 28 + frozen BRANDNAME 1 = LOGO prototype 37. Preserve LOGO 36 component proportions and gap, then uniformly fit the full visible lockup to the maximum square-canvas dimension. Current width is the limiting dimension and fills the canvas; remaining vertical transparency is centered. No added exterior padding in the master asset.

## Latest decisions — SYMBOL 29 / LOGO 38

Current: SYMBOL prototype 29 + frozen BRANDNAME 1 = LOGO prototype 38. Preserve LOGO 37 layout. Recalibrate maximum C width to match the wordmark C stem at current relative component scales: 51.201 symbol units, with unchanged 8-unit ends and progressive growth. This supersedes the 43.522-unit calibration from the older layout.

## Latest decisions — SYMBOL 30 / LOGO 39

Current: SYMBOL prototype 30 + frozen BRANDNAME 1 = LOGO prototype 39. Remove the final three orbit-side segments from each C and place its orbital dot at the new end. Keep the beginning dots, angular spark, remaining taper and current logo layout.

## Latest decisions — SYMBOL 31 / LOGO 40

Current: SYMBOL prototype 31 + frozen BRANDNAME 1 = LOGO prototype 40. Ending width narrows progressively across the final two segments: maximum 51.201 to 28 to 8 units. Retain orbital dots at the ends. Both left dots share x=415; both right dots share x=785. Preserve all remaining proportions and layout.

## Latest decisions — SYMBOL 32 / LOGO 41

Current: SYMBOL prototype 32 + frozen BRANDNAME 1 = LOGO prototype 41. Two segments preceding the final segment share constant maximum thickness (51.201 units). Rapid narrowing happens only on the final segment, to 8 units. Both beginning and end are equally thin at 8 units. Preserve paired dot alignment and all other artwork/layout.

## Latest proportional study — SYMBOL 33 / LOGO 42

Current exploration: SYMBOL prototype 33 + frozen BRANDNAME 1 = LOGO prototype 42. Small Fibonacci-guided adjustments only: taper intermediates blend 25% toward normalized 13:21:34:55 steps; dots radius 16.18; spark inset 47.746 with tips unchanged. Preserve 8-unit ends, maximum 51.201 plateau, final-only taper, centerlines and layout. Fibonacci ratios are a heuristic, not proof of better aesthetics. Sources and rationale are in SYMBOL_prototype33/research-notes.md.

## Latest decisions — SYMBOL 34 / LOGO 43

Current: SYMBOL prototype 34 + frozen BRANDNAME 1 = LOGO prototype 43. Shorten top spans and move both outer C sides inward 80 units symmetrically. Dot guides become x=495 and x=705. Horizontal distance from final dot center to spark center is 105 units, matching vertical distance between paired dots. Preserve Fibonacci weights, dot radii, spark and diagonal endings. This spacing rule supersedes older dot guide values.

## Latest decisions — SYMBOL 35 / LOGO 44

Current: SYMBOL prototype 35 + frozen BRANDNAME 1 = LOGO prototype 44. Spark has a true transparent circular hole at (600,400), radius 16.18, matching orbital dots. Preserve all prior geometry and layout. Center alpha verified as zero in PNG export.
