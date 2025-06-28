# Machine-Learning-Wine-Quality-Testing
Done a Project on Wine Quality Testing using Simple Machine Learning Techniques

# 🍷 Wine Quality Prediction

This project focuses on building and evaluating machine learning models to predict the quality of wine based on various physicochemical features. It uses a dataset of red wine samples and applies different preprocessing and modeling techniques to identify the best-performing model.

📊 Dataset

The dataset used is the **Red Wine Quality dataset** from the UCI Machine Learning Repository, which includes the following features:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target)

🧠 Models Used

The notebook explores and compares the following regression models:

- Simple Linear Regression
- Multi Linear Regression
- Polynomial Regression


Each model is evaluated using:

- **R² Score**
- **Mean Squared Error (MSE)**
- **K-Fold Cross Validation** for robust evaluation

🛠️ Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

📈 Results

The models are trained and evaluated on the dataset. The notebook provides visual comparisons of their performance through:

- Accuracy scores (R²)
- Cross-validation results
- Error metrics

Project Structure
Machine-Learning-Wine-Quality-Testing/
├── Winequality-testing-model.ipynb
├── README.md
└── winequality-red.csv (You need to download this manually if not included)


🏁 Getting Started

Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

