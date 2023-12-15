# tb_prediction

## Description
This package includes r codes, data and reports for predicting TB incidence.

## How to run
1. `Clone` the repository.
2. Check the `path` where you save/clone this repo.
3. To run code: <br>
    a. Go to `rcode` directory. <br>
    b. Open the file named `tb_incidence_prediction.R`. <br>
    c. Block the code that you want to run. <br>
    d. Run code

    ****

4. To run Rmd file: <br>
    a. Go to `root` directory. <br>
    b. Open `Report_BChoi.Rmd` file. <br>
    c. Hit the `knit` button. <br>
    
```
In case the code has path error:

Check ${setwd("./")} path in the ${tb_incidence_prediction.R} file. It is written at the first line of the file.

Check where you save the entire repo and change the path to run the codes.
```

## Data collection
Data provided by countries and territories are selected as predictor variables
- Case notifications 
- Drug resistance testing in pulmonary bacteriologically confirmed TB patients since 2017
- Laboratory diagnostic services
- Non-routine surveillance of HIV prevalence in TB patients
- TB policies and services in 2022
- Community engagement activities for TB
- Budgets for TB since fiscal year 2018
- Expenditure and utilization of health services for TB since fiscal year 2017
- GDP per capita in 2022
- The number of population in 2022

## Data preprocessing
- Missing: 50% values are miisng in observed, the variable is deleted.
- Standardized data: Fit scaler (mean and sd) for continuous variables.

## References
a. [WHO TB data](https://www.who.int/teams/global-tuberculosis-programme/data) <br>
b. [World Bank](https://data.worldbank.org)

### Copyright
> Bich Na Choi