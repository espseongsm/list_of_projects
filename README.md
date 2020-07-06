# List of Projects

**Please click the titles to see details.**

## [Buzz Prediction in Twitter](https://github.com/espseongsm/Buzz_prediction_on_twitter)

- Built 4 machine learning models by cross-validation and evaluated the best one
- Predicted the number of active discussions of a tweet(99% accuracy), paying attention to emergent issues in Twitter
- Identified Top 2 characteristics that most affect buzz tweets(bootstrap)
- Automated variable selection to improve the predictive power

## [Streaming and Analyzing Yahoo Stock Price in AWS](https://github.com/espseongsm/streaming_stock_prices_and_analyzing_in_AWS)

- Analyzed hourly high stock price by company(streamed Yahoo Finance stock price data into AWS S3 and queried using SQL in AWS Glue and Athena)

## [Bitcoin Price Time Series Analysis (Deep Learning)](https://github.com/espseongsm/Bitcoin_Time_Series_Deep_Learning)

- Developed a program that generates time-series data from history data (using linear algebra)
- Built the best model that predicts the Bitcoin price from past prices by comparing the performance of Deep Learning, LASSO, and Ridge (optimizing them by cross-validation | 97% accuracy)
  
## [Analysis on Yelp Business and Customer Patterns](https://github.com/espseongsm/Analysis_on_yelp_business_and_customer_patterns)

- read over 1 GB dataset from AWS S3 and analyzed in Pyspark(Jupyter Notebook, AWS EMR) 
- figured out meaningful business patterns from Yelp reviews(no difference between active and inactive reviewers, cutoff for good service quality, regional characteristics)

## [Analyzing Millions of NYC Parking Violation](https://github.com/espseongsm/STA9760_Big_Data_Project1)

- Visualized parking violation patterns of NYC (Top 5 violations, violation trend by time and county, fine reduction | Docker, AWS EC2, Elasticsearch, Kibana)
  
## [Nucleus Detection in Cell](https://github.com/espseongsm/Nucleus_Detection_in_Cell) 

- Developed predictive models that classify cell images with a nucleus to facilitate more efficient DNA research (98.5% accuracy | capturing the appearance of a nucleus) 
- Applied techniques (oversampling, tuning hyperparameters, regularization | 15% improvement)
- Utilized ggplot library (R) to visually demonstrate which of the models most effectively identifies a nucleus
- Used A/B experiments to reduce the data size while preserving predictive ability (45% reduction in training time)

## [Parkinson’s Disease Diagnosis from Acoustic Features](https://github.com/espseongsm/Parkinson_Disease_Diagnosis)

- Built three binary classification models to identify elderly patients with Parkinson’s Disease to facilitate patient diagnoses
- Improved the predictive ability of the model by optimizing hyperparameters (cross-validation | 7% improvement)
- Evaluated the classification models by visualizing the trade-off between model performance and training time
- Figured out important variables that identify Parkinson’s Disease efficiently