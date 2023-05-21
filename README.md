# Predicting-Movie-Ratings
## Description:

This project is a part of the course "Data Science".
The goal of this project is to predict the rating of a movie based on the movie's pre-released features.

## Installation:

1. Clone the repository.
2. Install the required packages from "requirements.txt" by running the command:
```
pip install -r requirements.txt
```
3. Run the notebooks from /source/small_data following this order (using the same order with big dataset):
```
    i. Small_DS_craw_visualize.ipynb
    ii. Small_DS_preprocess.ipynb
    iii. Small_DS_model.ipynb
```

## Notebook Description:

1. Small_DS_craw_visualize.ipynb: This notebook contains the code for crawling the data from the web and visualizing the data. (The code is set for crawing 10 demo records. Change the value of count variable to crawl more records.)
2. Small_DS_preprocess.ipynb: This notebook contains the code for preprocessing the data. The pre-processed data is stored in the file "Small_DS_preprocessed.csv".
3. Small_DS_model.ipynb: This notebook contains the code for splitting the data into train/validation/test, handling outlier, scaling, training the model and predicting the rating of the movie. Results are visualized in this notebook too.