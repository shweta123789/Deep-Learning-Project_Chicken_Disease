# End-to-End-Deep-Learning-Project-Chicken-Disease


#### Data Link: [Donwload Link](https://drive.google.com/file/d/1pV0DAdyjzsjk0HL7f8_5qiS_mVyjYk25/view?usp=sharing)


<img width="1887" height="780" alt="Screenshot 2025-11-05 112347" src="https://github.com/user-attachments/assets/b0f3f354-bc58-4864-8016-4fca2f8c6ff4" />



##🐔 Chicken Disease Classification using Deep Learning

This project focuses on building an end-to-end deep learning-based image classification system to detect diseases in chickens using image data.
The model is deployed using Flask API, and can classify uploaded chicken images into Healthy or Diseased categories.



## 📌 Project Features

✅ Trained CNN (Convolutional Neural Network) model
✅ Image preprocessing and augmentation
✅ Modular Python package (cnnClassifier)
✅ Flask-based backend API
✅ File upload support via REST API
✅ Config-driven development using YAML
✅ Logging & Exception handling
✅ Ready for deployment

.
├── app.py                          # Flask API
├── requirements.txt                # Dependencies
├── README.md                       # Project documentation
├── data/                           # Dataset (not included in repo)
├── logs/                           # Log files
├── artifacts/                      # Trained model + metadata
├── research/                       # Notebooks and experiments
├── setup.py                        # Package setup file
└── src/
    └── cnnClassifier/
        ├── components/             # Pipeline components
        ├── config/                 # Config & schema files
        ├── constants/              # Constant variables
        ├── entity/                 # Entity/dataclass definitions
        ├── exception/              # Custom exceptions
        ├── logger/                 # Logging setup
        ├── pipeline/               # Training + prediction pipelines
        └── utils/                  # Utility functions

#🚀 Setup & Installation
1️⃣ Create Virtual Environment
conda create -n medibot python=3.10 -y
conda activate medibot


2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Flask App
python app.py

🧠 Model Information

* Model Type: CNN (TensorFlow / Keras)
* Input Shape: 180x180x3
* Trained using image dataset of multiple chicken diseases
















