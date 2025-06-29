# AI-Based-Medical-Recommandation-system-using-neural-network
A beginner-level AI system built using a neural network to predict medical conditions based on user symptoms. The system also provides a description of the disease, suggested medications, precautions, recommended diets, and workouts.

# Features
Predicts disease based on selected symptoms using a trained neural network.

Provides:

Disease description

Precautions to take

Recommended medications

Suggested diet and workout

Handles missing data in the dataset

Includes user input interface for real-time testing

# Technologies Used
Language: Python

Libraries/Tools:

NumPy, Pandas, Matplotlib

TensorFlow (Keras)

scikit-learn

Model: Multi-layer Neural Network

Encoding: Label Encoding, One-hot Encoding

Optimization: Adam

Model Saving: Keras .h5 format

# 🧬 Dataset
Training.csv — Contains symptoms and corresponding disease labels.

Other CSV files used for supplementary information:

symtoms_df.csv

description.csv

precautions_df.csv

medications.csv

diets.csv

workout_df.csv

⚙️ How It Works
Load and preprocess data (including encoding and one-hot transformation)

Build and train a neural network model

Save the trained model to disk

Allow user to input symptoms via command line

Predict the disease using the trained model

Retrieve associated info (description, medication, etc.) from relevant datasets

💻 How to Run
Place all required datasets in a /datasets folder.

Run the Python script.

Enter symptoms as comma-separated input when prompted.

View the diagnosis and recommended guidance.

# 📊 Model Visualization
The program plots:

Training vs Validation Loss

Training vs Validation Accuracy
