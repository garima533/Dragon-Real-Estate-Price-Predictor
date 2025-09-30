# Dragon Real Estate - Price Predictor
A machine learning project designed to predict real estate prices using Python, Pandas, and Scikit-learn. This project demonstrates a complete workflow for a regression analysis task, from data exploration and preprocessing to model training and persistence.

The model is trained on the Boston housing dataset, and the final trained model is saved using Joblib for future inference.

# Tech Stack
Language: Python

Libraries:

Pandas and numpy (for data manipulation and analysis)

Scikit-learn (for machine learning models and utilities)

Joblib (for saving and loading the trained model)

Environment: Jupyter Notebook / VS Code

# Project Structure
.
├── Project_ML.ipynb      # Main notebook with the complete ML workflow
├── boston.csv            # The dataset used for training and testing
├── Dragon.joblib         # The final, pre-trained model artifact
├── logistic_regression.ipynb # (related work/scratchpad)
├── main.ipynb            # (related work/scratchpad)
└── tutorial.ipynb        # (related work/scratchpad)

# Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
You need to have Python 3 installed on your system.

Installation
Clone the repository:
First, clone this repository to your local machine. Replace your-username with your actual GitHub username.

git clone [https://github.com/garima533/Dragon-Real-Estate-Price-Predictor.git](https://github.com/garima533/Dragon-Real-Estate-Price-Predictor.git)

Navigate to the project directory:

cd Dragon-Real-Estate-Price-Predictor

Install the required packages:
Install the necessary Python libraries using pip.

pip install pandas scikit-learn jupyterlab

# Usage
Launch the Notebook:
Open the project folder in VS Code (which has built-in Jupyter support) or launch Jupyter Lab from your terminal:

jupyter lab

Run the Main Notebook:
Open and run the cells in Project_ML.ipynb to see the entire process, including data loading, training the model, and saving the final Dragon.joblib file.

This project serves as a practical application of machine learning for regression tasks. Feel free to explore the code and adapt it for your own projects.
