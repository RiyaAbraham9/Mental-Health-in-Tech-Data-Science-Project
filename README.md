# Mental-Health-in-Tech-Data-Science-Project
A data-driven analysis exploring mental health challenges within the technology industry. This project includes data cleaning, exploratory data analysis (EDA), predictive modelling, and visualization to uncover key insights and patterns affecting tech professionals' mental well-being.

## Project Motivation
Mental health in the tech industry is an increasingly important topic as workplace stress, burnout, and anxiety are prevalent among professionals. Understanding the factors influencing mental health can help organizations create supportive environments and encourage open conversations. This project aims to leverage data science to shed light on these challenges and promote awareness.

## Dataset
The analysis is based on publicly available dataset:
(Mental Health in Tech Survey Dataset)[https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey]
The dataset contains survey responses from tech employees on topics such as mental health status, treatment, workplace culture, and demographic information.

## Objectives
- Clean and preprocess raw survey data
- Perform Exploratory Data Analysis (EDA) to identify patterns and correlations
- Visualize key metrics affecting mental health in the tech sector
- Build predictive models to classify or predict mental health status
- Extract actionable insights and recommendations for tech companies and employees

## Technologies and Tools
- Python 3
- Jupyter Notebook
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn, Plotly for visualization
- Scikit-learn for machine learning models

## Methodology
1. Data Cleaning: Handling missing values, encoding categorical variables, and normalizing data.
2. Exploratory Data Analysis: Analyzing demographic trends, treatment status, workplace factors, and mental health conditions.
3. Feature Engineering: Creating new variables that may improve model performance.
4. Model Building: Applying classification algorithms (e.g., Logistic Regression, Random Forest) to predict mental health status.
5. Evaluation: Assessing models using accuracy, precision, recall, and F1 score.
6. Visualization: Using charts and graphs to illustrate findings and support conclusions.

## Key Findings

- **Gender and Mental Health Treatment**:
A higher percentage of female respondents reported receiving treatment overall.
Among men, those who work remotely are more likely to receive treatment (47%) than those who do not work remotely (44%).
Among women, those working remotely are also more likely to receive treatment (72%) compared to those not working remotely (67%).
This could suggest that remote work provides both men and women with more opportunities to prioritize their mental health, compared to those who work in-office. It also raises the question of whether in-office employees may experience more pressure or have less accessible support for mental health struggles.
The data shows that women are more likely to access mental health support whether they are remote or in-office, compared to men. This could suggest a need for more accessible, targeted support for men, both in the workplace and remotely. It also highlights the importance of addressing stigma around men's mental health and encouraging open conversations.
<img width="718" height="569" alt="image" src="https://github.com/user-attachments/assets/3939c953-c6a1-46c3-bb9b-7eea00ccfb70" />


- **Age Distribution** :
Highest Treatment Rates:
Individuals aged 26–35 and 36–45 reported the highest rates of mental health treatment.
These age groups often face pressures related to careers, finances, and family, increasing stress and prompting them to seek treatment.
**Young Adults (18–25):**
May face access barriers such as cost, so it is less likely for them to access mental health help.
High stigma and fear of judgment may prevent them from reaching out, especially in academic or early workplace settings.
**Midlife Adults (26–45):**
Likely benefit from better access to healthcare through employment.
More likely to recognize symptoms and seek help due to past experiences or growing awareness.
**Older Adults (55+):**
May be impacted by generational stigma surrounding mental health.
Could also face digital access issues, reducing their ability to benefit from online therapy or remote care options.
This suggests:
  - Increase early support and de-stigmatization efforts for young adults.
  - Improve access and outreach for older adults, possibly through in-person and age-friendly services.
  <img width="726" height="558" alt="image" src="https://github.com/user-attachments/assets/1ea2e41f-e157-42c1-a5cc-a510a6011e7d" />

- **Mental Health benefits influencing benefits**:
  - The data reveals a relationship between the influence of mental health benefits and the likelihood of individuals seeking treatment.
  - Interestingly, those unsure about their benefits ("Don’t know") exhibit the highest proportion of non-treatment—suggesting that lack of clarity around         coverage may act as a barrier to care.
  - individuals who recognize their benefits ("Yes") demonstrate the highest treatment uptake, underscoring the motivational effect of benefit awareness.
  - Those reporting no benefits occupy the middle ground, indicating that while the absence of coverage impacts treatment rates, uncertainty may be an even stronger deterrent than outright lack of benefits.

    **Improving benefit awareness may be a low-cost, high-impact way to increase mental health treatment engagement, potentially more influential than changing the benefits themselves.** 
  <img width="733" height="638" alt="image" src="https://github.com/user-attachments/assets/7a63fbb6-7b3b-4778-bc15-136b5e2b203d" />

-**Modelling Results**:
Here is a summary of the classication results for the 2 models: 
  | Model               | Accuracy | Precision | Recall | F1-score |
  | ------------------- | -------- | --------- | ------ | -------- |
  | Logistic Regression | 0.72     | 0.72      | 0.72   | 0.72     |
  | Random Forest       | 0.70     | 0.70      | 0.70   | 0.70     |
  
- I tested two classification models to predict whether a tech professional has sought treatment for a mental health condition:
  - **Best model:** Logistic Regression with 72% accuracy.
    <img width="520" height="390" alt="image" src="https://github.com/user-attachments/assets/29d68a98-5e03-49c7-8a0d-42f27408cbe7" />
    - The model correctly identifies ~70% of people who actually sought treatment.
    - The model correctly identifies ~74% of people who didn’t seek treatment.
    - Misclassified 38 individuals who sought treatment as not seeking treatment, which suggests improving recall could make the model more helpful for early            intervention
  -  **Most important features (Random Forest):**
    1. Family history of mental illness
    2. Age
    3. Care options
    4. benefits
     <img width="715" height="195" alt="image" src="https://github.com/user-attachments/assets/c96ec698-83f3-479a-bdcb-22784561281d" />

     Mental health in the tech industry is shaped by a combination of personal, demographic, and workplace factors.
     **Family history** of mental illness can make individuals to more vulnerable, requiring proactive support systems.
     **Age** plays a role in mental health dynamics—early-career professionals often face instability and imposter syndrome, while more experienced employees may experience burnout.
     **Care options**, such as accessible counseling, therapy coverage, and flexible schedules, directly affect engagement with mental health resources.
     **Benefits awareness** is critical, since employees who understand and trust their coverage are far more likely to seek timely help.

  **Future improvements:**
  To build a healthier tech workforce, companies can:
  
  - Normalize conversations around mental health through leadership visibility and peer networks.
  - Enhance benefits clarity with transparent, jargon-free communication and onboarding refreshers.
  - Expand care access by offering diverse options such as virtual therapy (subscriptions to platforms such as better help) and on-site counseling.
  - Target at-risk groups with tailored programs for early-career and employees who have been working for some time.
  - Invest in prevention by embedding mental wellness training into career development and performance reviews.

## Future Improvements:
- Expand dataset with more recent surveys
- Develop interactive visualisations for deeper insights, such as steamlit app
- Collaborate with mental health professionals to find out more information

## Contact:
Created by Riya Abraham. Feel free to reach out at riyasabraham@gmail.com and my LinkedIn is [https://www.linkedin.com/in/riya-a-78aa55227/].


