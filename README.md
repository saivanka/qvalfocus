# QvalFocus

The original QvalFocus consulting website, migrated from static HTML pages to a React + TypeScript + Vite app. It presents a consulting firm's pages (home, about, services, features, advisors, blog, reviews, contact) with React Router navigation.

## What it is

- A consulting-website front end in React 18 + TypeScript, built with Vite and Tailwind CSS
- Pages and routes live under `src/pages/` and `src/routes/`; shared UI under `src/components/`
- The repo root still contains the pre-migration static pages (`index.html`, `about.html`, `service.html`, `feature.html`, `advisor.html`, `blog.html`, `review.html`, `contact.html`, `single.html`) and a `mail/` folder from the static site
- Note: `node_modules/` is committed in this repo, which accounts for most of its size

## Tech stack

- React 18 + TypeScript + Vite, React Router 6, Tailwind CSS, ESLint

## How to run

```bash
npm install
npm run dev      # vite
npm run build    # tsc && vite build
npm run lint     # eslint
npm run preview  # vite preview
```

## Project structure

```
src/App.tsx       # App entry with routes
src/main.tsx      # Vite entry point
src/pages/        # Page components
src/routes/       # Route definitions
src/components/   # Shared components
index.html        # (legacy) static home page, also present at repo root
about.html, service.html, feature.html, advisor.html, blog.html, review.html, contact.html, single.html  # legacy static pages
mail/              # Legacy mail-related files from the static site
public/img/        # Images
```
