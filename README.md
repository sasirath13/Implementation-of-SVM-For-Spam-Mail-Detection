# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Start the program
2.Import the python pandas library as pd
3.Read the contents of the Spam csv file
4.Display the first 5 rows of the dataset using head()
5.Assign x as v1 values and y as v2 values
6.From sklearn library select the feature extraction and import CountVectorizer
7.CountVectorizer will convert the Text to Numerical Data
8.From sklearn library import Support Vector Classifier (ie. SVC)
9.Predict the x_test using SVC
10.Print the accuracy of the SVM Model 11.Stop the program

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: SASIDHARAN P 
RegisterNumber:  212223080051
*/
/*
import chardet
file='/content/spam.csv'
with open(file, 'rb') as rawdata:
  result = chardet.detect(rawdata.read(100000))
result

import pandas as pd
data=pd.read_csv("/content/spam.csv",encoding = 'Windows-1252')

data.head()

data.info()

data.isnull().sum()

x=data["v1"].values

y=data["v2"].values

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.feature_extraction.text import CountVectorizer
cv = CountVectorizer()

x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)

from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)
y_pred=svc.predict(x_test)
y_pred

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy
*/
```

## Output:

Result output

![image](https://github.com/sasirath13/Implementation-of-SVM-For-Spam-Mail-Detection/assets/160568449/2948604d-d4f0-4a77-a1ae-b86f3aa12e86)

data.head()


![image](https://github.com/sasirath13/Implementation-of-SVM-For-Spam-Mail-Detection/assets/160568449/3b612b40-1894-4e1b-9f37-0d995f509282)

 data.info()


![image](https://github.com/sasirath13/Implementation-of-SVM-For-Spam-Mail-Detection/assets/160568449/7a52d38d-2c1c-4942-aba6-232995e55302)

data.isnull().sum()


![image](https://github.com/sasirath13/Implementation-of-SVM-For-Spam-Mail-Detection/assets/160568449/8ce584b6-46fe-42af-b8e8-e84a3f83d8fe)

 Y_prediction value


![image](https://github.com/sasirath13/Implementation-of-SVM-For-Spam-Mail-Detection/assets/160568449/1334fc08-71ec-43c7-b676-5f1825b5b3e0)

Accuracy value


![image](https://github.com/sasirath13/Implementation-of-SVM-For-Spam-Mail-Detection/assets/160568449/908250e0-0fbc-4e5b-aa68-2a2402e0ea9f)

## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
