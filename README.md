This project is a machine learning model that predicts credit card approval status using various classification algorithms. The dataset is synthetically generated, and SMOTE (Synthetic Minority Over-sampling Technique) is used to handle class imbalance.

📌 Features
✅ Generates synthetic data using make_classification
✅ Handles class imbalance using SMOTE
✅ Trains multiple models, including:

Logistic Regression
Decision Tree
Random Forest
Gradient Boosting
✅ Evaluates models using Accuracy and AUC scores
✅ Visualizes results with bar charts and confusion matrices
✅ Identifies important features using Random Forest
📁 Project Structure
php
Copy
Edit
📂 Project Directory  
│── creditcard.py       # Main script for data processing, model training, and visualization  
│── README.md           # Project documentation  
│── requirements.txt    # Dependencies for running the project (optional)  
🚀 Installation & Usage
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/your-repository.git
cd your-repository
2️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
Or manually install required libraries:

sh
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
3️⃣ Run the Script
sh
Copy
Edit
python creditcard.py
🎯 How It Works
1️⃣ Generates synthetic data with 10 features and an approval status column.
2️⃣ Applies SMOTE to balance the dataset.
3️⃣ Splits data into training and testing sets.
4️⃣ Trains four machine learning models and evaluates them.
5️⃣ Visualizes model performance using bar plots and confusion matrices.
6️⃣ Displays feature importance from the best-performing model (Random Forest).

📊 Model Performance
The script compares four models and evaluates them based on Accuracy and AUC score. The best model's confusion matrix and feature importances are visualized.

🛠 Dependencies
Ensure you have the following installed:

sh
Copy
Edit
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
imbalanced-learn  
