# Sonar Rock vs Mine Prediction

## Project Overview
This project uses Machine Learning to classify underwater sonar signals as either **Rock (R)** or **Mine (M)** using Logistic Regression.

The model is trained on sonar data containing 60 numerical features representing the energy of sonar signals at different frequencies.

## Objectives
- Understand and analyse the sonar dataset.
- Perform exploratory data analysis.
- Train a Logistic Regression classification model.
- Evaluate the model using training and testing accuracy.
- Predict whether a sonar signal represents a rock or a mine.

## Dataset Information

| Description | Details |
|---|---|
| Total samples | 208 |
| Features | 60 |
| Classes | Rock (R), Mine (M) |
| Rock samples | 97 |
| Mine samples | 111 |
| Missing values | None |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Import the required Python libraries.
2. Load and explore the sonar dataset.
3. Perform data analysis and preprocessing.
4. Separate features and target labels.
5. Split the dataset into training and testing sets.
6. Train the Logistic Regression model.
7. Evaluate model performance.
8. Make predictions using the trained model.

## Model Performance

The Logistic Regression model achieved the following accuracy:

| Evaluation | Accuracy |
|---|---:|
| Training Accuracy | 83.73% |
| Testing Accuracy | 85.71% |

*The results are based on a stratified train-test split with `random_state=42`.*

## How to Run the Project

**1. Clone the repository**
```bash
git clone https://github.com/Gayatri-tech24/sonar-detection.git
```

**2. Navigate to the project folder**
```bash
cd sonar-detection
```

**3. Install dependencies**
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

**4. Launch Jupyter Notebook**
```bash
jupyter notebook
```

Open `Sonar_prediction.ipynb` and run the notebook cells.

## Future Improvements
- Experiment with other classification algorithms.
- Apply feature scaling.
- Evaluate the model using a confusion matrix and classification report.
- Perform cross-validation to assess model reliability.
- Improve prediction performance.

## Author
**Gayatri Arvind Gundad**

GitHub: [Gayatri-tech24](https://github.com/Gayatri-tech24)
