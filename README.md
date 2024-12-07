## HOME CREDIT DEFAULT RISK

### Summary of Business Problem and Project Objective

The **Home Credit Default Risk** project aims to enhance loan accessibility for individuals with limited or no credit history. These individuals often belong to underserved populations, leaving them vulnerable to unfair lending practices. By leveraging data from the application_train and application_test datasets, Home Credit seeks to improve financial inclusion by accurately assessing repayment capabilities. The project aims to develop predictive models that ensure fair and accurate loan approval decisions, minimizing risks for lenders and borrowers.

---

### Solution to the Business Problem

The solution implemented machine learning models to accurately predict repayment abilities. A variety of statistical methods, including naive bayes, logistic regression, random forests, and advanced techniques like gradient boosting models (XGBoost and LightGBM), were used.

The models were evaluated based on the Area Under the Receiver Operating Characteristic (AUC-ROC) curve. After feature engineering, applying class weights, and grid search for the best parameters, the LightGBM model emerged as the best-performing model, achieving an average AUC of 0.7350004 and Kaggle Score of 0.703 (Private Score).

Key outputs of the solution include:

1. Identification of three distinct risk profiles: high, medium, and low risk, along with their characteristics defined as persona profiles.

2. Enhanced persona profiles using simulations, including:
* Simulating repayment delay days based on risk categories.
* Summarizing enriched personas with profitability and repayment metrics.
* Loan profitability metrics to evaluate financial performance across risk categories.

### Contribution to the Project

* Conducted data exploration and preprocessing, including handling missing values, encoding categorical features, and scaling numerical variables.

* Engineered meaningful features to improve the model's predictive capabilities.

* Built and fine-tuned multiple machine learning models, including logistic regression and tree-based algorithms (Random Forest and XGBoost).
* 
* Analyzed model performance using the AUC-ROC metric and selected the best-performing model for deployment.
___

You can use the editor on GitHub to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Roadmap

This project has been discontinued and is no longer actively maintained. No new features or fixes will be added. If you're interested in contributing, feel free to fork the repository and customize it to your needs.
___

### References

[1] Jekyll theme "Minimal" for GitHub Pages: https://github.com/pages-themes/minimal (CC0 1.0 Universal License)
<br>[2] Dummy photo via: https://pixabay.com/photos/man-male-adult-person-caucasian-1209494/ (Pixabay License)
<br>[3] Dummy thumbnail image created by rawpixel.com: https://www.freepik.com/free-vector/set-elements-infographic_2807573.htm (Standard Freepik License)
