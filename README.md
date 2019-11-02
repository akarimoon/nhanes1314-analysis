# NHANES 2013-14 Analysis

## What is NHANES?
[NHANES](https://www.cdc.gov/nchs/nhanes/index.htm), National Health and Nutrition Experimentation Survey, is a national survey taken in the U.S. every year. It is "a program of studies designed to assess the health and nutritional status of adults and children in the United States". CSV formatted files are available [here](https://www.kaggle.com/cdc/national-health-and-nutrition-examination-survey).

## What are in the data?
- demographic.csv
- examination.csv: Contains blood pressure, body measures, etc.
- diet.csv: total nutrient intake, etc.
- labs.csv: chemicals substances in the body, etc.

## What I did
`eda.ipynb` shows my work for this dataset. I analyzed how income-levels and people's health awareness/education are related to each other.

Using simple [decision tree algorithm](https://medium.com/deep-math-machine-learning-ai/chapter-4-decision-trees-algorithms-b93975f7a1f1), I was able to achieve 97% for both training and test dataset.

## Further research
Predicting the risk factors (perhaps from [here](https://www.who.int/nmh/ncd-tools/indicators/GMF_Indicator_Definitions_Version_NOV2014.pdf)) from the questionnaire data seems interesting.
