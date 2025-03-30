# 🧠 CIFAR-10 CNN Enhancer – Neural Networks

The aim was to improve the classification accuracy of a CNN model on the CIFAR-10 dataset through architecture tuning, data augmentation, and dropout regularization.

---

## 📦 Dataset

[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) – a 60,000-image dataset across 10 classes like airplane, bird, cat, deer, dog, etc.

---

## 🧠 Key Enhancements

### 🔁 Data Augmentation
- `RandomHorizontalFlip()`
- `RandomCrop(32, padding=4)`

### 🧱 Model Architecture
- Intermediate block improvements:
  - Dropout for regularization
  - Adapted fully connected layers
- Output block:
  - Multiple FC layers with ReLU activation
  - Final FC layer outputs raw logits

### 🧪 Initialization & Optimisation
- Xavier (Glorot) initialization for weights
- **Adam Optimizer** with CrossEntropy Loss

---

## 📊 Training Results

- Accuracy increased gradually across epochs
- Final **Test Accuracy: 62%**
- Visualization of loss and accuracy over epochs

<p align="center">
  <img src="screenshots/final_plot.png" width="600"/>
</p>

---

## 📂 Project Structure

- `Final_Score.ipynb` – Full notebook including architecture, training, and evaluation
- `ECS659P_Neural_Network_Report.pdf` – Coursework documentation and analysis

---

## 🚀 How to Run

1. Clone the repository  
2. Run `Final_Score.ipynb` in Jupyter Notebook  
3. Required Libraries:
   - `torch`, `torchvision`, `numpy`, `matplotlib`

---

## 🏫 Module Info

- 📅 Year: 2023/24  
- 🏫 University: Queen Mary University of London  
- 👨‍💻 Author: Vickshan Vicknakumaran

---

## 📜 License

For educational and research purposes only.
