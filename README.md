# CodeAlpha Task 3: Data Visualization
## Nigerian Equipment Marketplace

This repository contains **Task 3 — Data Visualization** for the CodeAlpha Data Analytics Internship. It transforms the cleaned marketplace dataset into charts and a summary dashboard showing the distribution of equipment listings, location, seller-reported condition, and advertised prices.

## Business question

**What do the equipment listings on this marketplace reveal about category representation, geographic concentration, and advertised price availability?**

## Repository contents

| File | Purpose |
|---|---|
| [`Task 3_Data Visualization.ipynb`](Task%203_Data%20Visualization.ipynb) | Code and written interpretation for eight visualizations |
| [`data/nigerian_equipment_marketplace_cleaned.csv`](data/nigerian_equipment_marketplace_cleaned.csv) | Cleaned dataset from Task 2 (158 equipment listings) |
| [`01_listings_by_category.png`](charts/01_listings_by_category.png) | Listings by equipment category |
| [`02_listings_by_region.png`](charts/02_listings_by_region.png) | Listings by region |
| [`03_listings_by_condition.png`](charts/03_listings_by_condition.png) | Seller-reported equipment condition |
| [`04_price_availability.png`](charts/04_price_availability.png) | Availability of sale and rental prices |
| [`05_sale_price_distribution.png`](charts/05_sale_price_distribution.png) | Advertised sale-price distribution |
| [`06_median_price_by_category.png`](charts/06_median_price_by_category.png) | Median sale price by category |
| [`07_category_region_heatmap.png`](charts/07_category_region_heatmap.png) | Category-by-region listing counts |
| [`08_summary_dashboard.png`](charts/08_summary_dashboard.png) | Summary dashboard |
| [`requirements.txt`](requirements.txt) | Python dependencies |

## Visualizations

The notebook creates eight outputs:
1. Equipment listings by category
2. Equipment listings by region
3. Equipment listings by condition
4. Availability of advertised prices
5. Distribution of advertised sale prices
6. Median advertised sale price by category
7. Listings by category and region
8. Marketplace summary dashboard

## Selected insights

- **Category representation:** Transport & Logistic (32), Construction & Infrastructure (26), and Agriculture & Mining (21) account for half of the 158 listings.
- **Geographic concentration:** Lagos (84 listings) and Abuja / FCT (65) account for 94.3% of the sample.
- **Condition:** Used - Excellent (78) and Brand New (73) account for 95.6% of listings; condition is seller-reported and not independently verified.
- **Price coverage:** 129 listings (81.6%) show at least one advertised price; 119 (75.3%) show a sale price. Rental rates are much less common.
- **Sale prices:** Among 119 listings with a sale price, the median is approximately **₦6.0 million**. A small number of expensive listings pull the mean upward.

The findings describe advertised listings captured from this platform. They are not a census of Nigeria's equipment market, evidence of completed sales, or proof of market demand.

## Run locally

Python 3.10 or newer is recommended.

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Keep `data/nigerian_equipment_marketplace_cleaned.csv` in the `data/` directory. From the repository root, run `Task 3_Data Visualization.ipynb` from top to bottom. The notebook saves generated images into a `charts/` folder when run locally. The pre-generated PNG files are also linked above for quick review.

## Project sequence

- **Task 1 — Web Scraping:** [CodeAlpha_WebScraping](https://github.com/EmmanuelChukwuka001/CodeAlpha_WebScraping)
- **Task 2 — Exploratory Data Analysis:** [CodeAlpha_ExploratoryDataAnalysis](https://github.com/EmmanuelChukwuka001/CodeAlpha_ExploratoryDataAnalysis)
- **Task 3 — Data Visualization:** this repository

*CodeAlpha Data Analytics Internship · Task 3: Data Visualization*


## Folder layout

- `data/` — cleaned CSV input
- `charts/` — eight generated visualization images
- `Task 3_Data Visualization.ipynb` — visualization notebook
