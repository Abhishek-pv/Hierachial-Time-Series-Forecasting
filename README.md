# doppler

> Automatic Hierarchical Time-Series Forecast at different aggregation levels

***

#### Installing environment
```bash
$ conda create --name forecast
(forecast)$ conda env update --file environments --name forecast
```

#### Running it

`notebook` directory contains jupyter notebooks that were used for each step of the datascience pipeline

#### User Interface

[Frontend](https://github.com/sachwithgithub/doppler-frontend)

#### Contributers
##### Team: Deep Learners
- [Ria Gupta (Ria312)](https://github.com/Ria312)
- [Abhishek PV (Abhishek-pv)](https://github.com/Abhishek-pv)
- [Ishan Sahay (VWJF)](https://github.com/VWJF)
- [Sachin (sachwithgithub)](https://github.com/sachwithgithub)

#### Dataset

Due to an NDA agreement with our industry partner, we cannot share the data source or the intermediate files generated by it.

#### Data Science Pipeline

![data science pipeline][docs/pipeline.png]

#### Video
https://www.youtube.com/channel/UChgkiNv7qe2DbhzFW4AK6qQ/

[![doppler](http://img.youtube.com/vi/UChgkiNv7qe2DbhzFW4AK6qQ/0.jpg)](https://www.youtube.com/channel/UChgkiNv7qe2DbhzFW4AK6qQ/)


***

## Roadmap
[:arrow_up: Back to top](#doppler)
- [x] ETL
- [x] EDA
- [x] Statistical testing ACF/PACF
- [x] Basic Modeling using AR, MA, AR+MA
- [x] Modeling using ARIMA, SARIMA 
- [x] Modeling
- - [x] Recurrent Neural Network (LSTM)
- - [x] AutoArima
- - [x] Prophet
- - [ ] Probabilistic Modeling
- [x] Aggregation
- - [x] Aggregation matrix
- - [x] Bottom up aggregation
- [x] Hierarchically modeling (modeling across levels)
- - [x] Multi threaded parallelism
- - [ ] AWS EMR (explored)
- - [ ] AWS Sagemaker (explored)
- - [ ] AWS Lambda (explored)
- [x] User Interface 
- - [x] Flask app
- - [x] Plotly Dash integration



