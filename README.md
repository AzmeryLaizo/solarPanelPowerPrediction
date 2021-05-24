# solarPanelPowerPrediction

As the topic of Climate Change gets wide public attention, generating clean energy has become one of the top policy agendas. Governments across America are incentivizing the public to utilize clean energies, especially in the State of California. Solar panels have been installed in many California homes since solar is the most accessible source of clean energy.
One of the questions that California homeowners ask most is that how many solar panels do they need? Given the wide geographical variation in California, it is hard to generalize one standard for all California homeowners. 
The objective of this project is to help homeowners in Orange County accurately predict the number of panels needed.

The dataset for this study is extracted through an API from the National Solar Radiation Database https://nsrdb.nrel.gov/ for 69 zipcodes within Orange County. API-code file provides the python code used to extract dataset from the website. The code requires user's API key and lattitudes as well as longitudes of the locations that the user wants to extract solar irradiation data for. API key can be obtained from NREL website upon registration. 

RandomForestCode file contains code for the ML Random forest model created to make predictions for the Temperature variable.

solarPanelPredictionCode file contains code that uses GHI (solar irradiation) values and predicted temperature values to make predictions for the number of panels required based on the user's household annual power consumption needs and zip code.
