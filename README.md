# Image Classification Project: Pikachu vs Rondoudou

## 📋 Project Description
This project uses a Convolutional Neural Network (CNN) with TensorFlow/Keras to classify Pokémon images, specifically distinguishing between Pikachu and Rondoudou.

## 🏗️ Model Architecture
The CNN model follows this architecture:
- Preprocessing layer: Rescaling (pixel normalization between 0 and 1)
- 4 convolutional layers with ReLU activation
- 4 MaxPooling layers
- Flatten layer
- Fully-connected dense layer (64 neurons)
- Output layer with softmax activation (2 classes)

## 📊 Dataset
- **Split**: 80% training (140 images), 20% validation (34 images)
- **Classes**: ['pikachu', 'rondoudou']
- **Image dimensions**: 200×200 pixels
