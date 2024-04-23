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

But, after the model was trained and the decision tree was pruned, the model was left much simpler. The model required the following 15 unique features:

| Variable | Description |
| ----------- | ----------- |
| genre_Animation | Whether or not the genre of the film is Animation |
| genre_Horror | Whether or not the genre of the film is Horror |
| genre_Comedy | Whether or not the genre of the film is Comedy |
| genre_Drama | Whether or not the genre of the film is Drama |
| production_country_Canada | Whether or not the production country is Canada |
| production_country_United Kingdom | Whether or not the production country is the United Kingdom |
| production_country_United States of America | Whether or not the production country is the United States |
| production_country_India | Whether or not the production country is India |
| original_language_es | Whether or not the original language of the film is Spanish |
| original_language_hi | Whether or not the original language of the film is English |
| original_language_en | Whether or not the original language of the film is Hindi |
| budget | The budget of the film in $USD |
| vote_count | The number of votes given to the film on the IMDB profile for the movie |
| runtime | The runtime for the movie in minutes |
| release_month | The month (1-12) that the movie was released in |

## Output / Prediction
The model takes the features of a movie as the input varibles. Then, the model predicts the bin of categorized revenue it predicts the movie will fall into. These categories are as follows, with their labels and their dollar amounts:

| Categorized Revenue Bin | $ Amount |
| ----------- | ----------- |
| 1. Low | $0 - $29,178 |
| 2. Medium | $29,178 - $2,370,313.50 |
| 3. High | $2,370,313.50 - $23,604,902.25 |
| 4. Very High | $23,604,902.25 and up |

These dollars amounts were not just randomly selected. They are the quartile values for revenues. For example, the "Medium" category for revenue is from the 25th percentile to the 50th percentile of revenues in the dataset.

## Performance Metrics

Since the predictive model is a decision tree classifier, there are many different metrics that can be used to evaluate the model. 

## Using the Model for Prediction
