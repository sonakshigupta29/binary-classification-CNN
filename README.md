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
Overall my model was learning images patterns effectively and scored accuracy of -----.
image
