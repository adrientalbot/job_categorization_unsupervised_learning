# Job categorization to assess automation risk using unsupervised machine learning
Using the O* net dataset, Callum and I attempted to categorize jobs using NLP techniques and unsupervised  ML models as part of the workforce analytics course at Imperial College London.

## You can find in this repository:

### 1. Original O* Net data set in an excel format

### 2. The notebook with the code used to process the initial data set
- Here, we used NLTK libraries to clean up the task descriptions (remove stopwords etc) and group all the "action tasks" for each job, which will then be used for the job catagorization 

### 3. The jupyter notebook with the application of ML models with the aim to identify job clusters with high likelihood of automation risk

- We first used the word2vec package to vectorize words (assign numerical values) which would make it easier for the classification of the words.
- We then used the sklearn library and the implementation of K-means unsupervised algorithms to classify words into 5 different groups. 
- Then we decided to show the results of classifying the jobs using either hierarchical clustering and k-means models taking into account the frequency of each word group in each task (groups of words figuring in the O Net data set).

### 4. The HTML files containing the code
