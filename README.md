## A data analysis repository that is meant for https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf

Installation and software requirements to build upon this can be found below Results.

### Results:

My analisys has been to identify following:
- Hospitalization rate by age group and whether patient has previous medical condition or not
- ICU rate by age group and whether patient has previous medical condition or not
- Death rate by age group and whether patient has previous medical condition or not
- Hospitalization rate by age group and whether patient has previous medical condition or not


#### Hospitalization rate by age group and whether patient has previous medical condition or not
![Hospitalized](https://github.com/yittoo/cdc-covid-data-analysis/blob/master/results/hospitalized_by_age_group.png)

#### ICU rate by age group and whether patient has previous medical condition or not
![ICU](https://github.com/yittoo/cdc-covid-data-analysis/blob/master/results/icu_by_age_group.png)

#### Death rate by age group and whether patient has previous medical condition or not
![Death rate](https://github.com/yittoo/cdc-covid-data-analysis/blob/master/results/death_by_age_group.png)

#### Input compared to test cases of available data
![Actual vs test cases](https://github.com/yittoo/cdc-covid-data-analysis/blob/master/results/actual_vs_test_cases.png)

Where y axis is case count and x axis is date in unix timestamp. Green is actual data, red is predictions over test cases.

#### Future case count considering past 6 months
![Future cases](https://github.com/yittoo/cdc-covid-data-analysis/blob/master/results/future_predictions.png)

Where y axis is case count and x axis is date in unix timestamp. Green is actual data, red is predictions over test cases and blue is future predictions for next 4 months.

Just take the future predictions with a doubt. The data released by CDC is up until 15 days ago using that today's prediction (3.3M cases) is way off than the actual number (4.5M cases) as of writing this report (2020-08-02) so this is no way an actual credible prediction as there are way more factors at play.

#### Requirements:
1) Python 3.6 or above
2) Anaconda with core packages installed
3) Downloading the .csv data from https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf and putting in the root of the project

#### How to use:
Once software requirements above are met, open main.ipynb inside a python notebook editor.

