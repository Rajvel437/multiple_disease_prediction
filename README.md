# Multiple Disease Prediction with XAI (LIME)

## 🚀 Project Overview
This project is a **Multiple Disease Prediction System** built using **Flask** and **Machine Learning models**. It helps predict the likelihood of three major diseases:

- **Heart Disease** ❤️
- **Lung Disease** 🫁
- **Diabetes** 🍬

We leverage **Explainable AI (XAI)** using **LIME (Local Interpretable Model-Agnostic Explanations)** to provide users with insights into the predictions made by the model.

## 🎯 Features
✅ Predicts heart disease, lung disease, and diabetes with trained ML models.  
✅ Provides LIME visualizations to explain predictions.  
✅ Interactive web interface built with Flask.  
✅ Supports CSV-based training datasets for better customization.  
✅ User-friendly interface to input medical parameters.  

## 🛠 Tech Stack
- **Backend:** Flask, Python
- **Machine Learning:** scikit-learn, joblib, pandas, numpy
- **Explainable AI:** LIME (Local Interpretable Model-Agnostic Explanations)
- **Frontend:** HTML, CSS, Bootstrap

## 📂 Project Structure
```
📦 multiple-disease-prediction
├── 📁 static/               # Stores LIME HTML visualizations
├── 📁 templates/            # HTML templates for Flask
├── 📄 app.py                # Flask application logic
├── 📄 requirements.txt      # Dependencies
├── 📄 heart_X_train.csv     # Heart disease training dataset
├── 📄 lungs_train.csv       # Lung disease training dataset
├── 📄 diabetes_train.csv    # Diabetes training dataset
├── 📄 logistic_regression_model.joblib  # Heart model
├── 📄 lungs_model.joblib    # Lung model
├── 📄 diabetes.joblib       # Diabetes model
└── 📄 README.md             # Project documentation
```

## 🔥 Installation & Setup

### 🌍 Live Demo
[Click here to access the live project](https://healthforecast5.onrender.com/)
### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/multiple-disease-prediction.git
cd multiple-disease-prediction
```
### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Flask app
```bash
python app.py
```
Now, open your browser and visit `http://127.0.0.1:5000/` to use the web app.

## 🎨 Usage Guide
1. Select the disease you want to predict.
2. Enter the required medical parameters.
3. Click **Predict** to get the results.
4. View the **LIME explanation** for transparency into the prediction.

## 📊 Explanation with LIME
LIME helps make our AI model explainable by highlighting which features contributed the most to a particular prediction. This improves trust and interpretability in machine learning models.

## 🔍 Example Prediction
For **Heart Disease**:
- **Input:** Age: 50, Sex: Male, Chest Pain Type: 2, Cholesterol: 200...
- **Output:** *Heart Disease Probability: 89%*
- **LIME Explanation:** Displays a visual breakdown of key contributing factors.

## 🏆 Future Enhancements
- Add more diseases and models.
- Enhance UI/UX for better user experience.
- Deploy the application online using **Heroku** or **AWS**.

## 🤝 Contributing
Feel free to fork this repo and contribute! Open an issue or submit a pull request.

## 📜 License
This project is licensed under the **MIT License**.

---
💡 **Created by Rajvel R** | 🌟 Star this repo if you found it useful!

