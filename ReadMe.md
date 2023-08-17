# Project Title: Transplant Wait Time Prediction using Survival Analysis and Deep Learning

## Objective
The objective of the Transplant Wait Time Prediction project was to develop a robust predictive model for estimating the waiting time of prospective transplant recipients. By leveraging survival analysis methods and incorporating deep learning techniques, the project aimed to provide accurate predictions of the time recipients would have to wait for a suitable organ transplant. Rigorous statistical tests were conducted on the dataset, encompassing a comprehensive range of algorithms for survival analysis and deep learning, resulting in a commendable c-index of 0.68.

## Approach

## Previous Literature
Building on the work of Andrade & Team in 2021, the project used their study as a base. The study focused on Cox regression and Kaplan-Meier models. The proposed project aimed to enhance their model by infusing TDCR, random forest, pooled logistic regression (PLR), and other improved versions of survival analysis techniques. Additionally, conventional statistical analysis methods and various machine learning models were applied to capture non-linear relationships.

The base study by Andrade & Team can be found [here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0252069).

### Data Availability and Purpose
The project utilized the same dataset as the 'base study' conducted by Andrade and Team. This dataset is publicly available in the repository [here](https://www.kaggle.com/gustavomodelli/waitlist-kidney-brazil). The proposed project aimed to develop an improved predictor model using an ensemble of various machine learning models to estimate time on a kidney transplant waiting list. This improved model contributes to more efficient resource allocation, equitable transplantation programs, and the psychological well-being of patients.

### Rigorous Statistical Testing
The project employed an array of statistical methodologies to identify significant predictors influencing the waiting time. These tests went beyond the initial description and included advanced methods such as time-varying Cox regression and Random Survival Forests. The time-varying Cox regression accounted for dynamic changes in covariate effects over time, while Random Survival Forests offered a versatile ensemble approach to survival analysis.

### Feature Engineering
Building upon the initial feature engineering techniques, the project employed sophisticated methods to transform and enhance the dataset. Beyond risk scores and composite variables, advanced techniques such as recursive feature elimination and feature importance ranking were employed to ascertain the most influential predictors.

### Algorithms used

Survival analysis is a statistical approach used to analyze the time until an event of interest occurs. It's commonly applied in medical research to study time-to-event outcomes such as death, recovery, or transplant. The project employed several survival analysis algorithms:

#### Cox Proportional Hazards Model

The Cox Proportional Hazards model estimates the hazard function, representing the instantaneous risk of an event happening at a particular time. It's a fundamental technique in survival analysis and helps identify how various factors impact survival time.

**Learn more:** [Cox Proportional Hazards Model](https://en.wikipedia.org/wiki/Proportional_hazards_model)

#### Kaplan-Meier Estimator

The Kaplan-Meier estimator is a non-parametric method to estimate the survival function from incomplete data. It's used to plot the survival curve, offering insights into the probability of survival over time.

**Learn more:** [Kaplan-Meier Estimator](https://en.wikipedia.org/wiki/Kaplan%E2%80%93Meier_estimator)

#### Time-Varying Cox Regression

The Time-Varying Cox Regression model extends the Cox model to allow covariate effects to change over time. It's essential when the proportional hazards assumption is violated, capturing dynamic changes in covariate effects.

**Learn more:** [Time-Varying Covariates in the Cox Model](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4330079/)

#### Random Survival Forests

Random Survival Forests extend traditional random forests to survival analysis. They handle non-linear relationships and interactions between variables. By combining predictions from multiple decision trees, they generate survival estimates.

**Learn more:** [Random Survival Forests](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3042885/)

#### DeepSurv and DeepHit

DeepSurv and DeepHit are cutting-edge deep learning models for survival analysis. DeepSurv uses neural networks to directly estimate the hazard function. DeepHit combines a deep neural network with a mixture model to capture population-level and individual-level dynamics of survival data.

**Learn more:** [DeepSurv: Personalized Treatment Recommender System Using A Cox Proportional Hazards Deep Neural Network](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6237466/)

**Learn more:** [DeepHit: A Deep Learning Approach to Survival Analysis with Competing Risks](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5575877/)

These diverse algorithms enabled the project to handle various complexities in predicting kidney transplant waiting times. The combination of these techniques provided a robust and accurate prediction model that could account for different scenarios and data patterns.


### Model Evaluation Metrics
The project evaluated model performance using various metrics, including the widely-used c-index, which measures concordance between predicted and actual survival times. This metric gauges the model's ability to rank recipients based on their actual waiting times. Other complementary metrics like log-rank tests and integrated Brier scores were used to provide a comprehensive assessment.

### Power BI for Visual Representation
The results were showcased using Power BI, providing an interactive and visually appealing representation of the model's predictions, feature importance, and survival curves. This visualization tool added an extra layer of accessibility to the project's outcomes.

### Deployment on Heroku with Flask
To make the project accessible to a wider audience, it was deployed as a web application on Heroku. The application was containerized using Flask, allowing users to input relevant recipient information and receive real-time wait time predictions based on the developed model.

## Results

The Transplant Wait Time Prediction project concluded with significant achievements. The combined utilization of an extensive range of survival analysis algorithms and deep learning techniques led to a notable c-index of 0.68. This c-index highlights the model's ability to accurately distinguish between recipients with varying waiting times, indicating a substantial improvement over chance-level predictions.

## Future Implications

The project's outcomes extend beyond its immediate scope:

- **Enhanced Patient Care:** The accurate wait time predictions can significantly aid healthcare professionals in offering tailored guidance and support to transplant recipients, alleviating their anxieties and uncertainties.

- **Resource Allocation:** The reliable predictions provided by the model can streamline the allocation of medical resources, optimizing patient care and operational efficiency within healthcare institutions.

- **Process Improvement:** Insights gained from the model's analysis can drive continuous improvements in transplant procedures and policies, ultimately benefiting both patients and healthcare systems.

## Conclusion

The Transplant Wait Time Prediction project successfully demonstrated the harmonious integration of a diverse set of methodologies, encompassing survival analysis, statistical testing, and deep learning techniques. By delivering precise wait time estimates for transplant recipients, the project addressed a critical medical challenge. The commendable c-index of 0.68 serves as a testament to the model's capacity to generate valuable predictions. With potential applications spanning patient care enhancement, resource optimization, and transplant procedure refinement, the project's success has far-reaching implications for the medical field and healthcare industry as a whole.
