# AIDE: Autonomous AI for Data Science
Welcome to the official repository for AIDE, an AI system that can automatically solve data science tasks at a human level, and with human input, it can perform even better. We believe giving developers and researchers direct access to AIDE locally, with local compute and choice to use their own LLM keys, is the most straightforward way to make it useful. That's why we'll open-source it, and the tentative timeline is it will arrive before the end of April. Currently, this repository serves as a gallery showcasing its solutions for 60+ Kaggle competitions we tested.

## About AIDE
AIDE is an AI-powered data science assistant that can autonomously understand task requirements, design, and implement solutions. By leveraging large language models and innovative agent architectures, such as the Solution Space Tree Search algorithm, AIDE has achieved human-level performance on a wide range of data science tasks, outperforming over 50% of human data scientists on Kaggle competitions.

## Gallary
| task_name                                     |   top%_mean | file_link                                                                                                     | competition_link                                                                                       |
|:----------------------------------------------|------------:|:--------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------|
| bike-sharing-demand                           |        0.24 | [bike-sharing-demand.py](examples/bike-sharing-demand.py)                                                     | [competition link](www.kaggle.com/competitions/bike-sharing-demand/overview)                           |
| tabular-playground-series-jul-2021            |        0.16 | [tabular-playground-series-jul-2021.py](examples/tabular-playground-series-jul-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-jul-2021/overview)            |
| tabular-playground-series-jan-2022            |        0.48 | [tabular-playground-series-jan-2022.py](examples/tabular-playground-series-jan-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-jan-2022/overview)            |
| tabular-playground-series-feb-2022            |        0.25 | [tabular-playground-series-feb-2022.py](examples/tabular-playground-series-feb-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-feb-2022/overview)            |
| tabular-playground-series-feb-2021            |        0.71 | [tabular-playground-series-feb-2021.py](examples/tabular-playground-series-feb-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-feb-2021/overview)            |
| tabular-playground-series-aug-2022            |        0.59 | [tabular-playground-series-aug-2022.py](examples/tabular-playground-series-aug-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview)            |
| playground-series-s3e24                       |        0.55 | [playground-series-s3e24.py](examples/playground-series-s3e24.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e24/overview)                       |
| playground-series-s3e23                       |        0.2  | [playground-series-s3e23.py](examples/playground-series-s3e23.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e23/overview)                       |
| playground-series-s3e22                       |        0.87 | [playground-series-s3e22.py](examples/playground-series-s3e22.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e22/overview)                       |
| playground-series-s3e19                       |        0.18 | [playground-series-s3e19.py](examples/playground-series-s3e19.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e19/overview)                       |
| playground-series-s3e18                       |        0.26 | [playground-series-s3e18.py](examples/playground-series-s3e18.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e18/overview)                       |
| playground-series-s3e17                       |        0.46 | [playground-series-s3e17.py](examples/playground-series-s3e17.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e17/overview)                       |
| playground-series-s3e16                       |        0.64 | [playground-series-s3e16.py](examples/playground-series-s3e16.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e16/overview)                       |
| playground-series-s3e14                       |        0.71 | [playground-series-s3e14.py](examples/playground-series-s3e14.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e14/overview)                       |
| optiver-trading-at-the-close                  |        0.99 | [optiver-trading-at-the-close.py](examples/optiver-trading-at-the-close.py)                                   | [competition link](www.kaggle.com/competitions/optiver-trading-at-the-close/overview)                  |
| new-york-city-taxi-fare-prediction            |        1    | [new-york-city-taxi-fare-prediction.py](examples/new-york-city-taxi-fare-prediction.py)                       | [competition link](www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/overview)            |
| playground-series-s3e25                       |        0.79 | [playground-series-s3e25.py](examples/playground-series-s3e25.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e25/overview)                       |
| tmdb-box-office-prediction                    |        0.68 | [tmdb-box-office-prediction.py](examples/tmdb-box-office-prediction.py)                                       | [competition link](www.kaggle.com/competitions/tmdb-box-office-prediction/overview)                    |
| icr-identify-age-related-conditions           |        0.91 | [icr-identify-age-related-conditions.py](examples/icr-identify-age-related-conditions.py)                     | [competition link](www.kaggle.com/competitions/icr-identify-age-related-conditions/overview)           |
| house-prices-advanced-regression-techniques   |        0.41 | [house-prices-advanced-regression-techniques.py](examples/house-prices-advanced-regression-techniques.py)     | [competition link](www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)   |
| godaddy-microbusiness-density-forecasting     |        0.65 | [godaddy-microbusiness-density-forecasting.py](examples/godaddy-microbusiness-density-forecasting.py)         | [competition link](www.kaggle.com/competitions/godaddy-microbusiness-density-forecasting/overview)     |
| cat-in-the-dat                                |        0.69 | [cat-in-the-dat.py](examples/cat-in-the-dat.py)                                                               | [competition link](www.kaggle.com/competitions/cat-in-the-dat/overview)                                |
| tabular-playground-series-apr-2021            |        0.77 | [tabular-playground-series-apr-2021.py](examples/tabular-playground-series-apr-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-apr-2021/overview)            |
| tabular-playground-series-apr-2022            |        0.51 | [tabular-playground-series-apr-2022.py](examples/tabular-playground-series-apr-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-apr-2022/overview)            |
| tabular-playground-series-aug-2021            |        0.16 | [tabular-playground-series-aug-2021.py](examples/tabular-playground-series-aug-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-aug-2021/overview)            |
| ciphertext-challenge-iii                      |        0.91 | [ciphertext-challenge-iii.py](examples/ciphertext-challenge-iii.py)                                           | [competition link](www.kaggle.com/competitions/ciphertext-challenge-iii/overview)                      |
| ciphertext-challenge-ii                       |      nan    | [ciphertext-challenge-ii.py](examples/ciphertext-challenge-ii.py)                                             | [competition link](www.kaggle.com/competitions/ciphertext-challenge-ii/overview)                       |
| cat-in-the-dat-ii                             |        0.66 | [cat-in-the-dat-ii.py](examples/cat-in-the-dat-ii.py)                                                         | [competition link](www.kaggle.com/competitions/cat-in-the-dat-ii/overview)                             |
| tabular-playground-series-jan-2021            |        0.57 | [tabular-playground-series-jan-2021.py](examples/tabular-playground-series-jan-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-jan-2021/overview)            |
| career-con-2019                               |        0.99 | [career-con-2019.py](examples/career-con-2019.py)                                                             | [competition link](www.kaggle.com/competitions/career-con-2019/overview)                               |
| tabular-playground-series-jun-2022            |        0.7  | [tabular-playground-series-jun-2022.py](examples/tabular-playground-series-jun-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-jun-2022/overview)            |
| spaceship-titanic                             |        0.61 | [spaceship-titanic.py](examples/spaceship-titanic.py)                                                         | [competition link](www.kaggle.com/competitions/spaceship-titanic/overview)                             |
| tabular-playground-series-mar-2021            |        0.13 | [tabular-playground-series-mar-2021.py](examples/tabular-playground-series-mar-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-mar-2021/overview)            |
| tabular-playground-series-mar-2022            |        0.85 | [tabular-playground-series-mar-2022.py](examples/tabular-playground-series-mar-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-mar-2022/overview)            |
| tabular-playground-series-may-2021            |      nan    | [tabular-playground-series-may-2021.py](examples/tabular-playground-series-may-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-may-2021/overview)            |
| tabular-playground-series-may-2022            |        0.6  | [tabular-playground-series-may-2022.py](examples/tabular-playground-series-may-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-may-2022/overview)            |
| tabular-playground-series-oct-2021            |        0.62 | [tabular-playground-series-oct-2021.py](examples/tabular-playground-series-oct-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-oct-2021/overview)            |
| tabular-playground-series-oct-2022            |        0.54 | [tabular-playground-series-oct-2022.py](examples/tabular-playground-series-oct-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-oct-2022/overview)            |
| tabular-playground-series-sep-2021            |        0.62 | [tabular-playground-series-sep-2021.py](examples/tabular-playground-series-sep-2021.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-sep-2021/overview)            |
| tabular-playground-series-jul-2022            |        0.95 | [tabular-playground-series-jul-2022.py](examples/tabular-playground-series-jul-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-jul-2022/overview)            |
| sentiment-analysis-on-movie-reviews           |        0.42 | [sentiment-analysis-on-movie-reviews.py](examples/sentiment-analysis-on-movie-reviews.py)                     | [competition link](www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/overview)           |
| nlp-getting-started                           |        0.48 | [nlp-getting-started.py](examples/nlp-getting-started.py)                                                     | [competition link](www.kaggle.com/competitions/nlp-getting-started/overview)                           |
| jigsaw-toxic-comment-classification-challenge |        0.78 | [jigsaw-toxic-comment-classification-challenge.py](examples/jigsaw-toxic-comment-classification-challenge.py) | [competition link](www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/overview) |
| playground-series-s3e1                        |        0.6  | [playground-series-s3e1.py](examples/playground-series-s3e1.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s3e1/overview)                        |
| playground-series-s3e13                       |        0.03 | [playground-series-s3e13.py](examples/playground-series-s3e13.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e13/overview)                       |
| playground-series-s3e15                       |        0.56 | [playground-series-s3e15.py](examples/playground-series-s3e15.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e15/overview)                       |
| home-data-for-ml-course                       |        0.09 | [home-data-for-ml-course.py](examples/home-data-for-ml-course.py)                                             | [competition link](www.kaggle.com/competitions/home-data-for-ml-course/overview)                       |
| forest-cover-type-prediction                  |        0.47 | [forest-cover-type-prediction.py](examples/forest-cover-type-prediction.py)                                   | [competition link](www.kaggle.com/competitions/forest-cover-type-prediction/overview)                  |
| facial-keypoints-detection                    |      nan    | [facial-keypoints-detection.py](examples/facial-keypoints-detection.py)                                       | [competition link](www.kaggle.com/competitions/facial-keypoints-detection/overview)                    |
| playground-series-s3e20                       |      nan    | [playground-series-s3e20.py](examples/playground-series-s3e20.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e20/overview)                       |
| dont-overfit-ii                               |        0.98 | [dont-overfit-ii.py](examples/dont-overfit-ii.py)                                                             | [competition link](www.kaggle.com/competitions/dont-overfit-ii/overview)                               |
| scrabble-player-rating                        |      nan    | [scrabble-player-rating.py](examples/scrabble-player-rating.py)                                               | [competition link](www.kaggle.com/competitions/scrabble-player-rating/overview)                        |
| digit-recognizer                              |        0.14 | [digit-recognizer.py](examples/digit-recognizer.py)                                                           | [competition link](www.kaggle.com/competitions/digit-recognizer/overview)                              |
| tabular-playground-series-sep-2022            |        0.64 | [tabular-playground-series-sep-2022.py](examples/tabular-playground-series-sep-2022.py)                       | [competition link](www.kaggle.com/competitions/tabular-playground-series-sep-2022/overview)            |
| playground-series-s3e26                       |        0.56 | [playground-series-s3e26.py](examples/playground-series-s3e26.py)                                             | [competition link](www.kaggle.com/competitions/playground-series-s3e26/overview)                       |
| playground-series-s3e3                        |      nan    | [playground-series-s3e3.py](examples/playground-series-s3e3.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s3e3/overview)                        |
| playground-series-s3e5                        |        0.61 | [playground-series-s3e5.py](examples/playground-series-s3e5.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s3e5/overview)                        |
| playground-series-s3e7                        |        0.55 | [playground-series-s3e7.py](examples/playground-series-s3e7.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s3e7/overview)                        |
| playground-series-s3e9                        |        0.86 | [playground-series-s3e9.py](examples/playground-series-s3e9.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s3e9/overview)                        |
| playground-series-s4e1                        |        0.24 | [playground-series-s4e1.py](examples/playground-series-s4e1.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s4e1/overview)                        |
| playground-series-s4e2                        |        0.64 | [playground-series-s4e2.py](examples/playground-series-s4e2.py)                                               | [competition link](www.kaggle.com/competitions/playground-series-s4e2/overview)                        |
| competitive-data-science-predict-future-sales |        0.87 | [competitive-data-science-predict-future-sales.py](examples/competitive-data-science-predict-future-sales.py) | [competition link](www.kaggle.com/competitions/competitive-data-science-predict-future-sales/overview) |
| santa-2019-revenge-of-the-accountants         |        0.96 | [santa-2019-revenge-of-the-accountants.py](examples/santa-2019-revenge-of-the-accountants.py)                 | [competition link](www.kaggle.com/competitions/santa-2019-revenge-of-the-accountants/overview)         |