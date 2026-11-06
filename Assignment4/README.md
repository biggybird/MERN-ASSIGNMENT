# Portfolio v2 · Assignment 4

A refreshed, responsive portfolio for **Sarthak Budhaulia**, built with semantic HTML and an external CSS stylesheet.

## Files

- `index.html` — portfolio structure and content.
- `style.css` — layout, responsive styling, typography, and colour system.

## Design Choices

### Fonts
- **Space Grotesk** is used for headings because its geometric letterforms give the portfolio a modern, technology-focused identity.
- **Inter** is used for body text because it stays readable across paragraphs, cards, and smaller screens.

### Colour palette
The design uses a focused five-colour palette:
- Deep green (`#173f3a`) for strong headings, buttons, and the contact section.
- Teal (`#2c8c78`) for links and interactive accents.
- Lime (`#c8f169`) for small highlights.
- Off-white (`#f5f7f6`) for the main background.
- White (`#ffffff`) for cards and content surfaces.

### CSS structure
- CSS custom properties in `:root` store the colour palette, font families, font sizes, spacing, and layout values.
- Element selectors style base typography and links.
- Class selectors style reusable components such as cards and buttons.
- ID selectors target the main portfolio sections.
- Descendant selectors style nested navigation and project content.
- Pseudo-classes such as `:hover` and `:focus-visible` provide interactive feedback.

## Features

- Responsive layout for desktop and mobile screens.
- Sticky navigation with section links.
- Skills, education, college/course, projects, socials, and contact sections.
- Project previews for ByteForge and Brainrot Dictionary.
- External Google Fonts and external `style.css`.

## Run locally

Open `index.html` in a browser. An internet connection is needed to load Google Fonts and the embedded project previews.
