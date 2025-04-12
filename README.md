# Iris Flower Classification

## Project Summary
This project involves building a machine learning model to classify Iris flowers into one of three species — *Iris Setosa*, *Iris Versicolor*, and *Iris Virginica* — based on four key morphological features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The Iris dataset is a classic benchmark in pattern recognition and machine learning, known for its simplicity and effectiveness in testing classification algorithms. The main objective is to apply and evaluate multiple machine learning models to determine the best performer in terms of classification accuracy and stability.

---

## Models Implemented
The following machine learning models were  trained, and evaluated:

- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest
- Naive Bayes

Each model was trained using an 80-20 train-test split and further validated using 5-fold cross-validation to ensure robustness and generalization capability.

---

## Results Summary
**Average Accuracy Scores (via 5-Fold Cross-Validation):**

| Model               | Accuracy (Mean ± Std) |
|---------------------|---------------------------|
| Logistic Regression | 96% ± 0.02               |
| Decision Tree       | 96% ± 0.03               |
| SVM                 | 97% ± 0.02               |
| Random Forest       | 96% ± 0.03               |
| Naive Bayes         | 95% ± 0.04               |

---

##  Conclusion
Among all models tested, the **Support Vector Machine (SVM)** outperformed others in terms of both accuracy and consistency. With a mean accuracy of **97% ± 0.02**, SVM emerged as the most reliable and generalizable model for this classification task. It effectively captures the non-linear decision boundaries between species and demonstrates excellent performance on low-dimensional structured data.

This study illustrates the power of classical machine learning models in solving real-world classification problems and serves as a foundational example for future work in botanical data classification.

---

## Files Included
- `iris_classification.ipynb` - Jupyter notebook with all the code, visualizations, and evaluation
- `iris.csv` - Dataset used for training and testing
- `README.md` - Project overview and summary

---

## License
This project is licensed under the MIT License.

---

## Acknowledgements
- Dataset Source: [UCI Machine Learning Repository - Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- Developed using: Python, scikit-learn, pandas, seaborn, matplotlib

