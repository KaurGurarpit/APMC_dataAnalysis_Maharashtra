# APMC_dataAnalysis_Maharashtra
To understand trends in APMC (Agricultural produce market committee)/mandi price &amp; quantity arrival data for different commodities in Maharashtra.  Objective: Test and filter outliers. Understand price fluctuations accounting the seasonal effect Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities De-seasonalise prices for each commodity and APMC according to the detected seasonality type Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.
## Import Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
sns.set()
from google.colab import files
## Loading the datasets
