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

*OUTPUTS*:
<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/d4be39fc-bac0-4bb9-a953-e8947e33551b" />

<img width="1928" height="1169" alt="Image" src="https://github.com/user-attachments/assets/c09c82b4-fb8a-4273-a979-81207eafdfbf" />

<img width="2102" height="1257" alt="Image" src="https://github.com/user-attachments/assets/1fccf361-09a1-48a4-ac87-ade628e87df6" />

<img width="2559" height="1306" alt="Image" src="https://github.com/user-attachments/assets/cd6096b2-6a76-4342-a7d9-4a0521d6aed0" />

<img width="2557" height="1250" alt="Image" src="https://github.com/user-attachments/assets/b5283ff0-35d2-4941-9d7e-1a91bfab64e5" />

<img width="2559" height="1006" alt="Image" src="https://github.com/user-attachments/assets/2f3e0df5-075d-4f85-b7c3-49ebaebd9595" />

<img width="2559" height="1284" alt="Image" src="https://github.com/user-attachments/assets/e81186db-a292-4ffe-a267-89acce3504e6" />

<img width="1969" height="1179" alt="Image" src="https://github.com/user-attachments/assets/e44ea60a-a53d-4186-91ea-e813b836b22f" />

<img width="2085" height="1274" alt="Image" src="https://github.com/user-attachments/assets/089d12cc-276c-4106-a481-ce616cb30b55" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/b3b3c547-002c-4057-aecc-62524b9ec9c6" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/ead00884-756f-4ad8-9000-528e08fb8a99" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/9a4d67b8-fcb7-4133-bbb4-844fff6a02b7" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/8e9819b6-37a5-40e4-8195-23fee52f09fe" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/8b06b612-be56-4926-bf9c-1c8691600847" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/b823e134-bdcf-4c0f-b6af-b3070ce4d581" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/cca9fa7f-2639-43a8-b394-5a0b189ad960" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/5ef9430e-a665-420a-8620-e59329494904" />
