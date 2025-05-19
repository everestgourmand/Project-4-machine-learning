# Project-4-machine-learning

Open the or Colab file.

Upload the fire_incidents.csv file.

Run all cells in order.

View model accuracy, classification report, and confusion matrix.

# 🔥 Fire Incident Classification using PySpark

This project builds a machine learning pipeline in **PySpark** to classify fire incidents based on historical NYC fire department data. It involves data preprocessing, feature engineering, model training, and evaluation using a **Random Forest Classifier**.

## 📁 Dataset

The dataset used is `fire_incidents.csv`, which includes the following features:

- `Year`
- `IncidentNumber`
- `Timestamp`
- `Borough`
- `Battalion`
- `Division`
- `Station`
- `Structure Type`
- `Cause of Incident`
- `Fire Category`

## 🧪 Objective

Predict the **Cause of Incident** (or optionally, the **Fire Category**) from various features including time, location, and structural data.

1. Environment & Dependencies
Python 3 (Colab, local, or cloud environment)

Apache Spark 3.4.1

Java 11

Python packages:

pyspark

findspark

matplotlib, seaborn (for visualization)

pandas

scikit-learn (for evaluation)

2. Data Input
Clean and complete version of fire_incidents.csv with:

Proper timestamp formatting


Author
Developed by [everestgourmand]


---

Let me know if you want a version targeted toward deployment (e.g., for AWS or Databricks), or if you'd like to include Jupyter notebook links, CLI usage, or model inference examples.
