# Chaotive — current working design specification

Updated: 2026-11-01. User-selected final candidate for this iteration: SYMBOL 35 + frozen BRANDNAME 1 = LOGO 44. Preserve this baseline; future design changes receive new versions. The Fibonacci study below describes SYMBOL 33 / LOGO 42, followed by the spacing and transparency revisions incorporated into the final candidate.

## Identity and components

Chaotive means Creative Chaos and represents a solo videogame studio. Electricity, circuitry and energy complement the original orbital and creativity inspirations.

The wordmark remains frozen: exact custom letterforms, navy CHAO and crimson TIVE. The symbol uses opposing angular Cs, with the right C inverted on both axes (180-degree rotation). Current Cs end in dots and surround an angular four-point spark. The final three orbit-side segments were removed in SYMBOL 30. This supersedes earlier continuous-orbit requirements.

Palette: crimson `#FB011C`, navy `#013787`. The spark has a crisp diagonal split between those colors. Four dots use the corresponding C color. Left dot centers share x=415 and right dot centers x=785 in symbol coordinates. The spark center remains (600,400), with tips at (600,275), (725,400), (600,525), (475,400).

## Width and taper rules

Both C beginnings and endings are 8 units wide. Width grows toward a maximum plateau of 51.20105693 units, calibrated to the wordmark C stem at the current relative component scales. The two segments preceding the last segment remain at the same maximum width; rapid narrowing occurs on the last segment only. Preserve angular corners and 180-degree symmetry.

## Fibonacci study: exact changes

The outer centerlines, canvas, dot positions, spark tips, maximum plateau and 8-unit ends are unchanged. Only three intermediate widths, dot radii and spark inset vertices changed.

### Intermediate taper

Use the Fibonacci steps 13, 21, 34, 55 normalized to the existing maximum M=51.20105693. A full replacement would change the design too much, so move each intermediate width only 25% toward its Fibonacci target:

`new width = 0.75 × previous width + 0.25 × (M × Fibonacci step / 55)`

| Position in growing taper | Previous | Fibonacci step | New (approx.) |
| --- | ---: | ---: | ---: |
| First intermediate | 16 | 13 | 15.0255 |
| Second intermediate | 26 | 21 | 24.3874 |
| Third intermediate | 37 | 34 | 35.6629 |

This slightly lightens the developing stroke while retaining its overall growth and the exact maximum thickness.

### Dots

All four radii increase from 15 to 16.18 units, approximately 7.87%. The value is a convenient decimal multiple of the golden ratio, not a requirement derived from another logo dimension. Their centers and pairwise vertical alignment remain unchanged. The slightly larger dots reinforce the circuitry/terminal reading.

### Spark

Use phi=(1+sqrt(5))/2. Its complementary fraction is 1/phi² ≈ 0.381966. Multiply by the unchanged 125-unit tip radius to obtain 47.74575 units. Inset-corner offsets change from 42 to 47.746 units (approximately +13.68%).

Inset vertices become (647.746,352.254), (647.746,447.746), (552.254,447.746), (552.254,352.254). Outer tips, exact center, four-point silhouette and diagonal color split remain fixed. This makes the spark's body slightly fuller while preserving its footprint.

## Assembled layout

LOGO 42 preserves the compact LOGO 36/37 proportions and spacing. Scale the entire lockup uniformly to fill the square canvas's limiting dimension (currently width); center remaining vertical transparency. Do not stretch components or change the wordmark. Component size relationships are deliberate optical choices, not universal industry standards.

## Files and review workflow

Editable symbol: SYMBOL_prototype33/chaotive-symbol-p33.svg. Editable assembly: LOGO_prototype42/chaotive-logo-p42.svg. Each has a transparent PNG export. Root logo-showcase.html embeds the assets and preserves previous designs for comparison. Compare LOGO 41 against LOGO 42 at the same rendered size to assess these small changes.

Fibonacci ratios provide a repeatable design heuristic; they do not prove improved aesthetics. The final choice remains visual. No Fibonacci spiral, new motif or rounded construction was added.

## Sources

- [MIT: ratios of successive Fibonacci numbers](https://ocw.mit.edu/ans7870/18/18.013a/textbook/HTML/chapter00/section02.html).
- [Eurographics 2023: golden-ratio logo construction research](https://www.yongliangyang.net/docs/goldenLogo_eg23.pdf).

## Subsequent spacing revision — SYMBOL 34 / LOGO 43

Top C spans shortened; outer sides move inward equally by 80 units. Dot centers now share x=495 on the left and x=705 on the right. Final-dot horizontal offset from spark center x=600 is 105 units, matching right dot vertical separation 275−170=105 and left separation 630−525=105. This is a horizontal center-to-center interpretation, not edge clearance or Euclidean distance. All Fibonacci refinements and layout scales remain preserved.

## Transparent spark center — SYMBOL 35 / LOGO 44

Add a circular alpha cutout centered at (600,400), radius 16.18, equal to the orbital dots. This is transparent through all backgrounds, not a painted circle. All prior artwork and layout remain unchanged.
