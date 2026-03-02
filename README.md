# 🧠 Deep Learning Journey — From Zero to Hero

> **Starting from the very foundation: a Single Perceptron.**  
> Every complex neural network you'll ever see is built on this one simple idea.

---

## 📂 Repository Structure

```
deep-learning/
│
├── 📁 perceptron/
│   ├── 🔬 Single_Perceptron.ipynb          ← Chapter 1 (START HERE)
│   ├── 📊 college_student_placement_dataset.csv
│   └── 📁 plots/
│       ├── 01_placement_distribution.png
│       ├── 02_feature_distributions.png
│       ├── 03_correlation_heatmap.png
│       ├── 04_training_errors.png
│       ├── 05_confusion_matrix.png
│       ├── 06_perceptron_architecture.png
│       ├── 07_feature_weights.png
│       └── 08_decision_boundary.png
│
└── README.md
```

---

## 🗺️ Learning Roadmap

| # | Chapter | Status |
|---|---------|--------|
| **1** | 🔵 **Single Perceptron** — The first neuron | ✅ **Done** |
| 2 | 🟡 Multi-Layer Perceptron (MLP) | 🔜 Coming |
| 3 | 🟠 Backpropagation | 🔜 Coming |
| 4 | 🟢 Activation Functions Deep Dive | 🔜 Coming |
| 5 | 🔴 Convolutional Neural Networks (CNN) | 🔜 Coming |
| 6 | 🟣 Recurrent Neural Networks (RNN / LSTM) | 🔜 Coming |

---

## 🔵 Chapter 1: Single Perceptron

### 📖 What is a Perceptron?

A **Perceptron** is the **simplest artificial neuron** — the building block of all neural networks. Invented by **Frank Rosenblatt (1958)**, it takes inputs, multiplies them by weights, sums them up, and applies a step function.

$$\hat{y} = \text{step}\left(\sum_{i=1}^{n} w_i x_i + b\right)$$

### 🎯 Problem: Student Placement Prediction

We predict whether a college student gets **placed (1) or not placed (0)** based on:

| Feature | Description |
|---------|-------------|
| `IQ` | Student's IQ score |
| `CGPA` | Cumulative GPA |
| `Prev_Sem_Result` | Previous semester result |
| `Academic_Performance` | Academic score |
| `Internship_Experience` | Has internship? (0/1) |
| `Extra_Curricular_Score` | Extra activities score |
| `Communication_Skills` | Communication score |
| `Projects_Completed` | Number of projects done |

### 📊 Visualizations Included

| Plot | Description |
|------|-------------|
| 🥧 Placement Distribution | Class balance of the dataset |
| 📈 Feature Distributions | How each feature differs between classes |
| 🔗 Correlation Heatmap | Feature relationships |
| 📉 Training Error Curve | Perceptron learning over epochs |
| 🟦 Confusion Matrix | Model prediction quality |
| 🧠 Architecture Diagram | Visual of perceptron with weights |
| ⚖️ Feature Weights | Which features matter most |
| 🎯 Decision Boundary | 2D separation line (IQ vs CGPA) |

### 🧪 Key Concepts Demonstrated

- ✅ Perceptron learning algorithm (from scratch with NumPy)
- ✅ Step activation function
- ✅ Weight update rule: `w = w + η*(y - ŷ)*x`
- ✅ Feature scaling with `StandardScaler`
- ✅ Decision boundary visualization
- ✅ Comparison with `sklearn.linear_model.Perceptron`

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/deep-learning.git
cd deep-learning

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

# Launch the notebook
jupyter notebook perceptron/Single_Perceptron.ipynb
```

---

## 💡 Key Takeaway

> A perceptron can only separate **linearly separable** data.  
> That's why we need **Multi-Layer Perceptrons** with non-linear activations — which we'll build next! 🚀

---

*Made with ❤️ | Starting the deep learning journey one neuron at a time.*
