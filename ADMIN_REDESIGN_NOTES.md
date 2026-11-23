# Zentrixx Admin UI redesign

This update is a presentation-only redesign. Existing route definitions, Redux actions, API calls, event handlers, form fields, validation, and business logic have not been intentionally changed.

## What changed
- Added `src/admin-redesign.css`, a shared visual layer for the existing admin screens.
- Imported the stylesheet from `src/App.js` so it applies consistently to all admin routes.
- Updated the existing dashboard shell, sidebar, headers, tables, search areas, forms, cards, login/signup screens, and mobile navigation drawer styling.
- Kept the existing navigation and mobile drawer interaction in place.

## Run
```bash
npm install
npm start
```

The redesign uses the existing component structure and existing dependencies. No new runtime dependency was added.
