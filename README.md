# Chatter

A responsive landing page for Chatter, a blogging platform for readers and writers. Built with semantic HTML and plain CSS, no frameworks or build step.

## Preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8077
```

Then visit http://localhost:8077.

## Project structure

```
chatter/
├── index.html
├── css/
│   └── style.css
└── assets/
    ├── icons/     # feature icons (SVG)
    └── images/    # hero, library and people photos
```

## Design tokens

Defined as CSS variables at the top of `css/style.css`.

| Token      | Value        | Use                         |
| ---------- | ------------ | --------------------------- |
| `--purple` | `#543EE0`    | Logo, buttons               |
| `--cream`  | `#FFEDCC80`  | Testimonial and footer bg   |
| `--ink`    | `#111111`    | Text                        |

Font: [DM Sans](https://fonts.google.com/specimen/DM+Sans), loaded from Google Fonts.

## Sections

Header and navigation, hero, about, features, testimonial, call to action and footer.

## Responsive behavior

- **Desktop:** full layout, designed for a 1440px container.
- **Tablet (up to 1024px):** tighter gutters and a stacked about section.
- **Mobile (up to 720px):** single column, with the navigation collapsing into a burger menu. The menu is CSS-only, using a checkbox, so it needs no JavaScript.
