# Dialy_DSA-100-days

## Daily Log

### Day 25 - June 17, 2024

**Today's Focus:** AI Diagnostics using CNN for Hackathon

**Resources Used:**
- 📖 [Deep Learning with Python by François Chollet](https://www.amazon.com/Deep-Learning-Python-Francois-Chollet/dp/1617294438)
- 🌐 [TensorFlow Documentation](https://www.tensorflow.org/guide)

**Activities:**
- 📝 Focused on the AI diagnostics project for the hackathon.
- 📌 Implemented a Convolutional Neural Network (CNN) for diagnostic purposes.

**Detailed Notes:**
- 📝 AI Diagnostics using CNN:
  - Convolutional Neural Networks (CNNs) are a class of deep neural networks, most commonly applied to analyzing visual imagery.
  - They are inspired by biological processes, where the connectivity pattern between neurons resembles the organization of the animal visual cortex.

**Code Snippets:**
```python
# Example of a simple CNN in TensorFlow
import tensorflow as tf
from tensorflow.keras import layers, models

model = models.Sequential()
model.add(layers.Conv2D(32, (3, 3), activation='relu', input_shape=(150, 150, 3)))
model.add(layers.MaxPooling2D((2, 2)))
model.add(layers.Conv2D(64, (3, 3), activation='relu'))
model.add(layers.MaxPooling2D((2, 2)))
model.add(layers.Conv2D(64, (3, 3), activation='relu'))

model.add(layers.Flatten())
model.add(layers.Dense(64, activation='relu'))
model.add(layers.Dense(10, activation='softmax'))

model.compile(optimizer='adam', loss='sparse_categorical_crossentropy', metrics=['accuracy'])
Reflections:

🤔 CNNs are highly effective for image recognition tasks and can be crucial for medical diagnostics.
🚀 This project will provide valuable experience in applying deep learning to real-world problems.
Next Steps:

🔜 Continue refining the CNN model for better accuracy.
🔜 Prepare for the next hackathon tasks and integrate the CNN into the full diagnostics workflow.
