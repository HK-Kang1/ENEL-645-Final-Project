Overview
This project investigates the task of age estimation from facial images using deep learning. Age estimation is a complex yet impactful problem in computer vision, with key applications in security, healthcare, marketing, and identity verification. Unlike humans, who can instinctively estimate age from facial features, training machines to do so requires handling variability in appearance, lighting, and image quality.

Using the UTKFace dataset (20,000+ labeled images), we implement and compare three state-of-the-art convolutional neural networks:

MobileNetV2

ResNet50

EfficientNet-B0

Each model is fine-tuned with custom layers and evaluated for performance across age groups. Images are categorized into four age bins: 0–25, 26–50, 51–75, and 76–116.

In addition to classification, the project uses Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize which regions of the face the models focus on during prediction, providing insight into the model's decision-making process.