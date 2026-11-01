# Fibonacci proportion references

- https://ocw.mit.edu/ans7870/18/18.013a/textbook/HTML/chapter00/section02.html — ratios of successive Fibonacci numbers approach the golden ratio.
- https://www.yongliangyang.net/docs/goldenLogo_eg23.pdf — Eurographics 2023 logo construction research using golden-ratio constraints.

Use ratios only for small controlled adjustments, retaining established design decisions and comparing visually.

The exact implementation and numerical changes are recorded in [DESIGN-DETAILS.md](../DESIGN-DETAILS.md). The dot radius uses a convenient golden-ratio multiple; it is not mathematically derived from another mark dimension. The taper uses a 25% blend toward normalized Fibonacci steps, and the spark uses the complementary golden-ratio fraction 1/phi².
