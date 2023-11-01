# Retail Energy and Emissions calculator

# 1. Inputs

## 1.1 Files

All the files required to run this model are in the next link. Two folders are considered, the working folder "GenIMLLP_model" and previous models "NCST"

Link: https://ucdavis.box.com/s/mhpvmvgn9db75kbmfm6lql7yzo8wvqmv

## 1.2. Enter all the parameters 

Each scenario result as a combination of parameters that should be defined in the section "DATA REQUIRED TO RUN THE CODE" In[2] in the model "Model-5-23.ipynb". 
Bellow you can find the inputs specifications. 

**Base Purchasing Scenarios**

There are currently three high level scenarios in the model (and another, default, as a placeholder). While most of the values used are the same across all scenarios (and are by default selected considering the most common scenario), we detail below the most important scenario assumptions used in the model, and the rationale for the assumptions selected in the given base scenarios. Please find the csv files in the data folder. A file call example.xls with information of possible imputs are also in the same folder.

1. Retail Scenario
2. E-tail Scenario
3. Efficient e-tail Scenario
4. Omni - Both Scenario

**Metropolitan Statistical Areas (MSA)**

1. Chicago (CHI)
2. Washington D.C. (DC)
3. Los Angeles (LA)
4. New York City (NYC)
5. San Francisco (SF) 

**Population growth scenarios specification**

We attribute the future population growth to two developments, one is the future change in the socioeconomic conditions of the region, reflected in the change in the market shares of the different independent variables, and the other is the future growth of the total population of the region. We delineate two growth patterns, a moderate pattern, which implies little change in future socioeconomic conditions from the present and no significant growth in total population, and a high growth pattern, which implies a significant growth in both socioeconomic conditions and total population projection. After permutation, Table 2 shows the four population growth scenarios that we have delineated. 

1. Moderate-Moderate (MM)
2. Moderate-High growth (MH)
3. High growth-Moderate (HM)
4. High growth-High growth (HH)

**Energy and emission scenario**

User should provide here which scenario of Energy Intensity and Emission per year per vehicle want to consider: 

1. BAU - MOVES model
2. BAU - Energy Information Administration - EIA
3. NZE50 - Net Zero 2050 - IEA
4. Custom: Energy_Percentages.csv

**Year analyzed in the tornado diagram**

User has the option to change the year that want to analyze in the one direction sensitivity analysis.

**Path for running**

Paste the path of the working folder and the path of the NCST data folder.
