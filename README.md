# HARQ_model_and_EVT
## Explore article by G.Lui and others "Forecasting the value-at-risk of Chinese stock market using the HARQ model and extreme value theory"
#### Main idea: for VAR forecasting we need two steps (1)RV is forecasted by making use of HAR-type models (2) extreme value theory (GPD) is used to depict
the standardized return 
### Models:
    1. HAR 
          Heterogeneous autoregressive model 
    2. HAR-J and CHAR 
          Heterogeneous autoregressive with jumps model and continuous heterogeneous autoregressive model
    3. SHAR 
          Semi-variance-heterogeneous autoregressive model
    4. HARQ 
          Heterogeneous autoregressive quarticity model
### Extreme value theory were used with treshhold $u$? wich been choose as: the highest 10% and lowest 10% of observations.
### Tests to inspect accuracy of VaR:
    1. UC
          unconditional coverage
    2. IND
          independent backtesting
    3. CC
          conditional coverage backtesting
          
### So, the plan is:
    1. Learn about HAR models class
    2. Learn about VaR methodology
    3. Learn about UC, IND, CC tests to VaR backtesting
    4. Таке CSI300 index data
    5. Appling different models to CSI300 index data 
    6. Use differnt tests to results obtained on Step 5
#### Maybe try this models and tests on other indexes. For example MSCI China A index. 
