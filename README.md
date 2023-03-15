Project Name: Melanoma Skin Cancer Detection using Images: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Technologies used in this projects are as follows:
Tensorflow
Keras
Matplotlib
CNN Sequential Model

General Information Provide general information about your project here. 
We have used CNN architecture from scratch to classify skin lesions images. In this project, we used CNN Sequential model.

What is the business probem that your project is trying to solve? Problem statement: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Conclusion 1 : 
We did not use dropout layer or Data Augmentation while we build the first sequential model and found below based on our analysis:
Epochs 20 : After the end of epochs 20, the training accuracy and val_accuracy clearly shows that the model has been overfitted
Visualization : In the First Graph : After the visualization, we can see that the graphs indicates that traning accuracy is increased however the validation accuracy seems to be not increasing as much as training accuracy. In the second graph, the training loss has decreased but validation loss is increased. This graphs clearly tells a story that the model has overfitted and learnt the traninig dataset well but not performing well on validation dataset as much as it should. This is my observation from this visualization and we need to play with hyperparameters and use other techniques to ensure model does not overfit. Overfitting occurs when a model is too complex and performs well on the training data but poorly on new, unseen data. analysis.

Conclusion 2: We performed Data augmentation method and found the below onservation based on our analysis:
Epochs 20 : After the end of epochs 20, the training accuracy and val_accuracy clearly shows that the model has been overfitted
Visualization : In the First Graph : After the visualization, we can see that the graphs indicates that traning accuracy is increased however the validation accuracy seems to be not increasing as much as training accuracy. In the second graph, the training loss has decreased but validation loss is increased. This graphs clearly tells a story that the model has overfitted and learnt the traninig dataset well but not performing well on validation dataset as much as it should. This is my observation from this visualization and we need to play with hyperparameters and use other techniques to ensure model does not overfit. Overfitting occurs when a model is too complex and performs well on the training data but poorly on new, unseen data. analysis.

Conclusion 3: 
We used Augmentor to add artificial images in all the training images for each Image folder and based on our observation, we were successfully able to build a generalized model without any overfit or underfit issues and with good accuracy: After performing class imbalance technique and adding 500 samples to the existing images using Data Augmentor, we are able to derive perfect results and yes, we are able to get rid of Overfitting problem and the model has provided following results:
Loss has been minimized
Training accuracy of 94% achieved
Validation Accuracy of 90% achieved
Contact Created by AsifVirani5 - feel free to contact me!
