# Doctor Tracker - Standalone HTML Prototype

This folder contains the 100% pure client-side Raw HTML/CSS/Vanilla JavaScript version of the Doctor Tracker application.

## Key Features
- **Zero inline styles** (`style="..."`) and **zero internal `<style>` tags**.
- **100% external modular CSS** (`assets/css/style.css`, `dashboard.css`, `auth.css`).
- **100% responsive** across mobile, tablet, and desktop/laptop viewports.
- **Client-side state management** using LocalStorage and preloaded clinical datasets in `assets/js/data.js`.
- **Chart.js data visualizations** on `dashboard.html`.

## Pages Included
- `index.html`: Entry point that routes to `login.html` or `dashboard.html`.
- `login.html`: Admin login with password toggle and 1-click demo credentials (`admin@doctor-tracker.com` / `admin123`).
- `dashboard.html`: Executive dashboard with 4 KPI metrics, 4 Chart.js charts, recent admissions, and top active specialists.
- `doctors.html`: Doctor directory with multi-field search, specialization and hospital filters, date-wise filter, pagination, and Add/Edit/Delete modals.
- `doctor-details.html`: Dedicated doctor profile view showing assigned patient rosters, status breakdown, and quick add/delete patient operations.
- `patients.html`: Comprehensive patient registry with search, condition filters (Critical, Stable, Under Observation, Recovered), doctor assignments, room numbers, and Edit/Delete modals.

## How to Run
Simply open any `.html` file directly in a modern web browser, or run a local HTTP server:

```bash
# From within the frontend-html directory:
cd frontend-html
php -S localhost:3000
# or: npx serve .
```
Then visit `http://localhost:3000`.
# doctor-tracker-frontend
