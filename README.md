SMOKING AND HEALTH OUTCOMES

What 2,500 Patient Records Actually Showed
I built a health analysis dashboard using a dataset of 2,500 patients, segmented by smoking status: current smokers, former smokers, and people who have never smoked.
Here is what I found, and what surprised me.
The process
I cleaned and analysed the dataset in Python, built the dashboard in Power BI, and wrote the report in a plain-language format anyone could read. The goal was not just to visualise data but to make the findings useful to a non-technical audience.
The surprising stats
Never-smokers had the highest organ damage rate at 37.1%, compared to 34.9% for current and former smokers.
That sounds wrong. It is not. Never-smokers are the largest group in the dataset (1,136 patients), so they produce more damage cases in raw numbers. The rates across all three groups are actually very close. That alone is a lesson in how easy it is to misread raw counts without context.
Key findings
Current smokers had the worst cholesterol profile. 34.5% had cholesterol above 240 mg/dL versus 30% of never-smokers.
Former smokers had the highest blood pressure rate at 27.9% and the highest obesity rate at 50.7%. Quitting smoking is the right call, but the body does not reset overnight.
Liver and heart damage were most common in current smokers, with 68 and 59 cases respectively.
Alcohol and family history were almost identical across all three groups. They did not explain the differences.
The real lesson
Smoking status alone does not predict organ damage in a straight line. BMI, blood pressure, cholesterol, and family history all play a role. If you use a single variable to explain a health outcome, you will get a misleading picture.

Tool<img width="654" height="367" alt="Smoking Analysis Dashboard" src="https://github.com/user-attachments/assets/65a49dfe-fe96-4906-9393-4cc74b3c1e6e" />
 used:Power BI
Dataset: 2,500 patient health records
Full report available in this repository.

