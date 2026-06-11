**Project Title: Loan Default Modeling — Analysis & Implementation**

About: End-to-end loan default prediction pipeline on a 10,000-row dataset. Covers data preprocessing, two classifiers (Logistic Regression & Decision Tree), feature importance interpretation, and borrower-level Expected Loss computation.
Dataset Features: credit_lines_outstanding, loan_amt_outstanding, total_debt_outstanding, income, years_employed, fico_score, default (target)
Tech Stack: Python, Pandas, NumPy, scikit-learn, Matplotlib/Seaborn
Key Highlights:

70/30 train-test split with StandardScaler
Logistic Regression coefficients interpreted (FICO & income = protective)
Decision Tree visualized at max_depth=3
Expected Loss = PD × EAD × LGD formula implemented
