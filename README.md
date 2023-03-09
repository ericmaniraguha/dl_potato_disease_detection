# Deep learning for diseases detection using CNN.

Potato diseases can lead to significant yield losses and reduce the quality of potatoes. Identifying diseases early can help prevent or minimize these losses. In recent years, deep learning techniques such as convolutional neural networks (CNN) have shown promising results in detecting diseases in plants. This project focuses on using a CNN to detect potato diseases from images. By leveraging the power of deep learning, we aim to create an accurate and reliable system for detecting potato diseases that can assist farmers in making informed decisions about their crops.

NB: There are two diseases of potatoes (Early Blight and Late Bright)
data source : https://www.kaggle.com/datasets/arjuntejaswi/plant-village?resource=download 

#### Steps used:
1. Data collection
2. Data cleaning and processing (tf dataset and data augmentation) -> ML Ops(Machine Learning Operations)
- Data augmentation -> as we do not have enough images we need to rotate to create more training samples
3. Model building with CNN --> for image classification
4. ts serving --> FastAPi
5. Deployment GCP (google cloud )where it will be able to called by an App through the phone.
6. react native -> for scanning the diseases 
We will be having three classifications (Healthy, Early Bright and Late Bright)
##### Model building: 
1. TensorFlow 
2. CNN
3. data augmentation
4. tf dataset

##### Backend server
1. tf serving 
2. FastAPI

##### Model Optimization
1. Quantization 
2. TensorFlow Lite

##### Frontend and deployment --> this may come after, 
1. React JS
2. React Native 
3. Deployment tp GCP
