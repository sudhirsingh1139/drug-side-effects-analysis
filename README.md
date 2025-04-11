# Drugs, Side Effects, and Medical Conditions Analysis

## Project OverView

This project involves the analysis of a dataset containing information about various drugs, their side effects, and the medical conditions they are used to treat. The dataset provides valuable insights into the pharmaceutical industry, user reviews, and the relationships between drugs, side effects, and medical conditions.

## Dataset

- **Dataset Name**: Drugs, Side Effects, and Medical Conditions
- **Dataset Link**: [Kaggle Dataset](https://www.kaggle.com/datasets/jithinanievarghese/drugs-side-effects-and-medical-condition)
- **Number of Attributes**: 17
- **Number of Data Rows**: 2931

## Data Preprocessing

### Selection
- Dropped irrelevant attributes such as 'csa,' 'drug_link,' and 'medical_condition_url.'
- Filled empty spaces in binary attributes for easier analysis.

### Data Cleaning
- Tokenized 'medical_condition_description' using the NLTK module.
- Processed and cleaned textual data in the 'side_effects' column.
- Transformed and standardized the dataset for effective analysis.

## Descriptive Statistics and Data Analysis

### Dataset Dimensions after preprocessing
- The dataset has 2931 rows and 14 columns.

### Key Insights
- Analyzed unique drugs and medical conditions.
- Explored attributes such as 'rx_otc,' 'pregnancy_category,' 'alcohol,' and more.
- Utilized bar graphs, pie charts, line plots, scatter plots, and more to visualize data.
- Applied correlation matrices and Apriori algorithm to find related drugs.
- Used decision tree classification and clustering for data analysis.

## Conclusion

This project involved comprehensive data preprocessing and analysis of a pharmaceutical dataset. Through descriptive statistics, data visualization, association rule mining, decision tree classification, and clustering, we gained insights into the relationships between drugs, medical conditions, and user ratings.



## Python Modules used
- Pandas
- NLTK
- Matplotlib
- Seaborn
- Scikit-Learn
