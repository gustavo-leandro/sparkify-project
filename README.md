
### Table of Contents

1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Project Motivation<a name="motivation"></a>

This is a project made to predict users who churn from the Sparkify platform.

From a log file of user activities, I did some analysis, treatments and tested some ML models to make this prediction


## Installation <a name="installation"></a>

This project uses Python 3 and the following libraries:

datetime
pandas
pyspark.sql
pyspark.ml

## File Descriptions <a name="files"></a>

There is one files:
**Sparkify.ipynb** - notebook with all the code and analysis made.
**mini_sparkify_event_data.json** - json file with the logs of Sparkify usage.  


## Results<a name="results"></a>

The Random Forest model obtained the best result in comparison with the other models tested, but you can find more details at the post available [here](https://gustavo-sleandro.medium.com/how-to-predict-churn-in-sparkify-using-spark-6bf1a95adadc).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data belongs to [Udacity](https://www.udacity.com/). Feel free to use the code here as you would like!  

== End ==