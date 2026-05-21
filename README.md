# Binary Classification using CNN
In this project i implemented concepst Convolutional Neural Network (CNN) by performing *binary classification* on PetImages dataset- containing multiple images of dogs and cats.
I approached this by preprocessing images data, making it fit to feed to our CNN network, building a cnn architecture from scratch, training and validating on training and testing data tensors and finally evaluating the classification reults made by our nueral network.

# Learnings
- Learnt about images preprocessing- transforming and preprocessing images data efficiently
- CNN architecture and its underlying concepts in depth by building it from scratch
- Training and Validation loss analysis to check overfitting and underfitting cases
- Evaluation metrics, losses metrics and model parameters
- Binary classification concepts

# Debugging 
- I handled the issues of overfitting and slow training by introducing dropout layers between network layers, fixing typos and basic logical mistakes, by cleaning the pipeline and optimizing the training flow.
- Checking image preprocessing and data loading so all images were passed correctly to the model.
- Verifying training/validation behavior to ensure the model was actually learning image patterns instead of memorizing
- Removing corrupted/truncated images from the dataset before training.

These improvements helped the model learn image patterns more effectively and achieve stable training and validation performance.

# Results
The CNN model was able to learn meaningful image patterns effectively and achieved an accuracy of 81.98% on the validation/test dataset.
The training and validation loss curves show a consistent decrease over epochs, indicating stable learning and good generalization performance.

The close alignment between training loss and validation loss suggests that the model was able to reduce overfitting successfully with the help of dropout layers and proper preprocessing techniques. Additionally, debugging corrupted images and fixing logical issues in the training pipeline improved the overall model performance and training stability.

<p align="center"> <img src="https://github.com/user-attachments/assets/ea99c375-62a7-4e5e-9be5-e854e677f7dc" alt="Training and Validation Loss Graph" width="700"/> </p> <p align="center"> <em>Training vs Validation Loss across epochs for the CNN binary image classification model.</em> </p>

