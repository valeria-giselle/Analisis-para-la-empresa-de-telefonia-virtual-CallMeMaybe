# CallMeMaybe – Operator Performance Scoring System

## 📌 Business Problem
CallMeMaybe is a virtual telecom company that relies on call center operators to provide customer support.
Management needed a data-driven way to identify underperforming operators in order to improve service quality
and reduce customer wait times.

## 🎯 Objective
To develop a scoring system that identifies inefficient operators based on operational KPIs,
reducing manual analysis time and supporting data-driven decisions.

## 📊 Dataset
Call logs containing:
  - Incoming and outgoing calls
  - Missed calls
  - Waiting time
  - Operator ID
Data was cleaned and transformed using Python.

## 🛠️ Approach
1. Data cleaning and preprocessing
2. KPI definition:
   - Missed calls
   - High waiting times
   - Low outbound call volume
3. Scoring logic to rank operator performance
4. Visualization of insights in Tableau

## 📈 Key Results
- Identified underperforming operators using a clear scoring model
- Reduced analysis time by **30%**
- Enabled managers to focus coaching efforts on critical cases

## 📊 Dashboard
👉 https://public.tableau.com/app/profile/valeria.godoy/viz/Dashboard_17522059746270/Dashboard1?publish=yes
<img width="1454" height="780" alt="image" src="https://github.com/user-attachments/assets/e197a625-240c-4728-83cc-0218fc24e41f" />

## 📌 Business Recommendations
- Implement targeted training for low-scoring operators
- Monitor KPIs weekly instead of monthly
- Use the scoring model as an early warning system

## 📁 Repository Structure
- dashboard/     → Dashboard screenshots or Tableau link
- data/          → Datasets used in the analysis
- notebooks/     → Jupyter notebooks with analysis and scoring logic
- Hallazgos Evaluación Empresa CallMeMaybe.pdf
- README.md
- requirements.txt

## ⚙️ Technologies
- Python
- Pandas
- NumPy
- Seaborn
- Plotly
- Matplotlib

## ▶ How to Run the Project
pip install -r requirements.txt

jupyter notebook notebooks/proyecto_sprint_14.ipynb

## ✨ Final Note
This project demonstrates the application of data analysis to solve a real business problem, combining operational metrics, analysis automation, and visualization to support decision-making.
