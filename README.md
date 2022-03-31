# Project-10_ML_Subject-Multi-Classifier-Model-using-NLP

## <font color = Green > Problem Statement </font>  

In order to design a question set for the teachers in the future we need to identify a particular question from the pool of questions belonging to a particular subject. These questions are gathered and scrapped through the multiple channels and online open sources. Hence, need an classifier model to analyze the text in a question for identifying which subject it belongs to. 

## <font color = Green > Assignment Understanding </font>

1. The column subject is equivalent to the subject names provided under the author table. 'Subject' should be the target variable here with 4 labels/categories: Maths, Biology, Chemistry, Physics. This subject woulb be our "Actual Subject" and not the predicted one. 
2. There are one too many relationships between the subject and the chapters i.e 1 subject can have many chapters. That is what is included in the chapter column. 
3. We need predict the highest probability of the subject label present under a new column "Predicted Subject" basis of the words available in the question in form of the text. 
4. For this project, we need to focus only on two columns — "Subject” and “Question” to train the model. 

## <font color = Green > Objective </font>

Given a new question comes in, we want to assign it to one of the 4 categories i.e the classifier makes the assumption that each new question is assigned to one and only one subject label. 

## <font color = Green > Steps Followed </font>

+ **Data Understanding, Preparation, and Pre-Processing :**
+ **Exploratory Data Analysis :**
+ **Model Selection, Model Building, and  Prediction :**
