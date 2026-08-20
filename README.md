[Live hosted model link:](https://ayushsan1.github.io/Apartment-rent-predictor/)


apartment-rent-predictor/
├── ml-based-model.ipynb              # EDA + model training notebook
├── apartment_rent_data.csv           # Dataset
├── random_forest_regressor.pkl       # Saved model
│
├── app/
│   ├── app.py                        # Flask application
│   ├── templates/
│   │   ├── index.html                # Input form
│   │   └── result.html               # Prediction result page
│   └── static/
│       └── style.css                 # Optional styling
│
├── Dockerfile                        # Docker image definition
├── requirements.txt                  # Python dependencies
└── README.md                         # This file
