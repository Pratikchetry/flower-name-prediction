🌸 Flower Name Prediction

📌 Overview

The Flower Name Prediction project utilizes machine learning to classify different types of flowers based on their physical characteristics. The project is built using the Iris dataset and a Random Forest Classifier, allowing users to predict flower species based on input features like sepal and petal dimensions. Additionally, an interactive HTML-based UI has been developed to facilitate user interaction with the model.

🚀 Project Workflow

Data Collection: The dataset used is the well-known Iris dataset.

Data Preprocessing:

Selection of relevant features (Sepal Length, Sepal Width, Petal Length, Petal Width).

Standardization using StandardScaler.

Model Training:

A RandomForestClassifier is trained on the dataset.

The dataset is split into training and testing sets (70-30 split).

Model Deployment:

The trained model is saved as a .pkl file using pickle.

A web-based UI allows users to input flower measurements and receive predictions.

📊 Dataset

The Iris dataset consists of the following features:

Sepal_Length

Sepal_Width

Petal_Length

Petal_Width

Class (Flower species: Setosa, Versicolor, Virginica)

🛠️ Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib

Machine Learning Algorithm: Random Forest Classifier

Web Technologies: HTML, CSS, JavaScript (for UI)

Model Deployment: Pickle for model serialization

📈 Model Evaluation Metrics

Accuracy Score

Confusion Matrix

Precision, Recall, F1-Score

💡 Features

Predicts the species of a flower based on given input measurements.

A simple and interactive HTML UI for ease of use.

Efficient and accurate classification using Random Forest.

🚀 How to Run

Clone the repository.

Install required dependencies: pip install pandas scikit-learn flask

Run the Flask application: python app.py

Open the web UI in your browser and input flower features to get predictions.

🔥 Future Enhancements

Enhance the UI with a modern framework (e.g., React or Flask-based UI).

Deploy the model on a cloud-based service.

Extend classification to other flower species.
