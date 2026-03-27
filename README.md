# Fundamentals of Biometric Systems Design Final Project
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 
![PyAgrum](https://img.shields.io/badge/PyAgrum-Bayesian%20Networks-blue?style=for-the-badge)

**By:** Matteo Valente and Marcus Gee

## Overview  

This project builds a **Bayesian Network (BN)** using PyAgrum to analyze how lifestyle factors affect stress levels.  

Using the **Sleep, Health, and Lifestyle** dataset, we model probabilistic relationships between occupation, demographic factors, stress, and health outcomes such as heart rate and sleep quality among many others.

The goal is to use probabilistic reasoning to understand how different conditions influence stress and its effects.

## Objectives  

- Build a **Bayesian Network** using real-world data  
- Compute **Conditional Probability Tables (CPTs)**  
- Analyze how lifestyle factors influence stress  
- Perform **inference using different scenarios**  

## Dataset

Dataset used: **Sleep, Health, and Lifestyle**

Contains ~370 records including:
- Age, Gender  
- Occupation  
- Sleep Duration & Quality  
- Physical Activity  
- Stress Level
- BMI Catagory
- Blood Pressure  
- Heart Rate  
- Daily Steps
- Sleep Disorder 

## Installation and Setup  

### 1. Download or Clone Repository

**Option A – Clone (Recommended):**
```bash
git clone https://github.com/matteov021/Fundamentals-of-Biometric-Systems-Design-Final-Project.git
cd Fundamentals-of-Biometric-Systems-Design-Final-Project
```

**Option B – Download ZIP:**

* Click the green **“Code”** button on GitHub
* Select **Download ZIP**
* Extract the folder
* Open a terminal inside the project directory

### 2. Method A - Google Colab (Recommended)

* Go to [Google Colab](https://colab.research.google.com/)
* Click **“Upload Notebook”**
* Upload the `.ipynb` file from this project

#### Upload the Dataset

* On the **left sidebar**, click the folder icon
* Click **Upload**
* Upload: `Sleep_Health_Lifestyle.csv`
* The file will appear in the Colab file system (same directory as the notebook runtime)

#### Run the Notebook

* Click **Run All** near the top toolbar
* That’s it. Everything should work out of the box!

### 3. Method B - VS Code (Not Reccomended)