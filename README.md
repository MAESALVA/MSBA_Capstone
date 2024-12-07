## HOME CREDIT DEFAULT RISK

### Summary of Business Problem and Project Objective

The **Home Credit Default Risk** project aims to enhance loan accessibility for individuals with limited or no credit history. These individuals often belong to underserved populations, leaving them vulnerable to unfair lending practices. By leveraging data from the application_train and application_test datasets, Home Credit seeks to improve financial inclusion by accurately assessing repayment capabilities. The project aims to develop predictive models that ensure fair and accurate loan approval decisions, minimizing risks for lenders and borrowers.

---

### Solution to the Business Problem

The solution implemented machine learning models to accurately predict repayment abilities. Various statistical methods were used, including Naive Bayes, Logistic Regression, Random Forests, and advanced techniques like gradient boosting models (XGBoost and LightGBM).

The models were evaluated using the Area Under the Receiver Operating Characteristic (AUC-ROC) curve. After feature engineering, applying class weights, and grid search for the best parameters, the LightGBM model emerged as the best-performing model, achieving an average AUC of 0.7350004 and Kaggle Score of 0.703 (Private Score).

**Key outputs of the solution include:**

1. Identification of three distinct risk profiles: high, medium, and low risk, along with their characteristics defined as persona profiles.

2. Enhanced persona profiles using simulations, including:
  * **Simulating repayment delay days** based on risk categories.
  * Summarizing enriched personas with **profitability and repayment metrics.**
  * **Loan profitability metrics** to evaluate financial performance across risk categories.

---

### Contribution to the Project

**1. Analysis and Modeling:**

* Conducted data exploration and preprocessing, including handling missing values, encoding categorical features, and identifying and removing near-zero variance predictors before splitting the dataset into training and testing sets.
  
* Random Forest was utilized to identify the most important predictors, ensuring the model focused on the most relevant variables.

* Built and fine-tuned multiple machine learning models such as Naive Bayes, Logistic Regression, Random Forest, and Gradient Boosting to achieve optimal predictions.

* Engineered meaningful features to improve the model's predictive capabilities.
  
**2. Performance Evaluation:**

* Analyzed model performance using the AUC-ROC metric and selected the best-performing model for deployment.

* Applied the LightGBM model predictions to the test dataset and:
  
* Identified distinct risk profiles (high, medium, and low risk) with detailed characteristics.
  
* Enhanced profiles with simulations and summarized them using repayment and profitability metrics.
___


### The Business Value of the Solution
This project provides substantial value to Home Credit Group by:

* **Improving Financial Inclusion:** Enabling underserved individuals to access loans fairly based on accurate repayment predictions.
  
* **Reducing Default Risk:** Helping Home Credit make informed decisions, minimizing financial risks.
  
* **Persona-Based Strategies:** By defining risk profiles, Home Credit can tailor loan products and repayment plans to suit specific borrower characteristics, ensuring financial stability for both parties.
  
* **Profitability Insights:** Providing profitability and repayment metrics for each persona helps refine loan strategies and enhance overall financial outcomes.

---

### Difficulties Encountered Along the Way

* **Class Imbalance:** The dataset exhibited a significant imbalance, with far fewer defaulters compared to non-defaulters. Techniques such as resampling methods (oversampling, undersampling, and both) and class weighting were necessary to address this.

* **Feature Engineering Challenges:** Identifying impactful features from the application_train dataset and deciding which transformations would improve model performance required experimentation.

* **Computational Complexity:** Training Random Forest and gradient boosting models like XGBoost and LightGBM required substantial computational resources, especially during hyperparameter tuning for LightGBM.

* **Evaluation Complexity:** Interpreting the AUC-ROC score in the context of business decisions and understanding trade-offs between sensitivity and specificity was critical.

---

### What I Learned in the Project

**Technical Skills:**

* Feature engineering and data preprocessing techniques.
* Implementation and tuning of machine learning models using R.
* Evaluation of models using metrics like AUC-ROC and precision-recall.

**Business Insights:**

* The importance of tailoring financial products to underserved populations.
* Balancing technical accuracy with business practicality in predictive modeling.

**Personal Growth:**
  
* Problem-solving in the face of data challenges, such as missing values and class imbalances.
* Communicate technical results to non-technical stakeholders.

___

### References

[1] Jekyll theme "Minimal" for GitHub Pages: https://github.com/pages-themes/minimal (CC0 1.0 Universal License)
<br>[2] Home Credit Default Risk : https://www.kaggle.com/competitions/home-credit-default-risk/overview
<br>[3] 
