# CodeAlpha Data Visualization — Nigerian Equipment Marketplace

This repository contains **Task 3** of my CodeAlpha Data Analytics internship. It turns equipment marketplace data into charts and a summary dashboard to communicate patterns in categories, location, condition, and advertised pricing.

## Business question

**What does the marketplace's listed equipment inventory reveal about category representation, geographic concentration, and advertised prices?**

## Tools and libraries

- Python
- pandas and NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Visualizations

The notebook builds eight visual outputs:

1. Equipment listings by category
2. Equipment listings by region
3. Equipment listings by condition
4. Availability of advertised prices
5. Distribution of advertised sale prices
6. Median advertised sale price by category
7. Equipment listings by category and region
8. Marketplace summary dashboard

## Selected insights

- The dataset contains **158 approved equipment listings**.
- Lagos (84 listings) and Abuja / FCT (65) together account for **94.3%** of listings.
- Used - Excellent (78 listings) and Brand New (73) account for 95.6% of listings, based on seller-reported condition.
- 129 listings (81.6%) have at least one advertised price; rental rates are much less common than sale prices.
- Among 119 listings with a sale price, the median is approximately **₦6.0 million**. The mean is higher because a small number of expensive listings pull the distribution upward.
- Median advertised prices vary considerably by category. These are listing-level asking prices, not verified transaction prices.

The results represent the collected listings on this platform and should not be interpreted as a census of Nigeria's equipment market or as proof of demand.

## Expected input

The notebook reads `nigerian_equipment_marketplace_cleaned.csv` from the working directory. This cleaned dataset is produced during the analysis workflow; place it beside the notebook before running it.

## Run locally

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

Run the notebook cells in order. Chart images are written to a `charts/` directory.

## Internship

Completed as part of the **CodeAlpha Data Analytics Internship** — Task 3: Data Visualization.
