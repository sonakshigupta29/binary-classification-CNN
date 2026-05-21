# Binary Classification using CNN
In this project i implemented concepst Convolutional Neural Network (CNN) by performing *binary image classification* on PetImages dataset- containing multiple images of dogs and cats.

I approached this by preprocessing images data, preparing it for deep learning pipelines, building a cnn architecture from scratch using PyTorch, training and validating the model and finally evaluating classification performance.

The main objective of this project was to enable the CNN model to learn meaningful visual patterns and accurately distinguish between cat and dog images.

# Learnings
- Learnt image preprocessing and augmentation techniques
- Understood CNN architecture and convolution operations in depth
- Training and validation loss analysis for overfitting detection
- Binary image classification concepts
- Model evaluation metrics and prediction analysis
- Data loading and tensor handling using PyTorch

# Debugging 
- Removed corrupted/truncated images from the dataset before training
- Fixed typos and logical implementation mistakes
- Introduced dropout layers to reduce overfitting
- Optimized the training pipeline for smoother convergence
- Verified proper image preprocessing and data loading
- Monitored training/validation behavior to ensure the model learned patterns instead of memorizing

These improvements helped the model achieve stable training and better generalization performance.

# Results
The CNN model was able to learn meaningful image patterns effectively and achieved an accuracy of **81.98%** on the validation/test dataset.
The training and validation loss curves show a consistent decrease over epochs, indicating stable learning and good generalization performance.

The close alignment between training loss and validation loss suggests that the model was able to reduce overfitting successfully with the help of dropout layers and proper preprocessing techniques. Additionally, debugging corrupted images and fixing logical issues in the training pipeline improved the overall model performance and training stability.

<p align="center"> <img src="https://github.com/user-attachments/assets/ea99c375-62a7-4e5e-9be5-e854e677f7dc" alt="Training and Validation Loss Graph" width="700"/> </p> <p align="center"> <em>Training vs Validation Loss across epochs for the CNN binary image classification model.</em> </p>

# Tech Stack
- Python
- PyTorch
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
