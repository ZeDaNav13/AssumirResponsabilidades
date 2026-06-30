# Changelog

All notable changes to this project are tracked here.

## 2026-06-30

### `6908e79` - Update titles collective dashboard
- Added `mandatos.csv` to track presidential mandate start dates.
- Added mandate-based background bands and president chips to the main chart.
- Renamed the visible product copy and page title to `Títulos Colectivos`.
- Reworked the lower dashboard cards, footer credits, and CSV link panel.
- Updated the dataset and filtering/presentation logic to match the current site structure.

## 2026-06-10

### `1ee76f3` - Update site for current competition dataset
- Refreshed `data.csv` with the latest competition records.
- Updated the dashboard logic to support the newer dataset structure, including president-aware filtering and rendering adjustments.

## 2026-05-10

### `b82a645` - Set SLB favicon and update page title metadata
- Added the SLB favicon reference.
- Updated page metadata/title settings.

### `6676ca5` - Fix desktop clipping by removing 100vh lock layout
- Removed the fixed desktop-height layout that caused clipping on larger screens.

### `f37241f` - Polish dashboard visuals and add title metric toggles
- Refined the dashboard visual design.
- Added chart metric toggles for percentage versus titles.
- Added the `slb-logo-new.svg` asset.

### `5a1b07f` - New data
- Applied a small dataset update to `data.csv`.

### `38bcc92` - Support headerless CSV input for dashboard parser
- Made the CSV parser tolerant of headerless input.

### `3c45d57` - Harden CSV loading with fallback paths for GitHub Pages
- Added fallback CSV fetch paths to improve GitHub Pages compatibility.

### `2c31d8e` - Update dataset for latest entries
- Refreshed `data.csv` with a larger competition data update.

### `375701b` - Build GitHub Pages-ready dashboard with CSV filters and season range
- Replaced the initial placeholder page with the interactive dashboard.
- Added CSV-driven data loading, filters, and season range controls.
- Added the first chart, breakdown cards, and GitHub Pages-ready structure.

## 2026-05-09

### `5da580e` - Add Hello Benfica to index.html
- Created the initial page placeholder in `index.html`.
