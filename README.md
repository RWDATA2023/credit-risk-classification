# Credit Risk Classification: A Data-Driven Approach

## Synopsis

This study leverages logistic regression algorithms to scrutinize borrowers' credit risk based on historical data from a peer-to-peer lending service. Two variations of the logistic regression model were employed: one using original data and another utilizing data that was oversampled to tackle class imbalance.

## Key Metrics

### Standard Model:

- **Accuracy**: 99%
- **Precision**: Healthy Loans (1.00), High-Risk Loans (0.85)
- **Recall**: Healthy Loans (1.00), High-Risk Loans (0.91)

### Oversampled Model:

- **Accuracy**: 99.4%
- **Precision**: Healthy Loans (1.00), High-Risk Loans (0.84)
- **Recall**: Healthy Loans (0.99), High-Risk Loans (0.99)

## Conclusion & Recommendation

Both models exhibit stellar accuracy, but the oversampled variant slightly edges out in recall for high-risk loans, a critical metric for minimizing financial risk. Given the imperative of accurately identifying high-risk loans to safeguard the company's financial health, the oversampled logistic regression model is unequivocally recommended for deployment.

## Dependencies and Requirements

To successfully run the accompanying Jupyter notebook, the following software and libraries are required:

### Software

- Python 3.x
- Jupyter Notebook

### Python Libraries

- [NumPy](https://numpy.org/doc/)
- [pandas](https://pandas.pydata.org/docs/)
- [scikit-learn](https://scikit-learn.org/stable/documentation.html)
- [imbalanced-learn (imblearn)](https://imbalanced-learn.org/stable/)

### Installation Commands

\`\`\`bash
pip install numpy pandas scikit-learn imbalanced-learn
\`\`\`

## References

- [NumPy Documentation](https://numpy.org/doc/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [imbalanced-learn Documentation](https://imbalanced-learn.org/stable/)
