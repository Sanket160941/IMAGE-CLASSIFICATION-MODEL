# IMAGE-CLASSIFICATION-MODEL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: CTIS6838

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
In this task, we focused on building a complete image classification system using a Convolutional Neural Network (CNN) with TensorFlow. The primary goal was to classify different types of flower images into their respective categories. For this purpose, we used a flower dataset consisting of five classes: daisy, dandelion, rose, sunflower, and tulip. To make the dataset more manageable and suitable for training, it was resized and organized into structured folders, where each folder represented a specific flower category. Additionally, we ensured consistency by limiting the dataset size and renaming images properly for better handling.

The model development process began with loading the dataset using TensorFlow’s image data pipeline. We used image_dataset_from_directory to automatically assign labels based on folder names and split the dataset into training and validation sets. This helped in evaluating how well the model generalizes to unseen data. Before feeding the images into the model, preprocessing steps such as resizing and normalization were applied to ensure uniform input dimensions and stable training. To build the classification model, we designed a Convolutional Neural Network (CNN) using TensorFlow and Keras. The architecture included multiple convolutional layers to extract features from images, followed by max-pooling layers to reduce spatial dimensions and prevent overfitting. After feature extraction, the data was flattened and passed through dense (fully connected) layers to perform classification. The final layer used a softmax activation function to output probabilities for each flower class.

Initially, the model achieved moderate accuracy, but there was a noticeable gap between training and validation performance, indicating overfitting. To address this, several improvements were implemented. Data augmentation techniques such as random flipping, rotation, and zooming were introduced to increase dataset variability and help the model generalize better. Dropout layers were also added to reduce overfitting by randomly disabling neurons during training. Furthermore, optimization techniques like learning rate tuning, early stopping, and batch normalization were used to stabilize and improve model performance. For even better accuracy, transfer learning using a pre-trained model such as MobileNetV2 was applied, which significantly boosted the validation accuracy close to 85%.

After successfully training and optimizing the model, the next step was deployment. A Flask-based web application was developed to make the model accessible through a user-friendly interface. The application allows users to upload an image of a flower, which is then processed and passed to the trained CNN model for prediction. The result is displayed along with the predicted flower name and confidence score. To enhance user experience, a decorative interface with drag-and-drop functionality and image preview was implemented using HTML, CSS, and Python.

This task demonstrates the complete pipeline of an image classification system, from dataset preparation to model building, optimization, and deployment. Such systems have wide real-world applications, including plant identification, agricultural monitoring, biodiversity research, and mobile applications for recognizing objects. It also provides a strong foundation in deep learning concepts and practical experience in integrating machine learning models with web applications. Overall, this task not only helped in understanding CNN architectures and TensorFlow implementation but also provided valuable experience in improving model performance and deploying AI solutions in a real-world scenario.
