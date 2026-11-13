# Codeport Help Center

A landing page for the help center of **Codeport**, a fictional API tool. It features a search bar and category cards that guide users to the main support topics.

> **Note:** Codeport is a fictional product. This project was created for study purposes only.

Built with HTML and CSS only.

## Live demo

[rafaelcarvalho-dev.github.io/codeport-help-center](https://rafaelcarvalho-dev.github.io/codeport-help-center/)

## Features

- Header with navigation links ("Send a request" and "Sign in")
- Hero section with the headline "Como podemos ajudar?" and a search form
- Six help category cards:
  - Getting started
  - Managing your account
  - Managing projects and teams
  - Plans and billing
  - Authentication and API keys
  - Codeport support
- Footer with four link columns (Codeport, Resources, Community, Company) and contact info
- Mobile-first responsive layout

## Responsive behavior

The layout is built mobile-first and adapts with `min-width` breakpoints:

| Breakpoint | Layout |
| --- | --- |
| Default | Single-column cards and stacked footer |
| `600px` | Two-column layout |
| `970px` | Wider layout adjustments |
| `1200px` | Full desktop layout |

## Highlights

- Semantic HTML (`header`, `nav`, `main`, `article`, `section`, `footer`, `address`)
- `lang="pt-br"`, a descriptive `title` and a `meta description` for search engines
- Accessible search form with a visually hidden `label`
- Decorative icons use empty `alt` text; the search button icon has a descriptive `alt`
- Layout with Flexbox and CSS Grid
- SVG icons for crisp rendering at any size

## Running locally

No build step is needed.

```bash
git clone https://github.com/rafaelcarvalho-dev/codeport-help-center.git
cd codeport-help-center
```

Then open `index.html` in your browser.

## Project structure

```
codeport-help-center/
├── index.html
├── style.css
└── assets/
    └── *.svg
```

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, media queries)
- Deployed with GitHub Pages

> The page content is in Brazilian Portuguese. Links are placeholders (`#`) since the product is fictional.

## Next steps

- Add JavaScript interactivity (for example, filtering the category cards from the search bar)
- Give each repeated "Saiba mais" link a descriptive `aria-label`, so screen reader users know which topic it opens

## Credits

Visual reference: the Abstract help center page from Front End Practice. The code is my own implementation, written for study purposes.

## Author

**Rafael Carvalho** — [GitHub](https://github.com/rafaelcarvalho-dev) · [LinkedIn](https://www.linkedin.com/in/rafael-carvalho-95860a3b0/)
