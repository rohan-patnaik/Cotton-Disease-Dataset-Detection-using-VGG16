# Cotton-Disease-Dataset-Detection-using-VGG16
Predicting diseased data from a cotton disease dataset using VGG16 transfer model.

Download the dataset from the link given below :

https://www.kaggle.com/janmejaybhoi/cotton-disease-dataset

# Steps I take for this dataset are : 

We follow my favorite acronym IRO TFA CCFE as shown below

![image](https://user-images.githubusercontent.com/22250758/138545349-8062117b-8a2c-4ec6-a64c-ddee45af3e57.png)

So we start by resizing the image to our required dimensions.

Read the train and test datasets.

Move on with data augmentation.

Create model object for the vgg16 model(in hindsight vgg19 might have been a better fit.

Compile the model with loss = 'categorical_crossentropy' since its not a binary classification problem statement along with the other parameters provided.

![image](https://user-images.githubusercontent.com/22250758/138545697-d7395a7b-b0a8-4f88-b442-9febf84482c7.png)

We'll then fit the model and store it in a variable hist to be used to plot model losses and accuracies as shown below :

![image](https://user-images.githubusercontent.com/22250758/138545704-0b515549-e2c6-42d2-8028-e2f5809320de.png)

Save the model.

And then plot a few images for testing purposes.

![image](https://user-images.githubusercontent.com/22250758/138545732-8b775541-1d1c-4b94-9b3d-00f2257495bb.png)
