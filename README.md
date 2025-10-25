# Loan Status Approval Prediction

## Summary
Predicting client's loan approval status using classification model, comparing RandomForestClassifier and XGBClassifer. This project can be useful for someone to estimate if they eligble or not based on the feature can be input by the user

## Business Problem
1. Clasify loan application should be approved or denied based on the applicant data
2. Create simple interface(streamlit) for bank staff to get an immediate, data-driven recommendation loan's risk level
   
## Methodology
1. EDA & Preprocessing (handle gender columns, ranging age application, encode categorical columns, scaling)
2. Modeling (RandomForestClassifier & XGBClassifer)
3. Evaluation
4. Exporting Model into Pkl format
5. Setup Stremalit

## Skills
1. Python: Pandas, Scikit-Learn, Modeling, Evaluation, Modeling
3. Frontend: Streamlit
   
## Results
1. XGBClassfier was the best performing model with accuracy 93.35%
2. A final model.pkl succefully created ready to used in a live application
   
## Next Steps
1. Adding Model Explainability (XAI) to intergrate why the model approved or denied a specific loan, providing transparency for bank staff
2. Provide actionable advice based on prediction
3. Adding Weights to some feature importance explicitly that impact significantly loan status approval because a bad loan (False Positives) is more costly than a missed good loan (False Negatives).
