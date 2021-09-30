# Analysis_and_ML_Model_Health_Expenses_on_Age_Sex_Smoker_BMI
Analysis of health related expenses on physiological factors and smoking.

Outline
An investigatetive study and predictive ML model about healthcare costs on individuals age, sex, bmi, number of children and smoker status. Please read the Analysis_health_related_expenses_age_sex_BMI_children_and_smoker_status.pdf file attached for the analysis report.

Part 1. Analysis
Data were uploaded from .csv file followed by ETL. Data anlysis was performed using pandas. Visualizations were via haloview.  

Part 2. Predictive modeling 
Linear Regression analysis for classification was carried on the same dataframe with modification to introduce a risk cutoff at $40,000 which is tunable. Accuracy score was 0.98 although Recall score needs to be improved as such cost risks could be better improved.

Inputs
Data were read from insurance.csv for the analysis.

Outputs
Outputs are given out as mentioned above on the terminal as calculated values, visual plots/graphs/figures, and explanations about the results.

Remarks
Since the focus is to find the high cost/high risk individuals this will be inherently an imbalanced data set. Will be treated as such in a future analysis. Suggestions are given in the .pdf report file.
