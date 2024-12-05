# Neural-Network-Drug-Classification
This project implements a Neural Network algorithm to classify drug types based on features such as age, blood pressure, and cholesterol levels. The model is evaluated against a Logistic Regression model for precision, recall, F1-score, and accuracy.

# Getting Started
These instructions will help you set up the project on your local machine for development and testing purposes. See the Deployment section for notes on deploying the project on a live system.

 # Prerequisites
Python 3.7+
Required Libraries:
NumPy
pandas
scikit-learn
matplotlib (optional for visualization)

# To install these libraries, run:

pip install numpy pandas scikit-learn matplotlib

# Installing
Clone the repository:
copy code
git clone <repository-link>
cd <repository-folder>

# Prepare the dataset:
Ensure drugdataset.csv is in the root folder of the project.

# Run the script:
Execute the following command to test the Neural Network model:

python neural_network_model.py

# Running the Tests
End-to-End Tests
The script will:
Preprocess the dataset (e.g., convert categorical variables to numeric).
Split the data into training and testing sets (80/20).
Train a Neural Network model with the following hyperparameters:
Hidden Layers: (5, 4, 5)
Max Iterations: 10000
Random State: 100

Output evaluation metrics: accuracy, precision, recall, and F1-score.

Example output:
Precision: 0.92
Recall: 0.90
F1-Score: 0.91

# Coding Style Tests
Ensure the code adheres to PEP 8 standards by using tools like flake8:

Copy code:
pip install flake8
flake8 neural_network_model.py

Deployment
To deploy the script:
Place the dataset and script on the live server.
Ensure Python and required libraries are installed.
Use a scheduler like cron or a job queue to automate predictions if needed.

Built With
scikit-learn - Machine learning library
NumPy - Array and numerical computation
pandas - Data manipulation and analysis


# Authors
Kathleen Elaine - Initial work
Contact: kakadonsjb@gmail.com
See the list of contributors who participated in this project.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Hat tip to the DATA 1200 course for project inspiration.
Special thanks to all contributors and reviewers.
