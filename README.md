
# 🔢 Handwritten Digit Classification

A deep learning project that classifies handwritten digits from the **MNIST dataset** using a neural network built with **TensorFlow and Keras**.

## 📌 Project Overview

The MNIST dataset contains grayscale images of handwritten digits from **0 to 9**. The goal of this project is to train a neural network that can correctly identify the digit represented by an unseen image.

The images are normalized and passed through a simple fully connected neural network.

## 🧠 Model Architecture

```text
Input Image (28 × 28)
        ↓
     Flatten
        ↓
Dense Layer (128 neurons, ReLU)
        ↓
Dense Layer (10 neurons, Softmax)
        ↓
   Digit Prediction
```

## ⚙️ Training Configuration

| Parameter           | Value                           |
| ------------------- | ------------------------------- |
| Dataset             | MNIST                           |
| Training Images     | 60,000                          |
| Test Images         | 10,000                          |
| Input Size          | 28 × 28                         |
| Hidden Layer        | 128 neurons, ReLU               |
| Output Layer        | 10 neurons, Softmax             |
| Optimizer           | Adam                            |
| Loss Function       | Sparse Categorical Crossentropy |
| Epochs              | 5                               |
| Validation Split    | 10%                             |
| Pixel Normalization | Division by 255                 |

## 📊 Results

The trained model achieved:

**Test Accuracy: 97.74%**

**Test Loss: 0.0731**

### Training Accuracy

![Training Accuracy](training_accuracy(1).png)

### Training Loss

![Training Loss](training_loss(1).png)

## 🔍 Predictions

The trained model was also used to generate predictions on previously unseen handwritten digit images.

The notebook includes visualizations comparing the model's predictions with the actual digit labels.

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

## 📂 Repository Contents

```text
handwritten-digit-classification/
│
├── Handwritten_digit_classification.ipynb
├── README.md
├── training_accuracy.png
└── training_loss.png
```

## 🚀 How to Run

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib jupyter
```

Then launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `Handwritten_digit_classification.ipynb` and run the cells.

## 📚 What I Learned

Through this project, I gained practical experience with:

* Neural network architecture
* Image classification
* TensorFlow and Keras
* Dense layers
* ReLU activation
* Softmax activation
* Image normalization
* Model training and validation
* Evaluating classification performance
* Visualizing training accuracy and loss
* Making predictions using a trained neural network

---

⭐ Thanks for visiting this project!
