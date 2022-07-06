# COVID-19-Outcome-Prediction

The goal of this project is to predict whether a person is going torecover from coronavirus symptomsor not based on some pre-defined standard symptoms. These symptoms are based on guidelines given by the World Health Organization (WHO).

---
**DATASET DESCRIPTION**

The dataset contains 14 major variables : 
1) Country:where the person resides
2) Location:which part in the Country
3) Age: Classification of the age group for each person, based on WHO Age Group Standard
4) Gender:Male or Female 
5) Visited_Wuhan: whether the personhas visited Wuhan, China or not
6) From_Wuhan:whether the personis fromWuhan, China or not
7) Symptoms:there are six families of symptoms that are coded in six fields.
13) Time_before_symptoms_appear: 
14) Result: death (1) or recovered (0)

---

**MODELS USED**

-  K-Nearest Neighbors
-  Naive Bayes
-  Logistic Regression
-  Decision Trees
-  Support Vector Machines
---
**LIBRARIES NEEDED**

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn
- six
- IPython

---
**STEPS BEING FOLLOWED** 

- Load the dataset
- Import libraries
- Data analysis
- Data Pre-Processing
- Data Visualization
- Splitting data into test and train
- Apply diffrent classifiers
- Evaluate preformance using Confusion matrix 
- compare various classifiers using F2 

---

**CONCLUSION**
 
 Compare various classifiers:
  ![image](https://user-images.githubusercontent.com/73595891/177532260-b9cc42bb-b23a-4ead-bdd0-dd0bf845fbef.png)
  By comparing all classifiers we got Logistic Regression is best classifer 
 ```
      F2 Score:  0.923
      accuracy:  0.97 
      Precision: 0.85 
      Recall:  0.94     
      F1 Score:  0.89  
 ``` 
 
