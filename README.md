# Customer-Purchase-Probability-streamlit-app

## Overview
This web app predicts the probability that the customer will purchase something based on various inputs related to the customer. The user enters details such as age, gender etc., and the app uses a trained RandomForestClassifier model to predict the probability of purchase,The inputs are stored in a pandas dataframe and passed through a data preprocessing pipeline to generate predictions.

## Features
- Predict Purchase Probability: The app predicts the price of real estate based on user inputs.
- User-Friendly Interface: Built with Streamlit for a smooth, interactive user experience.
- Data Preprocessing: Inputs are processed and transformed before being passed through the prediction model.
- Machine Learning Model: Utilizes a RandomForestClassifier model for accurate price predictions.

## Technologies Used

- Streamlit:For creating the web app interface.
- Pandas:For handling data input and manipulation.
- Scikit-learn:For implementing the RandomForestRegressor model.
- Python:Programming language for backend logic.

## How to Use the App

### 1.Run the App Locally

To run the app on your local machine, follow these steps:

1.Clone the Repository: Clone the repository to your local machine:

```bash
git clone https://github.com/NishantRai567/dsi-streamlit-web-app.git
```
2.Navigate to the Project Directory:

```bash
cd dsi-streamlit-web-app
```
3.Install Dependencies: Install the required dependencies from requirements.txt:

```bash
pip install -r requirements.txt
```

4.Run the App: Launch the Streamlit app locally:

```bash
streamlit run "dsi-streamlit-web-app.py"
```

5.Access the App: The app will open in your browser at http://localhost:8501, where you can input the property details and get price predictions.

### 2. Access the App Online

If you don’t want to run the app locally, you can access the app directly via its deployment on Streamlit Sharing or another cloud platform.

Visit the deployed app at: https://dsi-app-web-app-fnjyrkz439fwudt5heeemd.streamlit.app/

Once on the site, you can enter the required customer details and receive the predicted purchase probability.
