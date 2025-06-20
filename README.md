
# Fashion MNIST ANN with PyTorch & Optuna

This project demonstrates how to build, train, and optimize an Artificial Neural Network (ANN) to classify clothing images from the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) using PyTorch. The model's hyperparameters are tuned using Optuna.

---

## 📌 Project Highlights

- 📊 Exploratory Data Analysis with Matplotlib
- 🧼 Data normalization and preprocessing
- 🧠 Custom ANN built with PyTorch
- 🔁 Batch training with `DataLoader`
- 🎯 Hyperparameter tuning using Optuna
- 🖥️ GPU support with CUDA
- 📈 Final evaluation using test accuracy

---

## 📂 Dataset

The dataset is split into 7 CSV files hosted on GitHub:
- Each file contains a portion of the Fashion MNIST dataset.
- Images are 28x28 grayscale, flattened to 784 features.
- Labels range from 0–9, representing clothing categories.

---

## 🧪 Hyperparameters Tuned

- Number of hidden layers
- Neurons per layer
- Learning rate
- Dropout rate
- Batch size
- Optimizer type
- Weight decay
- Number of epochs

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/pranta-iitp/fashion-mnist-ann-optuna.git
   cd fashion-mnist-ann-optuna
   ```

2. **Set up environment:**

   Install dependencies (you may want to use a virtual environment):

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**

   Open in Jupyter Notebook or Google Colab:

   * [Google Colab Link](https://colab.research.google.com/drive/1hmR-0BZGaLoxSWeIJqYDymPssqRI5ysJ)

---

## 🛠 Requirements

* Python 3.8+
* PyTorch
* Optuna
* NumPy
* Pandas
* Matplotlib
* scikit-learn

---

## 📊 Result

After 10 trials with Optuna, the best test accuracy and corresponding hyperparameters are displayed. These can be used to retrain the final model.

---

## 📎 Future Improvements

* Package code into a Python project
* Save trained model using `torch.save`
* Convert to API with Flask or FastAPI
* Deploy using Docker
* Add experiment tracking with MLflow

---

## 🧑‍💻 Author

**Pranta Pratim Roy**

---
