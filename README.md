## Cursor Landing Page Recreation

This project is a static recreation of the main marketing page for Cursor, built with plain HTML and CSS.


## 📸 Preview

![Cursor landing page – desktop](assets/desktop.png)

### Recreated Sections

- **Header & Navigation**: Top navigation bar with logo, product links, and primary actions (`Sign in`, `Download`).
- **Hero**: Main headline describing Cursor and a primary `Download for macOS` call-to-action, plus a hero product image.
- **Trusted by logos**: Strip showcasing trusted-by companies in card-style logo tiles.
- **Product feature bands**: Three alternating feature sections (Agent, Autocomplete, Everywhere software gets built) with text and accompanying product imagery.
- **Testimonials**: Grid of testimonial cards with quotes, avatars, names, and roles.
- **Frontier use cases**: Three-card layout highlighting models, codebase understanding, and enterprise use cases.
- **Changelog**: Version/date cards and a link to see what’s new in Cursor.
- **Research panel**: Split layout about Cursor as an applied research team with a large team photo.
- **Recent highlights**: List of recent posts with title, short description, and meta category/date.
- **Final CTA**: Centered call-to-action encouraging users to try Cursor, with a download button.
- **Footer**: Multi-column footer with product/resources/company/legal/connect links, plus bottom metadata, theme toggle, and language selector.

### Fonts Used

- **Primary display and UI font**: `Cursor Gothic`
  - Loaded via `@font-face` from `assets/fonts/CursorGothic-*.woff2`.
  - Used for headings, body text, navigation, buttons, and footer (`var(--font-cursor)`).
- **System fallbacks**: `system-ui`, `-apple-system`, `BlinkMacSystemFont`, `"Segoe UI"`, `Roboto`, `sans-serif` via `var(--font-sans)` and the fallback stack in `var(--font-cursor)`.

### Colors Used

Core colors are defined as CSS custom properties in `styles.css`:

- **Backgrounds**
  - Main page background: `#13120A` (`--color-bg`)
  - Section cards and panels: `#18160d`, `#1B1912`, `#201E18`, `#26241E`
- **Text**
  - Primary text: `#ffffff` (`--color-text`)
  - Muted/secondary text: `#a3a3a3` (`--color-text-muted`)
- **Buttons**
  - Primary button background: `#e5e5e5` (`--color-btn-primary-bg`)
  - Primary button text: `#0d0d0d` (`--color-btn-primary-text`)
  - Primary hover background: `#f5f5f5` (`--color-btn-primary-hover`)
- **Accent color**
  - Links and CTAs inside feature/frontier/changelog/highlights sections: `rgb(245, 78, 0)`

These colors combine to create a dark, high-contrast UI with light CTAs and orange accent links, closely matching the original Cursor marketing site.
