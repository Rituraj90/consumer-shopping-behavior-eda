# Consumer Shopping Behavior Survey — EDA

Exploratory data analysis of a 500-response consumer shopping survey spanning 25+ countries — covering demographics, channel/platform preference, purchase influencers (reviews, ads, discounts), payment methods, BNPL adoption, and satisfaction.

## Contents
- `EDA_Consumer_Shopping_Behavior.ipynb` — full analysis notebook: data quality check, univariate & bivariate charts, correlation analysis, and takeaways.
- `Consumer_Shopping_Behavior_EDA.pptx` — a 14-slide summary deck built from the same analysis, ready to share on LinkedIn or present.
- `consumer_shopping_behavior_survey.csv` — the raw dataset.

## Key findings
- **Young & budget-conscious sample**: median age in the low-20s, ~50% students, 54% earn under $1,000/month.
- **Mobile-first**: 63% shop primarily on smartphone.
- **Soft channel loyalty**: 49% prefer online, 26% offline, 25% say "equal / both."
- **Discounts beat ads and reviews** as a purchase driver, across every income band.
- **Digital wallets lead payment preference** (38%), ahead of debit, credit, and cash.
- **BNPL is mainstream**: 41% use installment plans at least occasionally.
- **No single "super-signal"**: influence, satisfaction, and impulse-purchase scores correlate weakly with each other — multi-signal segmentation beats any one proxy metric.

## How to run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter nbconvert --to notebook --execute --inplace EDA_Consumer_Shopping_Behavior.ipynb
```

## Note on the data
This is a modest-sized (n=500), self-reported survey sample with some missing values on conditional questions. Treat findings as directional signals rather than statistically definitive conclusions.
