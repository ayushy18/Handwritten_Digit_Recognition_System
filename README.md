🧠 Handwritten Digit Recognition System | Final Year Project

A Deep learning-based handwritten digit classification system that identifies digits (0–9) from image pixel data using a **Neural Network** trained on the MNIST-style dataset.  
This project demonstrates the workflow of real-world AI applications—from dataset preprocessing to model training, evaluation, and testing.

---

 📁 Project Overview

Handwritten digit recognition is a classical Deep learning problem used in fields like:

- Postal automation (ZIP code reading)
- Bank cheque processing
- Document digitization
- OCR-based systems

This project  focuses on developing a manually designed neural network architecture and training it with labeled digit images.

Model:https://aistudio.google.com/app/apps/drive/1Oqwl5renr1BjQodLNojfTfvGeAs5k_KM?showPreview=true&showAssistant=true&fullscreenApplet=true
---

🚀 Key Objectives

✔ Build a fully functional digit classifier  
✔ Train and evaluate the model using image dataset  
✔ Visualize dataset and training metrics  
✔ Demonstrate model performance and predictions  

---

🧪 Features

- Dataset cleaning & preprocessing
- Data visualization (sample images, label count)
- Train-test split strategy
- Fully functional Machine Learning pipeline
- Performance metrics (accuracy, loss graph, confusion matrix)
- Supports inference on new digit samples (optional)

---

## 🛠 Tech Stack

| Category | Technologies Used |
|---------|------------------|
| Language | Python |
| ML Libraries | NumPy, Pandas, Scikit-learn |
| Deep Learning | TensorFlow |
| Visualization | Matplotlib, Seaborn |
| Platform | Jupyter Notebook / Google Colab |

---

## 📦 Dataset

The project uses the following dataset files:

| File Name | Description |
|----------|-------------|
| `Train.csv` | Labeled pixel data for training |
| `test.csv` | Unlabeled/labeled data for testing |

- Each row contains **784 pixel values (28×28 image)** and a **label column** (for training).
- Pixel values range from **0 (white)** to **255 (black)**.

---

## 📂 Folder Structure

```

📁 Handwritten-Digit-Recognition
│
├── HandWritten_Digit_Recognition_System.ipynb   # Main project notebook
├── Train.csv
├── test.csv
├── README.md
└── requirements.txt

````

---

## 🧠 Model Architecture

| Layer Type | Description |
|-----------|-------------|
| Input Layer | Flattened 28×28 pixel image (784 neurons) |
| Hidden Layers | Fully connected layers with ReLU activation |
| Output Layer | 10 neurons (softmax) for digits 0–9 |

### Model Configuration (Example):

- **Optimizer:** Adam  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Metrics:** Accuracy  
- **Epochs:** 10–20 (modifiable)

---

## ⚙ Installation & Setup

### 📌 Step 1: Clone the Repo

```bash
git clone https://github.com/your-username/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition
````

### 📌 Step 2: Install Required Libraries

```bash
pip install -r requirements.txt
```

### 📌 Step 3: Open the Notebook

```bash
jupyter notebook
```

Or upload the `.ipynb` to Google Colab.

---

## ▶ Running the Model

1. Load the dataset
2. Normalize & preprocess pixel values
3. Train the neural network
4. Evaluate accuracy
5. Test predictions

---

## 📊 Results & Performance

| Metric            | Score      |
| ----------------- | ---------- |
| Training Accuracy | ** 96.81% ** |
| Test Accuracy     | **97.13%** |


---

## 🎓 Project Use Case

This project fulfills the academic requirements for a **Deep Learning Final Year Project**, showcasing:

* DL workflow understanding
* Data preprocessing techniques
* Neural network implementation skills
* Research, documentation, and evaluation knowledge


---

👨‍💻 Team Members:
Ayush Yadav
🎓 B.Tech Computer Science (Data Science & AI)
202210101150081
Nandini Agnihotri
🎓 B.Tech Computer Science (Data Science & AI)
202210101150066
Vaishali Gupta
🎓 B.Tech Computer Science (Data Science & AI)
202210101150068
Suyash Sharma
🎓 B.Tech Computer Science (Data Science & AI)
202210101150076

---

