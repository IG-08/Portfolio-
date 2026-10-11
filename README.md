# Ishwarya Gandamsetty — Portfolio

Personal data analyst portfolio site: a single-page React app showcasing projects, skills, education, and contact info.

**Live:** [portfolio-ishwarya6.vercel.app](https://portfolio-ishwarya6.vercel.app)

## Stack

- React 18 + Vite 5
- No CSS framework — inline styles throughout
- Fonts: [Poppins](https://fonts.google.com/specimen/Poppins) (headings) and [Nunito](https://fonts.google.com/specimen/Nunito) (body), loaded via Google Fonts

## Structure

```
src/
  main.jsx        # Vite entry point
  App.jsx         # Renders <Portfolio />
  Portfolio.jsx   # The entire site: nav, hero, about, skills,
                  # background, projects, contact — one component
public/
  images/                             # Portrait and other static images
  yelp-teardown-case-study.html       # Standalone write-up for the Yelp
                                      # teardown project, served as a
                                      # static page (see Projects below)
```

## Running locally

```bash
npm install
npm run dev       # starts the Vite dev server
npm run build     # production build to dist/
npm run preview   # preview the production build locally
```

## Projects featured

Each project links out to its own GitHub repo and live dashboard/demo rather than being hosted inside this repo:

| Project | Repo |
|---|---|
| Olist e-commerce analytics | [olist-project](https://github.com/IG-08/olist-project) |
| NC State budget analysis | [nc-budget-analysis](https://github.com/IG-08/nc-budget-analysis) |
| IPL 2025 season analysis | [ipl-2025-analysis](https://github.com/IG-08/ipl-2025-analysis) |
| SafeBites | [safebites](https://github.com/IG-08/safebites) |
| Yelp product teardown | [yelp-product-teardown](https://github.com/IG-08/yelp-product-teardown) |

The Yelp teardown's standalone HTML write-up (`public/yelp-teardown-case-study.html`) is a duplicate kept here for the portfolio's live link; the source of truth for that write-up lives in the `yelp-product-teardown` repo.

## Deployment

Deploys automatically to Vercel on every push to `Master`.
