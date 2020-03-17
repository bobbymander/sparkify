# Sparkify Project

Sparkify churn prediction project

The purpose of this project is to predict user churn based on the complete event log.

## Data
The data for this project can be found below.  There are 2 datasets, one for messages and one for categories.

Event Log:	s3n://udacity-dsnd/sparkify/mini_sparkify_event_data.json

## Files

Sparkify.html:	Full Jupyter notebook with output in html format
Sparkify.ipynb:	Full Jupyter notebook with output.

## Design

The ETL phase will involve:
    1.  Reading the data with Spark.
	2.  Analyzing the data with Spark.
	3.  Extracting feature data with Spark.
	
The machine learning model building stage will involve:
    1.  Preparing the feature set fully and normalizing.
	2.  Splitting the data into training and test sets.
	3.  Evaluating various classifier models for predicting churn.
	4.  Performing grid search on the most promising models.
	5.  Determining the best performing model along with its performance statistics.
	
## Setup

Only setup required is to launch the Jupyter notebook and to load the dataset locally from S3 or from Udacity directly.

## Libraries

A listing of libraries installed and used by the notebook is below:

1.  numpy:  computation
2.  pandas:  data manipulation
3.  sklearn:  machine learning classification libraries
4.  pyspark:  Spark python API libraries