# Data Science Programming Task
This repository contains the Data Analysis of Stackoverlow Posts for two tags (i.e., “wordpress” and “drupal”)  within a 6-month period (i.e., "01/2021-06/2021”). The repository contains the data extracted using big query api and the jupyter notebooks that are needed to perform an indepth analysis on the csv files of the two tags (e.g., “wordpress” and “drupal”). 

The following are the two types of Data Analysis techniques which were performed: 

1. Generate Shaded Density Plots with Rug Plot to understand the differences in distribution of the five different metrics (i.e., Answer Count, Comment Count, Favorite Count, View Count, Score) between the posts of the two tags (i.e.,  “wordpress” and “drupal”)

2. Generate Time Series Plots to understand the topical trend of the five different metrics (i.e., Answer Count, Comment Count, Favorite Count, View Count, Score) over the creation Date intervals between the posts of the two tags (i.e.,  “wordpress” and “drupal”)

# Required tools and packages
The following tools were installed on the machine where the scripts were originally executed:
* Python 3.6.8

In addition, the following Python packages were installed:

* pandas
* matplotlib
* seaborn
* datetime
* bq_helper

# Data Extraction
1. Obtain the SO posts, i.e., questions and their answers, for two tags (i.e., “wordpress” and “drupal”) within a given time period (i.e., "01/2021-06/2021") using biq query. 
2. Extracted for each post the mentioned id, creation_date, tags, answer_count, comment_count, favorite_count, view_count, and score. 
3. Generated csv files for the wordpress and drupal tags with one line per post, where each line contains an identifier for a post (i.e., id) and the values for the 5 chosen metrics (i.e., answer_count, comment_count, favorite_count, view_count, and score)

# Data Analysis Results

## Analysing the differences in distribution of the 5 metrics between the posts of the two tags

With the Shaded Density Plots of the 5 metrics (i.e., answer_count, comment_count, favorite_count, view_count, and score) mentioned below , we come to the conclusion that wordpress tag conatin higher density of metric distributions compared to drupal tag. In Addition, the Rug plots shows that the range of metric values of wordpress tag is more wide compared to drupal tag.

![](https://github.com/jaskirat111/StackoverFlowDataAnalysis/blob/main/figures/Shaded%20Density%20Plot%20with%20Rug%20Plot%20for%20Answer%20Count.jpg)
![](https://github.com/jaskirat111/StackoverFlowDataAnalysis/blob/main/figures/Shaded%20Density%20Plot%20with%20Rug%20Plot%20for%20Comment%20Count.jpg)
![](https://github.com/jaskirat111/StackoverFlowDataAnalysis/blob/main/figures/Shaded%20Density%20Plot%20with%20Rug%20Plot%20for%20Favorite%20Count.jpg)
![](https://github.com/jaskirat111/StackoverFlowDataAnalysis/blob/main/figures/Shaded%20Density%20Plot%20with%20Rug%20Plot%20for%20View%20Count.jpg)
![](https://github.com/jaskirat111/StackoverFlowDataAnalysis/blob/main/figures/Shaded%20Density%20Plot%20with%20Rug%20Plot%20for%20Score.jpg)

