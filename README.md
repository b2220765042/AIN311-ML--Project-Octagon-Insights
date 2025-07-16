# AIN311-ML--Project-Octagon-Insights

# MMA Fight Outcome Prediction

## Project Description
This project applies machine learning techniques to analyze and predict outcomes of MMA fights using historical fighter statistics and fight results. By preprocessing and exploring the data, training various classification algorithms, and evaluating model performance, the project provides insights into the factors influencing fight outcomes. Additionally, the project includes a prediction function to simulate hypothetical matchups, showcasing its practical application in sports analytics.
YouTube: https://www.youtube.com/watch?v=6NuS92tVtZY
---

## Key Features
- **Data Preprocessing**: Handling missing values, feature formatting, and ensuring data quality.
- **Exploratory Data Analysis**: Insights into the dataset's structure and key statistics.
- **Model Training**: Implementation of classification algorithms including:
  - Random Forest
  - Logistic Regression
  - Gradient Boosting
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (SVM)
- **Model Evaluation**: Accuracy comparisons and hyperparameter optimization.
- **Prediction Functionality**: Predict fight outcomes for custom matchups.

---

## Installation and Setup
To run this project, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/KaganCanerik/AIN311-Project-Octagon-Insights.git
   cd AIN311-Project-Octagon-Insights
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore and execute the project.

---

## Usage
### Example Prediction:
```python
chosen_model = models['Random Forest']
print(predict_winner("Alex Pereira", "Jon Jones", fighter_stats, chosen_model))
```

This function will predict the winner based on fighter statistics and the trained model.

---

## Dataset
### Files Used:
- `raw_fighter_details.csv`: Contains detailed statistics about fighters.
- `raw_total_fight_data.csv`: Includes fight matchups and results.

### Preprocessing Steps:
1. Cleaned and formatted key columns (e.g., `Str_Acc`, `TD_Acc`, `TD_Def`).
2. Merged fighter statistics with fight results for model training.

---

## Results
- Best-performing models:
  - **Gradient Boosting**: Accuracy = 0.72
  - **Logistic Regression**: Accuracy = 0.72
- Optimal `k` for KNN: **k = 20**, Accuracy = 0.66

---

## Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
For questions or feedback, feel free to reach out:
- **Name**: Özgün Serergün Koca
- **Email**: ozgunkoca@hacettepe.edu.tr
- **GitHub**: https://github.com/b2220765042
