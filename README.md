# USC Dashboard

After completing my journey at the University of Southern California I made a dashboard which summarizies my Masters in Applied Data Science from 2021 - 2023. 
Hoping that this would be helpful for any upcoming students at USC!

![Expenses](https://github.com/veda1234/usc-dashboard/assets/23010614/112e46b2-a6ac-4bb4-865c-a23cd4dfc4de)
![Course](https://github.com/veda1234/usc-dashboard/assets/23010614/642cfce8-ce2e-4e5b-9ff3-d76deb3d9ab6)
![Logbook](https://github.com/veda1234/usc-dashboard/assets/23010614/d26134f4-80f5-421c-a66b-c1d1343155ff)



Click <a href="https://public.tableau.com/app/profile/vedaanti.baliga/viz/USCDashboard_16856561525930/Expenses?publish=yes" target="_blank" rel="noopener noreferrer">here</a> to see the tableau notebook.


This repository has the code for the "Expenses" tab in the tableau workbook. I extracted all the transactions from my 2 years at USC and then used it to make an analysis for my expenditure. I wanted 
to get the categories for each transactions and hence used NLP and Data Analysis to label data.

This repository has the following notebooks :

1. EDA_before : Exploratory analysis for all transactions
2. Cleaning_data : Cleaned the data after doing EDA
3. EDA_after : Exploratory analysis after cleaning the data
4. Preprocessing_data : Pre-processed data after doing some more EDA in EDA_after
5. Expenses_final : Final notebook in which the modeling was done using BERT
