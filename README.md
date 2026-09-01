# 🌱 OptiCrop
### Smart Agricultural Production Optimization Engine

> **Data-driven crop recommendation and agricultural decision-support platform.**

<p align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-OptiCrop-2ea44f?style=for-the-badge&logo=render&logoColor=white)](https://opticrop-4xnf.onrender.com/)
[![GitHub](https://img.shields.io/badge/GitHub-leona--1808%2FOpticrop-181717?style=for-the-badge&logo=github)](https://github.com/leona-1808/Opticrop)

</p>

[svg](https://github.com/leona-1808/Opticrop#opticrop-smart-agricultural-production-optimization-engine)

**Live Demo:** [https://opticrop-4xnf.onrender.com/](https://opticrop-4xnf.onrender.com/)
**GitHub Repository:** https://github.com/leona-1808/Opticrop

---

### 🧰 Built With

`Python 3.11` · `Flask` · `Scikit-learn` · `Pandas` · `NumPy` · `SciPy` · `Matplotlib` · `Seaborn` · `SQLite` · `HTML/CSS/JavaScript` · `Render`

---

## 📌 Overview

[svg](https://github.com/leona-1808/Opticrop#overview)

OptiCrop is a **Smart Agricultural Production Optimization Engine** designed to provide data-driven insights for agricultural decision-making.

The system analyzes important soil and environmental factors such as **Nitrogen (N), Phosphorous (P), Potassium (K), temperature, humidity, pH, and rainfall** to recommend suitable crops and assess crop suitability under given conditions.

The project combines **data preprocessing, machine learning, clustering, data visualization, and a Flask-based web application** to transform agricultural data into useful recommendations and insights.

---

## 🎯 Problem Statement

[svg](https://github.com/leona-1808/Opticrop#problem-statement)

Agricultural production depends significantly on soil quality and environmental conditions. Selecting a suitable crop without considering these factors can affect productivity and resource utilization.

OptiCrop addresses this problem by analyzing agricultural and environmental parameters and providing data-driven recommendations to support better crop selection and agricultural planning.

---

## 🎯 Objectives

[svg](https://github.com/leona-1808/Opticrop#objectives)

| **No.Objective** |                                                                      |
| ---------------- | -------------------------------------------------------------------- |
| 1                | Recommend suitable crops based on soil and environmental conditions. |
| 2                | Evaluate the suitability of a selected crop under given conditions.  |
| 3                | Analyze crop-environment relationships using agricultural data.      |
| 4                | Apply machine learning techniques to agricultural data.              |
| 5                | Provide a web-based platform for agricultural decision support.      |
| 6                | Support better production decisions and resource efficiency.         |

---

## ✨ Key Features

[svg](https://github.com/leona-1808/Opticrop#key-features)

| **FeatureDescription**      |                                                                                  |
| --------------------------- | -------------------------------------------------------------------------------- |
| Crop Recommendation         | Recommends a suitable crop using soil and environmental parameters.              |
| Crop Suitability Assessment | Evaluates whether conditions are suitable for a selected crop.                   |
| Data Preprocessing          | Processes the agricultural dataset and handles outliers before training.         |
| Machine Learning            | Uses Logistic Regression for crop classification.                                |
| K-Means Clustering          | Analyzes groups of similar agricultural conditions.                              |
| Data Analysis               | Performs correlation and feature distribution analysis.                          |
| Visualization               | Generates analytical graphs including correlation and clustering visualizations. |
| Web Application             | Provides an interactive interface using Flask.                                   |
| User Authentication         | Provides registration and login functionality.                                   |

---

## 🌾 Use Cases

[svg](https://github.com/leona-1808/Opticrop#use-cases)

### 1. Smart Crop Recommendation for Farmers

[svg](https://github.com/leona-1808/Opticrop#1-smart-crop-recommendation-for-farmers)

A farmer enters soil and environmental information such as Nitrogen, Phosphorous, Potassium, temperature, humidity, pH, and rainfall.

OptiCrop analyzes the provided parameters and recommends a suitable crop based on the trained model.

### 2. Crop Suitability and Environmental Assessment

[svg](https://github.com/leona-1808/Opticrop#2-crop-suitability-and-environmental-assessment)

A user can evaluate whether the current soil and environmental conditions are suitable for a particular crop.

The system analyzes the provided conditions and provides a crop suitability assessment.

### 3. Agricultural Research and Policy Planning

[svg](https://github.com/leona-1808/Opticrop#3-agricultural-research-and-policy-planning)

Agricultural researchers and stakeholders can use the system to analyze crop-environment relationships and identify patterns that can support data-driven agricultural planning.

---

## 🧪 Input Parameters

[svg](https://github.com/leona-1808/Opticrop#input-parameters)

| **ParameterDescription** |                               |
| ------------------------ | ----------------------------- |
| Nitrogen (N)             | Soil nitrogen level           |
| Phosphorous (P)          | Soil phosphorous level        |
| Potassium (K)            | Soil potassium level          |
| Temperature              | Environmental temperature     |
| Humidity                 | Environmental humidity        |
| pH                       | Soil acidity/alkalinity level |
| Rainfall                 | Rainfall measurement          |

---

## 🤖 Machine Learning

[svg](https://github.com/leona-1808/Opticrop#machine-learning)

### Data Preprocessing

[svg](https://github.com/leona-1808/Opticrop#data-preprocessing)

The agricultural dataset is processed before model training. The project performs preprocessing and handles outliers to prepare the data for machine learning.

### Logistic Regression

[svg](https://github.com/leona-1808/Opticrop#logistic-regression)

OptiCrop uses **Logistic Regression** for multi-class crop classification. The trained model is saved as:

```
model.pkl

```

**svg**

### K-Means Clustering

[svg](https://github.com/leona-1808/Opticrop#k-means-clustering)

The project uses **K-Means Clustering** to analyze groups of similar agricultural conditions.

An **Elbow Method** analysis is also generated as part of the clustering process.

### Generated Model Files

[svg](https://github.com/leona-1808/Opticrop#generated-model-files)

| **FilePurpose**        |                                   |
| ---------------------- | --------------------------------- |
| `model.pkl`            | Trained crop classification model |
| `crop_ranges.pkl`      | Crop parameter range information  |
| `cluster_insights.pkl` | Clustering-related insights       |

---

## 📊 Dataset

[svg](https://github.com/leona-1808/Opticrop#dataset)

The project uses the following agricultural dataset:

```
Crop_recommendation.csv

```

**svg**

The dataset contains soil and environmental parameters used for crop recommendation and model training.

| **Dataset AttributeDescription** |                       |
| -------------------------------- | --------------------- |
| N                                | Nitrogen              |
| P                                | Phosphorous           |
| K                                | Potassium             |
| Temperature                      | Temperature condition |
| Humidity                         | Humidity condition    |
| pH                               | Soil pH               |
| Rainfall                         | Rainfall condition    |
| Label                            | Crop category         |

---

## 🛠️ Technology Stack

[svg](https://github.com/leona-1808/Opticrop#technology-stack)

| **CategoryTechnologies** |                       |
| ------------------------ | --------------------- |
| Programming Language     | Python 3.11           |
| Web Framework            | Flask                 |
| Machine Learning         | Scikit-learn          |
| Data Processing          | Pandas, NumPy         |
| Scientific Computing     | SciPy                 |
| Data Visualization       | Matplotlib, Seaborn   |
| Database                 | SQLite                |
| Frontend                 | HTML, CSS, JavaScript |
| Version Control          | Git, GitHub           |
| Deployment               | Render                |

---

## 🏗️ System Architecture

[svg](https://github.com/leona-1808/Opticrop#system-architecture)

```
User
  |
  v
Web Interface
  |
  v
Flask Application
  |
  +---------------------------+
  |                           |
  v                           v
Input Processing          Database
  |
  v
Machine Learning Model
  |
  +---------------------------+
  |                           |
  v                           v
Crop Recommendation     Suitability Assessment
  |
  v
Agricultural Insights

```

**svg**

---

## 🔄 Project Workflow

[svg](https://github.com/leona-1808/Opticrop#project-workflow)

1. User provides soil and environmental parameters.
2. The Flask application receives the input.
3. The input is processed according to the project's data-processing workflow.
4. The trained machine learning model analyzes the parameters.
5. The application provides crop recommendations or suitability results.
6. Additional agricultural and clustering insights can be viewed through the application.

---

## ⚙️ Local Installation

[svg](https://github.com/leona-1808/Opticrop#local-installation)

### Prerequisites

[svg](https://github.com/leona-1808/Opticrop#prerequisites)

| **RequirementSpecification** |                                      |
| ---------------------------- | ------------------------------------ |
| Operating System             | Windows / Linux / macOS              |
| Python                       | Python 3.x                           |
| Recommended Python Version   | Python 3.11                          |
| IDE                          | Visual Studio Code or equivalent     |
| Internet Connection          | Required for installing dependencies |

### 1. Clone the Repository

[svg](https://github.com/leona-1808/Opticrop#1-clone-the-repository)

```
git clone https://github.com/leona-1808/Opticrop.git
cd OptiCrop

```

**svg**

### 2. Install Dependencies

[svg](https://github.com/leona-1808/Opticrop#2-install-dependencies)

```
pip install -r "5. Project Development Phase/requirements.txt"

```

**svg**

For Windows with Python 3.11:

```
py -3.11 -m pip install -r "5. Project Development Phase/requirements.txt"

```

**svg**

### 3. Initialize the Database

[svg](https://github.com/leona-1808/Opticrop#3-initialize-the-database)

```
py -3.11 "5. Project Development Phase/database.py"

```

**svg**

### 4. Train the Model

[svg](https://github.com/leona-1808/Opticrop#4-train-the-model)

```
py -3.11 "5. Project Development Phase/train_model.py"

```

**svg**

### 5. Start the Application

[svg](https://github.com/leona-1808/Opticrop#5-start-the-application)

```
py -3.11 "5. Project Development Phase/app.py"

```

**svg**

The application will run locally at:

```
http://127.0.0.1:5000/

```

**svg**

---

## 🧩 Application Modules

[svg](https://github.com/leona-1808/Opticrop#application-modules)

| **ModuleDescription** |                                                                    |
| --------------------- | ------------------------------------------------------------------ |
| Home                  | Main entry point of the OptiCrop application.                      |
| Find Your Crop        | Accepts agricultural parameters and provides crop recommendations. |
| Suitability           | Evaluates the suitability of a selected crop.                      |
| Insights              | Provides agricultural data and machine learning insights.          |
| Register              | Provides user registration functionality.                          |
| Login                 | Provides user authentication functionality.                        |

---

## 📚 Project Documentation

[svg](https://github.com/leona-1808/Opticrop#project-documentation)

Detailed project deliverables are available in:

```
7. Project Documentation/

```

**svg**

The documentation includes:

| **DocumentDescription**      |                                          |
| ---------------------------- | ---------------------------------------- |
| Project Executable Files     | Installation and execution guide         |
| Sample Project Documentation | System documentation and technical guide |

---

## ⭐ Project Links

- 🚀 **Live Application:** https://opticrop-4xnf.onrender.com/
- 💻 **Source Code:** https://github.com/leona-1808/Opticrop

<p align="center">
  <sub>OptiCrop — Smart Agricultural Production Optimization Engine</sub>
</p>
