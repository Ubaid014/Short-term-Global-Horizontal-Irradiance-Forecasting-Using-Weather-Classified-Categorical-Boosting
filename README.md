# Short-term-Global-Horizontal-Irradiance-Forecasting-Using-Weather-Classified-Categorical-Boosting
## Abstract
Accurate short-term solar irradiance (SI) forecasting is crucial for renewable energy integration to ensure unit commitment and economic load dispatch. However, hourly SI prediction is very challenging due to atmospheric conditions and weather fluctuations. This study proposes a hybrid approach using weather classification and boosting algorithms for short-term global horizontal irradiance (GHI) forecasting. In data pre-processing steps,  we employ random forest for feature selection and K-means clustering for weather classification. The weather-based clustered data is used for the model training using categorical boosting (CatBoost). The proposed weather-classified categorical boosting (WC-CB) scheme is compared with benchmarks in literature like adaptive boosting (AdaBoost), bi-directional long short-term memory (BiLSTM) and gated recurrent unit (GRU) using datasets from two distinct geographical locations obtained from the National Solar Radiation Database (NSRDB). The results show that the proposed WC-CB hybrid approach has lower forecast errors compared to conventional CatBoost modelling. The error reduction of 16\% and 39\% in root mean square error and 6\% and 9\% in mean absolute error is recorded for the two datasets, respectively. These findings demonstrate the importance of weather classification in improving forecasting accuracy, which has potential implications for broader renewable energy applications.
## Reference
Please cite this work as:
@ARTICLE{10.3389/fenrg.2024.1401978,
AUTHOR={Ahmed, Ubaid  and Muhammad, Rasheed  and Abbas, Syed Sami  and Aziz, Imran  and Mahmood, Anzar },
TITLE={Short-term wind power forecasting using integrated boosting approach},
JOURNAL={Frontiers in Energy Research},
VOLUME={12},
YEAR={2024},
URL={https://www.frontiersin.org/journals/energy-research/articles/10.3389/fenrg.2024.1401978},
DOI={10.3389/fenrg.2024.1401978},
ISSN={2296-598X}}
