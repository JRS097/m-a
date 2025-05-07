📊 M&A Deal Prediction Using Machine Learning
This project uses machine learning to predict the likelihood of M&A (mergers and acquisitions) transactions based on financial indicators and historical deal records of ASX-listed companies.

🔍 Objective
To develop a binary classification model that distinguishes between:

Companies that were involved in a deal (BUY, SELL, BUY&SELL)

Companies that were not involved in any transaction

📁 Dataset
The dataset contains historical financial indicators and transaction labels for various companies. The labels are preprocessed into two categories: DEAL and NO DEAL.

⚙️ Features & Tools Used
Language: Python

Libraries: pandas, numpy, scikit-learn

Model: RandomForestClassifier (300 trees, entropy criterion)

Preprocessing:

Label encoding for target variable

Feature scaling (StandardScaler)

Train-test split (80/20)

🧠 Workflow
Load and preprocess the Excel dataset

Transform transaction labels into binary classes

Split data into training and testing sets

Apply feature scaling

Train a Random Forest classifier

Predict test set outcomes

Evaluate model performance using a confusion matrix

📈 Results
The model's performance is assessed using a confusion matrix to evaluate its ability to distinguish between companies that entered a deal and those that did not.
