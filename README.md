# data_anomaly
# Project - 6 :D(st)reams of Anomalies

#### Performed Anomaly detection on NAB data

#### The Numenta Anomaly Benchmark (NAB) is a novel benchmark for evaluating algorithms for anomaly detection in streaming, online applications. It is comprised of over 50 labeled real-world and artificial timeseries data files plus a novel scoring mechanism designed for real-time applications.

#### Data source : https://www.kaggle.com/boltzmannbrain/nab

#### I've applied anomaly detecting model on realKnownCause dataset "machine_temperature_system_failure.csv"

#### <img src=https://github.com/sushmitha-4/data_anomaly/blob/main/data_anomaly/reports/figures/Result6.jpeg>

## Feature Engineering

#### Generated year,day,hour,day of the week,month,week number,time of day and season from timestmap

#### <img src=https://github.com/sushmitha-4/data_anomaly/blob/main/data_anomaly/reports/figures/Result7.jpeg>

### Observation

#### I've mentioned the Count of anomaly and nomal for both the menthods
#### Type : Isolation forest
#### Normal: 21561
#### Anomoly: 1134


#### Type: ONE Class SVM :
#### Normal: 21617
#### Anomoly: 1078

#### As we can see One class SVM performed well than Isolation forest
#### From graphs we can also say that system failure has occuring
###### . First anomoly has occured during third week of December in 2015.
###### . Second anomoly  and third anomoly has occured during second week of Januray in 2014.


