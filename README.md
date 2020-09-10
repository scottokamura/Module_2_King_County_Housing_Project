# King County Housing Data Analysis

## Introduction
### Objective

> For this project, you'll be working with the King County House Sales dataset. We've modified the dataset to make it a bit more fun and challenging. The dataset can be found in the file "kc_house_data.csv", in this repo.
>The description of the column names can be found in the column_names.md file in this repository. As with most real world data sets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions relating to what the data means.
>You'll clean, explore, and model this dataset with a multivariate linear regression to predict the sale price of houses as accurately as possible.

### Summary of Approach
1. Determine the target audience
    - property owners looking to sell
2. Clean dataset
   - drop outliers
   - transform data if necessary (log, squared, etc)
3. Identify categorical and continuous variables
   - create dummy variables for categorical variables
   - group zipcodes by geographic location
4. Determine independent variables to use in model
    - using OLS and RFE
5. Check for multicollinearity
    - drop featuers with high correlation values
6. Generate model
7. Repeat
    - check if transforming data will improve $R^2$

### Methods and Technologies Used
1. Python libraries
2. Pandas, numpy
3. Matplotlib, seaborn
4. Plotly, cufflinks
5. Statsmodels, scipy


## How to Use Repository
1. Fork and clone this repository
2. Open 'King County Housing Analysis.ipynb'

### Additional Contents
1. Slide deck presentation ('presentation.pdf')
2. Related blog on creating effective slideshow presentations (https://scottokamura.github.io/data_science_non-technical_skill_slideshows)
