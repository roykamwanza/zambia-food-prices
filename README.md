# Zambia's Staple Food Prices: From Drought to Recovery (2022–2026)

How did the prices of mealie meal and maize change through Zambia's 2024 drought, and who pays the most today? This project follows three staple foods month by month for almost four years, using official prices from the Zambia Statistics Agency (ZamStats).

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/roykamwanza/zambia-food-prices/blob/main/zambia_food_prices.ipynb)

![Then, at the peak, and now](charts/02_then_peak_now.png)

## Headline finding

**Mealie meal prices more than doubled, then fell back to around mid-2023 levels.** A 25 kg bag of breakfast mealie meal cost K172 in December 2022, peaked at K364 in March 2025, and costs K236 today.

## Key findings

1. **Prices more than doubled, then fell.** Between December 2022 and early 2025, breakfast mealie meal rose from K172 to K364, roller mealie meal from K139 to K307 and maize grain from K88 to K229. Since then, they have fallen by 35%, 41% and 53%.
2. **Prices are back to around mid-2023 levels.** Breakfast mealie meal costs K236 today, close to what it cost in mid-2023, but still 37% more than in December 2022.
3. **2024 was the most expensive year overall.** Prices peaked in 2025, but they stayed high for almost all of 2024, making it the most expensive year on average for all three foods.
4. **Where you live matters.** Remote districts such as Chilubi and Chiengi were usually the most expensive for mealie meal. The most expensive district paid up to 2.2 times the cheapest price for breakfast mealie meal, 2.3 times for roller mealie meal and 2.7 times for maize grain.

## More charts

| | |
|---|---|
| ![Four years of prices](charts/01_prices.png) | ![Average price each year](charts/03_yearly_average.png) |
| ![The yearly cycle](charts/04_yearly_cycle.png) | ![Breakfast mealie meal by district](charts/05a_districts_breakfast.png) |
| ![Roller mealie meal by district](charts/05b_districts_roller.png) | ![Maize grain by district](charts/05c_districts_maize.png) |

## What's in this repository

| File | Description |
|---|---|
| `zambia_food_prices.ipynb` | The full analysis: data, charts, findings and limitations. The data is built into the notebook, so it runs with no extra files. |
| `charts/` | High-resolution images of the seven charts in the notebook. |

## Data

- **Source:** national average retail prices from 10 ZamStats Monthly Bulletins (December 2023 to October 2026 issues), covering every month from December 2022 to October 2026.
- **Foods:** breakfast mealie meal (25 kg bag), roller mealie meal (25 kg bag) and maize grain (20 litre tin).
- **District data:** the cheapest and most expensive district for each food, from 10 bulletins.

## Method

1. Took the price tables from the ZamStats bulletin PDFs.
2. Compared months that appear in more than one bulletin. All of them matched exactly.
3. Looked at how prices changed over time, from year to year, through the seasons, and between districts, using Python (pandas and matplotlib).

## Limitations

- 18 of the 47 months come from a single bulletin and could not be double-checked.
- These are the prices people paid at the time. They do not account for changes in incomes or in the cost of other goods.
- National averages hide large differences between districts.
- The data shows *when* prices changed, not *why*. Explanations such as the drought or harvest timing are context, not conclusions proven by this data.

## How to run

Click **Open in Colab** above, then choose **Runtime → Run all**. No setup or file uploads are needed.

## Author

**Roy Kamwanza**
