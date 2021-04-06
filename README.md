

# Flask-web-application-to-predict-cancerous-skin-lesions

Flask web application to predict skin cancer and detect features of  melanoma using saliency maps 

### End  to end  Deployment of flask application on AWS ECS using docker image and  Fargate service. 

### The app can be viewed by public ip :  http://18.224.251.56/  (Feel free to upload test images from link below for prediction results) 

### 1)  Dataset desription : Image folder containing two folders of test data and train data within which each contains "Beningn" and "Malignant" skin lesions.

Train data images : "Benign" - 727  , "Malignant" - 173      link : https://drive.google.com/file/d/1dPfxB_jC_Q-utQ7w9IqlKySf2zScl2NM/view?usp=sharing
Test data images : "Benign" - 304 , "Malignant" - 75
Data canbe

### 2) Handling data imbalance in training data where the raio of Benign:Malignant  = 727 : 173 using  Pytorch weighted random sampling 

### 3) Transfer Learning using pytorch Densenet121 to classify images 

### 4) Saliency maps to detect features of melanoma with Pytorch autograd

### 5) Downloading  the trained model as Skinlesions.pt as this model will be used within the flask application  

### 6) Docker to conatinerize the applications along with all dependencies and required libraries

### 7) Maintain AWS ECR and the docker image is pushed onto ECR and then deployed on severless services such as Fargate
