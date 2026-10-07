# Gold Gym - Midterm Project

Responsive six-page fitness club website created by **Yelnur Akhmetzhan, Akejan Ahmetov and Alikhan Yertaiuly** (AITU, SE-2504).

**Live site:** https://YOUR-USERNAME.github.io/YOUR-REPO/  <!-- replace after enabling GitHub Pages -->

## Team and pages

| Member | Role | Pages |
| --- | --- | --- |
| Yelnur Akhmetzhan | Frontend Developer | `index.html`, `about.html` |
| Akejan Ahmetov | UI & CSS Developer | `prices.html`, `trainers.html` |
| Alikhan Yertaiuly | Content & QA Developer | `locations.html`, `contact.html` |

## Page features

| Page | Features |
| --- | --- |
| Home | Responsive typography, CSS-only 3-card group (media queries, Flexbox inside cards), Bootstrap grid hero |
| About | Two-column grid (`col-lg-6`), Bootstrap cards with circular team photos |
| Prices | Responsive table, `btn-group`, button sizes and disabled state, Flexbox utilities |
| Trainers | Bootstrap card grid (`row-cols-*`), Flexbox card bodies with equal height |
| Locations | Nine-image carousel, three-column grid (`col-lg-4`), `container-fluid` |
| Contact | Bootstrap form: `form-control`, `input-group`, `form-select`, radio buttons, checkbox |

## Technologies

HTML5 semantic elements, CSS media queries (breakpoints 576 px and 992 px), CSS Grid, Flexbox, Bootstrap 5.3.3 from the official CDN (grid, spacing utilities, navbar, buttons, carousel, cards, form controls). The gold theme is applied to Bootstrap through its own CSS variables (`--bs-btn-*`, `--bs-link-color-rgb`), so Bootstrap components keep their standard classes (`btn-warning`, `btn-outline-warning`).

## Structure

```
index.html  about.html  prices.html  trainers.html  locations.html  contact.html
css/styles.css
images/
```

## How to run

Open `index.html` in a browser (internet is needed for the Bootstrap CDN), or publish the repository root with GitHub Pages (Settings, Pages, Deploy from a branch, `main`, `/ (root)`). All project files use relative paths.

## Accessibility

Semantic `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`; `alt` text on every image; `label` for every form field; `aria-label` on the navigation and its toggle button; visually hidden text on carousel controls; text contrast is above 6.8:1 everywhere.
