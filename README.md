# Chaotive logo prototypes

This workspace records the evolution of the Chaotive identity. Chaotive is a solo videogame studio brand built around the idea of **creative chaos**.

Open the [comparative logo showcase](logo-showcase.html) to see every prototype immediately, then compare them on the same backgrounds, at the same scale, and in a shared avatar test. The page is one standalone HTML file with every logo embedded.

## Current component system

The identity now uses three independently versioned tracks:

| Element | Current version | Status | Asset |
| --- | --- | --- | --- |
| LOGO | [Prototype 10](LOGO_prototype10/README.md) | Current assembled logo | [PNG](LOGO_prototype10/chaotive-logo-p10.png) |
| BRAND NAME | [Prototype 1](BRANDNAME_prototype1/README.md) | Frozen for now | [PNG](BRANDNAME_prototype1/chaotive-brandname-p1.png) |
| SYMBOL | [Prototype 4](SYMBOL_prototype4/README.md) | Active exploration | [PNG](SYMBOL_prototype4/chaotive-symbol-p4.png) · [SVG](SYMBOL_prototype4/chaotive-symbol-p4.svg) |

**SYMBOL prototype 4 + BRANDNAME prototype 1 = LOGO prototype 10**

## Legacy full-logo prototype index

| Version | Direction | Main change | Files |
| --- | --- | --- | --- |
| [Prototype 1](LOGO_prototype1/README.md) | Oversized A wordmark | Modernized the original horizontal logo while retaining its large crimson A and angular navy lettering. | [Logo](LOGO_prototype1/output/imagegen/chaotive-logo-v1.png) · [Showcase](LOGO_prototype1/logo-showcase.html) |
| [Prototype 2](LOGO_prototype2/README.md) | Square-first A/C identity | Rebuilt the composition as a compact square mark with an A/C emblem above the name. | [Logo](LOGO_prototype2/chaotive-logo-v2.png) · [Showcase](LOGO_prototype2/logo-showcase.html) |
| [Prototype 3](LOGO_prototype3/README.md) | Creative Chaos CC monogram | Replaced A/C with two Cs, adding a creative spark and fragmented chaos orbit. | [Logo](LOGO_prototype3/chaotive-logo-v3.png) · [Showcase](LOGO_prototype3/logo-showcase.html) |
| [Prototype 4](LOGO_prototype4/README.md) | Opposing CC system | Mirrored the navy C inward, reduced the wordmark, and alternated crimson/navy across its letters. | [Logo](LOGO_prototype4/chaotive-logo-v4.png) · [Showcase](LOGO_prototype4/logo-showcase.html) |
| [Prototype 5](LOGO_prototype5/README.md) | Split-name Creative Chaos system | Colors CHAO and TIVE as two word groups, reverses the CC color relationship, and clarifies chaos/orbit and creativity/spark symbolism. | [Logo](LOGO_prototype5/chaotive-logo-v5.png) · [Showcase](LOGO_prototype5/logo-showcase.html) |
| [Prototype 6](LOGO_prototype6/README.md) | Connected opposing CC | Mirrors the right C, connects both Cs as one two-color emblem, and simplifies the internal orbit and sparks. | [Logo](LOGO_prototype6/chaotive-logo-v6.png) · [Showcase](LOGO_prototype6/logo-showcase.html) |
| [LOGO prototype 7](LOGO_prototype7/README.md) | Separated component system | Combines the frozen wordmark with SYMBOL prototype 1, whose closed navy boundary contains a central orbit-plus-spark motif. | [Logo](LOGO_prototype7/chaotive-logo-p7.png) |
| [LOGO prototype 8](LOGO_prototype8/README.md) | Thin Creative Chaos system | Combines the frozen wordmark with SYMBOL prototype 2: thinner styled C bands, a centered spark pivot and a more eccentric fragmented orbit. | [PNG](LOGO_prototype8/chaotive-logo-p8.png) · [SVG](LOGO_prototype8/chaotive-logo-p8.svg) |
| [LOGO prototype 9](LOGO_prototype9/README.md) | Circular orbit system | Keeps the approved spark, thins the C enclosure again, and seats three balanced planets directly on one continuous circular orbit. | [PNG](LOGO_prototype9/chaotive-logo-p9.png) · [SVG](LOGO_prototype9/chaotive-logo-p9.svg) |
| [LOGO prototype 10](LOGO_prototype10/README.md) | Wide two-thirds symbol system | Matches the frozen wordmark palette, widens the C enclosure to 3:2, and divides the square lockup into two-thirds symbol and one-third brand name. | [PNG](LOGO_prototype10/chaotive-logo-p10.png) · [SVG](LOGO_prototype10/chaotive-logo-p10.svg) |

**Latest assembled logo:** LOGO prototype 10.

## Versioning convention

- Preserve assembled-logo directions in their numbered `LOGO_prototypeN/` folders.
- Version new work independently as `LOGO_prototypeN/`, `BRANDNAME_prototypeN/`, and `SYMBOL_prototypeN/`.
- Keep BRAND NAME unchanged while its status is frozen. Continue current exploration only in the SYMBOL track; create a new assembled LOGO version when a symbol is combined with the frozen wordmark.
- Do not overwrite earlier prototypes when exploring a new direction.
- Every prototype folder contains a `README.md` describing its intent, relationship to the previous version, and included files.
- Keep detailed rationale in `design-notes.md` when present and the exact generation instructions in the prompt file.
- Update this root index whenever a prototype is added or materially revised.
- Add every new assembled logo to the `PROTOTYPES` registry inside the root `logo-showcase.html`. Update its component registry whenever the current BRAND NAME, SYMBOL, or LOGO changes. Embed every PNG as a data URI.
- HTML showcases are self-contained and can be opened directly in a browser.

All generated logos are raster design prototypes. A chosen direction should eventually be rebuilt as vector artwork for exact geometry, spacing, responsive lockups, and production-ready color variants.
