# School-Budget-NLP

# Introduction to the Challange
Budgets for schools are huge, complex, and not standardized. Hundredds of hours each year are spent manually labelling.

**Goal**: Build a machine learning algorithm that can autiomate the process

**Dataset**:
  1. Line-item: text description of each item
  2. 9 Target variables: labels like ‘Textbooks’, ‘Math’, ‘Middle School’
Supervised classification problem.

We want to build a human-in-loop machine learning system. We don’t want to make direct prediction on whether each item is A or B, but want to say that “we are 60% sure that is belongs to A. If not, we are 30% sure it belongs to B…”.

**Performance Measurement**
The metric used in this problem is log loss. It is a loss function and a measure of error. Our goal is to minimize the error with our model.

  *Log Loss for binary classification
    The function sets that it is better to be less confident than confident and wrong, i.e., a high probability is assigned to the incorrect class.
    
**To Do Better**
*NLP*: stemming, stop-word removel

*Model*: RandomForest, k-NN, Naive Bayes

*Numeric Preprocessing*: Imputation strategies

*Optimization*: Grid search over pipeline objects

Experiment with new scikit-learn techniques
