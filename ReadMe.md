**Transplant Wait Time Prediction**
- Predictive Analytics of waiting time of potential RTRs (Renal Transplant Recipients) for cadaveric grafts using MLMs.

**PURPOSE**: The proposed project aims to develop a better predictor model to estimate time on a kidney transplant waiting list using an ensemble of various ML models. It can help patients and clinicians to discuss management, thus contributing to a more efficient use of resources and making the process more equitable.

**KEYWORDS**: Biostatistics, Biomedicine, Kidney Transplant, Predictive Analytics, Clinical Research, Healthcare Analytics, Generalized Linear Models, Machine Learning, Statistical Analysis, Prediction, Decision Trees, Random Forests, Support Vector Machine, Feature Engineering.

**INSPIRATION**: When it comes to kidney transplants worldwide, the supply of organs does not meet demand. Statistical Science is replete with data confirming that. Also, the gap between them is growing. 

Because of this demand-supply gap, recurrent tests become necessary every 2–3 years to maintain prospective RTRs on the active transplant list. This poses a significant economic burden on the healthcare system. 

So predicting a patient’s waiting time becomes necessary. It can help to plan for pre-transplant evaluation. And benefits in three major ways:
•	Promote a more efficient use of resources: If we are able to predict the wait-time of a potential recipient with a fair amount of accuracy, we would carry full pretransplant evaluation only in candidates with a high chance of being transplanted. Those less likely would undergo only the most necessary tests at registration level and have their complete evaluation done only 6–8 hours before surgery. 
•	Promote Equity: Estimating waiting time on the transplant list can help identify the underprivileged, and thus impact allocation score, bringing more equity to transplantation programs.
•	Mental health of patients: The waiting time imposes significant emotional burden on the patients on dialysis. It also affects the performance of other organs like heart which is affected mostly because of dialysis. Kidney patients are anyway prone to depression. Knowing how long they have to wait will help them come to terms with reality, and rather than waiting in depression for a kidney, they will spend their energy on constructive enjoyment of their lives.
_Thus, the proposed project has three angles: economic, psychological, and sociological._

**METHODOLOGY**: Andrade & Team did a similar study  in 2021 using hazard ratio which focused on Cox regression and Kaplan-Meier models. The study is open access under creative commons license and permits unrestricted use, distribution, and reproduction in any medium, provided we credit the authors.

One can find it here: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0252069  

We will make it our base and try to improve it with an infusion of TDCR (Time dependent Cox regression), random forest, pooled logistic regression (PLR) and other improved versions of survival analysis techniques. We will also try conventional statistical analysis methods, linear regression, and non-linear models, such as decision trees, random forests, nearest neighbors, and support vector machine, which can capture non-linear relationships.

**DATA AVAILABILITY**: We will use the same dataset as used in our ‘base-study’ done by Andrade and Team. It is in a public repository: https://www.kaggle.com/gustavomodelli/waitlist-kidney-brazil

**Method** Employed


Project Title:
Transplant Wait Time Prediction using Survival Analysis and Deep Learning

Objective:
The Transplant Wait Time Prediction project aimed to develop a robust predictive model for estimating the waiting time of prospective transplant recipients. By utilizing survival analysis methods and incorporating deep learning techniques, the project sought to provide accurate predictions of the time recipients would have to wait for a suitable organ transplant. Rigorous statistical tests were conducted on the dataset, encompassing feature engineering and the application of the Cox Proportional Hazards model, resulting in a commendable c-index of 0.68.

Approach:

Data Collection and Preparation: The project involved the collection of comprehensive data related to transplant recipients, including medical history, demographic information, organ compatibility, and historical wait times.

Rigorous Statistical Testing: Extensive statistical tests were implemented to identify significant predictors influencing the waiting time. These tests included hypothesis testing, correlation analysis, and feature importance ranking.

Feature Engineering: Feature engineering techniques were applied to transform and enhance the dataset. Engineered features included risk scores, medical history summaries, and composite variables designed to capture the intricate nature of recipient profiles.

Cox Proportional Hazards Model: The Cox Proportional Hazards model, a powerful survival analysis technique, was employed. This model assessed the proportional hazard assumption and estimated the hazard function, providing insights into the impact of various predictors on waiting times.

Deep Learning Survival Analysis: In addition to traditional survival analysis techniques, deep learning methods were also explored. Deep learning models, such as neural networks and recurrent neural networks (RNNs), were employed to capture complex relationships within the data and improve prediction accuracy.

Results:
The Transplant Wait Time Prediction project successfully concluded with significant achievements. The predictive model achieved a noteworthy c-index of 0.68, indicating its effectiveness in distinguishing between recipients with varying waiting times. The project's combination of rigorous statistical testing, feature engineering, and application of survival analysis contributed to its success.

Future Implications:
While the project has ended, its outcomes hold potential for broader applications:

Enhanced Patient Care: Accurate wait time predictions can aid healthcare professionals in better managing and counseling transplant recipients.
Resource Allocation: Reliable predictions facilitate efficient allocation of medical resources, optimizing patient care and hospital operations.
Process Improvement: Insights gained from the model can guide improvements in transplant procedures and policies.
Conclusion:
The Transplant Wait Time Prediction project demonstrated the synergy between survival analysis, statistical testing, and deep learning methodologies. By accurately estimating wait times for transplant recipients, the project addressed a crucial medical challenge. The achieved c-index of 0.68 showcases the model's capacity to provide valuable predictions. The project's success has potential implications for patient care, healthcare resource optimization, and overall transplant procedure enhancement.

