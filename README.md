Customer Segmentation and Prediction for Retail Marketing
This repository contains a marketing analytics project that uses customer data to create a segmentation and prediction model for a fictional online retailer, Luna7. The full analysis is detailed in the report, "NBS8604_Marketing_Analytics.pdf".

Project Overview
This project was undertaken to help Luna7, a US-based online retailer of clothing and home goods, improve the effectiveness of its promotional campaigns. The primary objectives were:
1.	To determine if psychographic and lifestyle factors can be used to create meaningful customer segments. 
2.	To assess how well these segments, along with past purchasing behaviour (RFM), can predict customer responsiveness to promotions in specific product categories. 
The study leverages a dataset of 265 customer responses to build a data-driven framework that enables personalized marketing, reduces campaign risk, and optimizes ROI.

File Structure
Marketing-Analytics-Customer-Segmentation
┣ NBS8604_Marketing_Analytics.pdf
┗ README.md

Methodology & Technologies
A multi-stage analytical approach was employed using SPSS to process the data and derive insights.
•	Data Preparation: Missing values in ordinal variables were imputed using the median of nearby points, while nominal variables were imputed with the mode. 
•	Exploratory Factor Analysis (EFA): Used to identify underlying psychographic dimensions from 43 variables. A KMO score of 0.870 and a significant Bartlett's Test confirmed the data's suitability for factor analysis. 
•	K-Means Cluster Analysis: Segmented customers into four distinct groups based on the factor scores derived from EFA. The four-cluster solution was chosen for its interpretability and statistical robustness. 
•	RFM (Recency, Frequency, Monetary) Analysis: Quantified customer value by analyzing past transaction behaviour. 
•	Binary Logistic Regression: Developed predictive models to determine the likelihood of customer response to promotions for clothing, accessories, and home goods. Model performance was assessed using accuracy, Nagelkerke R², and ROC-AUC. 
________________________________________
Key Findings & Results 📈
•	Customer Segmentation: Four meaningful psychographic segments were identified: 
o	Mindless Mobile Shoppers: App-driven and impulsive.
o	Rental Rationalists: Cautious and price-focused.
o	Social Validators: Highly influenced by peer reviews and visual content.
o	In-Store Seekers: Prefer physical retail experiences. 
•	Predictive Modelling: 
o	The model for the accessories category was the strongest performer, achieving 83% classification accuracy, a Nagelkerke R² of 0.558, and an AUC of 0.90. 
o	The home goods model had an accuracy of 84.9% and an AUC of 0.89. 
o	The clothing model showed moderate predictive power with 68.7% accuracy and an AUC of 0.76. 
•	Actionable Insights: The analysis confirmed that a combination of psychographic profiles and RFM scores significantly predicts promotional response, especially for accessories. "Social Validators" (Cluster 3) were found to be over 5.5 times more likely to respond to accessory promotions. 
________________________________________
Dataset
The analysis is based on a proprietary dataset from Luna7, which contains survey responses from 265 customers. The dataset includes over 130 variables covering:
•	Demographics
•	Psychographics (e.g., mindfulness, social media use) 
•	Digital and offline shopping behaviour 
•	Purchase history (Recency, Frequency, Monetary) 
•	Responses to promotional campaigns for clothing, accessories, and home goods. 
________________________________________
Business Recommendations
The findings lead to several strategic recommendations for Luna7:
1.	Enhance Visual Marketing for Accessories: Target "Social Validators" with user-generated content, influencer collaborations, and prominent review highlights in promotional materials. 
2.	Re-engage Mid-Tier Customers: Use mobile-first promotions like app-exclusive sales and loyalty programs to reactivate recent customers with low frequency and spend. 
3.	Operationalize Insights in CRM: Integrate psychographic cluster IDs and RFM scores into the CRM system to enable automated, real-time personalized campaign targeting.

Author
•	Chinmay Dunakhe
•	Institution: Newcastle University 
•	Course: NBS8604 Marketing Analytics 

