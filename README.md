# Schneider-Data-Science-DataMVT
Solution for Data Science Hackathon - Team DataMVT

We have  pulled the data from ENTSOE database for different regions using API keys for  a period 2022 (1 year)  . We are forecasting the Load consumed and Green electricity generated for the 1 hour after 2022 ie, Jan 1 2023 00:00:00 AM.
We have done data aggregation at the hourly level for all data sources. Next we have done cleansing and interpolation to handle NAN and missing values.
For modeling we have tried multiple models after observing the seasonal and trend patterns of load and generation data. We have made use of 80:20 train:test for analyzing model performance. Upon trying different Statistical and Machine learning algorithms we concluded TBAT Algorithm for forecasting. After forecasting Load and generation data we have calculated the surplus energy produced.
