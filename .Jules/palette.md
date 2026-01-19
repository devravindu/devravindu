# Palette's Journal

## 2024-05-22 - Context for Repeated Links in READMEs
**Learning:** In a flat README.md structure, repeated link text like "Live Demo" is an accessibility anti-pattern. Adding specific `aria-label`s (e.g., "Live Demo for [Project Name]") provides necessary context for screen reader users navigating by links. Also, inline styles in READMEs often fail contrast checks; lightening text to meet WCAG AA is essential.
**Action:** Always check contrast on inline styles and context on repeated links.
