# MODULE 9 - FIRST PROJECT.
    GITHUB Repository name: "m92project.

# TEAM MEMBERS: Patrick Nwankwo, Jesse Poljak, Larry Azar.

# DATA SOURCE:
    # Bank for International Settlements (2024):
    # Nominal Effective Exchange Rate (NEER), BIS WS_EER 1.0 (data set):
# https:// data.bis.org/topics/EER/BIS,WS_EER,1.0/D.N.B.US (accessed on 24 September 2024).
# SOURCE CODES:
    # "XPert" Learning Assistant, Bootcamp Module Assignments, Google Colabs "Gemini".  

# PROJECT AND PURPOSE 
# Our team is going to analyze the NEER from 1996 to 2024 for "external shocks" such as 
# The purpose is to attempt to answer the following questions:
    # how is the data modelled ? 
    # What changes can be identified in the spread of the data? 
    # Do any changes in the spread of the data over time appear to be affected by Seasonality ?
    # Can we make any predictions based on the data and Seasonality?

# EXAMINATION OF THE DATASET 

# Generally
    # The dataset is non seasonally adjusted. i.e. not adjusted for inflation
    # The data frequency is daily from 11/4/1996 to 9/24/2024 for the U.S Dollar Nominal Effective Exchange Rate measured  
    # against the geometric weighted average of 64 economies based on bilateral trade policies.
    # Year 2020 is the base year with an index of 100 against which all other years are measured against.

# What columns are there? 
    # Frequency, EER Type, EER Basket (broad), Reference Area (U.S.),Time_Period (Daily), Observed Value # OBS # of the EER, OBS_STATUS:Status, OBS_PRE_BREAK:Pre-break value

# What unique values do the columns contain?
    # Nominal Effective Exchange Rate (NEER) "index"   

# Are any columns especially suitable for grouping?
    # The Time Period column to extract and group the months of October and November after the U.S. Presidential Election.

# Are there any interesting questions based on the available columns? 
    # What does the EER represent?
    # The EER represents the index rater for measuring international competitiveness of one currency vs a basket of 64 economies in the group. 

# CLEANING THE DATASET 
    # Null values will be dropped, for e.g. Not a Number (NaN) is to be removed for public holidays & weekends 
    # Static columns will be dropped.
    The Unit_Measure "882" column is not needed.

# PERFORMING EXPLORATORY DATA ANALYSIS 
    # Using descriptive statistics to compare election versus non-election years
    # U.S. Presidential Election Years vs None U.S Presidential Election Years" in 30 days prior and after the election

# PERFORMING EXPLORATORY DATA ANALYSIS (EDA)
    # Create a Prophet model to understand how the data is modeled.
    # Fit the Prophet model by providing the future dataset and identifying for any changes due to Seasonality.
    # Create a DataFrame for date-times and observations to hold predictions
    # Conduct a time series forecast for forecasting based on the following Seasonality 
    # The U.S. Presidential Election on the first Tuesday in November every four years 

  

    


  
