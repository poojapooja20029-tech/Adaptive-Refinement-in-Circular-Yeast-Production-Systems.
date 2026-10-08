
# Adaptive Refinement in Circular Yeast Production Systems

## 📌 Project Overview

**Adaptive Refinement in Circular Yeast Production Systems** is a Django-based web application designed to support yeast production monitoring, yield prediction, and process optimization using machine learning.

The system analyzes important production parameters such as **temperature, pH, sugar concentration, and fermentation time** to predict yeast biomass/yield and support better production decisions.

## 🎯 Objectives

* Collect and manage yeast production data
* Monitor important fermentation parameters
* Predict yeast production yield using machine learning
* Support process optimization
* Provide a web-based interface for production data management
* Reduce production waste through data-driven analysis

## 🛠️ Technologies Used

* **Python**
* **Django**
* **Machine Learning**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **HTML**
* **CSS**
* **SQLite / MySQL**
* **Git & GitHub**

## 📊 Input Parameters

The system works with production parameters including:

* Temperature
* pH
* Sugar concentration
* Fermentation time
* Biomass / Yield

## ⚙️ System Workflow

```text
Production Data
       ↓
Data Preprocessing
       ↓
Machine Learning Model
       ↓
Yield Prediction
       ↓
Django Web Application
       ↓
Process Monitoring & Optimization
```

## 🚀 Key Features

* Production data collection
* Yeast production monitoring
* Machine learning-based yield prediction
* Process optimization support
* Django-based web interface
* Admin panel for managing production data

## 📁 Project Structure

```text
yeast_project_main/
│
├── config/
├── yeast/
├── templates/
├── static/
├── manage.py
├── requirements.txt
├── db.sqlite3
└── README.md
```

## 💻 Installation & Setup

### 1. Clone the repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd yeast_project_main
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply migrations

```bash
python manage.py migrate
```

### 6. Run the development server

```bash
python manage.py runserver
```

Open the application at:

```text
http://127.0.0.1:8000/
```

## 🔮 Future Enhancements

* Real-time production monitoring
* Advanced predictive analytics
* Improved machine learning models
* Interactive data visualization
* Automated process recommendations
* Cloud deployment

## 👩‍💻 Developed By

**Pooja**

Python Full Stack Developer | AWS Cloud & DevOps Trainee

---

⭐ This project was developed as part of an internship project to demonstrate skills in Python, Django, machine learning, database management, and web application development.
