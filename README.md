Skin Disease Classification using CNN

This project is a deep learning-based image classification model to detect and classify four types of skin diseases using Convolutional Neural Networks (CNNs).

Features
- Custom CNN model for skin disease classification  
- Classification into 4 categories:  
  - Basal Cell Carcinoma  
  - Melanoma  
  - Nevus  
  - Pigmented Benign Keratosis  
- Comparison with 5 pretrained models:  
  - MobileNetV2  
  - EfficientNetV2  
  - ResNet50  
  - DenseNet121  
  - Xception  
- Data augmentation applied during training  
- Evaluation based on accuracy and performance metrics

Dataset
- 1428 training images  
- 140 validation images  
- 4 classes of skin disease

Tech Used
- Python  
- TensorFlow / Keras  
- CNN architecture (custom + pretrained models)  
- Image preprocessing and augmentation

Input
- Input: Single image for Skin disease prediction (`.jpg`, `.png`)  
- Format: RGB image, resized as per model requirement (e.g., 224x224)  

Output
- Predicted disease class (one of the four)  
- Model accuracy and loss  
- Comparison of performance across different pretrained models  
- Confusion matrix or classification report
