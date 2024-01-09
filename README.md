# Lenders Club Prediction Project

## Overview
The Lenders Club Prediction project utilizes machine learning techniques, including Neural Networks, KNN Classification, Random Forest, and Support Vector Machines (SVM), to predict the feasibility of lending money to startups for investment within a lending club environment. The goal is to assist lenders in making informed decisions about loan approvals, risk assessment, and investment opportunities.

## Key Features
- Credit risk assessment using Neural Networks.
- Loan approval prediction with KNN Classification.
- Interest rate optimization using Random Forest.
- Portfolio analysis and optimization using Support Vector Machines (SVM).

## Dataset
The project is based on a comprehensive dataset that includes historical data on loan applications, approvals, rejections, repayments, defaults, and other relevant parameters. The dataset is available in the 'data' directory.

## Project Structure
lenders-club-prediction/
│
├── data/ # Dataset folder
│ └── lending_data.csv # Sample dataset file
│
├── notebooks/ # Jupyter notebooks for data exploration and model training
│ ├── data_exploration.ipynb
│ └── model_training.ipynb
│
├── models.py # Source code with all models
│
├── results/ # Result files, plots, and model evaluation metrics
│ ├── model_evaluations/
│ ├── prediction_results/
│ └── visualizations/
│
├── .gitignore
├── README.md # Project README file
└── requirements.txt # Python dependencies

perl
Copy code

## Getting Started
1. Clone the repository: `git clone https://github.com/yourusername/lenders-club-prediction.git`
2. Navigate to the project folder: `cd lenders-club-prediction`
3. Install dependencies: `pip install -r requirements.txt`
4. Explore the Jupyter notebook in the 'notebooks' directory for data exploration and model training.

## Usage
- Open the 'notebooks/model_training.ipynb' notebook to train all models at once.
- Use the trained models for predictions in your lending club environment.

## Model Evaluation
Refer to the 'results/model_evaluations' directory for detailed evaluations of each model, including accuracy, precision, recall, and F1 score.

## Contributing
Contributions are welcome! If you have suggestions or find issues, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
