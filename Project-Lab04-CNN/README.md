# Lab 04 – CNN for MNIST Handwritten Digit Classification

**Course:** ITAI 2376 – Deep Learning  
**Dataset:** MNIST (28×28 grayscale digits)

I built a **Convolutional Neural Network (CNN)** in Keras to classify MNIST digits:

- Data: normalized to [0,1], reshaped to (28, 28, 1), labels one-hot encoded  
- Architecture:
  - Conv2D(32, 3×3, ReLU) + MaxPooling2D
  - Conv2D(64, 3×3, ReLU) + MaxPooling2D
  - Flatten → Dropout(0.5) → Dense(10, softmax) :contentReference[oaicite:5]{index=5}  

## File

- `Lab04_CNN_BinteZahra_ITAI2376.pdf` – full Colab notebook export (code + explanations)

## What I Learned

- How CNNs extract features from images  
- Why normalization, pooling, and dropout matter  
- Basic hyperparameters (epochs, batch size) for training
