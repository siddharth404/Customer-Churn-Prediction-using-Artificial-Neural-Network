Artificial Neural Network - Customer Churn Prediction
This project uses an Artificial Neural Network (ANN) to predict customer churn. The model is built using Keras and TensorFlow and deployed via a Streamlit web application. The dataset used is focused on customer details to forecast churn.

Project Structure
app.py: Main file to run the Streamlit app.
Churn_Modelling.csv: The dataset used for training the model.
model.h5: Saved trained model.
label_encoder_gender.pkl: Pre-trained gender label encoder.
onehot_encoder_geo.pkl: Pre-trained one-hot encoder for geographical columns.
scaler.pkl: Pre-trained scaler for normalizing data.
requirements.txt: Python dependencies required for the project.


Dataset
The dataset (Churn_Modelling.csv) contains the following key columns:

Geography: Customer's country.
Gender: Customer's gender.
Age: Customer's age.
Balance: Customer's bank balance.
Exited: Whether the customer churned (1) or not (0).
Model
The ANN model was trained with the following structure:

Input layers with relevant features.
Two hidden layers with 64 and 32 units, respectively.
Output layer with 1 unit for binary classification (churn or no churn).
