# Image-segmentation
Self-Driving Car Image Segmentation for Indian Roadways

This project focuses on building an end-to-end image segmentation model aimed at enhancing self-driving car systems in India’s diverse road environments. Using a dataset of over 10,000 annotated images across 40 classes, the model was designed to address challenges such as class imbalance and complex road conditions.

Key Features:

Utilized a U-Net architecture with a pre-trained ResNet-34 encoder for multi-class semantic segmentation.
Implemented data augmentation techniques to increase robustness and improve model performance.
Employed Focal Loss and Dice Loss to handle class imbalance and achieve high segmentation accuracy.
Evaluated model performance with metrics like Dice Coefficient and Intersection over Union (IoU), achieving an average Dice Coefficient of 0.9321%.
Future work includes optimizing the model for real-time inference on low-power edge devices and leveraging transfer learning to improve adaptability across different road conditions.
