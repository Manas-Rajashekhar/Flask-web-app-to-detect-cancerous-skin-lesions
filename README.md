

## Flask-web-application-to-predict-cancerous-skin-lesions

Flask web application to predict skin cancer and detect features of  melanoma using saliency maps 

## End  to end  Deployment of flask application on AWS ECS using docker image and  Fargate service. 

## The app can be viewed by public ip :  http://18.224.251.56/

## 1)  Dataset desription : Image folder containing two folders of test data and train data within which each contains "Beningn" and "Malignant" skin lesions.

Train data images : "Benign" - 727  , "Malignant" - 173 
Test data images : "Benign" - 304 , "Malignant" - 75

## 2) Handling data imbalance in training data where the raio of Benign:Malignant  = 727 : 173 using  Pytorch weighted random sampling 

## 3) Transfer Learning using pytorch Densenet121 to classify images 

## 4) Salienc maps detect features of melanoma
