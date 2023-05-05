# Adult Income Analysis
## Analyzing the Features of a Group of Adults and How it Relates to their Income Level

**Author**: Hannah Ploutz

### Business problem:

We are looking into a variety of features from a dataset and seeing how it can be related to the income level of a group of Adults

### Data:

Data Source: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

### Data Dictionary:

<p align = "center"> 
  <img src = "https://github.com/hgploutz/Project-2/blob/main/adultdatadictionary.png">
</p>

### Data Description:

This data has 48842 rows, and 15 columns. The target variable is 'income' that is comprised of two categorical values: >50k and <=50k.
There are a multitude of features that describe adults that comprise of education, marital status, race, gender and more.

### 2 Analytical Insights from Data Analysis

- Initial analysis of the data, when comparing years of education to Capital Gain, showed that there was a correlation between the two
- It appears that the more years of education an adult has, the higher their capital gain 
- Then it drops off right at 16 years of education

<p align = "center"> 
  <img src = "https://github.com/hgploutz/Project-2/blob/main/stakeholderviz1.png">
</p>

- Further analysis of the data, when comparing Gender against income level, it showed that there was a correlation between the two as well
- It appears there is a higher count of Males that make more income then Females, who make less money

<p align = "center"> 
  <img src = "https://github.com/hgploutz/Project-2/blob/main/stakeholderviz2.png">
</p>

### The Best Model

- Ada Boosted Model with Tuned Hyperparameters
- Metrics displayed below, this model provided the highest metrics among all other models
- Other models created and tuned include Random Forest and KNN


<p align = "center"> 
  <img src = "https://github.com/hgploutz/Project-2/blob/main/bestmodel.png">
</p>


## Model Analysis

- This model would do the best to predict what income level a person makes based on their features
- It has a 93% chance to guess <=50k income level Adults and a 67% chance to guess >50k income level
- It's accuracy is 86%, which was the highest among all other models created and tuned
- This model has been tuned and is ready to be deployed to begin recieving data and predicting what income level adults are


### Recommendations:

- Overall this model would do a great job predicting Adults with an income level under 50k and a decent job prediciting them if they make over 50k
- This model could be utilized for real work analysis and works best on Adults that are making under 50k
- It is reccomended to use this model for analyzing Adults that are right out of college and have began their first real world career
- You can use this model to predict their income and thus create further marketing strategies from there

### Limitations:

- This model is limited on data soley from the United States, and is based almost entirely on white people
- There is not a lot of variety in the distribution of different cultures and race
- This model is great at predicting Adults with an income under 50K and average on those above 50k

### For further information

For any additional questions, please contact Hannah Ploutz @ **hgploutz@gmail.com**