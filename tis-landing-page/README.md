# TIS LTD — Training & Inspection Services Landing Page

A responsive landing page built for **Training and Inspection Services LTD**, a UK-based oil & gas inspection and training company, as a front-end training assignment.

🔗 **Live design reference:** built from a Figma/Adobe XD style mockup provided for this assignment.

## Preview

The page includes:
- Sticky header with navigation
- Hero section with call-to-action buttons
- API Courses card grid
- About section
- News/blog showcase grid
- "Trusted by agency and store" testimonial carousel section
- Email signup call-to-action
- Footer with contact info and social links

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, Flexbox, CSS Grid, mobile-first media queries
- **Vanilla JavaScript** — mobile nav toggle
- No frameworks, no build step — just open `index.html` in a browser.

## Folder Structure

```
tis-landing-page/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    ├── images/
    │   └── (hero, course, news, avatar, and logo graphics)
    ├── icons/
    │   └── (SVG UI icons — nav, social, arrows, etc.)
    └── fonts/
        └── README.md (font-loading notes)
```

## Responsive Breakpoints

Built mobile-first with two media query breakpoints:

| Breakpoint | Width           | Layout                                   |
|------------|-----------------|-------------------------------------------|
| Mobile     | `< 768px`       | Single column, stacked sections, hamburger nav |
| Tablet     | `≥ 768px`       | Two-column grids, inline navigation      |
| Desktop    | `≥ 1024px`      | Three-column course grid, wider spacing  |

## Running Locally

Clone the repo and open `index.html` directly in your browser:

```bash
git clone https://github.com/oyewolephilip-analytics/tis-landing-page.git
cd tis-landing-page
open index.html   # or just double-click the file
```

## Notes

- Images are custom SVG illustrations built to match the visual style of the original design (rig, dockyard, and industrial scenes) rather than licensed stock photography.
- Fonts: [Poppins](https://fonts.google.com/specimen/Poppins) and [Inter](https://fonts.google.com/specimen/Inter), loaded via Google Fonts CDN. See `assets/fonts/README.md` for self-hosting instructions.

## Author

Built by [Oyewole Philip](https://github.com/oyewolephilip-analytics) as a front-end development training assignment.
