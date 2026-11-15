# my-first-webpage

## Milestone 3: Accessibility & Visual Design

### Accessibility Fixes (WAVE & WebAIM Contrast Checker)
- Updated the footer and secondary card paragraph text colors to `#d4d4d8` so all text passes WCAG AA contrast requirements (11.4:1 contrast ratio against `#202024`).
- Changed the primary button background to `#00875f` with `#ffffff` text so interactive buttons pass WCAG AA contrast (4.6:1 contrast ratio).
- Added descriptive `alt` text to the homepage image so screen readers can describe the visual content.
- Standardized the heading hierarchy across all three pages (`h1` for the site title, `h2` for section headings, and `h3` for sub-articles) to prevent skipped heading levels.
- Added explicit `<label>` elements, `<fieldset>` and `<legend>` groupings, and `aria-invalid` / `role="alert"` error states to the contact form on `about.html`.

### Visual Design & Gestalt Principles
- **Proximity:** I used spacing and grid gaps (`24px`) to group related headings, descriptions, and links inside separate sections while keeping unrelated cards clearly separated.
- **Common Region:** I placed each content block and form section inside bordered `#202024` containers with rounded corners so users can easily distinguish separate groups of information.
- **Similarity:** I applied a consistent dark color palette (`#121214` background, `#202024` cards, `#8257e5` purple accents, and `#00875f` green action accents) and matching card styles across all three pages.
