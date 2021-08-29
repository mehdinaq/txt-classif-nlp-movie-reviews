# txt-classif-nlp-movie-reviews


### [Text Classification in NLP using Movie reviews data](https://github.com/mehdinaq/txt-classif-nlp-movie-reviews/blob/main/Text_Classification.ipynb)

### Overview
Text classification in NLP aims to assign a set of labels or categories based on contextual information. The goal of this analysis is to use the TF-IDF method for text classification of movie reviews and select the final model from a set of classification methods.<br /><br />

### Data Source
Movie reviews data posted on [website](http://ai.stanford.edu/~amaas/data/sentiment/). The dataset used for modeling contains 2000 movie reviews with a balanced distribution of positive/negative reviews.<br /><br />

### Analysis
- Perform EDA to uncover insights such as top 10 words occuring in positive/negative reviews, review sentiment by genre, and distribution of review length by positive/negative reviews
- Use TF-IDF to convert reviews into a sparse matrix to use in model training
- Test model performance of multiple classification techniques (SVM, Random Forest, Naive Bayes); selected Linear SVM as final classfication technique, and tweaked hyperparameters to improve model performance<br /><br />

[Detailed Analysis here](https://github.com/mehdinaq/txt-classif-nlp-movie-reviews/blob/main/Text_Classification.ipynb)<br /><br />

![top 10 words](https://user-images.githubusercontent.com/8281173/131254349-53dfd24b-f3f3-4f3c-845e-df8b4f00226b.png)
<br /><br />

### Model Performance<br />
Accuracy for Linear SVC : 89%<br /><br /> 
![confusion matrix nlp](https://user-images.githubusercontent.com/8281173/131254358-aef6f105-70e1-49a1-9fba-4cb5ed9aaf98.png)

