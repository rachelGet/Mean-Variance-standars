
# Mean-Variance-Standard Deviation Calculator

## 📌 About the Project
A Python-based data analysis tool that calculates descriptive statistics for a 3x3 matrix. Given a list of 9 digits, this program converts the list into a 3x3 NumPy array and computes the mean, variance, standard deviation, max, min, and sum along both axes, as well as for the flattened matrix.

Built as part of the **freeCodeCamp Data Analysis with Python** curriculum.

## 🛠️ Tech Stack
- **Python 3**
- **NumPy** (for efficient matrix manipulation and statistical calculations)
- **unittest** (for automated testing)

## ✨ Features
- Converts a flat list of 9 numbers into a 3x3 matrix.
- Calculates statistics across **columns (axis 0)**, **rows (axis 1)**, and the **flattened matrix**.
- Handles invalid inputs gracefully by raising a `ValueError` if the list does not contain exactly 9 elements.
- Returns results as standard Python lists/dictionaries (no raw NumPy objects) for easy JSON serialization.

## 🚀 How to Run

### Prerequisites
Make sure you have Python installed. You will also need `numpy`.
```bash
pip install numpy