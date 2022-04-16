**Introduction**

- Ensemble Learning

Ensemble learning is a machine learning paradigm. In ensemble learning, we will train multiple models (commonly known as "weak learners") to solve the same problem and combine them to obtain better results. The most important assumption is that when the weak models are combined correctly, we can get a more accurate and / or robust model.

   - bagging

This method usually considers homogeneous weak learners, learns these weak learners independently in parallel, and combines them according to a certain deterministic average process.

  - boosting

This method usually considers homogeneous weak learners. It learns these weak learners sequentially in a highly adaptive way (each basic model depends on the previous model), and combines them according to a certain deterministic strategy.

**DataSet** 

The datasets included this lecture is:
- Wheat seed dataset:

  - Similar to iris dataset. The data set contains seed information belonging to three different wheat varieties: Kama, Rosa and Canadian, represented by 1, 2 and 3 respectively
  - Link:https://www.kaggle.com/datasets/jmcaro/wheat-seedsuci
