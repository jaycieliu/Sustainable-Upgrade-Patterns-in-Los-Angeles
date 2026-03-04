# Sustainable Upgrade Patterns in Los Angeles Neighborhoods (2013–2023)

A data + dashboard project that analyzes LA building permit records to measure *who adopts sustainable home upgrades*, *what types*, and *where adoption clusters*—with a focus on **rooftop solar**, **EV chargers**, and **energy-efficiency retrofits**.

## Why this project matters

Clean-energy adoption is visible in permit activity—but it’s not evenly distributed.
This project surfaces **adoption gaps**, **geographic hotspots**, and **income-linked differences** to support decision-making for policy, programs, and real estate / community planning.

## What I built

- A reproducible pipeline to turn **unstructured permit text** into structured green-upgrade categories (**SOLAR / EV_CHARGER / ENERGY_EFFICIENT**)
- An analysis-ready dataset integrating **LA permits + census-tract income**
- An interactive **Streamlit dashboard** to explore trends, geography, and equity patterns

## Key findings (high-level)

- **Solar dominates** the sustainable-upgrade volume and drives most growth over time (notably 2020–2022).
- Adoption is **geographically clustered** (Westside / coastal / parts of the Valley), with relative underrepresentation in **South LA / East LA**.
- Clear **income-linked split**: higher-income tracts skew toward **solar + EV chargers**, while lower-income tracts show relatively more **energy-efficiency** upgrades.
- Valuation medians are broadly similar across groups, but lower-income areas show **wider dispersion** and larger retrofit outliers.

## Key outputs

- Cleaned + labeled dataset (green permits with income group + geo)
- Trend analysis and maps (year, type, neighborhood)
- Dashboard-ready views for segmentation and exploration
- Reproducible notebook workflow

## Quick links

- **Dashboard:** `app/streamlit_app.py` (run locally)
- **Full report:** `reports/Sustainable_Upgrade_Patterns_LA.pdf`
- **Notebook:** `notebooks/01_green_permits_eda.ipynb`
- **Figures:** `assets/figures/` (charts + maps)

***

## Tech Stack

- Languages: Python, SQL
- Libraries: pandas, NumPy, matplotlib / seaborn, Streamlit
- Data: Snowflake (Snowpark) + Census tract income
