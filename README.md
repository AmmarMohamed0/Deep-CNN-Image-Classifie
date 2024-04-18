# Deep-CNN-Image-Classifie

This Python script demonstrates building, training, evaluating, and using a deep learning model to classify images as "Happy" or "Sad". 

- **Importing Dependencies**: This section imports necessary libraries such as TensorFlow, OpenCV (cv2), and other utilities for handling images and data.

- **Remove Dodgy Images**: It removes images from the dataset that are not of the expected image file types.

- **Load Data**: It loads the image data from a directory into TensorFlow datasets and preprocesses it.

- **Build Deep Learning Model**: This section defines a convolutional neural network (CNN) model using TensorFlow's Sequential API.

- **Train**: The model is trained using the loaded data and validates it on a validation set.

- **Plot Performance**: It plots the training and validation loss and accuracy over epochs to visualize the model's performance during training.

- **Evaluate Performance**: The model's performance metrics such as precision, recall, and accuracy on a test set are evaluated.

- **Test**: It tests the model's prediction on a single image.

- **Save the Model**: The trained model is saved to a file and loaded back to make predictions.

- **System**: It defines a function `load_and_predict` to load an image, preprocess it, and make predictions using the saved model.

- I used the `Download All images` Extension to download images.
