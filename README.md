# 🎓 Student Performance Predictor

A Machine Learning web application that predicts a student's **Math Score** based on demographic and academic information such as gender, ethnicity, parental education, lunch type, test preparation, reading score, and writing score.

The application is built using **Python, Scikit-learn, Flask, Pandas, NumPy, and HTML/CSS**.

## 🚀 Features

* Predicts student performance using a trained Machine Learning model
* Flask-based web interface
* Takes student details through an HTML form
* Data preprocessing using `StandardScaler`
* Separate prediction pipeline for making predictions
* Modular project structure
* Easy to run locally

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **HTML/CSS**
* **Machine Learning**

## 📂 Project Structure

```text
Student-Performance-Predictor/
│
├── artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── src/
│   ├── components/
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   └── train_pipeline.py
│   └── exception.py
│
├── templates/
│   └── home.html
│
├── app.py
├── requirements.txt
├── README.md
└── setup.py
```

## ⚙️ How It Works

```text
Student Details
      ↓
HTML Form
      ↓
Flask Application
      ↓
CustomData
      ↓
DataFrame
      ↓
Preprocessing
      ↓
Trained ML Model
      ↓
Predicted Math Score
      ↓
Result on Web Page
```

## 📊 Input Features

The model uses the following student information:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Reading Score
* Writing Score

## 🧠 Machine Learning Pipeline

The project follows a basic ML pipeline:

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Model Serialization
8. Flask Deployment

The trained model and preprocessing object are saved as `.pkl` files and loaded during prediction.

## 💻 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-performance-predictor.git
cd student-performance-predictor
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Flask application

```bash
python app.py
```

The application will start on:

```text
http://127.0.0.1:5000/
```

## 🖥️ Application

Enter the student's details in the web form and submit them. The trained Machine Learning model processes the input and displays the predicted **Math Score**.

## 📌 Future Improvements

* Deploy the application on a cloud platform
* Improve model performance with hyperparameter tuning
* Add data visualization
* Add model comparison
* Improve UI/UX
* Add Docker support
* Add CI/CD pipeline

## 👩‍💻 Author

**Nikita Sati**

B.Tech CSE (AI & ML)

---

⭐ If you find this project useful, consider giving the repository a star!

