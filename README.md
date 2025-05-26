# Handwritten Digit Classifier with Logistic Regression

This project is a **handwritten digit classification app** built as part of the **COMP 472 – Artificial Intelligence** course (Summer 2025). It utilizes the MNIST dataset and demonstrates how to use basic machine learning tools in Python, specifically `NumPy`, `scikit-learn`, and `matplotlib`.

## 📌 Objective

To classify digits (0–9) from grayscale images using a **logistic regression model**, providing a basic introduction to AI libraries in Python.

## 🧠 What It Does

* Loads the MNIST handwritten digits dataset.
* Visualizes some training images for exploration.
* Reshapes and prepares the data for training/testing.
* Trains a logistic regression model using scikit-learn.
* Evaluates performance with a confusion matrix and classification report.

## 🔧 Technologies Used

* **Python 3**
* [NumPy](https://numpy.org/) – for array manipulation and data preparation.
* [Matplotlib](https://matplotlib.org/) – for visualizing digit images and model performance.
* [scikit-learn](https://scikit-learn.org/) – for building and evaluating the logistic regression model.
* [Seaborn](https://seaborn.pydata.org/) – for better heatmap visualization of the confusion matrix.
* [Keras](https://keras.io/) – to load the MNIST dataset easily.

## 📁 Project Structure

```
.
├── project1_comp472.py    # Main code file with training, evaluation, and visualization
└── README.md              # This file
```

## 📊 Sample Output

* **Digit Samples** – Visual inspection of images from the dataset.
* **Confusion Matrix** – Displayed using both `matplotlib` and `seaborn`.
* **Classification Report** – Shows precision, recall, and F1-score per digit.

## 🧪 How to Run

1. Make sure you have Python 3 installed.
2. Install required libraries (if not already installed):

```bash
pip install numpy matplotlib seaborn scikit-learn keras
```

3. Run the script:

```bash
python project1_comp472.py
```

## 📈 Performance

The model’s accuracy is assessed using:

* **Confusion Matrix** – for detailed prediction insights.
* **Classification Report** – for precision, recall, and F1-score.

> Note: This is a simple baseline model intended to demonstrate understanding of core concepts, not to maximize accuracy.

## 🧑‍🤝‍🧑 Authors

This project was completed as part of a team assignment for COMP 472. Replace the placeholders below with actual names and student IDs:

* **Jonathan Mehmannavaz** – 40210330

## 🎓 Course Info

**COMP 472 – Artificial Intelligence**
**Term:** Summer 2025
**University:** Concordia University

---

