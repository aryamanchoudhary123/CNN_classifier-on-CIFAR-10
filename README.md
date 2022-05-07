# CNN_classifier-on-CIFAR-10
 #### A CNN based classifier on CIFAR-10 dataset.

## The following are the code snippets to better understand the model

#### Training & Testing Data

```
print("Shape of training data : ", train_images.shape, train_labels.shape)
print("Shape of testing data : ", test_images.shape, test_labels.shape)
```
![Training and Testing Data](https://github.com/aryamanchoudhary123/CNN_classifier-on-CIFAR-10/blob/main/Images/training_data.png)

#### Model Summary 

```
model_one.summary()
```
![Model Summary](https://github.com/aryamanchoudhary123/CNN_classifier-on-CIFAR-10/blob/main/Images/model_summary.png)

#### Model Fitting on 100 epochs & 16 batch

```
model_one.evaluate(testing_data,test_Labels)
```
![Model Accuracy and loss](https://github.com/aryamanchoudhary123/CNN_classifier-on-CIFAR-10/blob/main/Images/epoch.png)

#### Model Predictions

```
model_one.predict(testing_data)
```
![Model Predicted Values](https://github.com/aryamanchoudhary123/CNN_classifier-on-CIFAR-10/blob/main/Images/predicted_values.png)


#### Loss Curves

![Loss Graph](https://github.com/aryamanchoudhary123/CNN_classifier-on-CIFAR-10/blob/main/Images/loss_curves.png)


#### Accuracy Curves

![Accuracy Graph](https://github.com/aryamanchoudhary123/CNN_classifier-on-CIFAR-10/blob/main/Images/accuracy_curves.png)
