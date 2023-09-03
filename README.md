

![kidney](https://github.com/Deepak21573/Kidney_Disease_Prediction/assets/97380822/499b89a4-ed95-419b-aa0c-d24d1015dd20)


# Kidney_Disease_Prediction
This machine learning research was developed using data that was gathered from both those who have the disease and from a variety of other people.It has a tonne of personal information, and I made the best model I could using that feature to determine whether or not a person has this ailment.

# What is Chronic Kidney Disease?
Chronic kidney disease (CKD) means your kidneys are damaged and can't filter blood the way they should. The disease is called “chronic” because the damage to your kidneys happens slowly over a long period of time. This damage can cause wastes to build up in your body. CKD can also cause other health problems.

# What causes Chronic Kidney Disease?
Diabetes and high blood pressure are the two most prevalent causes of CKD. Your blood sugar is too high if you have diabetes, which might harm your kidneys. The power of your blood in your blood vessels is too great if you have high blood pressure, which might harm your blood vessels and cause CKD.

# My solution approachs in this model

## Data preparation part
1. The dataset has very few data records but a slightly higher number of features/columns. In order to have a large number of columns to deal with, I built new columns by combining the ones that were already there. That was my only choice because we don't have enough data.
2. A few columns in the dataset include a large number of null values. Since they would undoubtedly bias my model if I imputed them, I eliminated these columns.
3. I removed some rows which have at least one null record. Because, they will corrupt the model.

## Model training part
   1. I used accuracy, precision, recall and F1 scores as model measuring metrices
   2. I tried support vector machine, decision tree and random forest algorithms
   3. Support vector machine was severly overfitting the dataset
   4. Decision tree was not fitting in quite as good as random forest. Because, the accuracy and other metrics were very low relatively to the random forest. Since, random forest is collection of decision trees, that will cover the issue of a single decision tree algorithm.
   5. RandomForest was fitting in the dataset quite very well. Ofcourse there is a little bit of over fitting but better than support vector machine. So, my final model is Random forest algorithm.

![rec](https://github.com/Deepak21573/Kidney_Disease_Prediction/assets/97380822/9719705b-5d37-42be-a01c-050e05bf9338)

      
      
