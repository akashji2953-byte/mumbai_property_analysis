# Mumbai Property Market Analysis

**PGDM Project | Business Analytics & Marketing**

I analyzed 9,514 sale, rental, and paying guest (PG) listings to compare asking prices across Mumbai and surrounding areas. The project shows how real estate teams can benchmark listings and shortlist areas for different buyer budgets.

## What I Built

- Locality-wise pricing dashboard with Budget, Mid, Premium, and Luxury tiers
- Random Forest model to estimate asking price per sq. ft. and flag listings for review
- Locality-wise 2 BHK gross rental yield estimates and an Excel summary report

## Key Findings

- Median sale asking price was ₹23,420 per sq. ft. and median advertised rent was ₹55,000 per month.
- The Random Forest model achieved an R² of 0.756 on the log price-per-sq.-ft. target.

The dataset covers listings posted from May 2022 to August 2023. Results reflect historical asking prices.

## How to Run

Open `mumbai_property_analysis.ipynb` in Google Colab. Upload the source CSV as `8b83c0af-mumbai.csv` and select **Runtime → Run all**. The dashboard and Excel report are saved in `outputs/`.

**Tools** — Python, pandas, Matplotlib, Seaborn, and scikit-learn.
