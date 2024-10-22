# MultiNetEmotion - Real-time Emotion Detection for E-Learning Platforms

## Project Summary
MultiNetEmotion is an emotion detection model designed to recognize six distinct human emotions: Angry, Fear, Happy, Neutral, Sad, and Surprise. The model leverages a custom deep learning framework that combines the strengths of ResNet50 and VGG16 architectures for robust feature extraction and classification. The system is built to integrate into e-learning platforms, providing real-time emotional insights into user behavior to enhance the learning experience.

## Key Features
- **Model Architecture**: The model employs a hybrid structure combining ResNet50 and VGG16 for feature extraction, followed by dense layers and dropout for effective classification.
- **Emotion Classes**: The system detects six emotions: Angry, Fear, Happy, Neutral, Sad, and Surprise.
- **Real-time Emotion Detection**: Designed to be integrated into applications for real-time emotion recognition using live camera feeds.
- **Personalized Recommendations**: Based on the detected emotions, the system offers personalized content suggestions, such as light-hearted videos if negative emotions are detected.

## Training and Evaluation
- The model was trained on a labeled dataset of facial expressions and achieved an accuracy of **60%** on the validation set.
- A comprehensive evaluation using confusion matrices, precision, recall, and F1-score was performed to analyze model performance across all emotion categories.
- The training was carried out over **10 epochs**, with significant improvements in training accuracy but signs of overfitting after the 5th epoch.

## Deployment
The system is designed to be deployed on e-learning platforms, where it tracks student emotions in real-time and recommends suitable content to improve engagement and learning outcomes.

## Conclusion
This project serves as an advanced emotion recognition tool for improving user experiences in educational environments. By addressing emotional states, it aims to foster better engagement and cater to student well-being.
