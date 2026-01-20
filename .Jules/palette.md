## 2024-05-23 - GitHub Profile README Constraints
**Learning:** This repository is a GitHub Profile README (`README.md` with embedded HTML). GitHub's Markdown renderer aggressively sanitizes HTML, stripping `<style>` blocks, inline `style` attributes (often), and event handlers like `onmouseover`.
**Action:** When suggesting UX improvements, prioritize standard Markdown or very basic HTML (tables, align attributes). Avoid relying on complex CSS or JS interactions as they likely won't render for the end user on GitHub. Focus on Accessibility (alt text, contrast) which is always preserved.
