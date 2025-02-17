#Detection Of Parkinson Disease Dataset
###Description :
This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD. We will use Jupyter Notebook for the training data and buiding our model using XGBClassifier.

###Google Colab Notebook
- For Colab Notebook click here
Prerequisites :
Required
Python Programming Language
Boosting Techniques in ML
Jupyter Notebook
Scikit-learn Library for python
Pandas Library for python
Installations :
Install Python
Execute the following command in terminal:
 pip install pandas
 pip install xgboost
 pip install seaborn
 pip install matplotlib
 pip install scikit-learn
Boosting in Machine Learning
Boosting is an ensemble modeling technique which attempts to build a strong classifier from the number of weak classifiers.
It is done building a model by using weak models in series.
Firstly, a model is built from the training data.
Then the second model is built which tries to correct the errors present in the first model.
This procedure is continued and models are added until either the complete training data set is predicted correctly or the maximum number of models are added.
Some Boosting Techinques:
Gradient Boosting Machine (GBM)
Extreme Gradient Boosting Machine (XGBM)
AdaBoost (Adaptive Boosting)
XGBClassifier
XGBoost (eXtreme Gradient Boosting) is an advanced implementation of gradient boosting algorithm.
It is a decision-tree-based ensemble Machine Learning algorithm that uses a gradient boosting framework.
XGBoost algorithm has become the ultimate weapon of many data scientist. It’s a highly sophisticated algorithm, powerful enough to deal with all sorts of irregularities of data.
XGBoost algorithm was developed as a research project at the University of Washington. Tianqi Chen and Carlos Guestrin presented their paper at SIGKDD Conference in 2016 and caught the Machine Learning world by fire


Advantages of XGBoost
Tree Pruning
Regularization
High Flexibility
Cross-validation
Parallel Processing
Hardware Optimization
Built-in Cross-Validation
Comparing XGBoost


Source:
The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals. The original study published the feature extraction methods for general voice disorders.

Acknowledments :
McSharry et al.’s 2007 paper, Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection
REFERENCES
Oxford Parkinson's Disease Detection Dataset will be used
DATASET download from here
parkinson-Prediction-healthcare-project-ACCIOJOB/detect parkinsons ML project/detect-parkinson-xgb at main · Kar788/parkinson-Prediction-healthcare-project-ACCIOJOB 
