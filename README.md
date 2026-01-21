# Oil-Well-Analytics
### Background

This project is part of the Tripleten data science practium. Focuses of the project is machine learning for buisness settings.

## Project Description

The purpose of this study is to recommend potential future oil wells with highest volume of reserves that yield highest possible profit margins and least amount of losses amoungst candidates presented by OilyGiant Mining Company.
Regional data yields 500 potential points out of which best 200 for profit calculation were choosen. Bugdet for 200 oil wells is 100 USD million.

- One barrel of raw materials = 4.5 USD of revenue.
- One unit of product = 4,500 dollars of revenue (volume of reserves is in thousand barrels).

Risk evaluation should only yield regions with 2.5% risk of losses. Regions fitting this criteria yielding highest average profit were selected.

## Data

Features available in our data consist of:
- id — unique oil well identifier
- f0, f1, f2 - features of points.
- product - volume of reserves in well (thousand barrels).

**Train data split ratio:** 3:1

**Models evaluated:** LogisticRegression

## Findings

Based on boostraped data samples and profit calculations relating to highest model predictions, we suggest region 2 for new oil well construction. Results in suggested region show:

Region posseses highest average profit at 6652410.58 USD million this is 5 USD million more than other regions.

.25 percentile in region shows at least 1579884.81 USD million in profit.

Region has least risk of loss at 0.3% compared to others, 2.0% and 3.0%

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, _NumPy_, _matplotlib_, _sklearn_
