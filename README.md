# Rule-Based Medical Symptom Checker

## Overview

This project is a simple AI-based expert system developed using Python. It helps users identify possible medical conditions based on the symptoms they enter. The system works by comparing user symptoms with a predefined knowledge base of diseases and calculating the best match.

This project was created as part of a first-year engineering course on **Fundamentals of Artificial Intelligence and Machine Learning**, focusing on concepts such as:
- Knowledge Representation  
- Rule-Based Reasoning  

---

## Features

- Accepts symptoms from the user through a simple interface  
- Uses rule-based logic to match symptoms with diseases  
- Displays a ranked list of possible conditions  
- Shows the most probable disease based on match percentage  
- Implemented using only basic Python concepts  

---

## Technologies Used

- **Python 3**
- **Jupyter Notebook**

No external libraries or frameworks are used, making the project easy to understand and run on any system with Python installed.

---

## How the System Works

The project is based on three main components:

### 1. Knowledge Base
A dictionary is used to store diseases and their associated symptoms.

### 2. Inference Engine
The program compares user-entered symptoms with stored symptoms and calculates a match percentage for each disease.

### 3. Output Module
The system displays a diagnosis report and highlights the most probable condition.

---

## How to Run the Project

### Step 1: Install Python
Make sure Python 3 is installed on your system.

### Step 2: Open Jupyter Notebook
Launch Jupyter Notebook and create a new Python notebook.

### Step 3: Copy the Code
Paste the full project code into a single cell.

### Step 4: Run the Program
Run the cell and enter symptoms when prompted, for example: fever, cough, headache

The system will display possible diseases and their match percentages.

---

## Sample Output
========== Diagnosis Report ==========

Flu: 75.00% match
Malaria: 50.00% match
Common Cold: 33.33% match
Most probable condition: Flu

---

## Project Structure
Medical-Symptom-Checker/
│
├── symptom_checker.ipynb
├── README.md
└── project_report.pdf

---

## Limitations

- The system uses a small set of diseases and symptoms  
- It is designed for educational purposes only  
- It does not replace professional medical advice  

---

## Future Improvements

- Add more diseases and symptoms  
- Store patient history  
- Create a graphical user interface  
- Improve accuracy using machine learning techniques  
