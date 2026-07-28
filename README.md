❤️ Heart Disease Risk — What's Actually Driving It?

Heart disease doesn't announce itself with one obvious cause — it's a mix of biology, lifestyle, and habits that quietly stack up over time. This project digs into patient-level health data to find out which factors actually move the needle on risk.

🔍 The Question

Given a patient's vitals, labs, and lifestyle — sleep, stress, exercise, diet — can the data tell us who's at higher risk before it becomes a diagnosis?

🛠️ The Pipeline

Raw patient data → cleaned & explored in Python → deep-dive EDA using pandas, matplotlib, seaborn in Jupyter Notebook

📊 What's in the Data

9,000 patient records covering demographics, cardiovascular vitals, blood work, and daily lifestyle habits.

Category	Columns
Demographics	age, sex
Vitals	resting BP (systolic/diastolic), resting & max heart rate
Blood work	cholesterol (total, HDL, LDL), triglycerides, fasting blood sugar, HbA1c
Body	BMI
Symptoms	chest pain type, exercise-induced angina, ST depression
Lifestyle	smoker status, alcohol units/week, exercise minutes/week, sleep hours, stress score, daily steps, diet quality score
Background	family history
Target	has_heart_disease
🔬 What I Actually Did
Cleaned the data: checked for missing values, verified data types, handled outliers in vitals/labs
Explored risk patterns:
How does age, BMI, and cholesterol relate to heart disease risk?
Do lifestyle factors (sleep, stress, exercise, diet) show a measurable link?
How much does family history and smoking status shift the odds?
Which single factor separates high-risk from low-risk patients most clearly?
Visualized the story: distribution plots, correlation heatmaps, and comparison charts across the has_heart_disease groups
📸 The Findings, Visually

er-attachments/assets/5091f146-f56c-4c80-9073-574184816de0" />    

<img width="692" height="552" alt="image" src="https://github.com/user-attachments/assets/5d1f8a16-bc36-4149-8652-95a11b94ea2e" />

<img width="301" height="277" alt="image" src="https://github.com/user-attachments/assets/2d7224ad-db1a-49c5-bf7b-09c89bed35b8" />

<img width="479" height="272" alt="image" src="https://github.com/user-attachments/assets/0b53a66f-2991-4372-a962-dd2bbcd3575b" />

<img width="692" height="545" alt="image" src="https://github.com/user-attachments/assets/5163e11f-7921-44c9-9022-e023911e848f" />


💡 Biggest Finding

(Fill this in with your real #1 insight once you re-share the notebook — e.g. "Patients with high stress scores AND low exercise minutes showed disease rates 2x higher than the rest of the dataset.")

🧠 Why It Mattered

This wasn't just plotting columns against a target — it meant thinking about which factors are modifiable (exercise, sleep, diet) versus fixed (age, family history), since that's the distinction that actually matters for prevention.

🧰 Tools

Python · pandas · numpy · matplotlib · seaborn · Jupyter Notebook

📁 In This Repo
heartdiseaseanalysis.ipynb — full analysis notebook
heart_disease_risk_2026.csv — dataset (9,000 records)
images/ — exported charts
📄 License

MIT — free to use, fork, and build on.
