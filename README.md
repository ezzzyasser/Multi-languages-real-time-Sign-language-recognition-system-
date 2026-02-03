Integrative Real-Time Sign Language Recognition for Enhanced Communication

Project Overview
This project focuses on bridging the communication gap between the deaf-mute community and the general public. It features an integrative real-time system capable of recognizing multiple sign languages, providing text outputs, and incorporating advanced features like text-to-speech and spelling correction.

Key Features
 * Multi-Language Support: Recognizes American Sign Language (ASL), Arabic Sign Language (ARSL), and Brazilian Sign Language (BSL).
 * Real-Time Recognition: Optimized for real-time performance in public settings such as hospitals, schools, and companies.
 * Spelling Correction: Includes a dedicated demo for word spelling correction to improve communication accuracy.
 * Assistive Modalities: Integrated text-to-speech for non-readers and speech-to-text to assist the deaf-mute population in receiving verbal communication.
 
System Architecture & Models
The system utilizes diverse deep learning architectures tailored for specific sign language datasets:
 * EfficientNetB0: Utilized for ASL recognition, achieving a high performance of 99.7% accuracy.
 * CNN (Convolutional Neural Network): Applied to the Arabic Sign Language dataset, reaching 96.53% accuracy.
 * VGG19: Implemented for video-frame-based recognition (BSL) to capture intricate spatial hand gestures.
 * SVM with HOG Features: Used as a powerful alternative classifier for large image datasets.

Datasets
 * ASL Dataset: A merged dataset of four American Sign Language sources, totaling 367,528 images across 29 classes.
 * ARSL Dataset: An Arabic Sign Language dataset consisting of 50,000 images and 32 classes.
 * BSL Dataset: A Brazilian Sign Language word dataset comprising 3,832 video frames across 15 classes.
 
Methodology
 * Data Collection: Gathering and merging diverse sign language datasets.
 * Preprocessing: Noise removal, grayscale conversion, and data augmentation.
 * Model Selection & Training: Comparative analysis of VGG19, EfficientNet, CNN, and LSTM architectures.
 * Evaluation: Rigorous testing to ensure high accuracy and real-world feasibility.
 
Tools & Technologies
 * Languages: Python
 * Frameworks/Libraries: PyTorch, CNN, HOG (Histogram of Oriented Gradients)
 * Platforms: Jupyter Notebook, Google Colab, Kaggle
 
Future Enhancements
 * Expanding support for additional sign language dialects.
 * Improving model scalability for resource-constrained mobile environments.
 * Developing more comprehensive video datasets to enhance motion-based recognition.
