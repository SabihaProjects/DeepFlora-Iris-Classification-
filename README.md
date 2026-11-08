# DeepFlora-Iris-Classification-
Iris flower classification using Deep Learning and Artificial Neural Networks.
# 🌸 DeepFlora – AI-Powered Iris Species Classification

## 📌 Project Overview
DeepFlora is a Deep Learning project focused on classifying Iris flowers into three species: Iris-setosa, Iris-versicolor, and Iris-virginica using Artificial Neural Networks (ANN).

The project explores how machine learning and neural networks can learn patterns from flower measurements and make accurate classification predictions.

## 🎯 Project Objectives
- Explore and understand the Iris flower dataset.
- Analyze relationships between flower measurements.
- Perform data preprocessing and feature scaling.
- Implement a baseline Perceptron model.
- Develop an Artificial Neural Network (ANN).
- Evaluate and compare model performance.

## 📊 Dataset Description
The project uses the Iris dataset containing 150 records and the following columns:

| Column | Description |
|---|---|
| Id | Sample identifier |
| SepalLengthCm | Sepal length |
| SepalWidthCm | Sepal width |
| PetalLengthCm | Petal length |
| PetalWidthCm | Petal width |
| Species | Target class |

The dataset contains three species, with 50 samples per species.

## 🛠️ Technologies & Libraries
- Python
- NumPy – Numerical operations
- Pandas – Data handling
- Matplotlib – Data visualization
- Seaborn – Exploratory data analysis
- Scikit-learn – Preprocessing, Perceptron and evaluation
- TensorFlow / Keras – ANN development

## ⚙️ Project Workflow
1. Dataset loading and inspection
2. Exploratory Data Analysis (EDA)
3. Feature and target separation
4. Label encoding and data splitting
5. Feature scaling using StandardScaler
6. Perceptron model implementation
7. Artificial Neural Network development
8. Model evaluation and comparison

## 📈 Model Results

| Model | Test Accuracy |
|---|---:|
| Perceptron | 86.67% |
| Artificial Neural Network (ANN) | 96.67% |

The ANN achieved higher test accuracy than the baseline Perceptron model.

## 📁 Project Structure

```text
DeepFlora-Iris-Classification/
│
├── ANN_Project.ipynb
├── Iris.csv
└── README.md
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `ANN_Project.ipynb` in Jupyter Notebook or Google Colab.
4. Make sure `Iris.csv` is available in the project directory.
5. Run the notebook cells sequentially.

## 🚀 Future Scope
- Experiment with additional neural network architectures.
- Explore larger flower image datasets.
- Develop an interactive flower classification application.
- Extend the project towards image-based flower recognition.

## 👩‍💻 Author

**Sabiha Parveen**  
Aspiring AI & ML Engineer

---

*DeepFlora – Turning Data into Intelligent Predictions.*
