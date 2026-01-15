# Asset Depreciation Web App

A clean, modern single-page web application to calculate and visualize asset depreciation.

## Features

- **Asset Management**: Add, track, and remove assets.
- **Persistence**: Assets are saved to your browser's Local Storage, so you won't lose data on refresh.
- **Depreciation Modes**:
  - **Straight-Line**: Equal depreciation over the asset's life.
  - **Declining Balance**: Accelerated depreciation (Double Declining Balance).
- **Reports**:
  - **Individual Schedules**: Detailed year-by-year breakdown of Depreciation, Book Value, and Monthly impact.
  - **Monthly Aggregate**: A consolidated view of your total monthly depreciation expenses over time.
  - **Smart Grouping**: The monthly report groups consecutive months with identical values for better readability.

## Usage

1. Open `index.html` in any modern web browser.
2. The app comes pre-seeded with sample data for demonstration.
3. Use the form to add new assets.
4. Switch tabs to view specific Depreciation Schedules or the Aggregate Monthly Report.

## Installation

No installation required. Just clone the repo and open the file.

```bash
git clone https://github.com/aneuhaus/asset-deprec-html.git
open index.html
```

## Technologies

- HTML5
- CSS3 (Vanilla, Responsive, Dark Mode)
- JavaScript (ES6+, LocalStorage)
