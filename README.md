# Liver Disease Prediction

## Overview

This project aims to predict the likelihood of liver diseases using machine learning techniques. The dataset includes various health indicators such as bilirubin levels, enzymes, and proteins, which are key factors in diagnosing liver conditions.

## Dataset

- **Source:** The dataset used for this project includes 583 records with 11 features:
  - `Age`: Patient's age.
  - `Gender`: Patient's gender.
  - `Total_Bilirubin`, `Direct_Bilirubin`: Measures of bilirubin levels.
  - `Alkaline_Phosphotase`: Alkaline phosphatase enzyme levels.
  - `Alamine_Aminotransferase`, `Aspartate_Aminotransferase`: Liver enzymes.
  - `Total_Protiens`, `Albumin`, `Albumin_and_Globulin_Ratio`: Protein levels and their ratios.
  - `Dataset`: Target variable indicating liver disease (1 for disease, 2 for no disease).

## Project Workflow

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and normalizing features.
2. **Exploratory Data Analysis (EDA)**: Visualizing the distribution of features and relationships with the target variable.
3. **Model Development**:
   - Multiple machine learning models are trained and evaluated to predict liver diseases.
   - Metrics such as accuracy, precision, recall, and F1-score are used for evaluation.
4. **Results**: The best-performing model is selected and analyzed.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation and analysis.
  - `matplotlib`, `seaborn` for data visualization.
  - Machine learning libraries such as `scikit-learn`.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Liver_diseases_prediction.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and execute the cells:
   ```bash
   jupyter notebook Liver_diseases_prediction.ipynb
   ```

## Results and Insights

- Detailed results of the model evaluation and insights derived from the dataset will be shared in the notebook.

## Future Work

- Incorporating advanced models or deep learning techniques.
- Exploring additional features or datasets to enhance accuracy.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for suggestions.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Let me know if you’d like any customization or additional details!
