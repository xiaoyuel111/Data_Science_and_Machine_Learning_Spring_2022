**Introduction**  

K-nearest neighbor algorithm is a basic classification and regression method.

K-nearest neighbor algorithm is to find the k nearest instances in the training data set for a new input instance given a training data set. Most of these K instances belong to a certain class, and then classify the input instance into this class. (this is similar to the idea that the minority obeys the majority in real life)

The idea of k-nearest neighbor algorithm is very simple and easy to understand. However, there are still many problems that need to be paid attention to in order to work an algorithm in practical application. For example, how to determine K, and how much is the best effect? How does the so-called nearest neighbor judge a given? In this assignment, we will try one by one

**DataSet**  

The data used in this task is

- Wheat seed dataset:

  - Similar to iris dataset. The data set contains seed information belonging to three different wheat varieties: Kama, Rosa and Canadian, represented by 1, 2 and 3 respectively
  - Link:https://www.kaggle.com/datasets/jmcaro/wheat-seedsuci
- Anime Recommendations Database:

  - The dataset contains the name and type of animation and the ratings of animation by more than 70000 users.
  - Link:https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database
