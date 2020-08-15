# atlanta-zipcode-analysis

This repo includes a non-technical summary presentation and jupyter notebook to get the estimates.
The notebook includes everything you'll need in a row to successfully run the notebook. However, you will need the following modules:
- Pandas
- Matplotlib
- Numpy
- Statsmodels
- Sci-kit learn
- Pyramid ARIMA

**Note: The data contained in zillow_data.csv is the raw data. To preprocess the data for Atlanta you will need to filter by the _Metro_ column for _Atlanta_**

The notebook deals with predicting the real estate values for the zipcodes that encompass the Atlanta metro area and how their value changes over time using time series analysis. The data ends in 2017, so the following values are predicted here:

| Zipcode | May 2018 | October 2018 | April 2019 |
| --- | --- | --- | --- |
| 30331 | $144,996 (.28%) | $150,547 (6.3%) | $169,655 (20%) |
| 30324 | $546,543 (.15%) | $541,136 (-.85%) | $551,665 (1.1%) |
| 30316 | $276,106 (1.3%) | $287,560 (5.5%) | $303,992 (12%) |
| 30308 | $603,982 (.78%) | $622,728 (3.9%) | $675,496 (13%) |
| 30307 | $590,713 (.62%) | $618,058 (5.3%) | $659,731 (12%) |
| 30317 | $394,741 (.80%) | $412,099 (5.2%) | $430,414 (10%) |
| 30326 | $598,301 (.66%) | $620,710 (4.4%) | $617,103 (3.8%) |
| 30363 | $339,330 (-.28%) | $333,488 (-2%) | $331,300 (-2.7%) |