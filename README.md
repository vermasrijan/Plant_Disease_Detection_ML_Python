# Plant_Disease_Detection_ML_Python (Convolutional Neural Network) (under the guidance of Prof. Sundaresan Raman)

![image](https://user-images.githubusercontent.com/24618926/50550370-3d52ae80-0c95-11e9-8a76-949053e8d428.png)

Used AlexNet with Tensorflow DL framework for classifying diseased leaf images .

# Problem Statement: - 
To be able to detect a disease on a leaf/fruit using technology . Disease detection plays an important role in agricultural fields as having disease in plants is quite natural. 
If proper care is not taken in this area, then it can cause serious effects on plants due to which respective product quality/quantity or productivity is affected .

# Specifications of alexnet used
8 layers in total .

First 5 Convolutional layers with last 3 fully connected layers .

ADAMs Optimizer with learning Rate = 0.0001

Cross Entropy Loss Function used .

ReLu (Rectified Linear Unit) used after every convolutional and fully connected layer .

# Specifications of the dataset used
Used 4 classes from the Plant Village Dataset :

1. Tomato Bacterial Spot
2. Tomato Healthy
3. Tomato Septoria Spot
4. Tomato Curl Virus

Total Training images used = 4000 (1000 from each class)

Total Testing images used = 800 (200 from each class)

Train:Val split used was 9:1 

# Hyperparameters and the results obtained
No of iterations for 1 epoch = (TrainImage/BatchSize) = 4000/32 = 125 

Test Accuracy = 91.3% 

Trained the AlexNet on Google Colab (Tesla K80 GPU)

No of epochs = 120 

Learning rate = 0.0001

Batch size = 32 

Loss = 0.42

![image](https://user-images.githubusercontent.com/24618926/50550345-d8975400-0c94-11e9-9807-2aac5795b9f4.png)


![image](https://user-images.githubusercontent.com/24618926/50550347-ddf49e80-0c94-11e9-99b7-8004d3498174.png)


