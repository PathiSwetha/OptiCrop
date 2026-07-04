# 🌱 OptiCrop

    Smart Agricultural Production Optimization Engine

OptiCrop is an AI-powered crop recommendation system that suggests the most suitable crop based on soil nutrients and environmental conditions. It uses Machine Learning models and a Flask web application to provide fast and accurate predictions.



 ✨ Features

- 🌾 Crop Recommendation
- 🌱 Soil Nutrient Analysis
- 🌦 Weather Parameter Analysis
- 🤖 Machine Learning Prediction
- 📊 Data Visualization
- 💻 Flask Web Application



 🛠 Tech Stack

- Python
- Flask
- HTML, CSS, JavaScript
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib



 📂 Project Structure   

        OptiCrop/
OptiCrop/
│
├── app.py                      # Flask application
├── train_model.py              # Model training script
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
├── .gitignore                  # Ignore unnecessary files
│
├── data/
│   └── Crop_recommendation.csv
│
├── models/
│   ├── crop_model.pkl
│   ├── kmeans_model.pkl
│   ├── label_encoder.pkl
│   └── model_name.txt
│
├── notebooks/
│   └── OptiCrop_Analysis.ipynb
│
├── src/
│   ├── __init__.py
│   ├── preprocess.py           # Data preprocessing functions
│   ├── predictor.py            # Prediction functions
│   ├── clustering.py           # K-Means clustering logic
│   ├── utils.py                # Helper functions
│   └── config.py               # Configuration paths
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│       ├── correlation_heatmap.png
│       ├── crop_distribution.png
│       └── temperature_rainfall.png
│
└── tests/
    └── test_predictor.py       # Unit tests (optional)


 📊 Dataset

- 2200 Records
- 22 Crop Classes


- Input Features:

  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature
  - Humidity
  - pH
  - Rainfall



  Run the Project

______bash________
pip install -r requirements.txt
python app.py


Open:

http://127.0.0.1:5000


 👥 Team

- Harsha
- Swetha
- Sneha
- Pranavi
- Jagan
