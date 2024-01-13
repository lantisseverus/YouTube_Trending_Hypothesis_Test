# YouTube_Trending_Hypothesis_Test
Utilized Python to do the data cleaning, data wrangling, data combining, and the hypothesis test. 

This dataset is a daily record of the top trending YouTube videos, coming from Kaggle: https://www.kaggle.com/datasets/datasnaek/youtube-new

We only downloaded the 2 tables from the whole datasets： US and Japan.

In this project, we import and set the index of the two data frames, clean the data and understand the data types, encode the category ID with respective names, and combine the tables to observe the aggregation of the numeric variables. 

I plotted the descriptive analysis result via seaborn barplot and then went further to the correlation matrix among the numeric variables. 

Finally, I tested the hypothesis that the audience in the US is more active in leaving comments than the ones in Japan with the right-tailed Wilcoxon-Mann-Whitney test.

## From this project we can know:
- Which category has the most views, likes, and dislikes in the US and Japan, respectively.
- The correlation between likes, dislikes, and comments count.
- Whether or not the audience in the US is more active in leaving comments than the ones in Japan.
