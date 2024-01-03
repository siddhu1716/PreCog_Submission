# Task - 3

For the given classification task, We intented to classify weather the give input is a hateful meme or not hateful meme 

For that classication purpose we have used images and their respective text along with their labels i.e hateful meme or not hateful meme.

Which are labeled in the JSON files as 
notepad
{"id": "08291", "img": "img/08291.png", "label": 1, "text": "white people is this a shooting range"}

0 - Not hateful meme, 1 - hateful meme

We have built two models for the calssification task

## 1. Model - 1 (Deep learning model):
Model Architecture: <br />
<img src="https://github.com/siddhu1716/PreCog_Submission/blob/main/Task_3/Model.png"/>

It mainly consists of 2 networks
1. Neural netrwork for image model
2. Lstm for text model

And finally concatinated both the model predictions 

## Accuried accuracy : 
notepad
Validation Accuracy: 71.82%


## Evalutation metrics : 
PR-Curve : <br />
<img src="https://github.com/hemanth1403/PreCog_Submission/blob/main/Task_3/PR_Curve.png">

ROC-Curve : <br />
<img src="https://github.com/siddhu1716/PreCog_Submission/blob/main/Task_3/ROC_Curve.png"/>


## 2. Model - 2 (KNN):

Used 3-NN Model for the classification purpose

## Accuried accuracy :
notepad
Accuracy: 0.8036470588235294

<img src="https://github.com/siddhu1716/PreCog_Submission/blob/main/Task_3/Data_Visualization.png"/>

