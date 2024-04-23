# Predictive Model

## Description
This final model created for this project is a decision tree classifier. The inputs to the model are different features of a specific film, such as the month it is planning to be released or the genre of the movie. The model then predicts the revenue category the film should fall into, in one of four categories:

1. Low
2. Medium
3. High
4. Very High

## Input Features

After the data was cleaned and prepped to be used in a predictive model, we were left with nine variables (eight excluding the categorized_rev label column). Here are those variables:

| Variable | Type | Description |
| ----------- | ----------- | ----------- |
| vote_count | int | Total count of votes received for the movie |
| categorized_revenue | str | Classification of the total revenue into low/medium/high/very high classes |
| runtime | int | Duration of the movie in minutes | 
| budget | int | Budget allocated for the movie |
| original_language | str | Original language in which the movie was produced |
| genre | str | the Genre the movie belongs to | 
| top20_production_company | bool | Whether or not the film was produced by one of the top 20 production companies based on total revenue |
| release_month | int | Month that the film was released |
| production_country | str | Main country of the movie production |

But, the categorical variables (non-numeric variables) needed to be encoded in order to be used in the predictive model. This is because the decision tree cannot recognize non-numeric variables as inputs. So, as menntioned, encoding was utilized to combat this. After encoding, there were over 200 inputs! This was because some variables had many categories, such as production_country.

But, after the model was trained and the decision tree was pruned, the model was left much simpler. 
