# AIML Lab Datasets 📊

A curated collection of standard Machine Learning and Data Science datasets in CSV format, paired with a minimalist dark-mode web portal for direct, one-click raw link copying into Google Colab, Jupyter Notebooks, and Python scripts.

## 🚀 Quick Usage in Python (Google Colab / Jupyter)

You can load any dataset directly using `pandas`:

```python
import pandas as pd

# Example: Load the Iris dataset
url = "https://raw.githubusercontent.com/SrujanK27/aiml-lab-datasets/main/iris.csv"
df = pd.read_csv(url)

print(df.head())
```

---

## 📁 Available Datasets

| Dataset | Filename | Common Use Case |
| :--- | :--- | :--- |
| **Auto MPG** | `auto-mpg.csv` | Regression / Fuel efficiency prediction |
| **Boston Housing** | `BostonHousing.csv` | Regression / Real estate price estimation |
| **Cricket Data Analysis** | `Cricket-Data-Analysis.csv` | Exploratory Data Analysis (EDA) |
| **Cricket Data Analysis (Edited)** | `Cricket-Data-Analysis - edited.csv` | Data cleaning & preprocessing |
| **Crop Recommendation** | `Crop Recommendation dataset.csv` | Multi-class Classification |
| **Diabetes** | `diabetes.csv` | Binary Classification (Pima Indians) |
| **Employees** | `employees.csv` | HR Analytics & Preprocessing |
| **Employees (Edited)** | `employees - edited.csv` | Data Cleaning / Missing values handling |
| **Fish Species** | `fish.csv` | Regression / Classification |
| **Iris** | `iris.csv` | Classification benchmark |
| **Mall Customers** | `Mall_Customers.csv` | K-Means Clustering / Customer Segmentation |
| **Marks** | `marks.csv` | Linear Regression / Student grading |
| **MTCars** | `mtcars.csv` | Classic regression & EDA |
| **Palmer Penguins** | `penguins.csv` | Classification / Multi-feature analysis |
| **Placement** | `placement.csv` | Binary Classification / Logistic regression |
| **Position Salaries** | `Position_Salaries.csv` | Polynomial Regression |
| **SEE Created** | `SEE created.csv` | Academic exam score analysis |
| **Student** | `student.csv` | Simple statistical analysis |
| **Tips** | `tips.csv` | Regression / Seaborn tutorial dataset |
| **Titanic** | `titanic.csv` | Binary Classification & Feature Engineering |

---

## 🌐 Web Portal (GitHub Pages)

This repository includes an `index.html` file that serves a web portal allowing students to quickly copy links.

To host it for free via GitHub Pages:
1. Navigate to **Settings** > **Pages** in this GitHub repository.
2. Under **Build and deployment** > **Branch**, select `main` and `/ (root)`.
3. Click **Save**.
4. Your site will be published at `https://srujank27.github.io/aiml-lab-datasets/`!
