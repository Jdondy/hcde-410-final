## Prelimary Proposal

### Motivation and Problem Statement 

I plan to analyze a refined version of the Cleveland health dataset, which includes information about heart disease. I chose to work on this dataset because of how interested I have been in the medical/health realm lately. Also, because of HIPAA medical data like this is hard to come by. This could be a particularly useful dataset to help us understand what factors contribute most to heart disease. I hope to learn how to make a model to predict whether or not someone may have heart disease, and what factors contribute most to heart disease. 

This dataset was sourced from Kaggle, and after searching for a Cleveland dataset that doesn’t have as many issues, I found this one. The Kaggle usability score for this dataset is 8.82, falling short of a 10 because it is not updated frequently, however, that’s not really applicable for this dataset anyway. The original source is: https://archive.ics.uci.edu/ml/datasets/Heart+Disease. And the Kaggle link is: https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci
The Kaggle license links to Reddit API terms: https://www.reddit.com/wiki/api .This dataset is suitable for my needs because it has binary heart disease outcomes and factors that may contribute to said heart disease in the dataset. Ethical considerations should always be made, one being that medical data is valuable, yet fragile, and nothing should be misconstrued. Furthermore, when I make a classification model, it needs to have as high of accuracy as possible, as such medical models could be the difference between life and death. 

Factors out of my control include: Confusion about the condition column as discussed on the Kaggle discussion board for this dataset, will research more.

-From the author: 
“The data is already presented in https://www.kaggle.com/ronitf/heart-disease-uci but there are some descriptions and values that are wrong as discussed in https://www.kaggle.com/ronitf/heart-disease-uci/discussion/105877. So, here is re-processed dataset that was cross-checked with the original data https://archive.ics.uci.edu/ml/datasets/Heart+Disease.”

### Overview and Research Questions

The goal of this project is to create an ML model that will be able to identify and classify "people" with heart disease given certain health states. The data analysis portion of this project is to be able to find what attributes contribute the most towards heart disease. Visualizations will be made along with the model that gives insight into the distribution of some of the attributes. 

Some research questions/hypotheses for this project include:
- What impact do cholesterol levels have on heart disease rates?
- What role do different resting blood pressure levels play on heart disease rates?
- What role can machine learning techniques play in the medical realm?

and 
- Higher cholesterol levels lead to higher rates of heart disease.
- Heart disease is more frequent in males rather than females.

### Background/Related Work

There has been a lot of research done surrounding different health attributes and heart disease, however, when comparing many of them to each other, I often find contradictions in the literature. For example, this paper on [ncbi]("https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6024687/") shows that there is a lack of evidence to support the common assumption that high levels of cholesterol affect cardiovascular (heart) disease rates. Furthermore, this Harvard [article]("https://www.health.harvard.edu/cholesterol/cholesterol-and-heart-disease-the-role-of-diet") seems to find a middle ground, stating that new studies say cholesterol isn't as bad as we used to think, but we should still stay away from high amounts from certain foods. Moreover, this Mayo Clinic [page]("https://www.mayoclinic.org/diseases-conditions/high-blood-cholesterol/symptoms-causes/syc-20350800" says that cholesterol is a direct correlation with heart disease and its' consumption should be limited. 

### Methodology 

I plan to investigate these phenomena by first taking into consideration the descriptive statistics of the data set. This will give me information about the significance of some of the attributes and the dataset as a whole, as well as provide more possibly needed background information. From there, I will subset and filter the data to show visualize the impact and relationship of different attributes on heart disease rates. Bar charts, scatterplots, treemaps, etc. will be utilized in this case. For the model, I plan to make several iterations, attempting to find what ML variation will provide the most accurate results without the risk of overfitting. These ML classification models may include SVM, logistic regression, Naive Bayes, clustering like KNN, and decision trees/random forests. After this, I will utilize different stats packages like sklearn, etc. to measure the accuracy of the models (confusion matrix or cross-validation). I will output the results in the form of a visualization or table when possible. 




