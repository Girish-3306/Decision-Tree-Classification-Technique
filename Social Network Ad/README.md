<h2>SOCIAL NETWORK AD</h2>

<h3>What is Decision tree?<h3>
  
Decision Tree algorithm is a supervised learning algorithm. Unlike other supervised learning algorithms, decision tree algorithm can be used for solving regression and classification problems too. The general motive of using Decision Tree is to create a training model which can use to predict class or value of target variables by learning decision rules inferred from prior data (training data).</br><h3></h3>

--------------------------------------------------MODEL 1----------------------------------------------------------</br>
  
STEP 1:- Imoprt the required Library {numpy,pandas,seaborn,matplotlib etc].</br>

STEP2:- Data provided in the project is a cleansed data</br>

STEP3:- Purchased is the target variable and rest are independent variable </br>

STEP4:- Make copy of the orignal data set.</br>

STEP5:- Drop unwanted columns and make documentaion of it.Reason behind removal of the column</br>

STEP6:- Convert Categorical variable into numeric value </br>
e.g.Gender from Male/Female to 0's and 1's

Step7:- Always keep a habit of making checkpoint for the project as well as for yourself.</br>  

STEP8:- Splitting of Datset into Training and Test Dataset</br>

STEP9:- Feature Scaling only on Continious variable. We only scale Continious variable[Numeric varible] as there is no need to scale categorical variable.</br> 

<h4>NOTE:- Decision tree can handle both regression as well as classification.</h4></br>

STEP10:- As the dataset contains target variable as categorical value[purchased] we will be using DecisionTreeClassifier model.</br>

STEP11:- Passing the parameters in classfier as per the requirement</br>

STEP12:- Fit and then predict on Test data set</br>

STEP13:- Confusion matrix one can check accuracy,Specitivity etc</br>

STEP14:- Visulising of the tree</br>

----------------------------------------------MODEL 2-----------------------------</br>

STEP15:- We are using Kflod and GridSearchCV</br>

STEP16:- Hyperparameter tuning</br>

STEP17:- Instantiate the grid search model and in that keep n_jobs parameter as 1 or else it will kill your system</br>

STEP18:- Predict the model</br>

STEP19:- Visulisation


<h3>Model must be simple and generic in nature</h3>
 
