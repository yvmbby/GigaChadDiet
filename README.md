# Fuel & Feast

A single-file, no-backend, animal-based meal and grocery budget planner for GitHub Pages.

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Create a public GitHub repository (for example `fuel-feast`).
2. Upload `index.html` to the repository root and commit.
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)** and save.
4. Open the Pages URL shown by GitHub after deployment.

## Important assumptions

- Grocery prices are transcribed from the user's October 14, 2026 screenshot; they are not live prices.
- The $134.53 Steak Lover's Combo contains 40 oz total. The current planner rounds up to whole bundles; leftovers aren't optimized between planning periods.
- Unpriced produce, fruit and pantry items use editable budget estimates.
- Protein rotations are heuristics, **not** a mathematical minimum-cost optimizer. Cheapest balanced means the least expensive of the three built-in templates, not the global optimum.
- Meal nutrition is not calculated from USDA or packaging data. Calories and protein displayed are **targets**, not verified meal totals.
- The calorie estimate uses the male Mifflin–St Jeor equation, activity multipliers, and a user-selected surplus. It is only a starting estimate.
- If using dairy, pasteurized alternatives are safer than raw dairy.
