<h2>📌 Project: Multiple Disease Prediction using Machine Learning with Smart Diet Chart</h2>
<h3>🔹 Overview</h3>
<p> This project is a web-based application that predicts the likelihood of multiple diseases using machine learning models and provides a personalized diet chart to promote a healthy lifestyle. The main aim is to integrate disease prediction with smart diet recommendations for improved user well-being.</p>

## 🛠 Tech Stack
### 1. Frontend
- HTML – Structuring the web pages.

- CSS – Styling and designing a responsive UI.

- JavaScript – Enhancing interactivity and dynamic content handling.

### 2. Backend

- Flask – Python-based micro web framework used to connect the ML model with the frontend.

### 3. Machine Learning & Data Processing

- Python Libraries:

  - NumPy – Numerical computations and array operations.

  - Pandas – Data manipulation and preprocessing.

  - Scikit-learn – Building and training ML models for disease prediction.

## ⚙️ Features
### 1. Multiple Disease Prediction

   - Supports prediction for different diseases (e.g., Diabetes, Heart Disease, Parkinson’s, etc.).

   - Uses pre-trained ML models with accuracy-optimized algorithms.

### 2. Smart Diet Chart Recommendation

  - Provides a customized diet plan based on the user details.

  - Aims to guide users toward healthier food choices.

### 3. User-Friendly Web Interface

  - Simple, intuitive, and mobile-friendly design for easy usage.

### 4. Backend Integration

  - Flask API connects the trained ML model to the frontend, enabling real-time prediction.
### 📂 Project Structure
```
Multiple Disease Prediction using Machine Learning with Smart Diet Chart 
├── static/        # frontend static files 
│   ├── cs/        # stylesheets
│   │   ├── style.css 
|   |   ├── style1.css
|   |   └── style2.css
│   ├── images/
|   |   └── ...    # all images & icons
│   ├── js/        # javascript script
│   │   └── script.js
├── templates/                   
|   ├── home.html                    # Home page 
|   ├── health.html                  # Disease Prediction page
|   ├── nutrition.html               # Page where user can provide their own nutrition/diet recommendation
|   └── diet-chart.html              # Displays generated diet chart based on prediction
|
├── app.py          # Main Flask application
├── model1.pkl      # for predict Heart Disease 
├── model2.pkl      # for predict Diabetes 
├── model3.pkl      # for predict Dengue
└── README.me       # Project documentation
```

### 📂 Workflow
  **1. User Input**→ The user enters health-related data through the web form.

  **2. Data Processing** → The data is preprocessed using Pandas and NumPy.

   **3. Prediction** → ML model (Scikit-learn) predicts the probability of a disease.

   **4. Diet Chart Generation** → Based on user input, a suitable diet plan is displayed.


