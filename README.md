# fraud_detection_project
This project uses machine learning to detect fraudulent financial transactions by analyzing features like transaction amount and account balances. It helps identify rare fraud cases in large datasets, improving security and reducing losses. Visual tools like scatter matrix plots reveal data patterns that support accurate fraud classification.
The project is a full machine learning fraud detection system in Python designed to identify fraudulent financial transactions from a large dataset. It takes as input raw transaction data including features like transaction type, amount, sender and receiver account balances before and after the transaction, among others.

# What it Takes:
- A large, labeled dataset with both fraudulent and non-fraudulent transactions.
- Data science libraries like Pandas, Numpy, Matplotlib/Seaborn for analysis and visualization.
- Machine learning tools from Scikit-learn, such as logistic regression, preprocessing (scaling and encoding), and model evaluation metrics.
- Handling significant class imbalance because fraudulent transactions are much rarer than legitimate ones.
- Computational resources for training on millions of transaction records.
- Deployment tools like Streamlit for building web applications.

# What it Gives:
- A trained machine learning model capable of distinguishing fraud with approximately 94% accuracy.
- A data processing pipeline that automates data scaling, encoding, training, and prediction.
- Insights into transaction patterns and fraud indicators through exploratory data analysis.
- Evaluation results with metrics (classification report, confusion matrix) indicating model effectiveness.
- A deployable Streamlit app for real-time fraud prediction based on new input transaction details.
- A reproducible and extendable fraud detection system suitable for real-world finance applications.

# what it will do:

1. Analyze and process large-scale financial transaction data to identify patterns and anomalies that indicate fraudulent activities.
2. Handle severe class imbalance between legitimate and fraudulent transactions by using balanced classification techniques.
3. Build and train a logistic regression model with preprocessing pipelines (scaling, encoding) to detect fraud accurately, achieving about 94% accuracy.
4. Evaluate the model using metrics like confusion matrix and classification report to understand precision, recall, and overall performance.
5. Deploy the trained model via a user-friendly Streamlit web app to predict fraud likelihood on new transaction inputs in real-time.
6. Continuously adapt to new fraud patterns by retraining models with updated transaction data (future extension).

### Explanation of Algorithms Used: Logistic Regression and Random Forest

**Logistic Regression**: is a linear classification algorithm that estimates the probability that a transaction is fraudulent based on input features. It is simple, interpretable, and fast, making it suitable as a baseline. However, it assumes a linear relationship between features and the log-odds of fraud, which may limit its effectiveness with complex fraud patterns.

**Random Forest**: is an ensemble learning algorithm that builds many decision trees using random subsets of data and features. It aggregates predictions from these trees, capturing complex, nonlinear relationships and interactions in the data. This leads to higher accuracy and robustness, especially in detecting rare fraud cases amid imbalanced data.

### Why Both Are Used
- Logistic Regression offers a straightforward, interpretable model useful for quick baseline results.
- Random Forest generally achieves higher precision and recall by modeling complex patterns and handling data imbalance better.
- Comparing both provides insights into their strengths and helps select the best-performing model for fraud detection.

### Supporting Evidence
Studies show Random Forest consistently outperforms Logistic Regression in fraud detection precision (e.g., 92.5% vs 71.6%), and is better at minimizing wrongly identified frauds. Logistic Regression remains valuable for its simplicity and transparency.

# Summary:
This project bridges raw transactional data to practical fraud detection by combining exploratory data analysis, careful feature engineering, machine learning classification, and user-friendly deployment. It addresses challenges like class imbalance and high dimensionality effectively, resulting in a powerful tool that can significantly aid in mitigating fraudulent financial activities. This comprehensive workflow is useful for data scientists looking to build robust fraud detection systems with Python.
