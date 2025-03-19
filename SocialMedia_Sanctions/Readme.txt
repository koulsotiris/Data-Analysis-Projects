Social Media Sanctions & Misinformation 

Overview
This project examines **Twitter suspensions** following the **2020 U.S. election**, analyzing the likelihood of suspension based on political hashtag usage.  
We use **cross-tabulation, corrections, and econometric models (Probit & Logit)** to investigate potential biases.

Technologies Used
- Python
- Pandas (Data Processing)
- Matplotlib (Visualization)
- Statsmodels (Probit & Logit Regression)
- Cross-tabulation & Likelihood Ratios

Data
- The dataset (`mosleh_et_al_data.csv`) contains Twitter users' **political hashtag usage** and **suspension status**.
- Data preprocessing includes:
  - Mapping **#Trump2020** and **#VoteBidenHarris2020** to numerical values.
  - Applying **corrections** for potential biases.
  - Computing **likelihood ratios** to quantify suspension disparities.
