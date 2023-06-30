# CNN model for Classifying CATS and DOGS.

So, This Repository is regarding the Task assigned to me by **[GreyFeathers]('https://www.greyfeathers.in/').**

## Task Description:
- Creating a Model (from scratch / using transfer learning).
- Image Manipulation.
- Creating more images for testing.
- Improving model.
- using CAM (Class Activation Maps)
- Model description

## Model Description: 

### CNN Model Architecture:
- **Two Convolutional Layers:**
> 1. First Layer: 32 filters & kernel size - (3x3)
> 2. Second Layer: 64 filters & kernel size - (3x3)

- **Two Fully connected Layers**

### Model Training:

- Trained model using the dataset of 4800 images (2400 - cats & 2400 - dogs).
- Created more images for testing using `ImageDataGenerator`.
- Loss function used: `sparse_categorical_crossentropy`.
- Optimizer used: `Adam`.
- Trained model for **10 EPOCHS & 32 Batch size**.

### Model Evaluation:

- Model achieved an accuracy of around 90%
- Model was very good at predicting dogs. The recall of models for cats was slightly low.
- Model can be improved further by better capturing of features.
