# Hotel-Recommendation-System

![image](https://user-images.githubusercontent.com/94131602/208264824-f21b56b5-701a-4962-a9ef-545f821bfbc2.png)



## Problem Statement:
If a person enjoys Chinese cuisine, There’s a good chance that the person would also like Korean cuisine, although it might be easy to find this out for a specific individual, finding preferences and recommendations for millions of customers that want to explore and order new food is quite complex. This is where data science comes into place. Typical, commonly used algorithms consider only the customer's past behavior to offer recommendations. This heavily limits the number of potential restaurants that can be recommended leading to sparsity and redundancy challenges, Thus we make use of knowledge gained from graphs and appropriate tools to recommend a wider variety of restaurants by comparing similarity between customers to show new restaurants that the customer may not have tried.<br>

## Dataset Description:
The dataset we have used here contains a multitude of hotels and a set of reviews given to each hotel by the customers. The dataset is in CSV format. Additional information like hotel ID for each hotel, user ID for each user, user rating are also given. The ratings given by each user for a hotel can range anywhere between 0 to 1. With this dataset, It is possible for us to create a smaller dataset with only two parties, Users and their preferred restaurants. This acts like a bipartite graph using which we can infer different information to conclude recommendations by algorithms like link prediction.
