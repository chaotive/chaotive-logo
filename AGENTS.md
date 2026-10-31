# Chaotive brand direction

## Project intent

Chaotive is the videogame studio brand of an individual developer. The name means **creative chaos**. The identity should express that meaning while feeling distinctive, professional, and suitable for an independent game studio.

## Logo brief

- Start from `logo original.png` as the reference for the redesign.
- Modernize the identity while preserving a recognizable connection to the original.
- Draw inspiration from the character of classic game studio identities such as id Software, Black Isle, Broderbund, and Bitmap Brothers. Develop an original identity rather than copying their logos.
- Make the logo suitable for videogame studio branding across game screens, websites, storefronts, and other applications.

## Application showcase

- Provide an HTML page that demonstrates the new logo across different use cases and backgrounds.
- Show enough variation to assess readability, contrast, and the identity's character in context.

## Prototype recordkeeping

- Preserve legacy identity directions in their existing numbered `prototypeN/` folders.
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

The identity is now split into three tracks. BRANDNAME prototype 1 freezes the navy CHAO / crimson TIVE wordmark. SYMBOL prototype 1 is the active exploration: its navy right boundary is closed and a crimson three-node orbit wraps a central navy spark. LOGO prototype 7 assembles those two components in the established square lockup.

The first generated concept retains the original's oversized red A and dark lettering, with angular forms and controlled collisions. This is an initial design direction, not a confirmed final identity.

- Original reference: `logo original.png`
- First logo concept: `output/imagegen/chaotive-logo-v1.png`
- Generation prompt: `output/imagegen/chaotive-logo-v1-prompt.txt`
- Local application showcase: `logo-showcase.html`

The showcase includes light and dark backgrounds, monochrome treatments, a game splash screen, a studio website header, illustrative store artwork, and interactive background and scale controls. Mockup copy and artwork are illustrative and do not represent announced games or confirmed brand messaging.
