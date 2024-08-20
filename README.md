# CeliacDiseasePredictor 

Millions of people worldwide suffer from celiac disease, an autoimmune disorder brought on by gluten consumption. The illness can cause anything from little discomfort to serious digestive problems. In order to properly manage the condition and enhance the quality of life for patients, early detection and intervention are essential. Machine learning algorithms have demonstrated potential in the recent past for the identification and prediction of a number of illnesses, including celiac disease.
ML models can help healthcare providers with quick intervention techniques and deliver accurate predictions by utilizing a variety of datasets that include genetic, clinical, and demographic information. This project aims to develop a robust ML model capable of predicting celiac disease risk based on relevant patient data. Through the integration of advanced algorithms and comprehensive feature selection techniques, the model endeavors to enhance diagnostic accuracy, thereby facilitating proactive management and personalized care for individuals at risk of celiac disease.
<br><br/>
<br><br/>
➤ **Data Collection and Processing**
<br><br/>The dataset for this project was sourced from Kaggle, a reputable platform for sharing datasets and machine learning resources. It comprises a diverse range of features related to celiac disease, including genetic markers, clinical symptoms, and demographic information. To ensure data quality and integrity, preprocessing steps were employed to handle missing values effectively. The data is then presented using data.head() and data.info() methods.
The pandas library in Python was utilized, specifically the dropna()  method, to remove instances with incomplete or null values. By systematically eliminating incomplete data points, we ensured the robustness and reliability of the dataset for subsequent analysis and model training. This streamlined preprocessing approach enabled us to focus on relevant and complete data, laying a solid foundation for the development of our predictive modeling framework.
<br><br/>
<br><br/>
➤ **Outcome/Result**
<br><br/>We used the Random Forest method in our celiac disease prediction model to create a robust machine learning model with an accuracy of 95.46% on the test dataset. Furthermore, through tree optimization up to depth 4, we achieved a fine-tune model, maintaining high accuracy of 92.44%, indicating the stability of the model's predictive capabilities.
The features selected such as Age, Abdominal Symptoms, Short Stature, Weight Loss, IgA Levels and IgG Levels, for our model were carefully chosen based on their relevance to celiac disease diagnosis and their availability in our dataset. Our model offers a useful tool for celiac disease early identification and detection which may help medical practitioners make better decisions and improve patient outcomes.
<br><br/>
<br><br/>
➤ **Conclusion**
<br><br/>
Our exploration into celiac disease prediction utilizing the Random Forest algorithm has yielded promising results achieving an accuracy of 95% on the test dataset. Our model not only offers predictive power but also provides insights into the key factors influencing celiac disease diagnosis. 
This holistic approach not only enhances clinical decision-making but also lays the foundation for future advancements in personalized medicine and targeted interventions. As a result, our research advances the field of predictive analytics while simultaneously highlighting the potential benefits of using machine learning to better understand complex disease pathways and improving patient care paradigms.


