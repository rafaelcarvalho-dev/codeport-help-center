# Codeport Help Center

A landing page for the help center of **Codeport**, a fictional API tool. It features a search bar and category cards that guide users to the main support topics.

> **Note:** Codeport is a fictional product. This project was created for study purposes only.

Built with HTML and CSS only.

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

> The page content is in Brazilian Portuguese. Links are placeholders (`#`) since the product is fictional.

## Author

**Rafael Carvalho** — [GitHub](https://github.com/rafaelcarvalho-dev) · [LinkedIn](https://www.linkedin.com/in/rafael-carvalho-95860a3b0/)
