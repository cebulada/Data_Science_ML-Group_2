# Data Science 4:  Machine Learning

## Group 2 Members

- 1. Melissa Hartwick - [Email](mailto:mhartwic@uwaterloo.ca)
- 2. McKinleigh Needham - [Email](mailto:mjneedha@uwaterloo.ca)
- 3. Daniel Adam Cebula - [Email](mailto:dacebula@uwaterloo.ca)
- 4. Athithian Selvadurai - [Email](mailto:a6selvad@uwaterloo.ca)
- 5. Aravind Kakarala - [Email](mailto:akakaral@uwaterloo.ca)
- 6. Allan Sales - [Email](mailto:asales@uwaterloo.ca)

## Group Topic

- Create a machine learning model classifying Toronto Transit Commission (TTC) Subway, Bus and Streetcar Delays (from a period of 2014 - 2019) using Historical Toronto Weather Data Temporally (from a period of 2014 - 2019).
- The data will undergo Dimensionality Reduction through Principal Component Analysis (PCA) and other methods and will be fed through a Pipeline into a variety of regression Machine Learning Algorithms.
- The best performing Machine Learning Algorithms will form an ensemble to better predict Subway, Bus and Streetcar Delays temporally and spatially.

## Data Source Links

- 1. Canadian Historical Weather
    - [link to Web Forms](https://climate.weather.gc.ca/historical_data/search_historic_data_e.html)
    - [link to Bulk Data Download](https://drive.google.com/drive/folders/1WJCDEU34c60IfOnG4rv5EPZ4IhhW9vZH)
- 2. Open Data Toronto TTC Datasets
    - [Subway Delay Data](https://open.toronto.ca/dataset/ttc-subway-delay-data/)
    - [Bus Delay Data](https://open.toronto.ca/dataset/ttc-bus-delay-data/)
    - [Streetcar Delay Data](https://open.toronto.ca/dataset/ttc-streetcar-delay-data/)

## Type of Analysis

- 1. Extract Load Transform (ELT) the 2 datasets into Jupyter Notebooks using Pandas
    - data is less than 50 MB total
    - Link the Historical Canadian Weather temporally to TTC Delay data
- 2. Perform preliminary data analysis on the combined datasets
    - check all features for their distribution and relevance to the Delay timings
    - make informed judgement calls on what data to slice off or transform to usable information
- 3. Pass the data through Dimensional Reduction Algorithms as part of a pipeline to the Machine Learning Algorithms
    - Utilize Principal Component Analysis (PCA) to reduce dimensionality
- 4. Test several machine learning algorithms and check various hyperparameters wth grid searches
    - combine the best performing machine learning algorithms into an ensemble to provide a better predictor of subway / bus / streetcar delays.

## Project Objectives

- 1. Collaborate with peers to develop a working predictive or clustering model.
- 2. Work in a group setting to complete a challenge within an agreed-upon time frame.
- 3. Engage with peers to discover their problem-solving process and lessons learned.
- 4. Carry out the entire modelling process from end to end.
- 5. Recognize the relative strengths of alternative modelling methods.
- 6. Evaluate the performance of alterative modelling methods.
- 7. Hone skills in explaining technical details to a non-technical audience.

## Project Outline for Data Analysis

- 1. Objective: What are you setting out to prove or predict? What is the business or other problem that you are trying to address with this model?
- 2. Data Preparation: What was your data source (e.g., web scraping, corporate data, a standard machine learning data set, open data, etc.)? How good was the data quality? What did you need to do to procure it? What tools or code did you need to use to prepare it for analysis? What challenges did you face?
- 3. Model Design: Describe your (two or more) models. How did you choose hyperparameters if they were required? Why did you choose those particular machine learning models?
- 4. Model Evaluation: How well did the model perform on the set-aside testing dataset? If you attempted an ensemble model how did it perform vs. the individual models in the ensemble?
- 5. Conclusions: Did you prove/disprove your hypothesis or create a useful model? What did you learn about your dataset? What would you do next to improve your model?