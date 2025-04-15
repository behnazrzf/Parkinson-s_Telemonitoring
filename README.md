# Parkinson’s Telemonitoring
Objective: This dataset is composed of a range of biomedical voice measurements from
42 people with early-stage Parkinson's disease recruited to a six-month trial of a
telemonitoring device for remote symptom progression monitoring. The recordings
were automatically captured in the patient's homes. Columns in the table contain
subject number, subject age, subject gender, time interval from baseline recruitment
date, motor UPDRS, total UPDRS (UPDRS=Unified Parkinson Disease Rating Scale), and
16 biomedical voice measures. Each row corresponds to one of 5,875 voice recording
from these individuals. The main aim of the data is to predict the motor and total
UPDRS scores ('motor_UPDRS' and 'total_UPDRS') from the 16 voice measures.
Possible Methodology: Use PCA to explore the data. Apply polynomial regression
models to estimate UPDRS from the demographic and voce features. Compare the
performance of different polynomial orders. Use cross-validation to establish the
correct model order.
Analyse the model ability to predict the different motor portion of the UPDRS
score. Use hypothesis testing to analyse which features are more significant
contributors to the prediction.
Data: https://archive.ics.uci.edu/static/public/189/parkinsons+telemonitoring.zip
