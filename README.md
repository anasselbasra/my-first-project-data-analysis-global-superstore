# Global Superstore Data Analysis

This repository documents my first end-to-end data analysis project using the **Global Superstore** dataset (2011–2014). The work walks through data acquisition, cleaning, transformation, exploratory analysis, and visualization to surface sales and profit insights across regions, markets, and product categories.

## Repository Contents
- `El Basraoui_Anass.ipynb`: Jupyter notebook containing the full workflow, including cleaning steps, feature exploration, and visualizations.
- `Global Superstore.xls`: Raw dataset used in the analysis.
- `assets/`: Exported visualizations referenced throughout the notebook and README.

## Environment Setup
1. Install Python 3.9+.
2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirement.txt
   ```
4. Launch the notebook to explore or extend the analysis:
   ```bash
   jupyter notebook "El Basraoui_Anass.ipynb"
   ```

## Key Insights & Visuals
The notebook details revenue and profit trends by time, geography, and product category. Highlighted visuals include:

| Visualization | Description |
| --- | --- |
| ![Annual revenue evolution](assets/Evolution%20of%20Sales.png) | Year-over-year sales growth, showing seasonality and overall trajectory. |
| ![Turnover vs profit per country](assets/Turnover%20vs%20Profit%20per%20Country%20(Annual%20Aggregates).png) | Relationship between annual turnover and profit by country, revealing markets with negative or low profitability despite high revenue. |

## Notebook Workflow
1. **Exploratory Data Analysis:** Inspect schema, quantify missing values, and review categorical distributions.
2. **Filtering & Transformation:** Remove non-informative columns, derive aggregates, and focus on markets/countries with meaningful contributions to revenue.
3. **Revenue Analysis:** Track revenue over time and identify top-performing countries and cities.
4. **Profit Analysis:** Compute profit margins, identify profitability leaders/laggards, and compare revenue vs. profit correlation.
5. **Product Insights:** Evaluate category-level contributions and product-level revenue/profit concentration.

## How to Reproduce
- Run the notebook sequentially to regenerate all figures and statistics.
- Modify filters (e.g., revenue thresholds or year ranges) within the notebook to tailor the analysis to specific regions or time periods.
- Export additional plots to `assets/` for inclusion in presentations or reports.

## Acknowledgements
Project authored by **Anass El Basraoui** (November 13, 2021) as an early exploration of data-driven business insights.
