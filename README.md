
#  Prevalance of malaria in Nigeria using Logistic Regression 

Malaria remains a major public health concern in many parts of the world, especially in regions with high transmission rates. This project aims to build a **logistic regression model** in **R** to predict the **prevalence of malaria** using key **demographic and environmental factors**.

##  Objective

Develop a predictive model that can help identify individuals and regions at higher risk of malaria, thereby enabling better public health planning and resource allocation.

## Dataset Features

The model considers the following variables:

-  Age of children  
-  Source of drinking water  
-  Maternal education level  
-  Gender  
-  Regional location  
-  Household wealth index  

##  Tools & Techniques

- **Programming Language:** R  
- **Model Type:** Logistic Regression (`glm` function in R)  
- **Evaluation Metric:** ROC Curve  
- **Performance Metric:** AUC (Area Under the Curve)

##  Model Performance

- **AUC Score:** `0.689490`  
- Interpretation: This AUC indicates a *fair* level of discrimination between individuals at high and low risk of malaria.

##  Key Insights

- The **age of children** and **source of drinking water** were found to be the most significant predictors of malaria risk.
- Other variables like **maternal education**, **gender**, **region**, and **household wealth** also contributed to malaria prevalence but with varying degrees of influence.

##  Implications for Public Health

This model can support public health agencies by:

- Identifying **high-risk groups and areas**
- Guiding the **distribution of insecticide-treated nets (ITNs)**
- Supporting **indoor residual spraying (IRS) programs**
- Informing **community education campaigns**
- Aiding in the **targeted deployment of medical resources**

##  Conclusion

This project emphasizes the importance of **data-driven approaches** in combating malaria. The logistic regression model provides useful insights into key risk factors and serves as a foundation for future model enhancement and more targeted public health strategies.

##  Keywords

`Malaria` · `Logistic Regression` · `R Programming` · `ROC Curve` · `AUC` · `Public Health` · `Prediction` · `Data Science`
