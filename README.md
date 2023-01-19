# A-machine-learning-approach-to-predicting-anxiety-and-depression-levels-amongst-Bangladeshi-students

Bangladesh kept its schools, colleges and universities closed, either partially or
fully, for a period of over 82 weeks, the longest period of closure of educational institutions
in the world. This negatively hampered the mental health of many students of the country
and many of them faced difficulties in coping with the new normal as the institutions were
reopened after 2 years. During the time this paper is written, Bangladesh has no such
public dataset that contains the mental health condition of the students based on their
social, lifestyle and health features, following the reopening of the educational institutions.
In this research, we look in the problem of predicting anxiety level and depression level
amongst students of Bangladesh after the reopening of schools, colleges and universities.
A survey is conducted in which students from 30 different institutions from many parts of
Bangladesh took part in, ranging from students of urban areas to rural towns and from a
variety of socio-economic demographics. The initial dataset is then preprocessed to make
it ready for supervised machine learning algorithms to work with. Our two target variables
which are being predicted are Anxiety Level and Depression Level. Exploratory Data
Analysis (EDA) has been performed on the data which produced several important trends
related to reasons why students have severe to moderate anxiety or severe to moderate
depression. Following that, various machine learning classification algorithms have been
applied over the preprocessed dataset, including Support Vector Machine (SVM), Light
Gradient Boosting Machine (LGBM), K-Nearest Neighbor (KNN), Logistic Regression,
Random Forest and Decision Tree. After exploring the hyperparameters used in each
classifier using GridSearchCV, the best hyperparameters have been used to train the
models of the six classifiers two times, once for predicting the Anxiety Level target variable
and once for predicting the Depression Level target. After evaluating the performance of
each model using several evaluation metrics like accuracy, precision, recall and f1-score,
KNN gave the best accuracy for predicting both the target variables of Anxiety Level and
Depression Level.
