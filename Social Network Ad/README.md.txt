What is Decision tree?
Decision Tree algorithm is a supervised learning algorithm. Unlike other supervised learning algorithms, decision tree algorithm can be used for solving regression and classification problems too. The general motive of using Decision Tree is to create a training model which can use to predict class or value of target variables by learning decision rules inferred from prior data (training data).


STEP 1:- Imoprt the required Library {numpy,pandas,seaborn,matplotlib etc]

STEP2:- Data provided in the project is a cleansed data

STEP3:- Purchased is the target variable and rest are independent variable 

STEP4:- Make copy of the orignal data set.

STEP5:- Drop unwanted columns and make documentaion of it.Reason behind removal of the column

STEP6:- Convert Categorical variable into numeric value 
e.g.Gender from Male/Female to 0's and 1's

Step7:- Always keep a habit of making checkpoint for the project as well as for yourself.  

STEP8:- Splitting of Datset into Training and Test Dataset

STEP9:- Feature Scaling only on Continious variable. We only scale Continious variable[Numeric varible] as there is no need to scale categorical variable. 

NOTE:- Decision tree can handle both regression as well as classification.

STEP10:- As the dataset contains target variable as categorical value[purchased] we will be using DecisionTreeClassifier model.

STEP11:- Passing the parameters in classfier as per the requirement

STEP12:- Fit and then predict on Test data set

STEP13:- Confusion matrix one can check accuracy,Specitivity etc

STEP14:- Visulising of the tree

###################MODEL 2########################
STEP15:- We are using Kflod and GridSearchCV

STEP16:- Hyperparameter tuning

STEP17:- Instantiate the grid search model and in that keep n_jobs parameter as 1 or else it will kill your system

STEP18:- Predict the model

STEP19:- Visulisation


MOdel must be simple and generic in nature
 