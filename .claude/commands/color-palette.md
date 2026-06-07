# Color Palette Generator

Generate a complete, harmonious color palette for a web project.

Given a brand color or description, produce:

1. **Primary scale** — 50 through 950 (light to dark), with CSS custom properties
2. **Semantic tokens**:
   - `--color-bg`, `--color-surface`, `--color-border`
   - `--color-text-primary`, `--color-text-secondary`, `--color-text-muted`
   - `--color-accent`, `--color-accent-hover`
   - `--color-success`, `--color-warning`, `--color-error`, `--color-info`
3. **Dark mode variants** using `@media (prefers-color-scheme: dark)`
4. **Tailwind config snippet** if applicable

Ensure all text/background combinations meet WCAG AA contrast (4.5:1 for normal text).

Show a visual preview using colored `div` blocks in HTML so the palette can be seen at a glance.

$ARGUMENTS
