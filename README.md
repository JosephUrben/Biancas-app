# Bianca Pilates — Studio Planner Prototype

A mobile-first, installable web-app prototype for a Pilates instructor or small studio.

## What is included

- Dashboard with upcoming classes and studio metrics
- Lesson planner with date, time, duration, level, client, goal and notes
- Visual lesson sequence builder with move-up, move-down and remove controls
- Pose library with 12 original SVG pose illustrations
- Search and filters by level and focus
- Custom pose creation with image upload
- Client records with goals, considerations and attendance totals
- Mark lessons complete and retain teaching notes
- JSON backup/import and CSV lesson-history export
- Local browser storage
- Offline support through a service worker
- Responsive desktop and mobile navigation

## Prototype data and privacy

This version is deliberately backend-free. Data is saved only in the browser's `localStorage`. Uploaded pose images are stored as browser data URLs, so small images are recommended.

Do not use the prototype for real sensitive health information. A production version should use authenticated accounts, encrypted storage, access controls, a privacy policy, consent workflows and appropriate data-retention controls.

## Run locally

Open `index.html` directly, or run a simple local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy with GitHub Pages

The included workflow publishes the repository through GitHub Pages after every push to `main`.

In the repository, open **Settings → Pages** and set **Source** to **GitHub Actions** if it is not already selected.

## Suggested next build

1. Confirm Bianca's brand name, logo, colours and teaching method.
2. Replace sample illustrations with approved photography or custom diagrams.
3. Add authentication and a cloud database.
4. Add recurring classes, bookings, attendance and payment status.
5. Separate general teaching notes from health or injury information.
6. Test the lesson builder with real class-planning workflows before adding complexity.
