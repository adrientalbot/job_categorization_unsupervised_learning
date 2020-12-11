# job_categorization_unsupervised_learning
Using the O* net dataset, Callum and I attempted to categorize jobs using NLP techniques and unsupervised  ML models as part of the workforce analytics course at Imperial College London.

## You can find in this repository:

### 1. Original O* Net data set in an excel format

### 2. The jupyter notebook with the application of ML models with the aim to identify job clusters with high likelihood of automation risk

- We first used the word2vec package to vectorize words (assign numerical values) which would make it easier for the classification. 
- We then used the sklearn library and the implementation of K-means unsupervised algorithms to first classify words into 5 different groups. 
- Then we decided to show the results of classifying the tasks (groups of words figuring in the O Net data set) using either hierarchical clustering and k-means models taking into account the frequency of each word group in each task. 

### 3. 
