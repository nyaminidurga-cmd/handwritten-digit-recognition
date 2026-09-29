# ✏️ Handwritten Digit Recognition using CNN

A deep learning project built with Python and TensorFlow/Keras that recognizes handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

## 🚀 Features
- **High Accuracy:** Trained on 60,000 images with >98% test accuracy.
- **Interactive UI:** Web interface powered by Gradio to draw custom digits live in the browser.
- **Preprocessing Pipeline:** Automatic color inversion (white-on-black) and array scaling.

## 🛠️ Tech Stack
- **Framework:** TensorFlow / Keras
- **Libraries:** NumPy, PIL, Matplotlib
- **Web App:** Gradio
- **Environment:** Google Colab (GPU)

## 📊 Model Architecture
1. **Conv2D** (32 filters, 3x3 kernel, ReLU)
2. **MaxPooling2D** (2x2)
3. **Conv2D** (64 filters, 3x3 kernel, ReLU)
4. **MaxPooling2D** (2x2)
5. **Flatten** & **Dense** (128 units, Dropout 0.2)
6. **Output Dense Layer** (10 units, Softmax)

## 🏃 How to Run
1. Open `Handwritten_Digit_Recognition.ipynb` in Google Colab.
2. Run all cells sequentially.
3. Open the generated Gradio live link to test drawings!
