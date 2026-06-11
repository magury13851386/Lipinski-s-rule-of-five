Lipinski Rule of Five – Drug Analysis
Project Overview
This project analyzes drug-like compounds using Lipinski’s Rule of Five, a widely used guideline in medicinal chemistry to evaluate the oral bioavailability of potential drug candidates.

The goal of this project is to identify compounds that satisfy Lipinski’s criteria and to explore the properties of compounds that fail these rules through statistical summaries and visualizations.

Lipinski Rule of Five
A compound is generally considered drug‑like if it satisfies the following conditions:

Molecular Weight ≤ 500
LogP ≤ 5
Hydrogen Bond Donors ≤ 5
Hydrogen Bond Acceptors ≤ 10
Compounds violating one or more of these rules may have reduced oral bioavailability.

Dataset
The dataset contains physicochemical properties of compounds including:

Compound_ID
Molecular_Weight
LogP
H_Bond_Acceptors
H_Bond_Donors
Project Workflow
Load and inspect the dataset
Apply Lipinski rule criteria
Classify compounds into Pass or Fail
Generate statistical summaries
Visualize property distributions and relationships
Analyze reasons for rule violations
Visualizations
The project includes several visualizations to better understand the dataset:

Distribution of molecular weight
Scatter plot of Molecular Weight vs LogP
Hydrogen bond donors vs acceptors relationship
Pass/Fail distribution
These plots help identify patterns in compounds that satisfy or violate Lipinski rules.

Outputs
The project generates the following outputs:

passed_drugs.csv → compounds that satisfy Lipinski rules
lipinski_labeled.csv → full dataset with Pass/Fail labels
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
How to Run the Project
Clone the repository
text
git clone https://github.com/yourusername/lipinski-drug-analysis.git
Install required libraries
text
pip install -r requirements.txt
Run the notebook
text
jupyter notebook
Then open:

text
Lipinski_drug_pj.ipynb
Conclusion
This project demonstrates how Lipinski’s Rule of Five can be applied to evaluate drug-likeness of chemical compounds. The analysis highlights how physicochemical properties influence compliance with these rules and provides insights into why certain compounds fail the criteria.