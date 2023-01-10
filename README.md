# 2022-NYCU-ML-Final_Project
This is a challenge of Kaggle! ([website link](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview))
![截圖 2023-01-10 下午5 49 33](https://user-images.githubusercontent.com/96174316/211518113-fd76bd0f-6613-4f76-810b-6a7d0b69e8e9.png)

### Challenge Overview
The August 2022 edition of the Tabular Playground Series is an opportunity to help the fictional company Keep It Dry improve its main product Super Soaker. The product is used in factories to absorb spills and leaks.

The company has just completed a large testing study for different product prototypes. Can you use this data to build a model that predicts product failures?

### Dataset Description
This data represents the results of a large product testing study. For each product_code you are given a number of product attributes (fixed for the code) as well as a number of measurement values for each individual product, representing various lab testing methods. Each product is used in a simulated real-world environment experiment, and and absorbs a certain amount of fluid (loading) to see whether or not it fails.

Your task is to use the data to predict individual product failures of new codes with their individual lab test results.

### Files
* train.csv - the training data, which includes the target failure
* test.csv - the test set; your task is to predict the likelihood each id will experience a failure
* sample_submission.csv - a sample submission file in the correct format

## Performance
* Baseline: 0.5899
* My result: 0.59126
![截圖 2023-01-10 上午1 43 02](https://user-images.githubusercontent.com/96174316/211377030-0016b2b5-bda8-4c32-82f7-0e11bc4b7d28.png)

## Test
- models link: https://drive.google.com/file/d/1F21z1mY8nLb02w5YxX9gpq8JSExCptuC/view?usp=share_link

## Reproducing Submission

## Reference
1. [TPSAUG22 EDA which makes sense ⭐️⭐️⭐️⭐️⭐️](https://www.kaggle.com/code/ambrosm/tpsaug22-eda-which-makes-sense)
2. [TPS August | EDA + Failure Prediction](https://www.kaggle.com/code/devsubhash/tps-august-eda-failure-prediction/notebook)
3. [TPS-Aug22 9th solution](https://www.kaggle.com/code/takanashihumbert/tps-aug22-9th-solution/notebook)
