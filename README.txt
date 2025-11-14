

 UCI Adult Income Dataset 
Research Question: 
- How do education level and gender influence income levels, and to what extent do they contribute to income differences? 

Workload Distribution 
1. Introduction & Data Summary (Fawwaz & Yandav) April 4-8 
2. Data Wrangling & Preprocessing (Ian) March 21-27 
3. Exploratory Data Analysis (EDA) & Visualization (Ian & Jack) March 21-27 
4. Analysis & Model Development (Ike) March 28-April 3 
5. Conclusion, Recommendations & Report Formatting (Fawwaz & Yandav) April 4-8 
Introduction The UCI Adult Income dataset is a popular resource for studying how demographic and employment factors relate to income. In this project, our primary goal is to determine whether and how education level and gender (sex) influence an individual’s likelihood of earning above $50k per year. 

Data Summary 
- The dataset contains approximately 48,842 rows, each representing an individual, and 15 features, namely: Age, Work Class, Education, Marital Status, Occupation, Relationship, Race, Sex, Capital Gain/Loss, Hours per Week, Native Country, and Income bracket (>50k or <=50k). 
- We found three features—Work Class, Occupation, and Native Country—had missing values marked as “?”, ultimately leading us to drop about 14% of the observations. Our final cleaned dataset retains around 30,000+ rows, ensuring sufficient sample size. 
- We also recoded “Income” as a binary variable (1 if >50K, else 0) and “Sex” as 1 for Male and 0 for Female. This makes it easier to perform the classification and statistical tests described below. 

What Does Our Data Contain? Feature Type Description Qualitative or Quantitative Age Integer Age of the individual Qualitative Work class Categorical Type of employment(self, private, etc) Quantitative Fnlwgt Integer Weight of individual Qualitative Education* Categorical Highest level of education Quantitative Education num* Integer Encoding of education level Quantitative Marital status Categorical Status(single, married, etc) Qualitative Occupation Categorical Current job Qualitative Relationship Categorical Status(husband, wife) Qualitative Race Categorical Rate of individual Qualitative Sex* Binary Male or Female Quantitative Capital gain Integer Gain income Quantitative 
