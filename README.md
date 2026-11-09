# Zambia's Staple Food Prices: From Drought to Recovery (2022–2026)

How did the prices of mealie meal and maize change through Zambia's 2024 drought, and who still pays the most? This project tracks three staple foods across four years using official data from the Zambia Statistics Agency (ZamStats).

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/roykamwanza/zambia-food-prices/blob/main/zambia_food_prices.ipynb)

![Breakfast mealie meal: price paid vs. real cost](charts/02_real_vs_price.png)

## Headline finding

**The hardest time to afford mealie meal was not when prices were highest.** The price of a 25 kg bag of breakfast mealie meal peaked at K364 in March 2025. But adjusted for inflation, it was least affordable almost a year earlier, in **April 2024** (K412 in October 2026 Kwacha). Today, all three staples are cheaper in real terms than they were in December 2022.

## Key findings

1. **Prices peaked in early 2025, then fell sharply.** Breakfast mealie meal fell from K364 (March 2025) to K236 (October 2026), about 35% lower. Maize grain fell more than 50% from its February 2025 peak.
2. **Affordability turned before prices did.** In real terms, breakfast mealie meal was hardest to afford in April 2024.
3. **Staples are now more affordable than four years ago.** In real terms, breakfast mealie meal is about 10% cheaper than in December 2022, roller mealie meal 14% and maize grain 20%.
4. **Where you live matters.** Remote districts such as Chilubi and Chiengi were the most expensive in almost every snapshot. In October 2026, a bag cost 2.2 times more in Chilubi than in the cheapest district.

## More charts

| | |
|---|---|
| ![Prices](charts/01_prices.png) | ![Affordability index](charts/03_affordability_index.png) |
| ![Yearly cycle](charts/04_yearly_cycle.png) | ![Districts](charts/05_districts.png) |

## What's in this repository

| File | Description |
|---|---|
| `zambia_food_prices.ipynb` | The full analysis: data, charts, findings and limitations. The data is built into the notebook, so it runs with no extra files. |
| `charts/` | High-resolution images of the five charts in the notebook. |

## Data

- **Source:** national average retail prices from 10 ZamStats Monthly Bulletins (December 2023 to October 2026 issues), covering every month from December 2022 to October 2026.
- **Products:** breakfast mealie meal (25 kg), roller mealie meal (25 kg) and maize grain (20 litre tin).
- **District data:** the cheapest and most expensive district for each product, from 10 bulletins.

## Method

1. Extracted price tables from the ZamStats bulletin PDFs.
2. Cross-checked months that appear in more than one bulletin. All overlapping values matched exactly.
3. Converted prices to October 2026 Kwacha using ZamStats' all-items Consumer Price Index, so months can be compared fairly.
4. Analysed trends, seasonal patterns and district differences with Python (pandas, matplotlib).

## Limitations

- 18 of the 47 months come from a single bulletin and could not be cross-checked.
- Real prices are my calculation, not figures published by ZamStats.
- National averages hide large differences between districts.
- The data shows *when* prices changed, not *why*. Explanations such as the drought or harvest timing are context, not conclusions proven by this data.

## How to run

Click **Open in Colab** above, then choose **Runtime → Run all**. No setup or file uploads are needed.

## Author

**Roy Kamwanza**
